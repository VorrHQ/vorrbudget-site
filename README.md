# vorrbudget-site

The VorrBudget website, served by GitHub Pages at https://vorrbudget.com.

Plain HTML and CSS. No build step, no JavaScript, no cookies, no trackers. Fonts are self-hosted.
The only outside service is Buttondown: the waitlist form (plain HTML, no JavaScript) posts to it. The home page's Content-Security-Policy allows form submissions only to this site and that one Buttondown address.

## Files

| File | What it is |
| --- | --- |
| `index.html` | Home page: always-visible hero, the waitlist form, then expandable sections (`<details>`; "What VorrBudget does" starts open) |
| `privacy.html` | Privacy page |
| `404.html` | Not-found page |
| `styles.css` | All styles (light and dark mode) |
| `assets/brand/VorrBudget_logo_light.svg` / `.png` | Full logo for light mode (white background), used in the home page hero |
| `assets/brand/VorrBudget_logo_dark.png` | Full logo for dark mode (#0B1426 background), used in the home page hero |
| `assets/brand/VorrBudget_app_icon.svg` / `.png` | App icon; favicon and Apple touch icon on the home and 404 pages |
| `assets/logo-mark-light.svg` | Logo symbol for light mode, used by `privacy.html` (the word "VorrBudget" next to it is HTML text in Montserrat Bold) |
| `assets/logo-mark-dark.svg` | Logo symbol for dark mode |
| `assets/app-icon.svg` | Older app icon, still used by `privacy.html` |
| `assets/app-icon.png` | App icon, 512x512, made from `app-icon.svg`; tab icon fallback and Apple touch icon |
| `assets/fonts/montserrat-latin-wght.woff2` | Montserrat, weights 400-700, Latin characters, from google/fonts `ofl/montserrat` |
| `assets/fonts/OFL.txt` | Montserrat's license (SIL Open Font License 1.1) |
| `licenses/feather-LICENSE.txt` | MIT license for the Feather icons on the home page (linked from the footer credit) |
| `assets/og-image.png` | Share image (1200x630) used when links are posted on social media: light logo and the hero headline |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Tells GitHub Pages to serve files as-is (needed for `.well-known/`) |
| `.well-known/assetlinks.json` | Android app links (empty for now) |

## Common edits

- **Logos / icon:** overwrite the files in `assets/brand/`, keeping the same names. The hero background is white in light mode and #0B1426 in dark mode to match the logo files' own backgrounds.
- **Google Play / pre-registration link:** in `index.html`, search for `PLAY STORE`. The comment has the exact line to swap in.
- **App privacy policy:** in `privacy.html`, search for `APP PRIVACY POLICY`.
