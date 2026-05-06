# VS Code 离线安装包与插件合集 (Windows 7 & Windows 10/11)

本仓库专为 PHP 和 HTML 开发者整理，提供了适配不同 Windows 系统的 VS Code 安装包及核心插件。

## 🚀 快速下载

👉 **[点击前往下载页面 (Releases v1.2.0)](https://github.com/yangyu91/vscode-collection/releases/tag/v1.2.0)**

---

## 📦 包含内容与插件详解

### 1. VS Code 安装程序
- **VSCode_Win7_v1.70.2.exe**: 适配 Windows 7 的最后稳定版。
- **VSCode_Win10_11_Latest.exe**: 适配 Windows 10/11 的最新稳定版。

### 2. 核心插件列表 (VSIX)
*注：文件名带 `_Win7` 的适配旧版 VS Code，带 `_Win10_11` 的为最新版。*

#### 🐘 PHP 开发增强 (解决补全问题)
- **Intelephense (PHP 智能感知)**
  - **作用**: 提供代码补全、跳转到定义、语法检查。
- **PHP IntelliSense (补全增强)**
  - **作用**: 作为 Intelephense 的补充，提供更深层的代码分析和补全。
- **PHP Namespace Resolver (命名空间解析)**
  - **作用**: 自动导入类名（Import Class）和修复命名空间。
  - **用法**: 选中类名，按 `Ctrl+Alt+I` 自动导入。
- **PHP Debug (调试)**
  - **作用**: 配合 Xdebug 进行断点调试，查看变量值。
- **PHP DocBlocker (文档注释)**
  - **作用**: 快速生成标准的 PHP 函数/类注释。
  - **用法**: 在函数上方输入 `/**` 然后按回车。

#### 🌐 基础与界面
- **Chinese Language Pack (简体中文包)**
  - **作用**: 将 VS Code 界面汉化。
- **Material Icon Theme (图标主题)**
  - **作用**: 为不同类型的文件提供精美的可视化图标。
- **Bracket Pair Colorizer (彩虹括号)**
  - **作用**: 用不同颜色区分嵌套的括号。

#### 📝 HTML/CSS 增强
- **HTML CSS Support**: 自动补全 CSS 样式名。
- **Auto Rename Tag (自动重命名标签)**: 修改开始标签时，结束标签同步修改。
- **Path Intellisense (路径补全)**: 输入文件路径时提供自动补全。

#### ✨ 代码格式化与片段
- **Prettier (代码格式化)**: 一键美化代码排版。按 `Alt+Shift+F` 执行。
- **JavaScript (ES6) Snippets**: 常用 JS 代码块简写。

---

## 🛠 安装说明
1. **安装 VS Code**: 运行对应系统的 `.exe` 文件。
2. **安装插件**:
   - 下载对应的 `.vsix` 文件。
   - 在 VS Code 中点击左侧“插件”图标 (Ctrl+Shift+X)。
   - 点击插件面板右上角的 **"..."** 菜单。
   - 选择 **"Install from VSIX..."**，选中下载的文件即可。

## 💡 提示
如果 PHP 补全仍不生效，请确保您的电脑已安装 PHP 环境，并在 VS Code 设置中搜索 `php.validate.executablePath` 指向您的 `php.exe` 路径。
