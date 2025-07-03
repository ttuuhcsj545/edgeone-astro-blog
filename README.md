
# 🚀 EdgeOne Astro Blog - A Minimalist Blog System Based on Astro

This is a blog project customized from [Astro Paper](https://github.com/satnaing/astro-paper), adapted for one-click deployment on [Tencent Cloud EdgeOne Pages](https://cloud.tencent.com/product/edgeone/pages). No server needed, zero configuration to quickly launch your personal blog ✨
- [简体中文](README.CN.md)
- [English](README.md)
---

## 🌐 Live Demo

> Click to visit the blog preview:  
👉 https://edgeone-astro-blog.edgeone.app

---

## ✨ Project Highlights

- 💨 Built with Astro, pre-rendered static site for ultimate performance  
- 📄 Supports Markdown writing, making posting articles as easy as note-taking  
- 🌙 Dark mode, responsive layout, excellent mobile experience  
- ⚙️ One-click deployment to Tencent EdgeOne Pages, no server required  
- 🧩 Highly customizable, supports extending pages, components, and themes

---

## 🚀 One-Click Deployment to EdgeOne Pages

> We recommend using Tencent EdgeOne Pages for static deployment in just a few steps  
> [![Use EdgeOne Pages to deploy](https://cdnstatic.tencentcs.com/edgeone/pages/deploy.svg)](https://edgeone.ai/pages/new?repository-url=https://github.com/ttuuhcsj545/edgeone-astro-blog)

### ✅ Deployment Steps:

1. Fork this project  
2. Log in to Tencent Cloud: https://console.cloud.tencent.com/edgeone/pages  
3. Click "Create Site" ➜ Select "Import GitHub Repository"  
4. Select your forked repository and configure the build parameters as follows:

| Parameter     | Value                   |
|---------------|-------------------------|
| Install Command | `pnpm install` (or `npm install`) |
| Build Command   | `pnpm build` (or `npm run build`) |
| Output Directory| `dist`                  |

5. Click deploy and wait a few seconds to access your blog!

---

## 💻 Local Development Guide

If you want to debug and develop locally:

```bash
pnpm install        # Install dependencies (npm can be used instead)
pnpm dev            # Start local development server (http://localhost:4321)
pnpm build          # Build static files
pnpm preview        # Preview the built files
```
