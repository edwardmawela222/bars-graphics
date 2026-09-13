# Bars Graphics

Marketing website for **Bars Graphics**, a media company based in Jane Furse,
Limpopo, covering weddings, parties, funerals and corporate events with
photography, video and edited content.

Built by [Blue Monday Studios](https://www.bluemondaystudios.co.za).

## Stack

Plain HTML, CSS and vanilla JS — no build step, no framework. This keeps the
site fast, simple to edit, and easy to deploy straight to GitHub Pages.

```
index.html
assets/
  css/style.css      site styles and brand tokens
  js/main.js         mobile nav toggle + footer year
  img/favicon.svg    tab icon (brand dot mark)
  img/brand/         original logo artwork supplied by the client
```

## Brand

The five colors in the Bars Graphics mark each represent an occasion the
business covers, and are used as accents throughout the site:

| Color  | Hex       | Represents               |
|--------|-----------|--------------------------|
| Purple | `#9427A6` | Weddings                 |
| Cyan   | `#00B8E6` | Photo Booth & Artist     |
| Orange | `#FF8611` | Corporate & Broadcasting |
| Green  | `#7AC11D` | Parties                  |
| Pink   | `#E8399A` | Funerals                 |

## Local preview

No build tooling is required. Open `index.html` directly in a browser, or
serve the folder locally, e.g.:

```
python3 -m http.server 8000
```

## Deployment

`.github/workflows/deploy.yml` publishes the repository root to GitHub Pages
on every push to `main`. Enable Pages for this repository under
**Settings → Pages → Source: GitHub Actions** to activate it.

## Outstanding before launch

A few real business details are still placeholders and need to be swapped in
before this goes live — see `TODO.md`.
