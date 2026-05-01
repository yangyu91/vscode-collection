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

#### 🌐 基础与界面
- **Chinese Language Pack (简体中文包)**
  - **作用**: 将 VS Code 界面汉化。
  - **用法**: 安装后若未自动切换，按 `Ctrl+Shift+P` 输入 `Configure Display Language` 选择 `zh-cn`。
- **Material Icon Theme (图标主题)**
  - **作用**: 为不同类型的文件（如 .php, .html, .css）提供精美的可视化图标。
  - **用法**: 安装后在弹出的提示中选择 "Material Icon Theme" 即可激活。
- **Bracket Pair Colorizer (彩虹括号)**
  - **作用**: 用不同颜色区分嵌套的括号。
  - **用法**: 安装即生效，让您一眼看出括号是否成对，防止代码逻辑出错。

#### 🐘 PHP 开发神器
- **Intelephense (PHP 智能感知)**
  - **作用**: 提供极强的代码补全、跳转到定义、语法检查功能。学 PHP 必装。
  - **用法**: 安装即用，它会自动扫描您的项目目录。
- **SQLTools (数据库管理)**
  - **作用**: 直接在 VS Code 里连接和操作 MySQL/MariaDB 等数据库。
  - **用法**: 点击侧边栏的数据库图标，添加连接信息即可像使用 Navicat 一样操作数据库。

#### 📝 HTML/CSS 增强
- **HTML CSS Support**
  - **作用**: 在 HTML 文件中编写 class 时，自动补全 CSS 文件中定义的样式名。
- **Auto Rename Tag (自动重命名标签)**
  - **作用**: 修改 HTML 开始标签时，结束标签会自动跟着同步修改。
  - **用法**: 安装即生效，大幅提升 HTML 编写效率。
- **Path Intellisense (路径补全)**
  - **作用**: 在输入文件路径（如 `<img src="./...`）时提供自动补全。
  - **用法**: 输入 `/` 或 `./` 即可触发路径提示。

#### ✨ 代码格式化与片段
- **Prettier (代码格式化)**
  - **作用**: 一键美化代码排版，让您的 HTML/CSS/JS 代码整齐划一。
  - **用法**: 按 `Alt+Shift+F` 执行格式化。建议在设置中开启 "Format On Save"（保存时自动格式化）。
- **JavaScript (ES6) Snippets**
  - **作用**: 输入简写（如 `clg`）即可快速生成常用的 JS 代码块（如 `console.log`）。

---

## 🛠 安装说明
1. **安装 VS Code**: 运行对应系统的 `.exe` 文件。
2. **安装插件**:
   - 下载对应的 `.vsix` 文件。
   - 在 VS Code 中点击左侧“插件”图标 (Ctrl+Shift+X)。
   - 点击插件面板右上角的 **"..."** 菜单。
   - 选择 **"Install from VSIX..."**，选中下载的文件即可。

