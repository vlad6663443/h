# Epic Legends - Gaming Website

## Overview

Epic Legends is a static gaming website showcasing fantasy characters in an immersive, futuristic design. The site features a character gallery with individual profile pages, modern UI elements, and a cyberpunk-inspired aesthetic. Built entirely with HTML, CSS, and JavaScript, it serves as a showcase for gaming characters with detailed profiles and interactive features.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Pure Static Website**: Built with vanilla HTML5, CSS3, and JavaScript
- **Multi-page Structure**: Separate HTML files for different sections (home, characters gallery, individual character profiles)
- **Responsive Design**: Mobile-first approach with responsive navigation and layouts
- **Component-based CSS**: Modular stylesheet organization with separate files for different sections

### Design System
- **Typography**: Google Fonts integration (Orbitron for headings, Rajdhani for body text)
- **Icons**: Font Awesome 6.0 for consistent iconography
- **Color Scheme**: Dark cyberpunk theme with cyan accents (#00ffff) and magenta highlights
- **Visual Effects**: CSS animations, gradients, and text shadows for immersive gaming aesthetics

## Key Components

### Navigation System
- **Fixed Navigation Bar**: Persistent header with logo, menu items, and hamburger menu
- **Responsive Menu**: Mobile-friendly hamburger navigation for smaller screens
- **Active State Management**: Visual indicators for current page location

### Character System
- **Character Gallery**: Grid-based layout showcasing multiple game characters
- **Individual Profiles**: Dedicated pages for each character (character1.html through character6.html)
- **Character Categories**: Filter system for different character types (warriors, mages, etc.)
- **Profile Structure**: Each character has background images, portraits, and detailed information sections

### Page Structure
- **Home Page (index.html)**: Hero section with main call-to-action and site introduction
- **Characters Page (characters.html)**: Gallery view with filtering capabilities
- **Character Detail Pages**: Individual character profiles with back navigation

## Data Flow

### Static Content Management
- **Image Assets**: External images hosted on Pixabay CDN for character portraits and backgrounds
- **Content Structure**: HTML-based content management with no backend database
- **Navigation Flow**: Simple anchor-based routing between static pages

### User Interaction Flow
1. User lands on home page with hero section
2. Can navigate to characters gallery via main navigation or hero CTA
3. Characters page displays filterable grid of character cards
4. Clicking character leads to individual profile page
5. Profile pages include back navigation to return to gallery

## External Dependencies

### CDN Resources
- **Font Awesome 6.0**: Icon library for UI elements and navigation
- **Google Fonts**: Typography system (Orbitron and Rajdhani font families)
- **Pixabay CDN**: External image hosting for character assets and backgrounds

### Browser Dependencies
- **Modern CSS Support**: CSS Grid, Flexbox, and CSS animations
- **ES6 JavaScript**: For interactive elements and menu functionality
- **Responsive Images**: CSS object-fit and responsive image techniques

## Deployment Strategy

### Static Hosting
- **No Server Requirements**: Pure static files suitable for any web server
- **CDN-Friendly**: All assets are web-optimized and can be cached effectively
- **Platform Agnostic**: Compatible with GitHub Pages, Netlify, Vercel, or traditional web hosting

### File Organization
- **Root Level Pages**: Main navigation pages in root directory
- **Separate Stylesheets**: Modular CSS organization with main styles.css and characters.css
- **Image Management**: External CDN usage reduces repository size and improves loading times

### Performance Considerations
- **Lazy Loading Ready**: Structure supports progressive enhancement
- **Minimal Dependencies**: Limited external resources for faster loading
- **Responsive Images**: Optimized for different screen sizes and devices

## Technical Notes

### Accessibility
- **Semantic HTML**: Proper heading hierarchy and navigation structure
- **Alt Text**: Image descriptions for screen readers (though some appear truncated in current files)
- **Keyboard Navigation**: Standard HTML form and navigation elements

### Browser Compatibility
- **Modern Browser Focus**: Utilizes contemporary CSS features
- **Progressive Enhancement**: Core functionality works without JavaScript
- **Mobile Responsive**: Designed for mobile-first user experience

### Maintenance
- **Simple Updates**: Content changes require only HTML editing
- **Scalable Structure**: Easy to add new characters by following existing patterns
- **Version Control Friendly**: Text-based files work well with Git workflows