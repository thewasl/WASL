# WASL — Connect with Arabic

A responsive, static landing website for the WASL Arabic learning platform.

## Files
- `index.html` — website content and structure
- `styles.css` — responsive design and visual identity
- `script.js` — mobile navigation and current year
- `assets/favicon.svg` — browser icon

## Preview locally
Open `index.html` in a browser. For a local development server, run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages
1. Create a new repository on GitHub, for example `wasl`.
2. Upload all files and folders in this project. Keep `index.html` at the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. Your URL will usually be `https://YOUR-USERNAME.github.io/wasl/`.

If you name the repository `YOUR-USERNAME.github.io`, the site can publish at `https://YOUR-USERNAME.github.io/`.

## Customisation before launch
- Replace the `hello@wasl.academy` email address in `index.html` with your real contact email.
- Add your actual course links, registration flow and social media links.
- The current page is a front-end brand/landing website. It does not yet include accounts, a learning management system, payment processing, course delivery or a database.
- Google Fonts are loaded online; the site uses fallback fonts if unavailable.
- Check trademark, domain and social-handle availability before commercial launch.
