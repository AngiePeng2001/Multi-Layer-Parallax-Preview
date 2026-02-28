多图层视差效果预览 (Multi-Layer Parallax Preview)

🇨🇳 中文版说明 (Chinese Version)

在线演示地址 / Live Demo: [在此填写您的网址 / Fill your URL here]

一个基于原生 JavaScript 和 Tailwind CSS 构建的高性能、可定制化多图层视差效果预览工具。用户可以通过鼠标移动感受深度空间感，并利用侧边栏实时控制每一个图层的表现。

🚀 核心功能

动态视差引擎：基于鼠标坐标的实时位移算法，支持无限图层叠加。

图层管理器：侧边栏支持动态添加、删除图层，并能清晰显示图层的上下叠加顺序。

独立参数控制：可为每个图层单独调节移动幅度（速度）和不透明度。

实时资源加载：支持通过点击上传按钮实时更换图层图片。

多语言支持：内置中英文 UI 切换，满足不同用户需求。

黑色艺术遮罩：内置半透明黑色滤镜层，增强画面高级感和文字可读性。

🛠️ 技术栈

HTML5/CSS3 (CSS 变量, Flexbox, Transitions)

Tailwind CSS (用于侧边栏及 UI 布局)

Vanilla JavaScript (原生渲染逻辑，零依赖)

📦 快速开始

准备图片：在 HTML 文件同级目录下准备三张图片，分别命名为：1.png（前层）、2.png（中层）、3.png（后层）。

运行项目：直接在浏览器中打开 parallax_page.html 即可看到视差效果。

自定义体验：展开右侧边栏，尝试调整滑块改变不同图层的速度，或使用“清空图层图片”功能重新上传。

🇺🇸 English Version

Live Demo: [Fill your URL here / 在此填写您的网址]

A high-performance, customizable multi-layer parallax preview tool built with Vanilla JavaScript and Tailwind CSS. Experience immersive depth through mouse movement and manage layer behavior in real-time.

🚀 Key Features

Dynamic Parallax Engine: Real-time displacement algorithm based on mouse coordinates, supporting infinite layers.

Layer Manager: Sidebar for adding/deleting layers with clear visual order indicators (Top to Bottom).

Independent Parameter Control: Individually adjust Amplitude (Speed) and Opacity for each layer.

Real-time Resource Loading: Update layer images instantly via upload buttons.

Multi-language Support: Built-in toggle between Chinese and English UI.

Artistic Black Overlay: Integrated semi-transparent mask for enhanced aesthetics and text readability.

🛠️ Tech Stack

HTML5/CSS3 (CSS Variables, Flexbox, Transitions)

Tailwind CSS (For sidebar and UI layout)

Vanilla JavaScript (Native logic, zero dependencies)

📦 Quick Start

Prepare Images: Place three images in the same directory as the HTML file, named: 1.png (Front), 2.png (Middle), and 3.png (Back).

Run Project: Open parallax_page.html in your browser to view the effect.

Customize: Expand the sidebar to adjust speeds or clear images to upload your own artwork.

💡 Tips

Depth Design: Place detailed elements (rain, particles) in the "Front", subjects in the "Middle", and landscapes in the "Back".

Transparency: Use PNG images with transparency for the best blending results.

Physics: Usually, back layers should have a higher amplitude than front layers to mimic real-world perspective.

📄 开源协议 (License)

本项目采用 MIT 协议开源。 (This project is licensed under the MIT License.)
