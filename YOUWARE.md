# H.P Printer Customer Support Website

This project is a customer support website for H.P Printer products. It provides users with resources to troubleshoot issues, download drivers, check warranty status, and contact support.

## Project Structure

- `index.html` - Main entry point for the website
- `css/` - Directory containing CSS styling files
  - `style.css` - Main stylesheet with custom styling using CSS variables
- `images/` - Directory containing all images and SVG assets used throughout the site
- `webfonts/` - Directory containing Font Awesome font files

## Design Features

- **Responsive design** - Adapts to desktop and mobile devices
- **Accessible UI** - ARIA attributes, semantic HTML, and keyboard navigation
- **CSS Variables** - For consistent theming and easy customization
- **Modern CSS layout** - Using Flexbox and CSS Grid
- **Interactive elements** - Cards, search forms, carousel, and mobile menu toggle

## Accessibility Features

The website follows web accessibility best practices:

- Skip to main content link
- ARIA attributes for better screen reader compatibility
- Focus management for keyboard navigation
- Proper form labels
- Sufficient color contrast
- Responsive design for various device sizes
- Semantic HTML structure

## Development Notes

### Adding New Content

When adding new content to the website:

1. Use semantic HTML elements (`section`, `article`, `nav`, etc.)
2. Follow the existing CSS variable naming convention
3. Include appropriate ARIA attributes for accessibility
4. Ensure responsive behavior on all screen sizes
5. Add proper alt text for images

### Modifying the Design

The design uses CSS variables defined in the `:root` selector of `style.css`. To modify the design:

1. Update color variables to change the color scheme
2. Adjust spacing variables for consistent spacing
3. Modify shadow variables for depth adjustments

### Font Awesome Integration

The site uses Font Awesome icons. If you need to add additional icons:

1. Make sure the icon is available in the Font Awesome library
2. Use the appropriate class name (`fas` for solid, `fab` for brands)
3. Include aria-hidden="true" for decorative icons

## Image Credits

The website uses various images for card backgrounds and illustrations. All images are stored in the `images/` directory with unique filenames.