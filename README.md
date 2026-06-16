# Portfolio (Static HTML/CSS)

Professional tech portfolio with beige/brown theme. Includes pages for resume, education, experience, certifications, skills, projects, and contact form.

## Features

- ✅ Responsive, mobile-friendly design
- ✅ Beige/brown color theme
- ✅ Resume PDF download
- ✅ Contact form (Formspree integration)
- ✅ SEO meta tags
- ✅ Google Analytics ready
- ✅ Fast static site (no backend needed)
- ✅ Easy to deploy (Vercel, Netlify, GitHub Pages)

## Quick Start

1. Place your resume PDF at `assets/resume.pdf`.
2. Update placeholder content on each page with your real information.
3. Replace "Your Name" with your actual name across all pages.
4. Test locally:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in your browser.

## Setup Checklist

- [ ] Add resume PDF to `assets/resume.pdf`
- [ ] Update home intro on `index.html`
- [ ] Add education entries to `education.html`
- [ ] Add work experience to `experience.html`
- [ ] Add certifications to `certification.html`
- [ ] Add skills to `skills.html`
- [ ] Update project entries on `projects.html`
- [ ] Configure Formspree contact form (see `DEPLOYMENT.md`)
- [ ] Set up Google Analytics (see `DEPLOYMENT.md`)
- [ ] Deploy to Vercel, Netlify, or GitHub Pages (see `DEPLOYMENT.md`)

## File Structure

```
portfolio/
├── index.html           # Home/intro page
├── resume.html          # Resume page
├── education.html       # Education
├── experience.html      # Work experience
├── certification.html   # Certifications
├── skills.html          # Skills
├── projects.html        # Projects
├── contact.html         # Contact form
├── css/
│   └── styles.css       # Beige/brown theme
├── assets/
│   └── resume.pdf       # Your resume (add yours here)
├── README.md            # This file
├── DEPLOYMENT.md        # Deployment instructions
└── .gitignore
```

## Deployment

See `DEPLOYMENT.md` for full instructions on deploying to:
- Vercel (easiest, recommended)
- Netlify
- GitHub Pages

Deploy in ~5 minutes with zero configuration.

## Customization

**Colors** — Edit `:root` variables in `css/styles.css`:
```css
:root {
  --bg: #f6f0ea;           /* light beige */
  --accent: #7a4b2a;       /* brown */
  --muted: #bfaea0;        /* muted beige */
  --text: #2b2b2b;
}
```

**Name** — Find and replace "Your Name" throughout all HTML files.

**Analytics** — Add your Google Analytics ID to scripts in HTML files.

**Contact Form** — Update the form `action` URL in `contact.html` with your Formspree endpoint.

## Support

Questions? Check the comments in each HTML file or review `DEPLOYMENT.md`.

