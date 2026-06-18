# WanHuaTong

**Live →** [yehloolau-afk.github.io/wanhuatong](https://yehloolau-afk.github.io/wanhuatong/)

Paste any Chinese elementary school lesson — get a full storyboard, AI-generated images, and video clips, ready to edit in After Effects or any video editor.

> **Designed for desktop.** Open in a browser, enter your API key, and start generating.

---

## How it works

```
Paste text → Configure → Parse storyboard → Generate images → Generate videos → Download
     1            2             3                  4                  5              6
```

1. Paste any Chinese text — textbook passages, poetry, stories
2. Choose grade level, art style, aspect ratio, and scene count (4 / 5 / 6 / 8 / 10)
3. Click "Parse Storyboard" — local JS extracts scenes and builds image prompts, zero API calls
4. Click "Generate Images" — Volcengine Seedream 5.0 generates all scenes in parallel
5. Click "Generate Videos" — Volcengine Seedance 1.5 Pro animates each image (async)
6. Download all assets → import into your video editor → add voiceover and subtitles

---

## Supported sizes

| Platform | Ratio | Resolution |
|---|---|---|
| Douyin / TikTok (vertical) | 9:16 | 1440×2560 |
| Xiaohongshu (vertical) | 3:4 | 1728×2304 |
| Xiaohongshu (square) | 1:1 | 2K |
| YouTube / Bilibili | 16:9 | 2560×1440 |

---

## Getting started

1. Open [yehloolau-afk.github.io/wanhuatong](https://yehloolau-afk.github.io/wanhuatong/)
2. Click the settings icon → enter your Volcengine Ark API Key
3. Paste any Chinese lesson text and generate

**Get a free API Key →** [Volcengine Ark Console](https://console.volcengine.com/ark)

---

## Stack

- Single HTML file — no framework, no build step, no backend
- Image gen: Volcengine Seedream 5.0
- Video gen: Volcengine Seedance 1.5 Pro (async polling)
- CORS proxy: Cloudflare Worker

`Claude Code` · `Vanilla HTML / CSS / JS` · `Netlify` · `Cloudflare Workers`

---

Star this if it is useful to you.
