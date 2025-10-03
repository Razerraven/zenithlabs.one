# Zenith Labs - Landing Page

A modern, responsive landing page for Zenith Labs, a company that builds and distributes innovative software products.

## Features

- **Modern Design**: Clean, professional UI with a beautiful gradient hero section
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, mobile menu, and form validation
- **Contact Section**: Complete contact information and functional contact form
- **Privacy Policy**: Comprehensive privacy policy page

## Pages

- `index.html` - Main landing page
- `privacy.html` - Privacy policy page
- `wifetranslator/index.html` - Wife Translator product page
- `wifetranslator/privacypolicy.html` - Wife Translator privacy policy page

## Sections

### Landing Page

1. **Navigation**: Fixed navigation bar with smooth scrolling
2. **Hero Section**: Eye-catching introduction with call-to-action buttons
3. **Features**: Four key features highlighting company strengths
4. **Products**: Three product showcase cards
5. **About**: Company information with statistics
6. **Contact**: Contact information and contact form
7. **Footer**: Links, legal information, and social media

### Privacy Policy

Comprehensive privacy policy covering:
- Information collection practices
- Data usage and sharing policies
- Security measures
- User rights (including GDPR and CCPA)
- Contact information for privacy inquiries

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **Vanilla JavaScript**: Interactive functionality without dependencies

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Customization

### Colors

The color scheme can be customized in `styles.css` by modifying the CSS variables:

```css
:root {
    --primary-color: #6366f1;
    --primary-dark: #4f46e5;
    --secondary-color: #8b5cf6;
    /* ... more variables */
}
```

### Contact Information

Update contact details in both `index.html` and `privacy.html`:
- Email addresses
- Phone numbers
- Physical address
- Business hours

### Form Handling

The contact form currently shows a notification on submission. To connect it to a backend:

1. Modify the form submission handler in `script.js`
2. Send form data to your backend API
3. Handle server responses appropriately

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Project Structure

```
zenithlabs.one/
├── index.html                              # Main landing page
├── privacy.html                            # Privacy policy page
├── styles.css                              # All styles
├── script.js                               # JavaScript functionality
├── README.md                               # This file
└── wifetranslator/                         # Wife Translator product
    ├── index.html                          # Product page
    ├── privacypolicy.html                  # Privacy policy page
    ├── Wife Translator Product Page.pdf    # Product information PDF
    └── Privacy Policy for Wife Translator.pdf  # Privacy policy PDF
```

## License

© 2025 Zenith Labs. All rights reserved.

