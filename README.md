# Nab Landing Page

Static landing page for Nab, intended to be deployed on GitHub Pages.

## Files

- `index.html` - main landing page
- `styles.css` - site styles
- `assets/` - brand assets copied from the app repo
- `images/` - public-facing imagery for the landing page
- `404.html` - GitHub Pages fallback page
- `robots.txt` - basic crawler rules
- `.nojekyll` - disables Jekyll processing on GitHub Pages

## Local Preview

Open `index.html` directly in a browser, or run a simple static server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## GitHub Pages Setup

1. Create a GitHub repo for this folder.
2. Push the contents to the default branch.
3. In GitHub, open `Settings -> Pages`.
4. Under `Build and deployment`, choose:
   - `Source`: `Deploy from a branch`
   - `Branch`: your default branch
   - `Folder`: `/ (root)`
5. Save, then wait for Pages to publish.

## After Launch

- Replace the placeholder App Store CTA in `index.html` with the real App Store URL.
- Replace the temporary visual-direction placeholders with real app screenshots.
- If you later use a custom domain, add a `CNAME` file at the repo root.

## Notes

- Privacy policy: `https://nrtattrie.github.io/nab-legal/privacy.html`
- Terms of service: `https://nrtattrie.github.io/nab-legal/terms.html`
- Support email: `nabreservations@gmail.com`
