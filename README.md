# Outbound Voice Capacity & Scaling Planner

A single-file, zero-dependency static web app for planning outbound voice
campaign capacity — backend concurrency, SIP channels, DIDs, and Azure
sessions — for a single campaign or a multi-tenant fleet.

All computation runs locally in the browser. There is no backend.

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy on Vercel

This is a pure static site. Import the repo in Vercel and deploy with the
defaults — no build step, no framework. `vercel.json` pins the static config.
