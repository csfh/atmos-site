# Atmos site

Product landing page for [Atmos](https://github.com/csfh/atmos), a Quickshell preferences window for [Omarchy](https://omarchy.org).

Production is [atmos.csfh.dev](https://atmos.csfh.dev) on Cloudflare Pages.

## Local development

```bash
npm install
npm run dev
```

That starts Vite at http://localhost:5173.

```bash
npm run build
npm run preview
```

`npm run build` writes static files to `dist/`. `npm run preview` serves that output locally.

## Cloudflare Pages

This repo is a vanilla Vite static site. Suggested dashboard settings:

| Setting | Value |
| --- | --- |
| Production branch | `main` |
| Framework preset | None (or **React (Vite)** — same command and output) |
| Build command | `npm run build` |
| Build output directory | `dist` |
| Node.js | `22` (optional `NODE_VERSION=22`; `.node-version` is in the repo) |

New Pages projects on the V3 build image already default to Node 22. No Functions or wrangler config are required.

## License

MIT. Copyright (c) 2026 Christoffer Hallas.
