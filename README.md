# AI工作流适用性评估工具

> **仓库简介（Repository Description）**
>
> 3 分钟回答 13 个问题，快速评估一项业务 / 任务是否值得引入 AI 工作流，并给出可执行的下一步建议。内置多个行业案例，一键填充即可体验。

---

## 在线体验 (Live Demo)

> ❗ 在 GitHub Pages / Vercel / Netlify 上静态托管即可跑起来，**零后端依赖**。
>
> * **Demo URL**：`https://your-domain.com/ai-workflow-evaluator/`

---

## 功能亮点 (Features)

| # | 模块               | 说明                                                        |
| - | ---------------- | --------------------------------------------------------- |
| 1 | **13 道评估题**      | 覆盖流程标准化、风险等级、创意需求、数据结构化等多维度指标，自动打分并映射到 4 个决策层级。           |
| 2 | **即时进度反馈**       | 进度条 + 已答题数，让受访者随时了解完成度。                                   |
| 3 | **行业案例一键填充**     | 内置 “发票审核”“热线客服”“品牌广告脚本”“仓库分拣机器人” 4 个示例场景，点击即可自动填写并获得评估结果。 |
| 4 | **结果解读 + 下一步行动** | 根据总分自动生成建议，附带针对单项弱点的提醒 (advices)。                         |
| 5 | **零后端・纯前端**      | 使用 **Alpine.js + TailwindCSS + DaisyUI**，任何静态服务器即可部署。     |

---

## 技术栈 (Tech Stack)

* **Alpine 3** – 轻量级响应式框架，负责状态管理 & 交互逻辑。
* **TailwindCSS 3.4** – 原子化 CSS。
* **DaisyUI 4.12** – Tailwind 组件库，加速 UI 开发。
* **HTML5 + vanilla JS** – 无构建依赖，直接打开 `index.html` 即可运行。

---

## 快速开始 (Quick Start)

```bash
# 1. 克隆仓库
$ git clone https://github.com/your-name/ai-workflow-evaluator.git
$ cd ai-workflow-evaluator

# 2. 本地预览（任选其一）
# 方法 A：使用 VS Code Live Server 插件
# 方法 B：Python 简易 HTTP 服务
$ python -m http.server 8080
# 访问 http://localhost:8080 即可

# 方法 C：直接双击 index.html（某些浏览器 CSP 会拦截本地文件中的 import，推荐使用 A/B）
```

### 构建 & 部署

该项目无任何打包步骤，直接把整个目录推到静态托管平台即可：

* **GitHub Pages**：在 Repository → Settings → Pages 中选择 `main` 分支 `/ (root)`。
* **Vercel / Netlify**：新建项目，Root 设置为仓库根目录。无 Build Command；Publish Dir 留空或填 `/`。

---

## 目录结构 (Project Structure)

```
.
├─ index.html                # 主应用 (canvas 内文件 Ai Workflow Evaluator With Sample)
├─ README.md                 # 本说明文档
└─ LICENSE                   # 许可证 (默认为 MIT，可自行更改)
```

> 💡 **index.html 已内联所有脚本与样式**，方便单文件部署；如需拆分或引入构建工具，请自行调整引用路径。

---

## 贡献指南 (Contributing)

1. **Fork → Clone → Create Branch**（遵循 `feat/xxx` / `fix/xxx` 命名）。
2. 提交 **简明 Commit Message**，推荐遵循 [Conventional Commits](https://www.conventionalcommits.org/lang/zh-hans/)。
3. 发送 **Pull Request** 并在描述中说明变更目的、相关 Issue 与截图 / 演示。
4. 维护者会尽快 Review & Merge 👀。

欢迎提交：

* 新的行业案例 (`samples` 数组)
* UI/UX 优化
* 国际化 (i18n)
* Bug 修复 & 性能提升

---

## License

[MIT](./LICENSE) © 2025 Your Name
