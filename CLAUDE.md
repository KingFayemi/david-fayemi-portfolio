# Portfolio Hero — project notes

Main file: `index.html` (David Fayemi portfolio).
Style: editorial — bold grotesque name wordmark (Helvetica Neue), mono labels/nav (SF Mono). Palette: #ffffff / #0a0a0a / #6f6c64, warm placeholder #d7d4cd.

## TODO — to revisit
- **Heading (hero) section** — refine further if needed.
- **"View work" pages** — LemFi Credit live at `work/lemfi-credit.html`; duplicate template for remaining projects (see `work/README.md`).

## Conventions in place
- Nav active-section underline: 1px solid currentColor (matches Selected Works underline weight).
- Team Photos: cursor-following label types out the photo title on hover (light #f4f3ee text, soft shadow).
- **About tab panels** (`#about-panels`): keep fixed `height: 392px` on desktop so switching About / Experience / Skills / Footprints never reflows the section. Adjust typography or content to fit; do not change this height to accommodate copy changes. Mobile overrides to `height: auto` in the `@media (max-width: 900px)` block.
- **Copy punctuation**: no em dashes in user-facing copy. Use commas, periods, or colons instead.

## Deploy
- GitHub: `david-fayemi-portfolio`
- Netlify: connect repo, publish directory `.`, no build command
