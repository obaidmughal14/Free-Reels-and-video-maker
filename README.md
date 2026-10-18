---
title: Reel Studio
emoji: 🎬
colorFrom: red
colorTo: yellow
sdk: static
pinned: false
---

# 🎬 Reel Studio — Free AI Faceless Reel Maker

**Type a topic. Get a viral-ready vertical video. Free, forever, in your browser.**

🌐 **Try it live now — no signup, no install:**
**[https://obaidasiaone-free-ai-reel-studio.static.hf.space](https://obaidasiaone-free-ai-reel-studio.static.hf.space)**

*(Also shared as a Muse app: [https://muse.ai/s/reel-maker-xkxv6o3xakb6nxk](https://muse.ai/s/reel-maker-xkxv6o3xakb6nxk))*

Reel Studio is a free, all-in-one faceless reel maker that runs entirely in your browser. Pick a niche, a viral format, and a length — type a topic (or tap a day from the built-in 30-day content library) — and it writes a hook-first script, generates a voiceover script plus caption and hashtag pack, **finds topic-relevant pictures and videos by itself**, and renders a real, downloadable vertical video. No accounts, no API keys, no subscriptions, no paid services.

## What it does

1. **Writes the script** — a hook-first, human-tone script built for retention: a pattern-interrupt hook in the first 2 seconds, substantive middle beats, a save line, and a call-to-action ending.
2. **Writes the voiceover script** — the full speakable narration (longer than the on-screen captions), in its own panel with copy/rebuild buttons.
3. **Writes the caption + hashtags** — posting-style caption that ends with a question or comment prompt, with copy button.
4. **Finds relevant media by itself** — every scene searches Wikimedia Commons for photos and videos matching *that scene's* keywords (videos preferred), deduplicated across scenes. Manual search, per-scene re-fetch, and your own uploads are all supported.
5. **Renders the video** — real 9:16 vertical (or 16:9 YouTube) video rendered in-browser with animated captions, motion backgrounds, and transitions, ready to download.

## Why it's unique

- **It's the whole pipeline, not one piece.** Most tools write text *or* render video. Reel Studio goes from topic → script → voiceover → media → rendered video in one click.
- **It fetches media that actually matches the topic.** Other free makers give you random stock clips or generic background packs. Reel Studio builds a per-scene search query from your topic plus each scene's keywords, then pulls matching footage from Wikimedia Commons automatically.
- **100% free, no catch.** Everything runs on your device. No API keys, no rate-limited cloud TTS, no watermark, no "premium export". (An optional Pexels key field exists for higher-end stock, but nothing requires it.)
- **Built for retention, not just rendering.** Hook scene, word-by-word karaoke captions, Ken Burns motion, zoom-cut transitions, progress bar, loopable endings, and niche CTAs are baked in — not add-ons.
- **One file.** The entire app is a single self-contained `index.html` (~3.6 MB). Host it anywhere static files work.

## Features

### 🤖 Auto mode
- Pick a **niche** (Tech, Politics, Relationships, Money, Motivation), a **viral format** (3 Things, Myth vs Reality, POV, Did You Know, Checklist, Before/After, Unpopular Opinion, Explained Simply…), a **length** (presets 15s → 10 min, or a custom seconds/minutes box), and a **topic**.
- Or tap any day in the built-in **30-day content library** (tech, neutral politics, relationships, money, motivation) — each day loads a ready-made script, caption, and hashtags.
- One click: script, voiceover script, caption + hashtags, matching media, rendered video.

### 🖼️ Self-fetching, topic-relevant media
- Automatic per-scene search on Wikimedia Commons (keyless, no signup); videos preferred, each scene deduplicated.
- Multi-search cascade per scene ranked by title match + orientation — so footage actually resonates with the topic.
- 🔍 Find button per scene: manual search with thumbnails and video-duration badges, paginated.
- ⟳ Re-fetch per scene, or "re-fetch topic media for all scenes".
- Your uploads always win: per-scene photo/video upload, drag-and-drop, or bulk-upload clips spread across scenes — never overwritten by auto-fetch.
- Preference toggle: Videos first / Photos first.
- Auto-built, copy-ready **media credits** box for your caption.
- Optional free Pexels API key field (stored only in your browser's localStorage, sent only to api.pexels.com) for higher-end stock.

### 🎙️ Voiceover
Step 4, "Voiceover":
- **Generate voiceover** — free browser-voice generator (voice picker, speed, pitch). Your browser asks permission to capture tab audio once; scenes auto-time to the narration and the voice is mixed into the export.
- **Record with mic** or **upload an audio file** instead.
- **Premium route** — a button opens the Free AI Voiceover Studio for higher-quality AI voices ([live here](https://obaidasiaone-free-ai-voiceover-studio.static.hf.space)); download and upload back here.

### 📐 Formats and export
- **Reel 9:16** (1080×1920 Full HD or 720×1280 HD) for Instagram / Facebook / TikTok.
- **YouTube 16:9** (1920×1080 Full HD or 1280×720 HD).
- Real-time rendering (a 60s reel takes ~60s; keep the tab open). Records WebM in Chrome, MP4 in Safari, with an automatic fallback retry if a recording ever comes out empty.
- **Your format, your choice:** after any render, tap "🎞 Also download as MP4" for a free in-browser WebM→MP4 conversion — best for Instagram's uploader. The converter loads once from a CDN (~30 MB, cached after); conversion happens entirely on your device, nothing is uploaded.
- Safe-zone-aware layout keeps text clear of platform UI overlays.

### ✨ Engagement features (always on)
Giant pattern-interrupt hook scene · word-by-word karaoke captions with keyword emphasis · Ken Burns zoom/pan · zoom-cut transitions · bottom progress bar · loopable endings that repeat the hook · niche CTAs · safe-zone-aware layout.

### 🗓️ 30-day content library
Built-in starter calendar across Tech, neutral Politics, Relationships, Money, and Motivation — ready-made scripts, captions, and hashtags, one tap to load. Content defaults: faceless, neutral-politics, no-religion.

## How to use

**Quickest:** open the live link above.

**From this repo:**
1. Download or clone the repo.
2. Open `index.html` in any modern browser (Chrome recommended).
3. Pick niche → format → length → topic, hit generate.

**Auto mode walkthrough:**
1. **Step 1 — Script:** choose niche, viral format, length, and topic (or tap a calendar day). Reel Studio writes the script, voiceover script, caption + hashtags.
2. **Step 2 — Media:** it fetches topic-relevant photos/videos per scene automatically. Review, use 🔍 Find to search manually, ⟳ to re-fetch, or upload your own clips.
3. **Step 3 — Style:** built-in animated backgrounds (Particles, Waves, Light streaks, Pulse rings) plus your fetched media; karaoke caption styling.
4. **Step 4 — Voiceover:** one-click browser-voice generation, mic recording, or audio upload. Scenes auto-time to narration.
5. **Step 5 — Render & download:** pick Reel 9:16 or YouTube 16:9, Full HD or HD, render, download the video file.

📖 Full instructions, tips, and troubleshooting: **[docs/USER-GUIDE.md](docs/USER-GUIDE.md)**

## Tech stack

- **Vanilla JS + HTML5 Canvas + MediaRecorder** — no frameworks, no build step.
- Media search: **Wikimedia Commons API** (CORS-friendly, keyless; thumbnail URLs + MP4 derivatives), optional **Pexels API** (user key only).
- Voiceover: **Web Speech API** (free browser voices) + tab-audio capture for mixing into the export.
- Rendering: canvas compositing at up to 1080×1920, exported via MediaRecorder.

## Honest limits

- Chrome downloads are **WebM**. YouTube accepts WebM directly; Instagram prefers MP4, so you may need a quick convert for Instagram posts.
- Rendering is **real-time** — a 10-minute video takes ~10 minutes to render; keep the tab open.
- Voiceover needs one browser permission (tab-audio capture) — it's a step-4 one-click action, not silent.
- Free Commons footage quality varies vs. premium stock; the Pexels key field or your own clips are the upgrade path.
- Scripts are built from built-in topic/hook banks — strong for common topics, templates for unusual ones.
- Everything runs client-side, so an internet connection is needed for media search (and the page itself must load).

## Privacy

Everything runs locally in your browser. The only network calls are media searches (Wikimedia Commons — and Pexels only if you add a key) and the optional Voiceover Studio link. Nothing you type or upload leaves your device otherwise.

## Run it yourself / hosting

The app is one self-contained `index.html`. Host it anywhere static files work:

- **GitHub Pages:** repo Settings → Pages → Deploy from branch.
- **HuggingFace Static Space:** this repo deploys as-is as a static space (this README's frontmatter carries the Space config).
- **Any static host:** Netlify, Vercel, your own domain — upload `index.html`.

## Repo contents

```
index.html          The entire app (script engine, media fetcher, renderer, UI)
docs/USER-GUIDE.md  Full user guide: auto mode, media, voiceover, export, tips
LICENSE             MIT
.gitignore
```

## Contributing

Fork it, hack it, open a PR. Ideas welcome: more niches, caption styles, language support, smarter script banks.

## License

MIT © 2026 Obaid Mughal — see [LICENSE](LICENSE).
