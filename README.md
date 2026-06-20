# Suriya Vijay — Portfolio

A modern, responsive personal portfolio website showcasing projects, skills, and professional achievements. Built with clean, contemporary design principles and smooth interactions.

## 📋 Overview

This portfolio is a single-page application designed to present professional work and experience. It features a dark theme with accent colors, custom typography, and an interactive canvas background for visual appeal.

**Portfolio Owner:** Suriya Vijay — CSE Engineer & Builder

## ✨ Features

- **Modern Design**: Dark theme with vibrant accent colors (teal, blue, gold)
- **Responsive Layout**: Adapts seamlessly to different screen sizes
- **Interactive Elements**: Smooth animations and transitions
- **Typography**: Custom fonts (Syne, DM Sans, DM Mono) for professional appearance
- **Code Display**: Styled code cards with syntax highlighting
- **Stats Section**: Key metrics and achievements at a glance
- **Navigation**: Smooth scrolling and fixed navigation bar

## 🎨 Design System

### Color Palette
- **Background**: `#080c14` (dark navy)
- **Primary Accent**: `#00d4aa` (teal)
- **Secondary Accent**: `#0099ff` (bright blue)
- **Accent Gold**: `#f5c842` (warm gold)
- **Text**: `#e8edf5` (light gray)
- **Muted**: `#7a8ba8` (subdued gray)

### Typography
- **Headings**: Syne (weights: 400, 600, 700, 800)
- **Body**: DM Sans (weights: 300, 400, 500)
- **Code/UI**: DM Mono (weights: 400, 500)

## 📁 File Structure

```
portfolio/
├── index.html       # Main HTML file with embedded styles and scripts
└── README.md        # This documentation file
```

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No build tools or dependencies required

### Installation

1. Clone or download the repository:
   ```bash
   git clone <repository-url>
   cd portfolio
   ```

2. Open `index.html` in your web browser:
   - Double-click the file, or
   - Use a local server (recommended for best results)

### Using a Local Server

For development, it's recommended to serve files locally:

**Using Python 3:**
```bash
python -m http.server 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

Then open `http://localhost:8000` in your browser.

## 🛠️ Customization

### Modifying Content
All content is embedded in `index.html`. Edit directly to customize:

- **Hero Section**: Update name, tagline, description
- **Navigation Links**: Modify URLs in the nav links
- **Stats**: Change numbers and labels in the stats bar
- **Call-to-Action**: Update button text and links

### Changing Colors
Edit the CSS variables in the `:root` selector:

```css
:root {
  --bg: #080c14;
  --accent: #00d4aa;
  /* ... other variables ... */
}
```

### Updating Fonts
Modify the Google Fonts import URL to use different fonts or weights.

## 📱 Responsive Design

The portfolio is mobile-first and includes:
- Flexible grid layouts
- Responsive typography (using `clamp()`)
- Optimized spacing for all screen sizes
- Touch-friendly navigation

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties, flexbox, grid
- **JavaScript**: Interactive features (if included)
- **Canvas API**: Background animations (if implemented)

## 📝 Sections

The portfolio includes:

1. **Navigation Bar**: Fixed header with logo and links
2. **Hero Section**: Main introduction with CTA buttons
3. **Code Card**: Showcase of technical skills
4. **Stats Bar**: Key metrics and achievements
5. *(Additional sections can be added)*

## 🌐 Deployment

### Quick Deployment Options

**Netlify:**
1. Push to GitHub
2. Connect repository to Netlify
3. Deploy automatically

**Vercel:**
```bash
npm i -g vercel
vercel
```

**GitHub Pages:**
1. Push to `gh-pages` branch
2. Enable GitHub Pages in repository settings

**Other Hosts:**
- Any static file hosting (Firebase Hosting, AWS S3, etc.)
- No backend or database required

## ✏️ Editing Guide

### Adding New Sections
1. Add HTML structure in `index.html`
2. Style with CSS in the `<style>` tag
3. Follow existing class naming conventions

### Adding Links
Update in two places:
- Navigation bar
- Call-to-action buttons

## 🐛 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This portfolio is personal work. Usage rights depend on your agreement with Suriya Vijay.

## 📞 Contact

For inquiries or collaboration opportunities, please use the contact information provided in the portfolio.

---

**Last Updated**: May 2026  
**Version**: 1.0
