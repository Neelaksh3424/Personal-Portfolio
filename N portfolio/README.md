# Neelaksh Sharma - Portfolio Website

A modern, responsive portfolio website showcasing my work, skills, and projects.

## Features

- 🎨 Modern and clean UI design
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Smooth scrolling and animations
- 🎯 Interactive navigation
- 📧 Contact form (frontend ready)
- 🌟 Highlighted skills and projects
- 🚀 Fast loading and optimized

## Getting Started

### Prerequisites

No special prerequisites needed! This is a static website that can be opened directly in a browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! The website should load and work perfectly.

### For Local Development

If you want to use a local server (recommended for testing):

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

Then visit `http://localhost:8000` (or the port shown) in your browser.

## Customization

### Update Personal Information

1. **Contact Information**: Edit the contact section in `index.html` (lines ~200-220)
   - Update email, phone, and location

2. **Social Media Links**: Update social media URLs in:
   - Hero section (lines ~60-75)
   - Footer section (lines ~260-270)

3. **About Section**: Modify the about text in `index.html` (lines ~100-120)

4. **Skills**: Update skills in the skills section (lines ~140-190)

5. **Projects**: Replace project information with your own projects (lines ~195-280)

6. **Statistics**: Update the stats in the about section (lines ~125-135)

### Styling

- Main styles are in `styles.css`
- Color scheme can be changed via CSS variables at the top of `styles.css` (lines 5-15)
- Fonts can be changed by updating the Google Fonts link in `index.html`

### JavaScript Functionality

- Navigation and interactions are handled in `script.js`
- Form submission is currently set up for frontend only (you'll need a backend for actual email sending)

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Technologies Used

- HTML5
- CSS3 (with CSS Variables, Flexbox, Grid)
- JavaScript (Vanilla JS)
- Font Awesome (icons)
- Google Fonts (Inter font family)

## License

This project is open source and available for personal use.

## Contact

For questions or suggestions, feel free to reach out through the contact form on the website!

---

**Note**: Remember to update all placeholder content (email addresses, social media links, project details, etc.) with your actual information before deploying.

