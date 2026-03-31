# atlascortex.dev

Product website for [Atlas Cortex](https://github.com/Betanu701/atlas-cortex) — a self-evolving personal AI platform.

**Live site:** [https://atlascortex.dev](https://atlascortex.dev)

## Stack

- Static HTML/CSS/JS — no build step, no framework
- Dark theme with cyan accents
- Mobile-first responsive design
- CSS-only scroll animations
- Google Fonts (Inter)

## Development

Open `index.html` in a browser. That's it.

For live reload during development:

```bash
# Python
python -m http.server 8000

# Node
npx serve .
```

## Deployment

Deployed automatically to GitHub Pages on push to `main` via `.github/workflows/deploy.yml`.

The `CNAME` file points to `atlascortex.dev`.

## Pages

| File | Description |
|------|-------------|
| `index.html` | Main single-page site (hero, products, architecture, privacy, specs) |
| `privacy.html` | Full privacy policy |

## License

MIT — see [LICENSE](LICENSE).
