<<<<<<< HEAD
# Gene-s-Drives
=======
# Gene's Drives - Front Page (Bootstrap)

This is a minimal Bootstrap-based front page scaffold containing a top navigation bar and several image sections with explanatory text.

Files:
- `index.html` — Main page using Bootstrap 5 via CDN.
- `styles.css` — Small custom styles.

How to view locally:
1. Open `index.html` directly in your browser (double-click) for a quick preview.

Or serve with a local HTTP server (recommended for consistent relative paths):

PowerShell (Windows):

```powershell
cd path\to\workspace\gene-drives-frontend
python -m http.server 8000
# then open http://localhost:8000 in your browser
```

Notes:
- Images are currently placeholder images from `https://picsum.photos`. To use your own images, create an `img/` folder and update the `src` attributes in `index.html` (e.g., `img/photo1.jpg`).
- You can customize the navbar links and section content in `index.html`.

Other pages added:
- `about.html` — In-depth information and technical details.
- `contact.html` — Contact and newsletter signup form (static page with optional Formspree integration).

Form / Newsletter details:
- The `contact.html` form uses a placeholder Formspree action: `https://formspree.io/f/{your-id}`. To enable real submissions, sign up at Formspree (or another provider), get your form endpoint, and replace the `action` attribute in `contact.html` with that URL.
- If you do not configure an endpoint (i.e., leave `{your-id}`), the page will show a local success message when the form is submitted so you can test validation and UI.

Next steps you might want me to do:
- Replace placeholder images with local image files and add an `img/` folder.
- Connect the contact form to a real endpoint (Formspree, Getform, Netlify Forms, etc.). I can help configure it.
- Add a small NPM toolchain or deploy the site to GitHub Pages or Netlify.
>>>>>>> de95886 (Initial commit: static site + GitHub Pages workflow)
