# The Last Object Archive

A futuristic digital archive for the faceless YouTube channel **The Last Object Archive**
(ARCHIVIST-9 — "Recovered Objects From Collapsed Timelines"). Each entry is one impossible recovered
object with a backstory, classified test logs, a branded display, and its YouTube Short. Entries
**unseal one per day** to drip the lore, with live countdowns to each release.

> Original fiction. Every recovered object is a fictional artifact.

## What's here
- `index.html` — the entire site, self-contained (images + fonts inlined). No build step to view.
- `404.html` — same app, so any path resolves to the archive.
- `.github/workflows/pages.yml` — auto-deploys to GitHub Pages on every push to `main`.

## Hosting
- **GitHub Pages:** enable once at **Settings → Pages → Source: GitHub Actions**. Pushes then deploy
  automatically to `https://troundtree13.github.io/The-Last-Object-Archive/`.
- **Cloudflare Pages (alt):** create a Pages project connected to this repo — framework preset *None*,
  build command *(empty)*, output directory `/`.

Embed in Google Sites with **Insert → Embed → Embed code** and a one-line iframe pointing at the URL.

## Source
Generated from the Amuri vault at
`Amuri-Memory/workspaces/youtube-workforce/channels/the-last-object-archive/` — edit
`site-assets/objects.data.json`, run `node site-assets/build.js`, and copy the new `index.html` here.
