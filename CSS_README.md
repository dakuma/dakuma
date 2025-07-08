# Dakuma CSS Framework

A modern, responsive CSS framework designed for developer and music producer portfolios.

## Features

- **Dark Theme**: Tokyo Night color scheme matching GitHub stats theme
- **Responsive Design**: Mobile-first approach with breakpoints at 768px and 480px
- **Music Producer Elements**: Waveform animations, genre tags, and music-specific styling
- **Developer Portfolio**: Project cards, tech stack displays, and code-friendly styling
- **Animations**: Smooth transitions, hover effects, and keyframe animations
- **Accessibility**: Focus states, reduced motion support, and semantic structure

## Color Palette

The framework uses CSS custom properties (variables) for easy customization:

```css
--primary-bg: #1a1b26;        /* Main background */
--secondary-bg: #24283b;      /* Card backgrounds */
--text-primary: #c0caf5;      /* Primary text */
--accent-purple: #bb9af7;     /* Primary accent */
--accent-blue: #7aa2f7;       /* Secondary accent */
--accent-green: #9ece6a;      /* Success/tech accent */
```

## Key Components

### Layout
- `.container` - Max-width container with responsive padding
- `.grid`, `.grid-2`, `.grid-3` - CSS Grid layouts
- `.flex`, `.flex-center`, `.flex-between` - Flexbox utilities

### Cards
- `.card` - Base card component with hover effects
- `.project-card` - Specialized for project portfolios
- `.music-player` - Music-specific styling

### Buttons
- `.btn` - Base button with hover animations
- `.btn-outline` - Outline variant
- `.btn-large` - Larger size variant

### Music Elements
- `.waveform` - Animated waveform visualization
- `.genre-tag` - Music genre badges
- `.music-player` - Music player container

### Developer Elements
- `.tech-stack` - Technology stack display
- `.tech-tag` - Individual technology badges
- `.project-grid` - Project portfolio grid

## Usage

1. Include the CSS file in your HTML:
```html
<link rel="stylesheet" href="styles.css">
```

2. Use the provided classes in your HTML structure
3. Customize colors by modifying CSS custom properties
4. See `example.html` for a complete implementation

## Browser Support

- Modern browsers with CSS Grid and Flexbox support
- CSS custom properties support
- Responsive design works on all screen sizes

## Customization

Override CSS custom properties in your own stylesheet:

```css
:root {
  --primary-bg: #your-color;
  --accent-purple: #your-accent;
}
```

## License

Free to use and modify for personal and commercial projects.