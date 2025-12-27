# CHERD Africa - Modern Website

A modern, responsive website for the Centre for Health Equity Research and Development in Africa (CHERD Africa), featuring interactive animations, smooth transitions, and mobile-first design.

## Overview

This website redesign transforms the CHERD Africa online presence into a modern, engaging platform that showcases their health research and development work across Africa. Built with HTML5, CSS3, JavaScript, and Bootstrap 5, the site emphasizes user experience through motion design and interactivity.

## Features

### Design & UX
- **Modern Hero Sections**: Eye-catching hero sections with gradient backgrounds and floating elements
- **Smooth Animations**: Scroll-triggered animations using Intersection Observer API
- **Interactive Cards**: Hover effects and transitions on service and project cards
- **Responsive Design**: Mobile-first approach ensuring perfect display on all devices
- **Motion Design**: Floating elements, parallax effects, and smooth transitions
- **Accessibility**: Semantic HTML and ARIA labels for screen readers

### Technical Features
- **Bootstrap 5**: Modern responsive grid system and components
- **Custom CSS Animations**: Keyframe animations for fade-ins, slides, and scale effects
- **JavaScript Interactivity**: Dynamic scroll effects, form validation, and filters
- **Font Awesome Icons**: Professional iconography throughout the site
- **Optimized Performance**: Lazy loading and efficient CSS/JS

### Pages

1. **Homepage (index.html)**
   - Hero section with call-to-action
   - Statistics counter with animated numbers
   - About preview section
   - Services showcase
   - Featured projects
   - Why choose us section

2. **About Us (about.html)**
   - Mission, Vision, and Purpose cards
   - Leadership team showcase
   - Expert team section
   - Core values
   - Animated statistics

3. **Services (services.html)**
   - Comprehensive service descriptions
   - Project Management & Research Implementation
   - Data Management
   - Monitoring & Evaluation
   - Grant Writing
   - Data Analysis
   - Software Development
   - Training & Capacity Building
   - Legal & Human Rights
   - Financial Management

4. **Projects (projects.html)**
   - Featured projects grid
   - Interactive filter system
   - Project impact statistics
   - Research excellence highlights
   - Animated project cards

5. **Contact (contact.html)**
   - Contact information cards
   - Interactive contact form with validation
   - Office locations
   - Working hours
   - Social media links
   - Map placeholder

## Technologies Used

- **HTML5**: Semantic markup for better SEO and accessibility
- **CSS3**: Modern styling with flexbox, grid, and animations
- **JavaScript (ES6+)**: Interactive features and dynamic content
- **Bootstrap 5.3**: Responsive framework and components
- **Font Awesome 6.4**: Icon library
- **Google Fonts**: Inter font family for modern typography

## File Structure

```
cherd-africa/
├── index.html              # Homepage
├── about.html              # About Us page
├── services.html           # Services page
├── projects.html           # Projects page
├── contact.html            # Contact page
├── css/
│   └── style.css          # Custom styles and animations
├── js/
│   └── main.js            # JavaScript functionality
├── images/                 # Image assets folder
├── README.md              # Project documentation
└── LICENSE                # License file
```

## Key Animations & Effects

### CSS Animations
- `fadeInUp`: Element fades in while moving up
- `fadeInDown`: Element fades in while moving down
- `fadeInLeft`: Element fades in from left
- `fadeInRight`: Element fades in from right
- `scaleIn`: Element scales up while fading in
- `float`: Continuous floating motion
- `pulse`: Subtle pulsing effect

### JavaScript Features
- Scroll-triggered animations
- Animated counter for statistics
- Smooth scroll navigation
- Form validation and submission handling
- Project filtering system
- Navbar scroll effects
- Scroll-to-top button
- Parallax effects

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Optimizations

- Efficient CSS with minimal specificity
- Debounced scroll events
- Intersection Observer for lazy animations
- Optimized images and assets
- Minified production-ready code structure

## Customization

### Colors
The color scheme is defined in CSS variables in `style.css`:
```css
--primary-color: #0066cc;
--secondary-color: #00b4d8;
--accent-color: #ff6b35;
--dark-color: #1a1a2e;
--light-color: #f8f9fa;
```

### Animations
Animation delays and durations can be adjusted in the CSS file. Use utility classes:
- `.delay-1` through `.delay-6` for staggered animations
- `.reveal` class for scroll-triggered animations

## Setup & Installation

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Open `index.html` in your browser or serve using a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js http-server
npx http-server
```

3. Access the site at `http://localhost:8000`

## Future Enhancements

- Integration with Google Maps API for interactive maps
- Backend integration for contact form submissions
- Blog/News section for updates
- Multi-language support
- Dark mode toggle
- Image gallery for projects
- Team member detail pages
- Newsletter subscription functionality

## Credits

**Design & Development**: Modern redesign of CHERD Africa website
**Content**: CHERD Africa (www.cherdafrica.org)
**Framework**: Bootstrap 5
**Icons**: Font Awesome
**Fonts**: Google Fonts (Inter)

## Contact

For questions or support regarding this website:

**CHERD Africa**
Email: info@cherdafrica.org
Phone: +233 248 168 933
Location: Accra, Oyarifa, Ghana

---

© 2024 CHERD Africa. All Rights Reserved.
