# 🎨✂️✨ 在线SVG编辑器与转换器

一个强大且用户友好的在线工具，用于编辑、查看、优化和转换SVG图形。它提供了一个实时编辑器、即时预览，并集成了SVGO进行高效的代码压缩，同时支持多种图片格式（PNG, JPEG, ICO）和Data URI的导出。

## 🚀 在线体验

[**点击此处在线体验 (若已部署), https://199311.xyz/svg/**](https://199311.xyz/svg/)

## ✨ 主要功能

*   **实时代码编辑器**: 基于 [Ace Editor](https://ace.c9.io/) 提供语法高亮、代码补全、自动换行和行号显示等专业编辑体验。
*   **即时SVG预览**: 在您编辑SVG代码的同时，右侧面板会立即渲染并显示结果。
*   **SVG优化与压缩**:
    *   集成 [SVGO](https://github.com/svg/svgo) 库，一键对SVG代码进行高效压缩，显著减小文件大小。
    *   支持单独的“格式化”功能，使代码更具可读性。
    *   显示原始大小、压缩后大小以及压缩率，直观展示优化效果。
*   **灵活的SVG导入**: 支持通过点击“上传”按钮选择文件，或直接将SVG文件拖拽到页面任意位置进行导入。
*   **强大的导出功能**:
    *   **图片导出**: 将SVG导出为PNG、JPEG和ICO格式，支持自定义导出宽度。
        *   ICO导出支持多种常见尺寸（16x16, 32x32, 64x64等），方便生成网站图标。
    *   **Data URI导出**: 提供三种Data URI形式，方便在CSS或HTML中直接嵌入SVG：
        *   Minified Data URI (压缩后的编码)
        *   Base64编码
        *   `encodeURIComponent` 编码
*   **预览区域交互**: 支持鼠标滚轮缩放和拖拽平移功能，方便查看SVG细节。
*   **一键复制与下载**: 快速复制SVG代码或各种导出内容到剪贴板，或直接下载生成的SVG及图片文件。
*   **简洁的用户界面**: 直观、易用的布局，让SVG操作变得简单高效。

## 🛠️ 技术栈

*   **前端框架**: [Vue 3](https://vuejs.org/) (通过CDN引入，轻量级)
*   **代码编辑器**: [Ace Editor](https://ace.c9.io/) (强大的JavaScript代码编辑器)
*   **SVG优化**: [SVGO](https://github.com/svg/svgo) (用于JavaScript的Node.js工具，通过CDN引入其浏览器版本)
*   **核心语言**: HTML5, CSS3, JavaScript

## ⚙️ 本地运行

本项目是一个独立的HTML文件，无需复杂的构建过程或后端服务器即可运行。

# 其他说明
- 页面效果图见`appimg`目录
- <img src="https://gcore.jsdelivr.net/gh/dhjz/svg@master/appimg/app1.jpg" style="width: 340px;"/>
- <img src="https://gcore.jsdelivr.net/gh/dhjz/svg@master/appimg/app2.jpg" style="width: 340px;"/>

- 项目地址: [https://github.com/dhjz/svg]( https://github.com/dhjz/svg)  
- 预览地址: [https://199311.xyz/svg/](https://199311.xyz/svg/)