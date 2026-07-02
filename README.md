# canflow-landing

The landing page for [Canflow](https://canflow.app) — the minimal board for tasks, tickets, roadmaps and beta bugs, with an MCP server so Claude Code and Codex can work your board directly.

## What's in here

A single self-contained HTML file, no build step.

```
index.html         # the whole landing page
assets/            # Claude Code + Codex logos, sourced from the app
```

## Run locally

Any static server works. Pick one:

```bash
# Python
python3 -m http.server 4173

# Node
npx serve .
```

Then open `http://localhost:4173`.

## Deploy

Drop the folder into anything that serves static files — Vercel, Netlify, Cloudflare Pages, GitHub Pages, S3. No env vars, no runtime.

## Design system

Mirrors the Canflow app design tokens (`--surface`, `--text`, `--accent`, `--border`, IBM Plex Mono, 5px corners). Light and dark modes share the same DOM.
