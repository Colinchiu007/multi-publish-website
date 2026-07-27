# Multi-Publish 官网

Multi-Publish 官方网站的静态页面仓库。

## 关于项目

Multi-Publish 是一个开源 AI 内容工作站：一份内容，触达全网。支持 15+ 平台一键发布、50+ AI 服务商、13 视频创作管线，Cookie 本地 AES-256-GCM 加密，可离线运行。

本仓库仅包含官网相关的代码和资源，独立于 [multi-publish](https://github.com/multi-publish/multi-publish) 主项目。

## 文件结构

```
.
├── index.html              # 官网首页
├── images/                 # 轮播图与视觉素材
│   ├── ai-content.jpg
│   ├── global-distribution.jpg
│   └── video-creation.jpg
└── docs/                   # 设计与规划文档
    ├── WEBSITE-DESIGN-COHERE.md
    └── WEBSITE-PLAN.md
```

## 视觉设计

官网采用 Cohere 风格的极简设计系统：

- 浅色背景 + 暖灰辅助色
- 几何感标题字体 Space Grotesk
- 珊瑚色（#ff7759）作为点缀
- 大圆角卡片与胶囊按钮

详见 [docs/WEBSITE-DESIGN-COHERE.md](docs/WEBSITE-DESIGN-COHERE.md)。

## 本地预览

直接用浏览器打开 `index.html` 即可预览。也可以使用任意静态文件服务器：

```bash
npx serve .
```

## 图片版权

轮播图来自 [Pexels](https://www.pexels.com/) 免费图库，遵循 Pexels 许可协议，可免费用于商业和非商业用途：

- `ai-content.jpg` — Photo by [Markus Winkler](https://www.pexels.com/@markus-winkler-1430818/)
- `global-distribution.jpg` — Photo by [Gabby K](https://www.pexels.com/@gabby-k-7411941/)
- `video-creation.jpg` — Photo by [Ron Lach](https://www.pexels.com/@ron-lach-8089248/)

## License

MIT License © 2026 Multi-Publish
