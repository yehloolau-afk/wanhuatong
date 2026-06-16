# WanHuaTong · 万花筒

**Live →** [yehloolau-afk.github.io/wanhuatong](https://yehloolau-afk.github.io/wanhuatong/)

Chinese elementary school text-to-video automation. Paste a lesson text, get a full storyboard, AI-generated images, and AI-generated video clips — ready to edit.

---

## Workflow

```
Lesson text → Storyboard → AI Images → AI Video clips → Download
```

1. Paste the lesson text (e.g. a classical poem or prose)
2. Auto-generates storyboard scenes with visual descriptions
3. Batch generates images via Volcengine Seedream
4. Batch generates video clips via Volcengine Seedance
5. Download all assets for post-production

---

## How to use

Open the live link above. Bring your own Volcengine API key — everything runs in the browser, nothing is sent to a server.

**Default settings:** Grade 1 · Storybook style · 6 scenes

---

## How it's built

- Single HTML file — open and use, no install
- No backend, no login, no framework
- Image API: `Volcengine Seedream 5.0`
- Video API: `Volcengine Seedance 1.5 Pro` (async polling)

`Claude Code` · `Vanilla HTML / CSS / JS`
