# Dr. Shivani Battulwar - BDS Dentist Website

A modern, responsive website for Dr. Shivani Battulwar, Bachelor of Dental Surgery (BDS).

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with gradient accents
- **Smooth Animations**: Fade-in effects and smooth scrolling for better user experience
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Contact Form**: Interactive appointment booking form with validation
- **Service Showcase**: Comprehensive display of dental services offered

## Sections

1. **Home/Hero**: Eye-catching introduction with call-to-action
2. **About**: Professional background and qualifications
3. **Services**: Six key dental service categories
4. **Contact**: Contact information and appointment form

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Poppins)

## Getting Started

Simply open `index.html` in a web browser to view the website.

```bash
# Open in default browser (macOS)
open index.html

# Or on Linux
xdg-open index.html

# Or on Windows
start index.html
```

## Customization

### Update Contact Information

Edit the contact section in `index.html`:
- Email address
- Phone number
- Clinic address
- Working hours

### Change Colors

Modify the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2193b0;
    --secondary-color: #6dd5ed;
    /* ... other variables */
}
```

### Add Doctor's Photo

Replace the placeholder in the About section with an actual image:

```html
<div class="about-image">
    <img src="path-to-your-image.jpg" alt="Dr. Shivani Battulwar">
</div>
```

### Form Integration

To make the contact form functional, integrate with:
- Email services (EmailJS, Formspree)
- Backend API
- Google Forms
- Or other contact form services

## File Structure

```
shivaniWeb/
│
├── index.html      # Main HTML file
├── styles.css      # Styling and responsive design
├── script.js       # Interactive functionality
└── README.md       # Documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Dr. Shivani Battulwar, BDS. All rights reserved.
