# Reel Studio

Free, all-in-one faceless reel maker. Type a topic (or tap a day from the built-in 30-day content library) and Reel Studio writes a hook-first script, generates captions and hashtags, fetches topic-relevant pictures and videos by itself, and renders a real downloadable vertical video — all in the browser, no accounts, no API keys, no paid services.

## Features

- **Auto mode** — pick a niche, a viral format, a length (15s to 10 min) and a topic; one click writes the script, caption + hashtag pack, and renders the video
- **Self-fetching media** — each scene searches Wikimedia Commons for topic-relevant photos and videos (videos preferred), deduplicated across scenes; per-scene manual search and re-fetch included
- **Engagement baked in** — pattern-interrupt hook scene, word-by-word karaoke captions, Ken Burns motion, loopable endings, niche CTAs, progress bar
- **Voiceovers** — free browser-voice generator, mic recording, or upload your own audio; scenes auto-time to the narration and the voice is mixed into the export
- **Formats** — Reel 9:16 and YouTube 16:9, Full HD or HD export (WebM/MP4 depending on browser)
- **30-day content library** — tech, neutral politics, relationships, money and motivation topics with ready-made scripts, captions and hashtags

## Documentation

- [User Guide](docs/USER-GUIDE.md) — full instructions: Auto mode, media, voiceover, formats, export, tips

## Use

Open `index.html` in a browser, or enable GitHub Pages on this repo (Settings → Pages → Deploy from branch) for a hosted link. Everything runs client-side; an internet connection is needed for the media search.

Built with vanilla JS + HTML canvas + MediaRecorder. Media via the Wikimedia Commons API (optional Pexels API key field in settings for higher-end stock).

## License

MIT — see [LICENSE](LICENSE).
