# 万花筒 · WanHuaTong

**Live →** [yehloolau-afk.github.io/wanhuatong](https://yehloolau-afk.github.io/wanhuatong/)

粘贴任意文本，自动生成分镜脚本、AI 图片、AI 视频片段，一键下载素材。

> Paste any Chinese text → get a full storyboard, AI-generated images, and video clips — ready to edit in AE / 剪映.

---

## 效果展示

写实国风风格 · 4 个分镜场景自动生成：

![万花筒效果截图](https://yehloolau-afk.github.io/wanhuatong/preview.png)

---

## 工作流

```
粘贴文本 → 配置参数 → 解析分镜 → 批量生图 → 批量生视频 → 下载素材
    1           2           3           4           5           6
```

1. 粘贴课文、古诗、故事等任意文本
2. 选择年级、画面风格（故事绘本 / 卡通动漫 / 中国水墨 / 写实国风）、输出尺寸、场景数量
3. 点「解析分镜脚本」—— AI 自动提取关键画面并生成中文图像提示词
4. 点「批量生图」—— 调用 Volcengine Seedream 5.0 一键生成所有场景图片
5. 点「批量生视频」—— 调用 Volcengine Seedance 1.5 Pro 生成视频片段
6. 下载全部素材导入 AE / 剪映合成

---

## 支持尺寸

| 平台 | 比例 | 分辨率 |
|---|---|---|
| 抖音竖屏 | 9:16 | 1440×2560 |
| 小红书竖版 | 3:4 | 1728×2304 |
| 小红书方形 | 1:1 | 2K |
| 横屏（B站 / YouTube） | 16:9 | 2560×1440 |

---

## 如何使用

打开上方链接，填入自己的火山方舟 API Key 即可开始。所有生成均在浏览器端完成，无需安装，无需登录，无后端。

**API Key 获取**：[火山方舟控制台](https://console.volcengine.com/ark) → 创建 API Key

---

## 技术栈

- 单文件 HTML，无框架，无构建工具
- 图片：Volcengine Seedream 5.0
- 视频：Volcengine Seedance 1.5 Pro（异步轮询）
- CORS 代理：Netlify Functions

`Claude Code` · `Vanilla HTML / CSS / JS` · `GitHub Pages`
