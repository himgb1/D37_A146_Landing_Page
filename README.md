# D37 A146 Landing Page

A one-page index that links to the two live product sites.

| Button | URL |
|---|---|
| **D37** | https://himgb1.github.io/D37/ |
| **A146** | https://himgb1.github.io/A146/ |

Each button opens the target site in a **new tab** (`target="_blank"` with
`rel="noopener noreferrer"`).

## Files

```
D37_A146_Landing_Page/
├── index.html     # the whole page
├── styles.css     # design tokens + layout
├── preview/       # rendered screenshots (not needed to run the page)
└── README.md
```

No JavaScript, no build step, no dependencies. The only external request is the
Google Font (Plus Jakarta Sans); the page renders fine without it.

## Open it

Double-click `index.html`, or serve the folder:

```bash
cd /home/him/Downloads/project/D37_A146_Landing_Page
python3 -m http.server 8000
# → http://127.0.0.1:8000/
```

## Deploy

Drop the folder on any static host. With GitHub Pages, push the contents to the
root of a repository (or its `gh-pages` branch).

## Design

Reuses the same design system as the two product landing pages
(`/home/him/projects/landing/`): Indigo `#6366F1` / `#4F46E5` for D37, Emerald
`#059669` / `#047857` for A146, Plus Jakarta Sans.

Both button colours clear WCAG AA with white text (6.3:1 and 5.5:1).
