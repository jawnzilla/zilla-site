# ZILLA

A standalone interactive ASCII signal site.

## Features

- Blocky `ZILLA` hero title
- Full-page bright gradient field
- Falling Matrix-style ASCII hero animation
- Water-style ASCII motion field
- Cursor-reactive directional distortion
- Top fade mask so the body ASCII motion blends into the gradient
- Responsive layout and reduced-motion support

## Run locally

This is a zero-dependency static site. The repo includes a small server that binds only to localhost:

```bash
node server.js
```

Then open `http://127.0.0.1:8787/`.

You can also use any static HTTP server pointed at this directory.

## Project structure

- `index.html` — complete site, styles, and canvas animation logic
