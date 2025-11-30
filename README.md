# KING TEST

A modern digital magazine for men pursuing excellence in adventure, innovation, conquest, leadership, and philosophy.

## 🎯 Overview

King Test is a premium online magazine designed to inspire and educate men who are committed to personal growth, achievement, and living with purpose. Our content spans five core pillars:

- **⛰️ Adventure** - Pushing boundaries and exploring new frontiers
- **💡 Innovation** - Cutting-edge ideas and groundbreaking technology
- **🏆 Conquest** - Achieving greatness through strategic pursuit
- **👑 Leadership** - Mastering influence and building powerful teams
- **📚 Philosophy** - Timeless wisdom for a meaningful life

## 🚀 Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Fast Loading** - Lightweight and performance-optimized
- **SEO Optimized** - Structured for search engine visibility
- **Newsletter Integration** - Email subscription functionality (ready for backend)
- **Category Navigation** - Easy browsing by topic
- **Smooth Scrolling** - Enhanced user experience with smooth page transitions

## 🛠️ Tech Stack

- **HTML5** - Semantic markup for better accessibility
- **CSS3** - Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript** - No frameworks, pure performance
- **Google Fonts** - Playfair Display & Inter font families

## 📁 Project Structure

```
king_test/
├── index.html          # Main landing page
├── styles.css          # All styling and responsive design
├── main.js            # Interactive features and animations
├── README.md          # Project documentation
└── .gitignore         # Git ignore rules
```

## 🎨 Design System

### Color Palette
- **Primary**: #1a1a1a (Deep Black)
- **Secondary**: #c9a961 (Royal Gold)
- **Accent**: #2c2c2c (Charcoal)
- **Text**: #333333 (Dark Gray)
- **Background**: #ffffff (White)

### Typography
- **Headings**: Playfair Display (Serif)
- **Body**: Inter (Sans-serif)

## 🚀 Getting Started

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/king_test.git
cd king_test
```

2. Open `index.html` in your browser:
```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local server:
```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server
```

### GitHub Pages Deployment

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial commit"
git push origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings
   - Navigate to Pages section
   - Select source branch (main)
   - Select root folder
   - Save and wait for deployment

Your site will be live at: `https://yourusername.github.io/king_test/`

## 📝 Customization

### Adding New Articles

Articles are currently hardcoded in the HTML. To add new content:

1. Duplicate an article card structure in `index.html`
2. Update the title, excerpt, category, and metadata
3. Update the background gradient or add image URLs

### Modifying Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --color-primary: #1a1a1a;
    --color-secondary: #c9a961;
    /* Add your custom colors */
}
```

### Newsletter Integration

The newsletter form currently shows an alert. To integrate with a service:

1. Sign up for an email service (Mailchimp, ConvertKit, etc.)
2. Update the form submission handler in `main.js`
3. Add your API endpoint and key

## 🔮 Future Enhancements

- [ ] Individual article pages
- [ ] Backend integration for content management
- [ ] Search functionality
- [ ] User authentication and profiles
- [ ] Comment system
- [ ] Social media sharing
- [ ] Dark mode toggle
- [ ] Article bookmarking
- [ ] Advanced filtering and sorting
- [ ] RSS feed
- [ ] Multi-language support

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📧 Contact

For questions or feedback, please open an issue on GitHub.

---

**Built with passion for excellence** | © 2025 King Test
