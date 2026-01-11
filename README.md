# 中文网字计划 (The Chinese Web Fonts Plan)

> **让中文 Web 字体像英文一样轻快。**

这是一个致力于解决中文 Web 字体加载难题的开源项目，提供从**字体分割 (WASM)**、**CDN 加速**到**性能分析**的全链路解决方案。

---

## 🚀 核心价值

- **极速加载**：利用 `cn-font-split` 技术，将数 MB 的中文字体切分为按需加载的小分片，首屏加载速度提升 10 倍以上。
- **零成本部署**：专为静态托管（Netlify, Vercel, Cloudflare Pages）优化，无需复杂服务器即可拥有专业的字体服务。
- **极致性能**：基于 Astro 5.0 + Solid.js 的孤岛架构（Islands Architecture），实现 100/100 的 Lighthouse 性能评分。
- **智能分析**：内置字形查看器、覆盖度报告及 Web 支持度检测，让字体选择更科学。

---

## 🪄 AI 驱动的架构演进

本项目曾经历了一次从 `Solid.js + Vinxi` 到 `Astro` 架构的高难度迁移。

在此过程中，**[Zen Code](https://github.com/KonghaYao/zen-code)** 担任了**迁移项目的大主力**。

- **重构效率**：Zen Code 自动化处理了 90% 以上的组件迁移逻辑，将复杂的 SSR 逻辑无缝转换为 Astro 的高性能静态生成模式。
- **智能翻译**：利用 Zen Code 的代码理解能力，快速完成了多语言路由与 i18n 系统的重构。
- **样式升级**：在迁移过程中，Zen Code 辅助完成了从 Less 到 Tailwind CSS 的全面原子化升级，极大地减小了 CSS 体积。

_这就是 AI 辅助开发的未来：复杂的架构变更不再是研发的负担。_

---

## 🛠️ 技术特性

- **Astro 5.x**: 顶尖的静态站点生成框架，极致的构建产物。
- **Solid.js**: 响应式内核，驱动复杂的 WASM 字体分割逻辑。
- **WebAssembly**: 纯前端字体切分，保护隐私且不占用后端资源。
- **MDX 文章系统**: 支持数学公式、图表嵌入的开发者友好文档系统。
- **ECharts SSR**: 兼顾 SEO 与动态数据的图表展示方案。

---

## 📦 快速开始

```bash
# 克隆仓库
git clone https://github.com/KonghaYao/chinese-font.netlify.app.git

# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev
```

---

## 🤝 参与贡献

我们欢迎任何形式的贡献，无论是增加新的中文字体资源，还是改进分割算法。

---

## 📄 开源协议

本项目基于 [MIT](LICENSE) 协议开源。

---

**由 [Zen Code](https://github.com/KonghaYao/zen-code) 驱动，致力于构建更好的中文 Web 生态。**
