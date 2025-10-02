# 🎉 喵咕记事本 v1.0.0 正式发布

![GitHub Release](https://img.shields.io/badge/release-v1.0.0-orange) [![Date](https://img.shields.io/badge/date-2025--09--2-blue)](https://github.com/hhyufan/miaogu-ide)

## 🚀 版本亮点

### ✨ 首个正式版本发布

这是喵咕记事本的首个正式版本，标志着一个**超轻量级代码高亮记事本**的诞生！基于 **Tauri + React + Monaco Editor**
技术栈，实现了桌面应用的性能与现代 Web 技术的完美融合。

### 🎯 核心优势

- **🪶 极致轻量**: 应用体积仅 **< 15.9MB**，相比传统 Electron 应用减少 90%+ 体积
- **⚡ 单文件部署**: 打包生成单个 `.exe` 文件，无需安装，即下即用
- **🔥 原生性能**: 基于 Rust 后端 + 系统 WebView，启动秒开，内存占用极低
- **🌍 零依赖运行**: 无需预装 Node.js、.NET Framework 等运行时环境

## 📋 功能特性

### 🎨 编辑器功能

- **Monaco Editor 集成**: 提供 VS Code 级别的代码编辑体验
- **语法高亮**: 支持 100+ 编程语言的语法高亮
- **智能补全**: 内置代码补全和语法提示
- **多主题支持**: 内置亮色/暗色主题，支持主题切换
- **代码折叠**: 支持代码块折叠和展开

### 📁 文件管理

- **多标签页**: 支持同时编辑多个文件
- **自动保存**: 智能检测文件变更并提示保存

### ⚙️ 个性化设置

- **编辑器配置**: 字体大小、行号显示、自动换行等
- **主题定制**: 亮色/暗色主题一键切换
- **窗口设置**: 支持窗口透明度、无边框模式
- **快捷键**: 完整的快捷键支持

## 🛠 技术架构

### 前端技术栈

- **React 18.3.1**: 现代化的用户界面框架
- **Ant Design 5.10.0**: 企业级 UI 组件库
- **Monaco Editor 0.52.2**: VS Code 同款编辑器内核
- **Redux Toolkit**: 状态管理和数据持久化
- **Vite 6.2.4**: 极速的前端构建工具

### 后端技术栈

- **Tauri 2.x**: Rust 驱动的桌面应用框架
- **Rust**: 内存安全的系统编程语言
- **系统 WebView**: 复用操作系统内置浏览器引擎

## 🎯 使用场景

- **代码片段编辑**: 快速编辑和测试代码片段
- **配置文件编辑**: 编辑 JSON、YAML、TOML 等配置文件
- **脚本编写**: 编写 Shell、Python、JavaScript 等脚本
- **文档编写**: 支持 Markdown 语法高亮

## 🙏 致谢

感谢以下开源项目的支持：

- [Tauri](https://tauri.app/) - 现代化的桌面应用框架
- [Monaco Editor](https://microsoft.github.io/monaco-editor/) - 强大的代码编辑器
- [React](https://reactjs.org/) - 用户界面构建库
- [Ant Design](https://ant.design/) - 企业级 UI 设计语言
- [Rust](https://www.rust-lang.org/) - 系统编程语言

## 📄 许可证

本项目采用 MIT 许可证，详见 [LICENSE](./LICENSE) 文件。

---

如果您觉得这个项目有用，请给我们一个 ⭐ Star，您的支持是我们持续改进的动力！
