# Context Engineering — Edi Hezri Hairi

A responsive, static companion page for www.edihezri.com, featuring a context brief builder with three scenarios and five selectable layers. No API key, backend, tracking, or build step. Examples are illustrative; this site does not run a model or claim measured model improvements.

## Preview

Open `index.html`, or serve this directory with `python3 -m http.server 8000` and visit http://localhost:8000. Clipboard access works best on localhost or HTTPS. Fonts use Google Fonts with local fallbacks.

## Publish with GitHub Pages

1. Push these files to the `main` branch of MrFluidHead/Context-Engineering.
2. In the repository's Settings → Pages, choose **Deploy from a branch**, then `main` and `/ (root)`.
3. Save the Pages settings and wait for the automatic Pages deployment.
4. Use the exact URL returned by the deployment. The expected project URL is https://mrfluidhead.github.io/Context-Engineering/ (not verified until deployment).

Add a Context Engineering navigation link on your main website to the deployed page. This repository does not contain your main website, so its navigation has not been changed. Serving this page specifically at www.edihezri.com/context-engineering requires adding these files to that site's own source or configuring its host; GitHub Pages does not mount a separate project under an external website's path automatically. Do not add a CNAME for the existing main domain to this repository.

## Edit

- `index.html`: page copy and structure.
- `styles.css`: colour, typography, responsive layouts.
- `app.js`: example scenarios and interactive brief builder.

Conceptual reference: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
