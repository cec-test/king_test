# Logo Upload Instructions

## How to Upload Your Logo

### Option 1: Via GitHub Web Interface (Easiest)
1. Go to https://github.com/cec-test/king_test
2. Navigate to `assets/images/` folder
3. Click "Add file" → "Upload files"
4. Drag and drop your logo file
5. Name it `logo.png` (or `logo.svg` for vector)
6. Commit the changes

### Option 2: Via Git Command Line
```bash
# Copy your logo to this directory
cp /path/to/your/logo.png /workspace/assets/images/logo.png

# Then commit and push
git add assets/images/logo.png
git commit -m "Add Usurper logo"
git push origin main
```

### Recommended Logo Specifications
- **Format**: PNG (with transparency) or SVG (scalable)
- **Size**: 200-400px width for PNG
- **Aspect Ratio**: Horizontal/landscape orientation works best
- **File Name**: `logo.png` or `logo.svg`

The website code is already configured to use `assets/images/logo.png` by default.
