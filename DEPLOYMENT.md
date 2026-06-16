# Deployment Guide

Your portfolio is ready to deploy. Follow steps for your preferred platform.

## Deploy to Vercel (Recommended)

1. Push your repo to GitHub:
```bash
git init
git add .
git commit -m "Initial portfolio commit"
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
git push -u origin main
```

2. Go to [vercel.com](https://vercel.com), sign in with GitHub.
3. Click "New Project" → select your repo → Deploy.
4. Vercel auto-detects static site and deploys instantly.
5. Claim your custom domain (optional).

## Deploy to Netlify

1. Push repo to GitHub (see above).
2. Go to [netlify.com](https://netlify.com), sign in with GitHub.
3. Click "New site from Git" → select repo → Deploy.
4. Done! Site is live. Connect domain if desired.

## Deploy to GitHub Pages

1. Push to GitHub main branch.
2. Go to repo Settings → Pages → enable GitHub Pages.
3. Site is live at `https://YOUR_USERNAME.github.io/portfolio`.

## Local Preview

```bash
python3 -m http.server 8000
# Open http://localhost:8000
```

## Configure Analytics

1. Create a Google Analytics account at [analytics.google.com](https://analytics.google.com).
2. Create a new property for your site.
3. Get your Measurement ID (starts with `G-`).
4. Replace `G-XXXXXXXXXX` in all HTML files with your ID.

## Configure Contact Form

1. Visit [formspree.io](https://formspree.io).
2. Sign up free and create a form.
3. Copy your form endpoint (e.g., `https://formspree.io/f/xyz123`).
4. Update the `action` attribute in `contact.html` with your endpoint.
5. Test the form by submitting from your site.

## Optimize & Next Steps

- Add your name and content to each page.
- Replace project placeholders with real case studies.
- Add profile image to home page.
- Compress images for faster load.
- Set up a custom domain.
- Enable HTTPS (auto on Vercel/Netlify).
