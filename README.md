# lucidia.earth

> BlackRoad OS, Inc. — lucidia.earth domain repo. Proprietary.

Part of the [BlackRoad OS](https://blackroad.io) ecosystem — [BlackRoad-OS-Inc](https://github.com/BlackRoad-OS-Inc)

---

# lucidia.earth

> AI creator platform — make content with AI, keep 90%+ of the revenue.

**Live at [https://lucidia.earth](https://lucidia.earth)**

## What Lucidia Earth Is

Lucidia Earth is a creator platform where AI does the production and you keep the money. Voice-first content creation, faceless video generation, and AI-assisted editing — all running on infrastructure that costs us $38/mo, so we pass the margins to creators.

## Features

- **Voice-first content** — speak your idea, Lucidia produces the content (Web Speech API)
- **Faceless video** — generate video content without showing your face, powered by local AI
- **90%+ revenue share** — we take less than 10% because our infrastructure is cheap
- **AI editing** — auto-cut, auto-caption, auto-thumbnail from local Ollama models
- **Multi-format output** — blog posts, short-form video, podcasts, social clips from one input
- **No platform lock-in** — export everything, own your content files

## How It Works

You talk. Lucidia listens (Web Speech API), transcribes, and generates content across formats. Video rendering, captioning, and thumbnail generation all happen on the Pi fleet. No cloud GPU bills means we don't need to take 50% of your revenue.

## Pricing

| Plan | Price | What You Get |
|------|-------|-------------|
| Creator | $49/mo | Full platform, all AI tools, 90%+ revenue share |

## Architecture

- Frontend: HTML/CSS/JS served from Gematria (Caddy TLS)
- AI: Ollama on Pi fleet (52 TOPS, 16 models)
- Speech: Web Speech API (browser-native, no external service)
- Your device, your data, your agents

## Part of BlackRoad OS

BlackRoad OS, Inc. (Delaware C-Corp, est. November 2025)
See [blackroad.io](https://blackroad.io) for the full platform.

## License

**PROPRIETARY** — BlackRoad OS, Inc. All rights reserved.

---

*BlackRoad OS — Remember the Road. Pave Tomorrow.*
