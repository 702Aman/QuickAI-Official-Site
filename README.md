# QuickAI Landing Website

A modern, responsive, production-ready landing website for the QuickAI Chrome extension.

## 🚀 Features

- **Dark-first design** matching the QuickAI extension UI
- **Fully responsive** (mobile → desktop)
- **Fast loading** with minimal dependencies
- **SEO-optimized** structure
- **Accessible** with keyboard navigation support
- **No backend required** - static files only

## 📸 Screenshots

![Website UI](assets/QUICKAISITE.png)

## 📁 Project Structure

```
QuickAi Web/
├── index.html          # Main HTML file
├── css/
│   └── styles.css      # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── assets/
│   ├── favicon.svg     # Site favicon
│   └── og-image.svg    # Open Graph image for social sharing
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Flexbox, Grid, animations
- **Vanilla JavaScript** - No frameworks required
- **Google Fonts** - Inter font family

## 🚀 Deployment

### GitHub Pages

1. Push this folder to a GitHub repository
2. Go to Settings → Pages
3. Select "Deploy from a branch"
4. Choose `main` branch and `/ (root)` folder
5. Your site will be live at `https://username.github.io/repo-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: (leave empty - static site)
3. Set publish directory: `/`
4. Deploy!

### Vercel

1. Import your GitHub repository
2. Vercel auto-detects static site
3. Deploy!

## 🎨 Customization

### Colors

Edit CSS variables in `css/styles.css`:

```css
:root {
    --accent-blue: #3b82f6;
    --accent-cyan: #06b6d4;
    --bg-primary: #0a0a0f;
    /* ... more variables */
}
```

### Links

Update these links in `index.html`:

- Chrome Web Store URL (search for `chrome.google.com/webstore`)
- GitHub repository URL (search for `github.com/user/quickai`)

## 📱 Browser Support

- Chrome 88+
- Firefox 78+
- Safari 14+
- Edge 88+

## 📄 License

MIT License - feel free to use this template for your projects!

---

**Built for QuickAI** - Local AI · Fast · Private
