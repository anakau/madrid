# Madrid — Cooling Coalition

Static site built to match the Figma design ["Website Wireframe"](https://www.figma.com/design/2JzXxPlhm1NaQFnhRYzief/Website-Wireframe?node-id=250-1423) (Homepage frame) pixel-for-pixel: full header, hero, challenge stats, goal cards, 6-item approach grid, portfolio-tool section with layer tags, and all 7 demonstrator cards.

Preview

- Open `index.html` in your browser, or run a simple server:

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

Notes

- Fonts: `Pridi`, `Funnel Sans`, `Funnel Display` and `DM Sans` are all loaded from Google Fonts, matching the Figma text styles exactly.
- `assets/hero-photo.jpg`, `assets/hero-circles.png`, `assets/portfolio-illustration-left.png` and `assets/logo.png` are exported directly from the Figma file.
- To pull updated content/styling from Figma again, re-fetch the file via the Figma REST API using the URL above and a personal access token.

Live link

- https://anakau.github.io/madrid/ (published via GitHub Pages)

Structure

- `index.html`, `styles.css` — the site
- `assets/` — images the site uses
- `brand/` — reserved for brand guidelines and a downloadable asset kit, once ready to share those