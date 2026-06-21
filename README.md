# David Fayemi — Portfolio

Editorial portfolio site for David Fayemi, Senior Product Designer.

## Local development

Serve the project root over HTTP (required for the dc-runtime and assets):

```bash
python3 -m http.server 8080
```

Open [http://localhost:8080/](http://localhost:8080/)

## File map

| File | Purpose |
|------|---------|
| `index.html` | Homepage (Design Components + React runtime) |
| `support.js` | dc-runtime |
| `image-slot.js` | Image placeholder component |
| `work/` | Case study pages |
| `assets/` | Project images, team photos, favicon |

## Deploy

Pushes to `main` deploy automatically via [Netlify](https://www.netlify.com/) (see `netlify.toml`).

## Adding a case study

1. Copy `work/lemfi-credit.html` as a template
2. Add images under `assets/projects/<slug>/`
3. Add an `image` field to the project in `index.html` → `projects()`
4. Set `cta: 'View Work'` and remove `soon: true` when ready
