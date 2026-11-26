# art-memo.com

Static site for Bellrock games, served by GitHub Pages from `main` (custom domain in `CNAME`).

**Do not edit or move `app-ads.txt` or `CNAME`** — AdMob verifies both apps against `https://art-memo.com/app-ads.txt`.

## Structure

| Path | What |
|---|---|
| `/index.html` | Studio home page with game cards |
| `/art-master-quiz/` | Art Master: Art History Quiz — page, `privacy/`, `terms/`, `theme.css` |
| `/sports-dynasty-football/` | Sports Dynasty: Football — page, `privacy/`, `terms/`, `theme.css` |
| `/sports-dynasty-college-football/` | Sports Dynasty: College Football — page, `privacy/`, `terms/`, `theme.css` |
| `/stereorama/` | Stereorama: 360° 3D VR Camera (iOS) — page, `privacy/`, `terms/`, `theme.css` (unlisted: not linked from the home page, not in `sitemap.xml`; no app art yet, uses the shared favicon) |
| `/vrpano/` | Redirects to `/stereorama/` (the app's former name; links in installed builds still point here) |
| `/assets/` | Shared CSS, Roboto variable font, Google Play badge, favicon |

## Replacing images

Keep the file name or update the `src`, `width` and `height` in the HTML.

| File | Used for | Size |
|---|---|---|
| `art-master-quiz/img/card.webp` | Home page card | 1600 × 1000 (16:10) |
| `art-master-quiz/img/hero.webp` | Game page image | any portrait, e.g. 1080 × 1350 |
| `sports-dynasty-football/img/card.webp` | Home page card | 1600 × 1000 (16:10) |
| `sports-dynasty-football/img/hero.webp` | Game page image | 1080 × 1783 (transparent background) |
| `sports-dynasty-college-football/img/card.webp` | Home page card | 1600 × 1000 (16:10) |
| `sports-dynasty-college-football/img/hero.webp` | Game page image | 1080 × 1920 |
| `sports-dynasty-college-football/img/icon-192.png` | Icon, favicon | 192 × 192 |
| `sports-dynasty-college-football/img/icon-512.jpg` | Social preview (`og:image`) | 512 × 512 |

## Licenses

Roboto (`assets/fonts/Roboto-VF.ttf`) is licensed under the SIL Open Font License 1.1.
The Google Play badge is a trademark of Google LLC.
