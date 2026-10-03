# 你好，我是 Jum 👋

**结构工程 · 参数化建模 · 有限元可视化**

🌐 [tilyes.github.io](https://tilyes.github.io) ｜ ✉️ [leijun0601@foxmail.com](mailto:leijun0601@foxmail.com)

---

## 关于我

- 华南理工大学土木与交通学院结构工程专业博士研究生，本科与硕士也都读在这里。研究方向是结构与构件的**冲击动力学**：装配式混凝土柱在水平冲击下的动力失效机理与加固方法，此前还做过广府古建木结构的抗震性能。日常的构成大致是试验、有限元建模，以及大量的数据处理。
- 特别感兴趣的一件事，是**把机器学习用到结构工程里**：用图神经网络结合 Transformer 预测钢筋混凝土构件的冲击力时程响应；用 GRU 从公开试验数据中预测柱的滞回曲线；用 U-Net 做混凝土裂缝的像素级分割。熟悉 RNN、CNN、Transformer 等网络结构，日常用 PyTorch 与 TensorFlow，也在用 LangChain、Dify 搭一些小的智能体应用。
- 有个改不掉的习惯：看到两处代码在重复算同一件事，就想把它们合并成一处——因为这种重复不会报错，只会在某天悄悄给出一个对不上的结果。

## 🛠 技术栈

**编程**　Python · C++20 · LaTeX · Git

**工程分析**　OpenSees · Abaqus · SAP2000 · 有限元分析

**图形 / 工具链**　Vulkan · ImGui · CMake · vcpkg · GLSL

**研究方向**　结构冲击动力学 · 装配式混凝土 · 古建木结构抗震

## 🚀 项目

- **[OpenSees-GPU-Solver](https://github.com/Tilyes/OpenSees-GPU-Solver)** — 在 OpenSees 之上接入自研的 cuSPARSE GPU 迭代求解器（CG / BiCGStab + Jacobi / ILU(0) 预条件）。三个 3D 场景相较串行 SuperLU 最高加速 212×，并定位了 sm_120 平台上两个损坏的官方 API。
- **[Geodesic-Shell-Parametric-Modeling](https://github.com/Tilyes/Geodesic-Shell-Parametric-Modeling)** — 短程线网壳参数化建模脚本。按正二十面体五重对称做 Class I 弦分法生成球面杆系，自动搜索最优分角让杆长尽可能均匀，再导出 Abaqus / SAP2000 模型。
- **[OpenSees_viewer](https://github.com/Tilyes/OpenSees_viewer)** — 基于 C++20 + Vulkan 的 OpenSees 有限元模型 3D 可视化工具，含 TCL 模型解析、离屏渲染与轨道相机。
- **[Tilyes.github.io](https://github.com/Tilyes/Tilyes.github.io)** — 个人主页站点，零依赖纯静态，Markdown 渲染器自己写。

## ✍️ 最近写的

- [在 OpenSees 里塞进一块 GPU：把有限元求解加速 212 倍](https://tilyes.github.io/post.html?p=opensees-gpu-solver) — 2026-10-03
- [从 450 行到 280 行：一次网壳建模脚本的重构](https://tilyes.github.io/post.html?p=refactor-geodesic-shell) — 2026-10-03
- [用不到 100 行写一个够用的 Markdown 渲染器](https://tilyes.github.io/post.html?p=mini-markdown-renderer) — 2026-09-28
- [为什么我把个人主页搬到了 GitHub Pages](https://tilyes.github.io/post.html?p=hello-github-pages) — 2026-09-20

## 📫 找我

[GitHub](https://github.com/Tilyes) · 邮箱：leijun0601@foxmail.com

---

[![GitHub 统计](https://github-readme-stats.vercel.app/api?username=Tilyes&show_icons=true&hide_border=true)](https://github.com/Tilyes)

<sub>这个 README 由 <b>Tilyes/Tilyes</b> 仓库渲染，显示在 github.com/Tilyes 个人页。</sub>
