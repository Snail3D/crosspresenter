# ✝ CrossPresenter.ai

**AI-powered church presentation system** — ProPresenter replacement with live voice commands, AI deck building, and Bible verse lookup.

## Features

- 🎤 **Voice Commands** — "next slide", "bring up John 3:16", "blank screen", "5 minute countdown"
- 🤖 **AI Deck Builder** — Describe your service, get a complete slide deck in seconds
- 📖 **Bible Integration** — Instant verse lookup (KJV, ESV, NIV, NASB, WEB) via bible-api.com
- 🖥️ **Fullscreen Projection** — Clean slide rendering to any display/projector
- 📱 **PWA** — Install on any device, works offline, no install needed
- 🎵 **Slide Types** — Welcome, worship lyrics, verses, announcements, countdowns, images, video, blank
- BYOK — Bring your own AI API key (OpenAI, Anthropic, or custom)

## Tech Stack

- Single-file HTML/CSS/JS — no frameworks, no build tools
- PWA with service worker for offline use
- Web Speech API for voice commands
- bible-api.com for verse lookups
- BYOK AI: OpenAI, Anthropic, or any OpenAI-compatible endpoint

## Deploy

Host on Cloudflare Pages, Netlify, GitHub Pages, or any static host.

```bash
# Local testing
cd ~/crosspresenter && npx serve .
```

## License

MIT
