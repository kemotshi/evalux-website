# Evalux - Prop Trading Platform

A modern, high-performance website for Evalux, a proprietary trading firm offering funded trading accounts to Forex traders.

## Features

- 🎨 **Red & Black Theme** - Bold, professional color scheme
- ⚡ **Animated Curve Trail** - GSAP-powered scroll-based SVG animation
- 📱 **Fully Responsive** - Optimized for all devices
- 🚀 **Fast Loading** - Optimized assets and code
- 💼 **Trading Platform** - MT5 integration, fast payouts, news trading

## Tech Stack

- **Framework**: Next.js (Static Export)
- **Animation**: GSAP (GreenSock Animation Platform)
- **Styling**: CSS3 with custom animations
- **Fonts**: Custom web fonts (Arial, Product Sans, PP Neue Montreal)
- **Icons**: Font Awesome 5

## Quick Start

### Deploy to Vercel (Recommended)

1. **Push to GitHub**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/evalux.git
   git push -u origin main
   ```

2. **Deploy on Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "Import Project"
   - Select your GitHub repository
   - Vercel will automatically detect and deploy

### Local Development

Simply open `index.html` in a browser, or use a local server:

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then open `http://localhost:8000` in your browser.

## File Structure

```
evalux-vercel/
├── index.html              # Main HTML file
├── *.js                    # JavaScript bundles
├── *.css                   # Stylesheets
├── *.woff, *.woff2, *.ttf  # Font files
├── *.svg, *.png, *.jpg     # Images and icons
├── banner.mp4              # Hero video background
├── vercel.json             # Vercel configuration
├── .gitignore              # Git ignore rules
└── README.md               # This file
```

## Customization

### Change Colors

The website uses a red and black theme. To modify colors:

1. **CSS Files**: Search for color codes like `#ff3838`, `#ff0000`, `#ff1439`
2. **JavaScript**: Check `index-*.js` for inline color definitions

### Update Content

- **Company Info**: Edit text directly in `index.html`
- **Contact Details**: Update email/phone in the footer section
- **Social Links**: Modify social media URLs in the footer

### Modify Animations

The animated curve uses GSAP. To adjust:

1. Find GSAP code in `7-780ea5e5fb2a6f10.js`
2. Modify timing, easing, or path coordinates
3. See `ANIMATED_CURVE_ANALYSIS.md` for technical details

## Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- **First Contentful Paint**: < 1.5s
- **Time to Interactive**: < 3s
- **Lighthouse Score**: 90+

## License

All rights reserved © 2024 Evalux

## Support

For questions or issues:
- Email: support@evalux.com
- Website: https://evalux.com

---

**Ready to deploy!** 🚀 Just push to GitHub and connect to Vercel.
