# 🌌 DARK RETRO THEME - Course Repository

## Theme Features

### Visual Style
- **Dark Background**: Deep space blue (#0a0e27) with subtle grid pattern
- **Neon Colors**: 
  - Magenta/Purple (#ff00ff) - Primary headers and accents
  - Cyan (#00ffff) - Links and interactive elements  
  - Matrix Green (#00ff41) - Body text and success states
  - Yellow (#ffff00) - Warnings and highlights

### Typography
- **Headers**: VT323 (retro terminal font)
- **Body**: Share Tech Mono (clean monospace)
- **Code**: Share Tech Mono with neon borders

### Effects
- **CRT Screen Effect**: Scanline overlay with subtle flicker
- **Animated Scan Line**: Cyan line moving down the page
- **Neon Glow**: Text-shadow effects on headers
- **Glitch Animation**: Header title with periodic glitch effect
- **Hover States**: Neon glow intensifies on interaction

### Components
- **Cards/Sections**: Dark panels with neon borders
- **Tables**: Cyan headers with hover effects
- **Buttons**: Transparent with neon borders and hover glow
- **Code Blocks**: Dark background with magenta borders
- **Info Boxes**: Color-coded by type (info=cyan, success=green, warning=yellow, highlight=magenta)

### Navigation
- **Breadcrumbs**: Cyan with hover effects
- **Module Cards**: Color-coded borders (Module 1=Magenta, Module 2=Cyan, Module 3=Yellow)
- **Buttons**: VT323 font with "EXECUTE.MODULE" style text

### Special Features
- **Scan Line**: Animated cyan line simulating CRT monitor
- **Grid Pattern**: Subtle background grid for depth
- **Hover Effects**: Cards lift and glow on hover
- **Copy Buttons**: AI Prompts page has click-to-copy functionality
- **Responsive**: Mobile-friendly breakpoints

## Color Palette

```css
Background: #0a0e27 (Deep Space Blue)
Primary:    #ff00ff (Neon Magenta)
Secondary:  #00ffff (Neon Cyan)
Success:    #00ff41 (Matrix Green)
Warning:    #ffff00 (Neon Yellow)
Accent:     #16213e (Dark Slate)
Borders:    #1a1a2e (Dark Panel)
```

## Typography System

```css
Headers:     'VT323', monospace (Retro Terminal)
Body:        'Share Tech Mono', monospace (Clean Mono)
Size Scale:  
  - H1: 2.5-3.5rem
  - H2: 2rem
  - H3: 1.5rem
  - Body: 1rem
  - Code: 0.9-1.1rem
```

## Theme Inspiration
- 1980s computing terminals
- Cyberpunk aesthetics  
- Matrix green screen
- Synthwave neon
- Retro arcade machines
- CRT monitor effects

## File Structure
```
outputs/
├── index.html              # Homepage with animated header
├── module1-seo.html        # SEO module
├── module2-ai.html         # AI module
├── module3-ux.html         # UX module
├── ai-prompts.html         # Prompt library with copy buttons
├── quick-reference.html    # Reference guide
└── retro-style.css         # Shared dark retro styles
```

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive
- Touch-friendly buttons (44x44px minimum)
- Fallback fonts included

## Accessibility Notes
While maintaining the retro aesthetic:
- Sufficient color contrast maintained
- Text remains readable
- Hover states have multiple indicators
- Keyboard navigation supported
- Screen reader friendly structure

## Usage
Simply open `index.html` in any modern web browser. All styles are self-contained and work offline.

---

**Theme by**: Dark Retro Design System
**Last Updated**: 2024
**License**: Educational Use
