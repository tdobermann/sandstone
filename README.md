# Sandstone Economics

A minimal, responsive landing page for Sandstone Economics. Plain HTML, CSS and SVG, with no JavaScript sent to the browser, no build step and no npm dependencies.

## Preview

With Node.js 20 or later:

```sh
npm run dev
```

Open http://127.0.0.1:4173. The preview server binds only to localhost. Any static file server can also serve `dist/`.

## Deploy

Publish the contents of `dist/` with any static host. No install or build command is required. Relative asset links also support deployment below a subpath.

`.openai/hosting.json` records the private Sites preview and its static directory. The GitHub repository is the editable source of this site.

## Edit

- Copy and the geometric illustration: `dist/index.html`
- Layout, responsive rules and colour tokens: `dist/styles.css`
- Favicon: `dist/mark.svg`

The visual language carries through the warm paper palette, ochre, indigo, serif typography and fine geometry of the related modelling tools, adding cobalt as the main illustration accent. EB Garamond and IBM Plex Mono load from Google Fonts, with system fallbacks if unavailable. No analytics or cookies are added by this page.

There is deliberately no contact action until a destination is supplied. The illustration is decorative, not a chart or statement of model results. Motion respects the visitor's reduced-motion setting.
