# Project Structure

```
/
├── index.html        # Entire site: HTML, CSS (inline <style>), JS (inline <script>)
├── 20241226_135203.jpg  # Profile photo referenced in index.html
├── robots.txt        # SEO crawler rules
├── sitemap.xml       # SEO sitemap
└── .kiro/
    └── steering/     # Kiro steering docs
```

## Conventions
- All code lives in `index.html` — no separate CSS or JS files
- CSS uses CSS custom properties (variables) defined in `:root` for the color palette
- Dark theme only; color tokens: `--accent-blue`, `--accent-cyan`, `--accent-purple`, `--accent-pink`, `--accent-green`
- Projects are defined as a JS array (`defaultProjects`) and rendered dynamically via `loadProjects()`
- Sections use `id` attributes for anchor navigation: `#home`, `#about`, `#skills`, `#projects`, `#achievements`
- Scroll-based animations use `IntersectionObserver` with `.fade-in` / `.visible` classes
- Responsive breakpoints: 768px (tablet), 480px (mobile)
