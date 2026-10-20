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
| `assets/logo-mark-light.svg` | Logo symbol for light mode (the word "VorrBudget" next to it is HTML text in Montserrat Bold) |
| `assets/logo-mark-dark.svg` | Logo symbol for dark mode |
| `assets/app-icon.svg` | App icon, used as the browser tab icon |
| `assets/app-icon.png` | App icon, 512x512, made from `app-icon.svg`; tab icon fallback and Apple touch icon |
| `assets/fonts/montserrat-latin-wght.woff2` | Montserrat, weights 400-700, Latin characters, from google/fonts `ofl/montserrat` |
| `assets/fonts/OFL.txt` | Montserrat's license (SIL Open Font License 1.1) |
| `licenses/feather-LICENSE.txt` | MIT license for the Feather icons on the home page (linked from the footer credit) |
| `assets/og-image.png` | Share image (1200x630) used when links are posted on social media |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (needed for `.well-known/`) |
| `.well-known/assetlinks.json` | Android app links (empty for now) |

## Common edits

- **Logos / icon:** overwrite the files above, keeping the same names. If `app-icon.svg` changes, re-make `app-icon.png` at 512x512.
- **Store buttons:** in `index.html`, search for `STORE BUTTON`. Each button has a comment with the exact line to swap in.
- **Weeks strip labels:** in `index.html`, search for `WEEKS STRIP`.
- **Phone screenshot in the hero:** in `index.html`, search for `PHONE`; the comment says what to replace.
- **Screenshots:** in `index.html`, search for `SCREENSHOTS` and follow the three steps in the comment.
- **App privacy policy:** in `privacy.html`, search for `APP PRIVACY POLICY`.
