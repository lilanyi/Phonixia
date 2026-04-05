# MTF HRT 知识库

> 跨性别女性激素替代治疗（HRT）中文知识库

## 📖 关于

这是一个关于跨性别女性激素替代治疗（HRT）的中文知识库，基于：
- Reddit 社区经验
- Transfeminine Science 科学研究
- 医学文献
- 中文社区实践

## 🌐 本地预览

### 安装 Hugo

```powershell
winget install Hugo.Hugo.Extended
```

### 克隆并运行

```bash
git clone --recurse-submodules https://github.com/your-repo/hrt-knowledge-base.git
cd hrt-knowledge-base
hugo server
```

打开 http://localhost:1313/

## 🚀 部署到 GitHub Pages

1. 创建 GitHub 仓库
2. 推送代码：
   ```bash
   git remote add origin https://github.com/your-repo/hrt-knowledge-base.git
   git push -u origin main
   ```
3. 在仓库设置中启用 GitHub Pages，选择 GitHub Actions
4. 网站会自动部署到 `https://your-username.github.io/hrt-knowledge-base/`

## 📁 项目结构

```
hrt-knowledge-base/
├── content/           # 网站内容（Markdown）
│   ├── basics/       # 基础知识
│   ├── development/  # 发育指南
│   ├── regimens/     # 用药方案
│   ├── safety/       # 安全警示
│   └── resources/    # 资源链接
├── static/           # 静态文件（图片、视频）
├── layouts/          # 自定义布局
├── themes/PaperMod/  # 主题（Git 子模块）
└── hugo.yaml         # Hugo 配置
```

## 🔄 未来升级

### 添加搜索功能

使用 Algolia 或 Fuse.js（已配置）

### 添加评论系统

使用 Giscus（基于 GitHub Discussions）：
1. 在 hugo.yaml 中取消注释 giscus 配置
2. 填入你的 GitHub 仓库信息

### 迁移到动态网站

所有内容都是 Markdown 文件，可以轻松迁移到：
- Next.js
- Nuxt
- Astro
- 其他静态站点生成器

## ⚠️ 免责声明

本站内容**仅供参考**，不构成医疗建议。

- 所有 DIY 方案都有风险
- 建议在医生指导下进行 HRT
- 定期血液检测是必须的
- 个体差异很大，他人经验不一定适用于你

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

*维护者：Nova AI*
*创建时间：2026-04-05*
