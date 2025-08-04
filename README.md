# Valentine's Day Website ❤️

An animated website featuring a pixel-art heart with background music, modernized to 2025 web standards.

## Live Demo

Visit: [https://rkruk.github.io/valentine-day/](https://rkruk.github.io/valentine-day/)

## Features

- **Animated Pixel Heart**: Hand-crafted CSS pixel art created using `box-shadow` technique
- **Pulsing Animation**: Smooth blur and transform effects with hover pause interaction
- **Background Music**: "When We Collide" by Rfał Kruk with modern HTML5 audio handling
- **Responsive Design**: Three breakpoints optimized for desktop, tablet, and mobile
- **Modern Web Standards**: SEO optimization, accessibility features, and social media integration
- **Cross-browser Compatibility**: Enhanced vendor prefixes and fallbacks

## Technical Implementation

### Audio Implementation
- HTML5 `<audio>` element with native browser controls
- Source: `media/When_We_Collide.mp3` (MP3 format) - author rights reserved by Rafał Kruk (https://kruk.co). 
- Modern autoplay handling with user interaction fallback
- Enhanced error handling that gracefully hides player on failure
- Multiple interaction triggers: click, keydown, and touchstart events
- Console feedback with user-friendly messages
- Fixed positioning (bottom-right: 20px desktop, 10px mobile)
- Smooth opacity transitions and subtle hover scaling

### Modern Enhancements
- **SEO Optimization**: Meta description, keywords, author tags
- **Social Media**: Open Graph and Twitter Card support for link previews  
- **Accessibility**: ARIA labels, semantic HTML with `<main>` element, keyboard navigation
- **Performance**: CSS reset, modern font stack, mobile optimizations with `will-change`
- **User Experience**: Clean interactions without focus outlines or visual distractions

### CSS Architecture
- **Background**: Linear gradient (135deg) from #ad013a to #7B6762
- **Heart Creation**: Single `::before` pseudo-element with complex multi-color box-shadow
- **Responsive Strategy**: Proportional scaling maintaining pixel art integrity
- **Layout**: Absolute centering with calculated negative margins
- **Typography**: Modern system font stack for better performance

## File Structure

```
valentine-day/
├── index.html              # Single-file website with embedded CSS and JavaScript
├── README.md              # Project documentation
└── media/
    └── When_We_Collide.mp3   # Background music file
```

## Browser Compatibility

- **Modern Browsers**: Chrome, Firefox, Safari, Edge (supports HTML5, CSS3, ES6+)
- **Required Features**: `box-shadow`, `@keyframes`, `transform`, `filter` properties
- **Audio Support**: HTML5 audio with MP3 format support
- **Responsive**: Works on all screen sizes from mobile to desktop
- **Graceful Degradation**: Fallbacks for unsupported features

## Development Notes

- **No Dependencies**: Pure HTML, CSS, JavaScript - no frameworks or libraries
- **Single File**: Everything embedded for easy deployment and hosting
- **Mobile-First**: Responsive design with mobile optimizations
- **Accessibility**: Keyboard navigation and screen reader support
- **Performance**: Optimized animations and efficient event handling

## Music Credit

**Song**: "When We Collide"  
Music Copyright © 2025 Rafał Kruk.
All rights reserved.

The background track used on this website was created by Rafał Kruk using Udio.
You may not use, redistribute, or remix this track without explicit permission from the author.

---

*A modernized expression of love through code* ❤️
