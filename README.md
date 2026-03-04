# 🧩 字库崩了 · Glitch Font Generator

> 模拟公交LED屏幕字库损坏的乱码生成器  
> A playful glitch generator that simulates a broken Chinese font library, just like those flickering bus stop displays.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## 📖 简介 · Introduction

**中文**  
输入任意文本，点击“转换”，程序会随机将一部分字符替换为错别字、异体符号或乱码，重现“字库崩了”的经典场景。例如：  
`温迪是蒙德的风神。` → `问迪⑩蒙的の疯神？`  
适合生成故障艺术、创意表情包，或作为前端字符回退机制的趣味测试。

**English**  
Enter any text and hit “Convert”. The tool randomly replaces characters with typos, weird symbols, and unexpected glyphs — mimicking a corrupted font library on an LED signboard.  
Example:  
`The quick brown fox jumps over the lazy dog.` → `Tｈe qu!ck br@wn f0x jump$ 0ver the la%y d0g.`  
Perfect for glitch art, memes, or testing fallback font behavior in browsers.

---

## ✨ 功能特点 · Features

- **随机替换**：从包含数字、字母、日文假名、希腊字母、特殊符号及常见错别字的故障池中随机抽取字符。
- **强度调节**：滑动条控制“崩坏概率”（0% ～ 100%），可制造轻微干扰或彻底混乱。
- **保留格式**：空格、换行符等不会被替换，保持原文排版。
- **快捷键**：在文本框内按 `Ctrl + Enter` 快速触发转换。
- **纯前端**：无需后端，打开即用，所有处理均在本地浏览器完成。

---

## 📝 使用方法 · How to Use

1. 在文本框中输入或粘贴你想要“破坏”的文字。
2. 拖动下方的滑块，调整崩坏强度（百分比越高，被替换的字符越多）。
3. 点击 **✨ 转换 · 字库崩坏** 按钮，或直接按 `Ctrl + Enter`。
4. 下方输出区域立即显示乱码结果，可复制分享。

---

## 🛠️ 技术实现 · Technical Details

- **核心逻辑**：遍历输入字符串的每个字符（除空白符外），根据设定的概率决定是否替换。若替换，则从预定义的故障字符池中随机选取一个字符。
- **故障池设计**：包含数字、大小写字母、常用标点、日文假名、希腊字母、特殊符号、带圈数字以及大量常见错别字（如同音字、形近字），总计约 300+ 个候选字符。
- **保留空白**：对空格、制表符、换行符不做处理，保持原文段落结构。
- **UI 交互**：使用原生 HTML/CSS/JavaScript，无任何外部依赖，响应式布局适配手机与桌面。

---

## 🤖 AI 生成声明 · AI Generation Note

本项目绝大部分代码由 **AI 助手（DeepSeek）** 辅助生成，包括核心逻辑、界面设计及文档编写。  
生成过程遵循清晰的需求拆解与迭代优化，最终由人工审核并微调。  
本工具旨在展示 AI 在创意编码与趣味工具开发中的辅助能力，所有代码均可自由使用、修改和分发。

---

## 📦 部署到 GitHub Pages

1. 将本仓库克隆或下载到本地。
2. 确保首页文件名为 `index.html`。
3. 在 GitHub 上创建一个名为 `你的用户名.github.io` 的仓库（公开）。
4. 将文件推送到该仓库的 `main` 分支。
5. 进入仓库 Settings → Pages，选择 `main` 分支并保存，等待几分钟即可通过 `https://你的用户名.github.io` 访问。

> 详细图文教程可参考 [GitHub Pages 官方文档](https://pages.github.com/)。

---

## 📄 许可证 · License

本项目采用 **MIT 许可证**，你可以自由使用、修改、分发，甚至用于商业目的，只需保留原版权声明。

---

## 🙌 致谢 · Acknowledgements

- 灵感来源于街头那些“字库崩了”的公交 LED 显示屏。
- 字符池参考了日常错别字与 Unicode 符号表。
- 感谢 AI 技术让创意快速落地。

---

**Have fun glitching!** 🎛️
