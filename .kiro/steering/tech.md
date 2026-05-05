# Tech Stack

## Architecture
Single-page static website — no build system, no framework, no package manager.

## Technologies
- HTML5, CSS3, vanilla JavaScript (all inline in `index.html`)
- Google Fonts: Inter, JetBrains Mono (loaded via CDN)
- Font Awesome 6.5.0 (loaded via CDN)
- No npm, no bundler, no transpiler

## Hosting
- Vercel (static hosting)
- SEO: `robots.txt` and `sitemap.xml` present

## Common Commands
Since there is no build system, open the site directly in a browser:

```bash
open index.html
```

Or serve locally with any static file server:

```bash
npx serve .
# or
python3 -m http.server 8080
```
