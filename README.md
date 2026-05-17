# My Website

A beautiful, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- ✨ **Modern Design** - Clean and professional appearance with gradient backgrounds
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- 🎯 **Smooth Navigation** - Smooth scrolling and active link highlighting
- 🎨 **Animated Elements** - Fade-in animations and hover effects
- ⚡ **Lightweight** - No external dependencies, pure HTML/CSS/JavaScript
- 🚀 **Fast Loading** - Optimized for quick page load times

## File Structure

```
Website/
├── index.html      # Main HTML structure
├── styles.css      # CSS styling and animations
├── script.js       # JavaScript interactivity
└── README.md       # Documentation
```

## Getting Started

### Local Development

1. Clone this repository:
   ```bash
   git clone https://github.com/anuragsoni8085/Website.git
   ```

2. Open `index.html` in your browser, or use a local server:
   ```bash
   python -m http.server 8000
   ```

3. Visit `http://localhost:8000` in your browser

### Customization

#### Update Your Information

Open `index.html` and update:
- Your name in the `<title>` and `.nav-brand`
- Hero section text
- About section description
- Project cards with your work
- Contact links (email, GitHub, LinkedIn, Twitter)

#### Customize Colors

In `styles.css`, find the gradient colors and update them:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Try different color combinations:
- Blue & Purple: `#667eea` to `#764ba2`
- Orange & Pink: `#f093fb` to `#f5576c`
- Green & Blue: `#4facfe` to `#00f2fe`

#### Add More Projects

In `index.html`, duplicate a `.project-card` and update:
```html
<div class="project-card">
    <div class="project-image"></div>
    <h3>Your Project Name</h3>
    <p>Project description here</p>
    <a href="your-link" class="project-link">Learn More →</a>
</div>
```

## GitHub Pages Deployment

1. Go to your repository settings
2. Scroll to "GitHub Pages" section
3. Select "main" branch as source
4. Save and your site will be available at: `https://anuragsoni8085.github.io/Website`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Page Load: < 1 second
- Lighthouse Score: 95+
- Fully Responsive Design

## License

This project is open source and available under the MIT License.

## Contact

For questions or suggestions, reach out on:
- GitHub: [@anuragsoni8085](https://github.com/anuragsoni8085)
- Email: your-email@example.com

---

Made with ❤️ by Anurag Soni
