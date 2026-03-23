# ReRain Umbrella - Static HTML Website

This folder contains the complete static HTML conversion of the ReRain umbrella React application.

## Folder Structure

```
rerain-umbrella-main/
├── index.html              # Main HTML file (single page website)
├── assets/
│   ├── css/
│   │   └── styles.css     # All custom styles and Tailwind-like utilities
│   ├── js/
│   │   └── main.js        # Interactive animations and functionality
│   └── images/            # All image assets
│       ├── hero-umbrella.png
│       ├── problem-waste.jpg
│       ├── innovation-fabric.jpg
│       ├── process-recycling.jpg
│       ├── circular-nature.jpg
│       ├── vision-future.jpg
│       └── logo.png
└── README.txt             # This file
```

## Features Preserved

✅ **All Sections:**
- Hero Section with animated umbrella
- Problem Section with lifecycle visualization
- Innovation Section with feature cards
- Process Section with timeline
- Impact Section with comparison cards
- Circular Section with step-by-step flow
- Vision Section with target audience
- Footer

✅ **All Animations:**
- Scroll-triggered fade-in animations
- Floating elements (hero umbrella, particles)
- Hover effects on cards and buttons
- Smooth transitions and transformations
- Mobile navigation toggle
- Timeline animations
- Rotating icons and spinning elements
- Counter animations for statistics

✅ **All Images:**
- Original high-quality images preserved
- Properly optimized for web use
- Responsive image sizing

✅ **Responsive Design:**
- Mobile-first approach
- Breakpoints at 768px and 1024px
- Adaptive navigation (desktop/mobile)
- Flexible grid layouts

## How to Use

Simply open `index.html` in any modern web browser:

```bash
# Double-click the file, or
# Open from command line
open index.html          # macOS
start index.html         # Windows
xdg-open index.html      # Linux
```

No server required! The website works completely offline.

## Technical Details

### CSS Architecture
- Custom CSS variables for theming
- Utility-first approach similar to Tailwind
- CSS animations replacing Framer Motion
- Responsive design with media queries
- Smooth scroll behavior

### JavaScript Features
- Intersection Observer for scroll animations
- Mobile menu toggle functionality
- Smooth scroll to anchor links
- Dynamic hover effects
- Stagger animations for lists
- Counter animations for stats

### Color Palette
All original colors preserved using HSL values:
- Primary: Green (#16a34a equivalent)
- Secondary: Blue (#3b82f6 equivalent)
- Eco tones: Mint, Ocean, Sky, Earth
- Destructive: Red for warnings

### Typography
- **Headings:** Space Grotesk (Google Fonts)
- **Body:** Plus Jakarta Sans (Google Fonts)
- Font weights: 300-800

## Browser Compatibility

Tested and working on:
- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Differences from React Version

1. **No Build Process:** Pure HTML/CSS/JS - no compilation needed
2. **No Dependencies:** Standalone files, no npm packages
3. **Simplified Icons:** Inline SVG instead of Lucide React
4. **CSS Animations:** Replaced Framer Motion with native CSS animations
5. **Vanilla JS:** No React, just plain JavaScript

## File Sizes

- `index.html`: ~45 KB
- `styles.css`: ~42 KB
- `main.js`: ~9 KB
- `images/`: ~1.1 MB total

Total: ~1.2 MB (optimized for fast loading)

## Performance

- Instant load time (no JavaScript framework)
- Smooth 60fps animations
- Optimized CSS selectors
- Minimal reflows and repaints
- Lazy-loaded scroll animations

## Customization

To modify colors, edit the CSS variables in `assets/css/styles.css`:

```css
:root {
  --primary: 160 60% 36%;
  --secondary: 215 70% 50%;
  /* ... other colors */
}
```

To change animations, modify keyframes in the CSS file or animation classes.

## Accessibility

- Semantic HTML5 elements
- ARIA labels for interactive elements
- Keyboard navigation support
- Smooth scroll respects user preferences
- Alt text on all images

## License

This is a concept project demonstrating sustainable product design.

---

**Created with ❤️ for a sustainable future**

For questions or issues, please refer to the original React project documentation.
