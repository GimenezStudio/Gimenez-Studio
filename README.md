# Gimenez Studio Portfolio

A modern, professional portfolio website for Augusto Gimenez — a short-form video editing specialist.

## Features

✨ **Modern Design**
- Clean, minimalist aesthetic with Apple-inspired design principles
- Smooth scroll animations and reveal effects
- Fully responsive layout (mobile, tablet, desktop)
- Dark mode color scheme with blue accents

📱 **Sections**
- **Hero** - Compelling headline with CTAs
- **Stats** - Key metrics showcasing experience
- **About** - Personal introduction and highlights
- **Services** - Detailed service offerings
- **Process** - Step-by-step workflow visualization
- **Portfolio** - Work showcase with video placeholders
- **CTA** - Call-to-action section
- **Contact** - Contact form and information
- **Footer** - Navigation and copyright

🎨 **Design System**
- Custom CSS variables for consistent theming
- Blue color palette (#0071E3) matching professional branding
- Smooth transitions and micro-interactions
- Optimized typography using Syne and DM Sans fonts

## Getting Started

### Option 1: GitHub Pages (Recommended)

1. Go to your repository Settings → Pages
2. Under "Build and deployment"
3. Select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click Save

Your site will be live at: `https://gimenezstudio.github.io/Gimenez-Studio`

### Option 2: Local Development

```bash
# Clone the repository
git clone https://github.com/GimenezStudio/Gimenez-Studio.git
cd Gimenez-Studio

# Open in browser
open index.html  # macOS
start index.html # Windows
```

## Customization

### Update Contact Information

Replace in `index.html`:
- `your@email.com` → your actual email
- Social media links and handles
- Location information

### Colors

Edit CSS variables in the `:root` section:

```css
:root {
  --blue: #0071E3;           /* Primary color */
  --blue-dark: #0058B0;      /* Hover state */
  --black: #1D1D1F;          /* Text color */
  /* ...more variables */
}
```

### Add Real Portfolio Videos

1. Replace portfolio placeholders in the `<!-- PORTFOLIO -->` section
2. Add actual video thumbnails or use video preview images
3. Update project titles and descriptions

### Form Handling

The contact form currently shows a success message locally. For full functionality:

1. **Option A: Use Formspree**
   - Sign up at [formspree.io](https://formspree.io)
   - Replace the form endpoint

2. **Option B: Use Netlify Forms**
   - Deploy on Netlify instead of GitHub Pages
   - Add `netlify` attribute to form

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
Gimenez-Studio/
├── index.html          # Main website file
├── README.md          # This file
└── .gitignore        # Git ignore rules
```

## Performance

✅ All CSS is inline for fast loading
✅ Minimal JavaScript for animations
✅ Optimized for Core Web Vitals
✅ Mobile-first responsive design

## Next Steps

1. ✏️ Update all text content with your information
2. 🎨 Customize colors if desired
3. 📸 Replace portfolio placeholders with real work
4. 📧 Set up form handling (Formspree/Netlify)
5. 🚀 Deploy to GitHub Pages or your hosting

## License

This portfolio template is free to use and modify for personal or commercial projects.

---

**Made with ❤️ by Gimenez Studio**