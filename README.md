# 项目简介
这是一个为 Uniaball 的开源项目（**DesktopGlues** 和 **OpenJDK-Android**）提供的下载站，由AI辅助生成

网站采用 _**Material Design 3**_ 设计语言，提供清晰、快速的构建文件下载体验，无需登录即可从 *GitHub Actions* 和 *Releases* 获取最新版本

# 网站链接
<https://uniaball.github.io>

# 功能特点
- 使用 _**Material Design 3**_ 的设计语言
- 简约、无冗余信息
- 通过 `nightly.link` **直接下载**
- 支持渲染完整的 **Markdown** 格式

# 项目结构
```
webside_root/
├── assets/
│   └── background.png
├── index.html
├── desktopglues.html
├── openjdk.html
└── style.css

```

# 技术栈
- **HTML5 + CSS3** *（Material Design 3 规范）*
- 原生 **JavaScript** *（ES6+）*
- GitHub REST API v3
- ` nightly.link ` *（构建文件代理下载）*
- **marked.js** *（Markdown 解析）*

# 开源协议
**本项目代码采用 MIT 协议，可直接使用或修改**

## 涉及的第三方服务

- GitHub API - GitHub 服务条款
- nightly.link - 其服务条款
- Material Icons - Apache License 2.0
