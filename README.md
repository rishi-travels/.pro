# Software Engineer Portfolio Website

A modern, responsive portfolio website for software engineers with smooth animations, transitions, and a professional design.

## Features

### 🎨 **Design & Animations**
- Modern gradient backgrounds and glassmorphism effects
- Smooth scroll animations and fade-in effects
- Interactive hover states and micro-interactions
- Floating elements with parallax scrolling
- Typing animation for the hero section
- Custom cursor trail effect (desktop only)

### 📱 **Responsive Design**
- Mobile-first approach
- Hamburger menu for mobile navigation
- Adaptive grid layouts
- Touch-friendly interface

### 🚀 **Sections**
1. **Home** - Hero section with animated introduction
2. **Projects** - Showcase of your work with tech stacks
3. **Certification** - Display your professional certifications
4. **About** - Personal information and skills
5. **Contact** - Contact form and social links

### ⚡ **Interactive Features**
- Smooth scrolling navigation
- Active section highlighting
- Form validation with notifications
- Easter egg (Konami Code)
- Intersection Observer for performance
- Debounced scroll handlers

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Interactive functionality
- **Font Awesome** - Icons
- **Google Fonts** - Typography (Inter)

## Customization

### Personal Information
Update the following in `index.html`:
- Your name in the hero section
- Profile image URL
- Contact information
- Social media links
- Project details
- Certification information
- Skills and experience

### Colors
Modify the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4F46E5;
    --secondary-color: #8B5CF6;
    --accent-color: #EC4899;
    /* ... other colors */
}
```

### Animations
Adjust animation speeds and effects in the CSS:
- `fadeInLeft`, `fadeInRight`, `fadeInUp` animations
- `float` animation for elements
- `bounce` animation for scroll indicator

## File Structure

```
portfolio/
├── index.html          # Main HTML structure
├── styles.css          # All styles and animations
├── script.js           # Interactive JavaScript
└── README.md          # This file
```

## Getting Started

1. **Download or clone** the files to your local machine
2. **Open `index.html`** in your web browser
3. **Customize** the content with your information
4. **Deploy** to your preferred hosting platform

## Browser Support

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance Features

- Optimized animations using CSS transforms
- Intersection Observer for lazy loading animations
- Debounced scroll events
- Efficient DOM manipulation
- Minimal external dependencies

## Easter Egg

Try the Konami Code on your keyboard:
↑ ↑ ↓ ↓ ← → ← → B A

## License

This project is open source and available under the [MIT License](LICENSE).

---

**Created with ❤️ for software engineers**
