# Quick Deployment Guide

## Option 1: Deploy to Vercel (Recommended)

### Step 1: Upload to GitHub

1. Extract the archive
2. Open terminal in the `evalux-vercel` folder
3. Run these commands:

```bash
git init
git add .
git commit -m "Initial commit: Evalux website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/evalux.git
git push -u origin main
```

### Step 2: Deploy on Vercel

1. Go to https://vercel.com and sign in with GitHub
2. Click **"Add New..."** → **"Project"**
3. Select your `evalux` repository
4. Vercel will auto-detect the settings
5. Click **"Deploy"**
6. Done! Your site will be live at `https://your-project.vercel.app`

## Option 2: Deploy to Netlify

1. Go to https://netlify.com
2. Drag and drop the entire `evalux-vercel` folder
3. Your site goes live instantly!

## Option 3: Deploy to GitHub Pages

1. Upload to GitHub (see Step 1 above)
2. Go to repository **Settings** → **Pages**
3. Select branch: `main`, folder: `/ (root)`
4. Click **Save**
5. Your site will be at `https://YOUR_USERNAME.github.io/evalux`

## Custom Domain Setup

### On Vercel:
1. Go to your project → **Settings** → **Domains**
2. Add your custom domain (e.g., `evalux.com`)
3. Update DNS records as instructed
4. SSL certificate is automatic!

### DNS Records (example):
```
Type: A
Name: @
Value: 76.76.21.21

Type: CNAME
Name: www
Value: cname.vercel-dns.com
```

## Troubleshooting

### Images not loading?
- Make sure all image paths start with `/` (e.g., `/logo.png`)
- Check that all files are in the root directory

### Animations not working?
- Ensure all `.js` files are uploaded
- Check browser console for errors

### Video not playing?
- Video file (`banner.mp4`) must be in root directory
- Some browsers block autoplay - this is normal

## Performance Tips

1. **Enable Compression**: Vercel does this automatically
2. **CDN**: Vercel provides global CDN by default
3. **Caching**: Set in `vercel.json` (already configured)

## Need Help?

- Vercel Docs: https://vercel.com/docs
- GitHub Pages Docs: https://docs.github.com/pages
- Netlify Docs: https://docs.netlify.com

---

**Estimated deployment time**: 2-5 minutes 🚀
