# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- ✨ Modern and clean design
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth animations and transitions
- 🔄 Active navigation highlighting
- 📧 Contact form
- ⚡ Fast and lightweight
- ♿ Accessible design

## Sections

1. **Hero Section** - Introduction and call-to-action buttons
2. **About** - Personal information and statistics
3. **Skills** - Technical skills organized by category
4. **Projects** - Showcase of featured projects
5. **Contact** - Contact information and form

## Getting Started

### Prerequisites

No prerequisites needed! Just a modern web browser.

### Installation

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process required.

### Local Development

If you want to run it locally with a server (recommended), you can use:

**Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Node.js:**
```bash
# Using http-server
npx http-server

# Using live-server (auto-reload)
npx live-server
```

**VS Code:**
- Install the "Live Server" extension
- Right-click on `index.html` and select "Open with Live Server"

Then open your browser and navigate to `http://localhost:8000` (or the port shown)

## Customization

### Personal Information

1. **Name and Title**: Edit the hero section in `index.html`:
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <p class="hero-subtitle">Web Developer & Designer</p>
   ```

2. **About Section**: Update the text in the about section

3. **Skills**: Modify the skills in the skills section

4. **Projects**: Add your own projects with:
   - Project name
   - Description
   - Technologies used
   - Links to live demo and GitHub

5. **Contact Information**: Update email, phone, and location in the contact section

6. **Social Links**: Update the social media links (GitHub, LinkedIn, Twitter) in the contact section

### Colors

To change the color scheme, edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #4a90e2;
    --secondary-color: #7b68ee;
    --text-color: #2c3e50;
    /* ... */
}
```

### Fonts

The website uses Google Fonts (Inter). To change the font, update the Google Fonts link in `index.html` and change the font-family in `styles.css`.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## File Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── styles.css          # All styles
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## Features in Detail

### Navigation
- Fixed navigation bar that changes opacity on scroll
- Active section highlighting
- Mobile-responsive hamburger menu

### Animations
- Smooth scroll animations
- Fade-in effects on scroll
- Hover effects on interactive elements

### Contact Form
- Form validation
- Currently shows an alert on submission
- Ready to integrate with a backend service

## Future Enhancements

Consider adding:
- Backend integration for contact form
- Blog section
- Dark mode toggle
- More animation effects
- Project filtering/search
- PDF resume download

## License

Feel free to use this portfolio template for your personal website!

## Contact

If you have any questions or suggestions, feel free to reach out.

---

Made with ❤️ for showcasing your work

