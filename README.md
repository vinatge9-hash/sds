# FitCore Studio - Gym Website

A complete, production-ready gym website built with Tailwind CSS (via CDN) and a responsive, accessible design. This three-page site (Home, About, Contact) demonstrates a modern gym brand with a strong hero, service highlights, team bios, and a contact form.

## Pages Included

1) Home (index.html)
- Hero section with a full-bleed background image and an overlay to ensure readability
- Services overview (Personal Training, Group Classes, Nutrition, 24/7 Access)
- Client testimonials
- CTA to contact page

2) About (about.html)
- Our Story, Values, and Team spotlight
- 3 trainer bios with images and roles

3) Contact (contact.html)
- Location, hours, and a fully accessible contact form
- Basic enterprise-grade UX with validation-ready fields

## Setup Instructions

1. Open the project folder in your code editor.
2. View locally by opening index.html in your web browser.
3. Navigate between pages using the top navigation (Home, About, Contact).
4. For deployment, upload all files to your web server and ensure index.html is the default page.

## Customization Guide

- Images: Replace all image sources with high-quality assets. For hero, use a local or CDN-hosted image with appropriate alt text.
- Colors: This design uses the gym category palette (crimson primary, black accents, orange for highlights). Update color values in the HTML if you customize the theme.
- Fonts: The site uses Google Fonts with Oswald for headings and Roboto for body text. The fonts are loaded via @import in a style tag (see index.html).
- Content: Update business name, address, hours, services, and testimonials to reflect your gym brand.

## Accessibility & Performance
- All images include descriptive alt text.
- Keyboard navigation is supported; focus states are visible.
- Tailwind CSS CDN is used for fast, responsive styling.
- JavaScript handles the mobile menu and basic interactions; no external dependencies beyond CDN are required.

## Browser Compatibility
- Chrome, Firefox, Safari, and Edge are supported. The site uses standard HTML5, CSS (Tailwind utility classes), and a light JavaScript layer.

## File Structure
```
website/
├── index.html          # Homepage
├── about.html          # About page
├── contact.html        # Contact page
└── README.md             # This file
```

## Credits
- Design & Development: AI Website Builder (You)
- Icons: Font Awesome (CDN)
- Typography: Google Fonts
- CSS Framework: Tailwind CSS (CDN)

For questions, feel free to ask for adjustments (e.g., more pages, a services page, or a blog).