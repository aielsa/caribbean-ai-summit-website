# Caribbean AI Summit 2026 — Website

Official website for **Caribbean AI Summit 2026** — the largest AI conference of the Caribbean. October 9–10, 2026 · San Juan, Puerto Rico.

🌐 **Live:** [caribbeanaisummit.com](https://caribbeanaisummit.com) *(coming soon)*
🎟️ **Tickets:** [Eventbrite](https://www.eventbrite.com/e/caribbean-ai-summit-2026-registration-1981768097728?aff=website)

## Stack

Single-file static site — vanilla HTML + CSS + JavaScript. No build step, no framework.

- `index.html` — the entire site (markup, styles, scripts inline)
- `assets/` — images, logos, sponsor logos, speaker photos

## Local preview

```bash
# From this folder
python3 -m http.server 8080
```

Then open `http://localhost:8080` (or `http://<your-ip>:8080` from another device on the same Wi-Fi).

## Deploy

The site deploys to **GitHub Pages** automatically from the `main` branch (Settings → Pages → Source: `main` branch / root).

## Credits

- Produced by **PRAIC** — Puerto Rico AI Community
- Built by **Enalca**
- Identity by **W@W**
