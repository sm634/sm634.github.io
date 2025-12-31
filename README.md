# Safal's Portfolio Website

A modern, artistic personal portfolio website showcasing work in technology, consciousness, and beauty.

## 🌟 Features

- **Responsive Design**: Mobile-first approach with seamless adaptation across all devices
- **Dark/Light Mode**: Toggle between themes with persistent preference storage
- **Smooth Animations**: Intersection Observer-based scroll animations and transitions
- **Interactive Gallery**: Lightbox functionality for full-size image viewing
- **Filterable Projects**: Dynamic filtering by category (Technology, Research, Creative)
- **Accessibility**: WCAG AA compliant with keyboard navigation and screen reader support
- **Performance Optimized**: Lazy loading, efficient animations, minimal dependencies

## 🚀 Live Demo

Visit the live site at: [https://sm634.github.io](https://sm634.github.io)

## 📁 Project Structure

```
sm634.github.io/
├── index.html              # Main HTML file
├── css/
│   ├── style.css          # Core styles and layout
│   ├── responsive.css     # Responsive design rules
│   └── animations.css     # Animation definitions
├── js/
│   ├── main.js           # Core JavaScript functionality
│   └── animations.js     # Advanced animation controllers
├── images/               # Portfolio images
└── docs/                 # Documentation
    ├── design-concept.md
    └── implementation-guide.md
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox
- **JavaScript (ES6+)**: Vanilla JS, no frameworks
- **Google Fonts**: Inter & Poppins

## 📖 Documentation

- **[Design Concept](docs/design-concept.md)**: Design philosophy, color palette, and architecture
- **[Implementation Guide](docs/implementation-guide.md)**: Technical details, customization, and maintenance

## 🎨 Design Highlights

### Color Palette

- **Primary**: Deep Navy (#1a1a2e) - Sophistication and depth
- **Secondary**: Warm Red (#e94560) - Energy and creativity
- **Tertiary**: Soft Gold (#f4a261) - Warmth and approachability
- **Background**: Off-white (#f8f9fa) with dark mode support

### Typography

- **Headings**: Poppins - Modern and bold
- **Body**: Inter - Clean and readable

## 🚀 Quick Start

### Local Development

1. Clone the repository:

```bash
git clone https://github.com/sm634/sm634.github.io.git
cd sm634.github.io
```

2. Open with a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js
npx http-server

# Or simply open index.html in your browser
```

3. Visit `http://localhost:8000` in your browser

### GitHub Pages Deployment

This site is automatically deployed via GitHub Pages:

1. Push changes to the `main` branch
2. GitHub Actions automatically deploys the site
3. Changes appear at `https://sm634.github.io` within 1-2 minutes

## ✏️ Customization

### Adding New Projects

Edit [`index.html`](index.html) in the Work section:

```html
<article class="work__card" data-category="technology">
  <div class="work__card-image">
    <img src="images/your-image.png" alt="Project name" loading="lazy" />
  </div>
  <div class="work__card-content">
    <h3 class="work__card-title">Your Project Title</h3>
    <p class="work__card-description">Description here</p>
    <div class="work__card-tags">
      <span class="work__tag">Tag1</span>
    </div>
    <a href="#" class="work__card-link">View Project →</a>
  </div>
</article>
```

### Changing Colors

Edit CSS custom properties in [`css/style.css`](css/style.css):

```css
:root {
  --color-primary: #your-color;
  --color-secondary: #your-color;
  --color-tertiary: #your-color;
}
```

### Adding Images to Gallery

1. Add image to `images/` folder
2. Add gallery item in [`index.html`](index.html):

```html
<div class="gallery__item">
  <img src="images/your-image.png" alt="Description" loading="lazy" />
  <div class="gallery__overlay">
    <span class="gallery__icon">🔍</span>
  </div>
</div>
```

## 🧪 Testing

### Browser Compatibility

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Responsive Breakpoints

- Mobile: < 480px
- Tablet: 768px
- Laptop: 1024px
- Desktop: 1400px+

## 📊 Performance

- **Page Load**: < 3 seconds
- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices, SEO)
- **Optimizations**: Lazy loading, efficient animations, minimal dependencies

## ♿ Accessibility

- Semantic HTML5 elements
- ARIA labels for interactive elements
- Keyboard navigation support
- High contrast ratios (WCAG AA)
- Screen reader friendly
- Focus indicators

## 🔧 Maintenance

### Regular Updates

- Update projects and articles regularly
- Test on latest browser versions
- Monitor performance metrics
- Keep documentation current

### Backup

- Repository automatically backed up on GitHub
- Consider local backups of images folder

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Safal**

- Website: [sm634.github.io](https://sm634.github.io)
- GitHub: [@sm634](https://github.com/sm634)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio websites
- Google Fonts for typography
- GitHub Pages for hosting

## 📞 Contact

For questions or feedback:

- Open an issue on GitHub
- Email: [your.email@example.com](mailto:your.email@example.com)

---

**Built with ❤️ exploring technology, consciousness, and beauty**
