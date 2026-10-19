# Jontymale.com
Jonty Male’s Personal Website

A single-page academic homepage in a dark academia palette (black and
mahogany, white text), served by GitHub Pages at <https://jontymale.com>.

## Editing

All content lives in `index.html`. Every spot that needs your details is
marked with an `<!-- EDIT -->` comment, and placeholder text is in
`[square brackets]`.

- **Research & Projects**: each box is one `<li class="card">` block.
  Copy one to add another; the grid reflows on its own.
- **Photo**: replace `assets/img/portrait.jpg` with a 3:4 portrait crop
  (900×1200 is plenty). Strip location metadata before committing.
- **Colours and fonts**: the variables at the top of
  `assets/css/style.css`.

## Files

| Path | Purpose |
| --- | --- |
| `index.html` | Home page |
| `404.html` | Not-found page |
| `assets/css/style.css` | All styling |
| `assets/fonts/` | Self-hosted Cormorant Garamond, EB Garamond and DM Mono (SIL OFL) |
| `CNAME` | Custom domain (`jontymale.com`) |

## Preview locally

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
