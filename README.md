# Swathi C — Portfolio Website

A dark, animated, single-page portfolio built with plain HTML, CSS, and JavaScript (no build tools required).

## What's inside

```
index.html              → main page (all sections)
style.css                → all styling (dark navy theme, gold/teal accents)
script.js                → animations, typewriter, certificate lightbox, nav behaviour
assets/img/profile.jpg   → your profile photo
assets/certs/*.jpg       → all certificates, converted to images for fast loading
```

## How to view it

Just double-click `index.html` — it opens directly in any browser, no server needed.

To publish it for free, you have a few easy options:

1. **GitHub Pages** (recommended, and you already have a GitHub account):
   - Create a new repository, e.g. `portfolio`.
   - Upload all files in this folder (keeping the `assets` folder structure intact).
   - Go to Settings → Pages → set source to the `main` branch → Save.
   - Your site will be live at `https://Swathi-CSE-28.github.io/portfolio/`.

2. **Netlify Drop**: go to https://app.netlify.com/drop and drag this whole folder in. Live in seconds, free hosting, easy custom domain later.

3. **Vercel**: similar drag-and-drop flow at https://vercel.com/new.

## What you may want to personalize further

- The LinkedIn and GitHub links are already filled in with your real profile URLs from your resume.
- The "Bugsmash, Quizbyte — Cybercrest 2K26" achievement is shown as a text card (no certificate image was available for it). If you have that certificate file, save it as `assets/certs/cybercrest.jpg` and I can wire up the image + lightbox for it too.
- Feel free to swap the typewriter roles in `script.js` (search for `const roles = [...]`) if you want different rotating taglines.

## Sections included

- Hero (animated intro, rotating role typewriter, profile photo)
- About
- Skills (animated skill bars + tag cloud)
- Education (timeline + internship highlight)
- Projects (4 projects, including the Explainable AI internship project)
- Certificates (filterable gallery: All / NPTEL / Industry / Internship, click to enlarge)
- Achievements (Botathon 2nd prize, CodeCraze, Cybercrest)
- Contact (email, phone, GitHub, LinkedIn, location)

Everything is responsive down to mobile, and respects reduced-motion preferences for accessibility.
