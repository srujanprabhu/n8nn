# Summit Peak Expeditions - Mount Everest Climbing Website

## Overview

Summit Peak Expeditions is a static website for a Mount Everest climbing expedition company. The project showcases climbing adventures and services through a modern, responsive web interface. The site is built using vanilla HTML, CSS, and JavaScript, focusing on clean design and smooth user interactions to attract potential climbers and adventurers.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Static Website Structure**: Built with vanilla HTML5, CSS3, and JavaScript without any frameworks
- **Single Page Application (SPA) Design**: Uses anchor-based navigation with smooth scrolling between sections
- **Responsive Design Pattern**: Mobile-first approach with CSS media queries and flexible layouts
- **Component-Based CSS**: Modular CSS structure with separate concerns for typography, navigation, and layout
- **Progressive Enhancement**: Core functionality works without JavaScript, with JavaScript enhancing the user experience

### Design System
- **Typography**: Uses Google Fonts (Montserrat for headings, Open Sans for body text) for professional appearance
- **Icon System**: Font Awesome 6.4.0 for consistent iconography
- **Color Scheme**: Professional palette with neutral grays (#1F2937, #6B7280) and light backgrounds (#F8FAFC)
- **CSS Reset**: Comprehensive reset for cross-browser consistency

### Navigation System
- **Fixed Navigation Bar**: Sticky header that changes appearance on scroll
- **Mobile-First Navigation**: Hamburger menu for mobile devices with toggle functionality
- **Smooth Scrolling**: JavaScript-powered smooth scrolling between page sections
- **Active State Management**: Dynamic navigation highlighting based on scroll position

### User Interface Features
- **Hero Section**: Full-screen image background with overlay for visual impact
- **Intersection Observer**: Modern scroll-based animations and content reveals
- **Responsive Images**: Optimized images from Pixabay for fast loading
- **Mobile Toggle**: Three-bar hamburger menu with CSS animations

## External Dependencies

### Content Delivery Networks (CDNs)
- **Google Fonts**: Montserrat and Open Sans font families for typography
- **Font Awesome**: Version 6.4.0 for icons and visual elements

### Image Resources
- **Pixabay**: External image hosting for hero background and gallery content
- **Image URLs**: Direct links to optimized images for Mount Everest and climbing scenes

### Browser APIs
- **Intersection Observer API**: For scroll-based animations and content loading
- **Scroll Events**: Window scroll detection for navigation effects
- **DOM Manipulation**: Native JavaScript for interactive elements

### Development Tools
- **CSS Custom Properties**: For maintainable theming and consistent design tokens
- **Semantic HTML5**: Proper document structure for accessibility and SEO
- **Cross-Browser Support**: Compatible with modern browsers supporting ES6+ features