# Interactive Business Card & Portfolio - Abdesselam Salmi

A premium, highly interactive personal portfolio and business card website featuring modern glassmorphism design, a custom video player showcase, and an integrated interactive resume.

## Features

- ✨ **Glassmorphism Design** - Sophisticated frosted glass effects with dynamic blur and conic gradients.
- 📱 **Perfectly Responsive** - Optimized for all devices with specialized mobile handling for the video showcase.
- 🎥 **Custom Video Showcase** - Bespoke cinematic video modal with custom controls and perfect viewport containment.
- 📝 **Interactive Resume** - Integrated full-page resume experience with smooth transitions and layout logic.
- 🌙 **Modern Dark Theme** - Elegant high-end aesthetic inspired by obsidian and gold design tokens.
- ♿ **Highly Accessible** - WCAG compliant, ARIA-enabled, with support for reduced motion and high contrast.
- 🎨 **Pure Performance** - Built with vanilla HTML5, CSS3, and JavaScript—zero external frameworks.

## Project Structure

```text
D:\yacinesse.github.io\
├── index.html          # Core structure and interactive logic
├── assets\
│   ├── styles.css      # Base layout and business card styles
│   ├── resume.css      # Extended styles for the interactive resume
│   ├── Demo_Reel.mp4   # Portfolio video showcase
│   ├── Profile_Pic.webp # Main profile avatar
│   └── ...             # Resume and other static assets
└── README.md
```

## Quick Start

### Local Preview

1. Clone or download the repository.
2. Open `index.html` in any modern web browser.

### Deployment

This site is ready for **GitHub Pages**, **Vercel**, or **Netlify**.
- Ensure the `assets/` folder is uploaded along with `index.html`.
- No build step required.

## Customization

### Personal Details
Most content can be updated directly in `index.html`:
- **Name & Title**: Search for `<span class="name-first">` and job title sections.
- **Social Links**: Update the `href` and `data-icon` attributes in the social links section.

### Visual Identity
Update design tokens in `assets/styles.css` under the `:root` selector:
```css
:root {
    --obsidian:      #04040a; /* Primary background */
    --gold:          #c8a86b; /* Accent color */
    --gold-glow:     rgba(200,168,107,0.4);
    --glass:         rgba(255,255,255,0.04);
}
```

### Video Showcase
Replace `assets/Demo_Reel.mp4` with your own video. The custom player is designed for 16:9 content and automatically handles mobile scaling and touch controls.

## Mobile Responsiveness
The site features a specialized responsive engine that:
1. **Dynamic Scaling**: Adjusts typography and spacing for three distinct mobile tiers.
2. **Modal Containment**: Ensures the video showcase never overflows horizontally, using modern `aspect-ratio` primitives.
3. **Touch Controls**: Automatically reveals video player controls on touch devices where hover is unavailable.
4. **Landscape Logic**: Provides specific layout overrides for small landscape viewports.

## Browser Support
Supports all modern browsers including Chrome 90+, Firefox 90+, Safari 14+, and Edge.

## License
Free to use and modify for personal and commercial projects.

---
Built with ❤️ by Abdesselam Salmi
