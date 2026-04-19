# Business Card Website - Abdesselam Salmi

A professional, responsive business card website featuring modern glassmorphism design.

## Features

- ✨ **Glassmorphism Design** - Beautiful frosted glass effect with blur and transparency
- 📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- 🌙 **Dark Theme** - Elegant dark minimalistic design
- ♿ **Accessible** - WCAG compliant with ARIA labels and keyboard navigation
- 🎨 **Pure HTML/CSS** - No external frameworks, lightweight and fast
- 🌐 **Offline Ready** - Works offline except for icon CDN

## Files

| File | Description |
|------|-------------|
| `index.html` | Main HTML structure with semantic markup |
| `styles.css` | CSS styles with glassmorphism effects |
| `Profile_Pic.png` | Profile picture (replace with your image) |

## Quick Start

### Local Preview

1. Place all files in a folder
2. Open `index.html` in a web browser

### Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html`, `styles.css`, and `Profile_Pic.png`
3. Go to repository **Settings**
4. Navigate to **Pages** section
5. Select **main** branch as source
6. Click **Save**
7. Your site will be live at `https://[username].github.io/[repo-name]`

### Deploy to Netlify (Alternative)

1. Drag & drop the project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your GitHub repository
3. Site will be deployed instantly

## Customization

### Profile Picture

Replace `Profile_Pic.png` with your own image:
- Recommended size: 500x500px or larger
- Format: PNG with transparent background works best
- The image will be automatically scaled and rounded

### Personal Information

Edit the following in `index.html`:
- **Name**: Line ~45 - Change "Abdesselam Salmi"
- **Title**: Line ~46 - Change job title
- **Social Links**: Lines ~48-95 - Update URLs and labels
- **Email**: Line ~92 - Update `mailto:` address

### Color Scheme

Edit CSS variables in `styles.css`:
```css
:root {
    --bg-color: #0f0f10;        /* Background */
    --glass-bg: rgba(255,255,255,0.08);  /* Glass effect */
    --text-primary: #ffffff;     /* Main text color */
    --text-secondary: #b3b3b3;   /* Secondary text */
}
```

## Browser Support

- Chrome 90+
- Firefox 90+
- Safari 14+
- Edge 90+
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **No external dependencies** (except Font Awesome CDN)
- **Minimal CSS** (~3KB gzipped)
- **Fast LCP** (Largest Contentful Paint)
- **Optimized animations** (GPU accelerated)

## Accessibility Features

- ARIA labels on all interactive elements
- Keyboard navigation support
- Focus visible states
- Reduced motion support
- High contrast mode support
- Semantic HTML5 structure

## SEO

- Proper meta tags
- Descriptive title
- Alt text for images
- Semantic HTML structure

## License

Free to use and modify for personal and commercial projects.

---

Built with ❤️ using pure HTML5 & CSS3
