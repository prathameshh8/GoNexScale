# GoNexScale Landing Page

A high-converting, dark-themed landing page for GoNexScale — helping YouTube creators understand how the algorithm actually works.

## Features

- **Dark Theme**: Black background with white/gray text for high contrast
- **Inter Typography**: Clean, modern sans-serif throughout
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Single Goal**: Designed to convert visitors into booked discovery calls

## Setup

1. **Calendly Link**: Already configured in `index.html` — update the `data-url` in the Calendly widget if needed.

2. **Open the Page**:
   - Simply open `index.html` in a web browser
   - Or serve it using a local server:
     ```bash
     # Python 3
     python -m http.server 8000

     # Node.js
     npx http-server
     ```

## File Structure

```
.
├── index.html               # Main landing page
├── privacy-policy.html      # Privacy policy
├── terms-and-conditions.html # Terms and conditions
├── thank-you.html           # Post-booking confirmation page
├── styles.css               # All styling and theme
├── favicon.ico              # Site favicon
├── Logo/                    # Logo assets
└── img/                     # Image assets
```

## Design Notes

- **Color Scheme**: Pure black (#000000) background with white (#ffffff) and light gray (#e5e5e5) text
- **Layout**: Clean, spacious sections with generous padding
- **CTA Buttons**: White buttons with black text for maximum contrast

## Browser Support

Works in all modern browsers (Chrome, Firefox, Safari, Edge).
