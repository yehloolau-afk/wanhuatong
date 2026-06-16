# WanHuaTong · 万花筒

**Live →** [yehloolau-afk.github.io/wanhuatong](https://yehloolau-afk.github.io/wanhuatong/)

Paste any Chinese text — get a full storyboard, AI-generated images, and video clips, ready to edit in AE / 剪映.

> **Designed for desktop.** Optimized for large screens; a mobile-friendly version is in the works.

---

## Preview

Realistic Chinese style · 4 storyboard scenes auto-generated:

![WanHuaTong screenshot](https://yehloolau-afk.github.io/wanhuatong/preview.png)

---

## Workflow

```
Paste text → Configure → Parse storyboard → Generate images → Generate videos → Download
     1            2             3                  4                  5              6
```

1. Paste any Chinese text — textbook passages, poetry, stories
2. Choose grade level, art style (storybook / cartoon / ink painting / Chinese realism), aspect ratio, and scene count
3. Click "Parse Storyboard" — AI extracts key scenes and generates image prompts
4. Click "Generate Images" — calls Volcengine Seedream 5.0 to create all scene images
5. Click "Generate Videos" — calls Volcengine Seedance 1.5 Pro to animate each scene
6. Download all assets and import into AE / 剪映

---

## Supported Sizes

| Platform | Ratio | Resolution |
|---|---|---|
| Douyin (vertical) | 9:16 | 1440×2560 |
| Xiaohongshu (vertical) | 3:4 | 1728×2304 |
| Xiaohongshu (square) | 1:1 | 2K |
| Landscape (Bilibili / YouTube) | 16:9 | 2560×1440 |

---

## Getting Started

Open the link above, enter your Volcengine Ark API Key and start generating. Everything runs in the browser — no install, no login, no backend.

**Get an API Key:** [Volcengine Ark Console](https://console.volcengine.com/ark) → Create API Key

---

## Stack

- Single HTML file — no framework, no build tools
- Images: Volcengine Seedream 5.0
- Videos: Volcengine Seedance 1.5 Pro (async polling)
- CORS proxy: Netlify Functions

`Claude Code` · `Vanilla HTML / CSS / JS` · `GitHub Pages`
