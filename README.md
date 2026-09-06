# Ryan Ray — Portfolio

A self-contained, single-file portfolio site for Ryan Ray, Senior Software Engineer.

## What's here

- **`index.html`** — the entire site. CSS, JS, web fonts (Google Fonts), and all
  company/university logos are inlined (logos as base64 data URIs), so the file is
  fully standalone with no build step and no dependencies.

## Run locally

Just open the file:

```bash
open index.html            # macOS
# or serve it:
python3 -m http.server 8000   # then visit http://localhost:8000
```

## Deploy

It's static — deploy `index.html` to any static host.

- **Vercel:** import the repo (Framework Preset: **Other**, no build command) or drag
  the folder into vercel.com/new.
- **GitHub Pages / Netlify / Cloudflare Pages:** point at the repo root.

## Design source

The `design/` folder holds the Claude Design canvas source (`Main.dc.html`,
`canvas.json`) used to prototype the visual direction. It is not required to run the site.
