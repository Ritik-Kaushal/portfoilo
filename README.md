# Ritik Kaushal - Portfolio Website

A modern, responsive portfolio website showcasing my skills, projects, and professional experience.

## 🚀 Live Demo

[View Live Portfolio](https://your-portfolio-url.com) <!-- Replace with your actual URL -->

## 📋 Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Project Structure](#project-structure)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Mobile hamburger menu
  - Scroll-triggered animations
  - Contact form with validation
  - Hover effects and transitions
- **Performance Optimized**: Fast loading with optimized assets
- **SEO Friendly**: Semantic HTML structure for better search engine visibility
- **Accessibility**: Built with accessibility best practices

## 🛠 Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons and visual elements
- **Google Fonts**: Inter font family

### Features
- CSS Grid & Flexbox for layouts
- CSS Custom Properties (Variables)
- CSS Animations & Transitions
- Intersection Observer API
- Form Validation
- Responsive Design Patterns

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/portfolio.git
   cd portfolio
   ```

2. **Open in browser**
   - Simply open `index.html` in your preferred web browser
   - Or use a local server for development:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

3. **View the website**
   - Navigate to `http://localhost:8000` in your browser

## 🎯 Usage

### Basic Setup
1. Open `index.html` in a text editor
2. Replace placeholder content with your information
3. Update contact details and social media links
4. Add your actual project information
5. Customize colors and styling in `styles.css` if needed

### Customization Guide

#### Personal Information
Update the following sections in `index.html`:

```html
<!-- Hero Section -->
<h1 class="hero-title">
    Hi, I'm <span class="highlight">Your Name</span>
</h1>
<p class="hero-subtitle">Your Job Title</p>

<!-- Contact Information -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your.email@example.com</span>
</div>
```

#### Projects Section
Add your projects in the projects grid:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-project-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="github-link" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="live-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
        </div>
    </div>
</div>
```

#### Skills Section
Update your skills in the skills grid:

```html
<div class="skill-item">
    <i class="fab fa-technology-icon"></i>
    <span>Technology Name</span>
</div>
```

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── assets/             # Optional: Images and other assets
    ├── images/
    └── icons/
```

## 🎨 Customization

### Colors
The main color scheme is defined in CSS custom properties:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #fbbf24;
    --text-color: #1f2937;
    --bg-color: #f8fafc;
}
```

### Fonts
The website uses Inter font family. To change fonts:

1. Update the Google Fonts link in `index.html`
2. Modify the font-family in `styles.css`

### Animations
Customize animations by modifying the CSS transition and animation properties in `styles.css`.

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📱 Mobile Responsiveness

The website is fully responsive and includes:
- Mobile-first CSS approach
- Flexible grid layouts
- Touch-friendly navigation
- Optimized typography for mobile
- Hamburger menu for mobile devices

## 🚀 Performance

- Optimized CSS and JavaScript
- Minimal external dependencies
- Fast loading times
- Smooth animations with hardware acceleration
- Efficient scroll event handling

## 🔧 Development

### Local Development
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes to HTML, CSS, or JavaScript
4. Refresh browser to see changes

### Building for Production
1. Optimize images (if any)
2. Minify CSS and JavaScript (optional)
3. Test across different browsers
4. Deploy to your hosting platform

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/yourusername/portfolio/issues).

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

**Ritik Kaushal**

- 📧 Email: [ritik.kaushal@email.com](mailto:ritik.kaushal@email.com)
- 💼 LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)
- 🐙 GitHub: [Your GitHub Profile](https://github.com/yourusername)
- 🌐 Website: [Your Website](https://yourwebsite.com)

## 🙏 Acknowledgments

- [Font Awesome](https://fontawesome.com/) for icons
- [Google Fonts](https://fonts.google.com/) for typography
- [Unsplash](https://unsplash.com/) for inspiration
- All the open source contributors who made this possible

---

⭐ If you found this project helpful, please give it a star on GitHub!

## 📝 Changelog

### Version 1.0.0
- Initial release
- Responsive design
- Interactive navigation
- Contact form
- Project showcase
- Skills section
- Mobile optimization

---

**Made with ❤️ by Ritik Kaushal**