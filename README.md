# vorrbudget-site

The VorrBudget website, served by GitHub Pages at https://vorrbudget.com.

Plain HTML and CSS. No build step, no JavaScript, no cookies, no trackers. Fonts are self-hosted.
The only outside service is Buttondown (the waitlist form posts to it).

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page |
| `privacy.html` | Privacy page |
| `404.html` | Not-found page |
| `styles.css` | All styles (light and dark mode) |
| `assets/logo-light.svg` | Logo for light mode (**placeholder, replace**) |
| `assets/logo-dark.svg` | Logo for dark mode (**placeholder, replace**) |
| `assets/app-icon.png` | App icon, used as the site icon (**add this file**) |
| `assets/fonts/montserrat-latin-wght.woff2` | Montserrat, weights 400-700, Latin characters, from google/fonts `ofl/montserrat` |
| `assets/fonts/OFL.txt` | Montserrat's license (SIL Open Font License 1.1) |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (needed for `.well-known/`) |
| `.well-known/assetlinks.json` | Android app links (empty for now) |

## Common edits

- **Logos / icon:** overwrite the files above, keeping the same names.
- **Store buttons:** in `index.html`, search for `STORE BUTTON`. Each button has a comment with the exact line to swap in.
- **Screenshots:** in `index.html`, search for `SCREENSHOTS` and follow the three steps in the comment.
- **App privacy policy:** in `privacy.html`, search for `APP PRIVACY POLICY`.
