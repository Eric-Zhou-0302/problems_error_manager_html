# 错题整理系统

[English](#wrong-question-management-system) | 简体中文

## 项目简介

错题整理系统是一个基于Web的错题管理工具，帮助用户高效收集、整理和管理学习中的错题。系统支持文本输入、图片上传、Markdown编辑和数学公式渲染等功能，所有数据存储在浏览器本地，确保用户隐私安全。

Wrong Question Management System is a web-based tool designed to help users efficiently collect, organize, and manage wrong questions encountered during study. It supports text input, image uploads, Markdown editing, and mathematical formula rendering. All data is stored locally in the browser, ensuring user privacy and security.

## 功能特点

- 📝 **Markdown支持**：使用Markdown格式编辑错题内容
- 📊 **数学公式渲染**：支持LaTeX数学公式
- 🖼️ **图片拖拽上传**：支持题目和答案图片上传
- 🏷️ **标签系统**：为错题添加标签以便分类和搜索
- 📈 **数据统计**：可视化展示错题分布和添加趋势
- ⏰ **时间线视图**：按时间顺序查看错题记录
- 🎨 **主题切换**：支持浅色/深色主题
- 💾 **本地存储**：所有数据保存在浏览器本地
- 📤 **多种导出格式**：支持HTML、PDF和ZIP格式导出
- ⌨️ **快捷键支持**：提供多种快捷键提高操作效率

## 使用说明

### 基本操作

1. **添加错题**：
   - 在编辑页面填写知识点、题目、答案和解题思路
   - 拖放或粘贴图片到题目/答案区域
   - 使用Markdown和LaTeX语法丰富内容
   - 设置重要性级别和标签

2. **管理错题**：
   - 在预览页面查看所有错题
   - 使用搜索功能筛选错题
   - 点击错题可编辑或删除

3. **导出错题**：
   - 支持导出为HTML知识卡片
   - 支持导出为PDF文档
   - 支持导出为包含Markdown和图片的ZIP压缩包

### 快捷键

- `Ctrl+S`：保存当前错题
- `Esc`：重置当前编辑内容
- `P`：在编辑和预览页面间切换
- `D`：切换深色/浅色模式
- `1-4`：快速切换不同页面（编辑、预览、统计、时间线）

## 技术栈

- **前端**：纯HTML5 + CSS3 + JavaScript
- **Markdown解析**：Marked.js
- **数学公式**：KaTeX
- **图表展示**：Chart.js
- **文件处理**：JSZip, FileSaver.js
- **PDF生成**：jsPDF, html2canvas
- **拖拽排序**：Sortable.js
- **粒子效果**：particles.js
- **图标库**：Font Awesome

## 项目结构

```
错题整理系统/
├── index.html          # 主HTML文件（包含所有CSS和JS代码）
├── README.md           # 项目说明文档
└── (无需其他依赖，所有资源通过CDN引入)
```

## 如何运行

1. 直接使用浏览器打开`index.html`文件
2. 或部署到任何Web服务器上

**注意**：由于使用了一些现代浏览器特性，请确保使用现代浏览器（Chrome、Firefox、Safari、Edge等）访问。

## 贡献

欢迎提交Issue和Pull Request来改进这个项目。

## 许可证

本项目采用MIT许可证。详见LICENSE文件。

## 联系方式

- 作者：Eric_Zhou
- 邮箱：18803166626@163.com

---

# Wrong Question Management System

English | [简体中文](#错题整理系统)

## Project Introduction

Wrong Question Management System is a web-based tool designed to help users efficiently collect, organize, and manage wrong questions encountered during study. It supports text input, image uploads, Markdown editing, and mathematical formula rendering. All data is stored locally in the browser, ensuring user privacy and security.

## Features

- 📝 **Markdown Support**: Edit wrong question content using Markdown format
- 📊 **Mathematical Formula Rendering**: Support for LaTeX mathematical formulas
- 🖼️ **Drag-and-Drop Image Upload**: Support for uploading question and answer images
- 🏷️ **Tag System**: Add tags to wrong questions for categorization and search
- 📈 **Data Statistics**: Visual display of wrong question distribution and addition trends
- ⏰ **Timeline View**: View wrong question records in chronological order
- 🎨 **Theme Switching**: Support for light/dark themes
- 💾 **Local Storage**: All data is saved locally in the browser
- 📤 **Multiple Export Formats**: Support for HTML, PDF, and ZIP format exports
- ⌨️ **Shortcut Key Support**: Various shortcut keys to improve operational efficiency

## Usage Instructions

### Basic Operations

1. **Add Wrong Questions**:
   - Fill in knowledge points, questions, answers, and solution ideas on the edit page
   - Drag and drop or paste images into the question/answer area
   - Enrich content using Markdown and LaTeX syntax
   - Set importance levels and tags

2. **Manage Wrong Questions**:
   - View all wrong questions on the preview page
   - Use search function to filter wrong questions
   - Click on wrong questions to edit or delete

3. **Export Wrong Questions**:
   - Support for export as HTML knowledge cards
   - Support for export as PDF documents
   - Support for export as ZIP archives containing Markdown and images

### Shortcut Keys

- `Ctrl+S`: Save current wrong question
- `Esc`: Reset current editing content
- `P`: Switch between edit and preview pages
- `D`: Toggle dark/light mode
- `1-4`: Quickly switch between different pages (edit, preview, statistics, timeline)

## Technology Stack

- **Frontend**: Pure HTML5 + CSS3 + JavaScript
- **Markdown Parsing**: Marked.js
- **Mathematical Formulas**: KaTeX
- **Chart Display**: Chart.js
- **File Processing**: JSZip, FileSaver.js
- **PDF Generation**: jsPDF, html2canvas
- **Drag-and-Drop Sorting**: Sortable.js
- **Particle Effects**: particles.js
- **Icon Library**: Font Awesome

## Project Structure

```
Wrong-Question-Management-System/
├── index.html          # Main HTML file (contains all CSS and JS code)
├── README.md           # Project documentation
└── (No other dependencies, all resources are imported via CDN)
```

## How to Run

1. Directly open the `index.html` file in a browser
2. Or deploy to any web server

**Note**: Due to the use of some modern browser features, please ensure you use a modern browser (Chrome, Firefox, Safari, Edge, etc.) to access.

## Contributing

Issues and Pull Requests are welcome to improve this project.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact

- Author: Eric_Zhou
- Email: 18803166626@163.com
