# 🚀 EdgeOne Astro Blog - 基于 Astro 的极简博客系统

这是一个基于 [Astro Paper](https://github.com/satnaing/astro-paper) 魔改适配的博客项目，支持一键部署到 [腾讯云 EdgeOne Pages](https://cloud.tencent.com/product/edgeone/pages)，无须服务器，零配置快速上线你的个人博客 ✨

---

## 🌐 在线演示

> 点击访问博客预览地址：  
👉 https://edgeone-astro-blog.edgeone.app
---

## ✨ 项目亮点

- 💨 基于 Astro 构建，预渲染静态网站，极致性能
- 📄 支持 Markdown 写作，写文章像写笔记一样
- 🌙 暗色模式，响应式布局，移动端体验优良
- ⚙️ 一键部署至腾讯 EdgeOne Pages，无需服务器
- 🧩 魔改灵活，支持自行拓展页面、组件、主题

---

## 🚀 一键部署到 EdgeOne Pages

> 推荐使用腾讯 EdgeOne Pages 实现静态部署，仅需几步：
> [![Use EdgeOne Pages to deploy](https://cdnstatic.tencentcs.com/edgeone/pages/deploy.svg)](https://edgeone.ai/pages/new?repository-url=YOUR_REPO_URL)

### ✅ 部署步骤：

1. Fork 本项目
2. 登录腾讯云：https://console.cloud.tencent.com/edgeone/pages
3. 点击【新建站点】 ➜ 选择【导入 GitHub 仓库】
4. 选择你 Fork 的仓库后，配置以下构建参数：

| 参数项 | 设置值 |
|--------|--------|
| 安装命令 | `pnpm install`（或 `npm install`） |
| 构建命令 | `pnpm build`（或 `npm run build`） |
| 输出目录 | `dist` |

5. 点击部署，等待几秒，即可访问你的博客！

---

## 💻 本地开发指南

如果你想在本地调试和开发：

```bash
pnpm install        # 安装依赖（可用 npm 替代）
pnpm dev            # 启动本地开发服务器（http://localhost:4321）
pnpm build          # 构建静态文件
pnpm preview        # 预览构建后的文件
