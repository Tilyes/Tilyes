# 你好，我是 Jum 👋

**结构工程 · 参数化建模 · 有限元可视化**

🌐 [jumjumblog.com](https://jumjumblog.com) ｜ ✉️ [leijun0601@foxmail.com](mailto:leijun0601@foxmail.com)

---

## 关于我

- 做结构工程的，方向是**空间结构与短程线网壳**。日常在 Python 里算几何，再把模型丢进有限元软件里验证结构性能。
- 最近在写一个 **OpenSees 模型的 3D 可视化工具**，C++20 + Vulkan，从 Instance 创建、Swapchain 到离屏渲染整条链路自己搭了一遍，界面用 ImGui。
- 有点强迫症地喜欢把重复代码收拾干净：网壳脚本里「搜索最优系数」和「建模」原本各算一遍几何，现在只算一次，Abaqus 和 SAP2000 两个下游共用同一份拓扑。

## 🛠 技术栈

**编程**　Python · C++20 · LaTeX · Git

**工程分析**　OpenSees · Abaqus · SAP2000 · 有限元分析

**图形 / 工具链**　Vulkan · ImGui · CMake · vcpkg · GLSL

**研究方向**　空间结构 · 短程线网壳 · 参数化建模

## 🚀 项目

- **[Geodesic-Shell-Parametric-Modeling](https://github.com/Tilyes/Geodesic-Shell-Parametric-Modeling)** — 短程线网壳参数化建模脚本。按正二十面体五重对称做 Class I 弦分法生成球面杆系，自动搜索最优分角让杆长尽可能均匀，再导出 Abaqus / SAP2000 模型。
- **[OpenSees_viewer](https://github.com/Tilyes/OpenSees_viewer)** — 基于 C++20 + Vulkan 的 OpenSees 有限元模型 3D 可视化工具，含 TCL 模型解析、离屏渲染与轨道相机。
- **[Tilyes.github.io](https://github.com/Tilyes/Tilyes.github.io)** — 个人主页站点，零依赖纯静态，Markdown 渲染器自己写。

## ✍️ 最近写的

- [从 450 行到 280 行：一次网壳建模脚本的重构](https://jumjumblog.com/post.html?p=refactor-geodesic-shell) — 2026-10-03
- [用不到 100 行写一个够用的 Markdown 渲染器](https://jumjumblog.com/post.html?p=mini-markdown-renderer) — 2026-09-28
- [为什么我把个人主页搬到了 GitHub Pages](https://jumjumblog.com/post.html?p=hello-github-pages) — 2026-09-20

## 📫 找我

[GitHub](https://github.com/Tilyes) · 邮箱：leijun0601@foxmail.com

---

[![GitHub 统计](https://github-readme-stats.vercel.app/api?username=Tilyes&show_icons=true&hide_border=true)](https://github.com/Tilyes)

<sub>这个 README 由 <b>Tilyes/Tilyes</b> 仓库渲染，显示在 github.com/Tilyes 个人页。</sub>
