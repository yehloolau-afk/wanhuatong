# WanHuaTong · 万花筒

**Live →** [wanhuatong-a.netlify.app](https://wanhuatong-a.netlify.app/)

Paste any Chinese elementary school lesson — get a full storyboard, AI-generated images, and video clips, ready to edit in AE / 剪映.

> **Designed for desktop.** Open in a browser, paste your API key, and start generating.

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
6. Download all assets → import into AE / 剪映 → add voiceover and subtitles

---

## Supported sizes

| Platform | Ratio | Resolution |
|---|---|---|
| Douyin (vertical) | 9:16 | 1440×2560 |
| Xiaohongshu (vertical) | 3:4 | 1728×2304 |
| Xiaohongshu (square) | 1:1 | 2K |
| Bilibili / YouTube | 16:9 | 2560×1440 |

---

## Getting started

1. Open [wanhuatong-a.netlify.app](https://wanhuatong-a.netlify.app/)
2. Click the settings icon → enter your Volcengine Ark API Key
3. Paste any Chinese text and generate

**Get a free API Key →** [Volcengine Ark Console](https://console.volcengine.com/ark)

---

## Stack

- Single HTML file — no framework, no build step, no backend
- Image gen: Volcengine Seedream 5.0
- Video gen: Volcengine Seedance 1.5 Pro (async polling)
- CORS proxy: Cloudflare Worker

`Claude Code` · `Vanilla HTML / CSS / JS` · `Netlify` · `Cloudflare Workers`

---

⭐ If this is useful to you, leave a star!
