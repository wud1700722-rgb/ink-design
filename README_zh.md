<div align="center">

**语言**

[English](README.md) | [简体中文](README_zh.md)

</div>

# Ink · 一套克制的中文设计系统

不追花哨的配色，不做多余的动效。Ink 提供一套语义清晰的设计令牌与组件，让界面回归到内容本身。

## 在线预览

由于当前入口文件为 `home.html`，请点击下方链接体验：

**[https://wud1700722-rgb.github.io/ink-design/home.html](https://wud1700722-rgb.github.io/ink-design/home.html)**

## 特性

- **零依赖**：纯 CSS 实现，不依赖任何框架，无需构建步骤。
- **语义令牌**：颜色、间距、圆角、动效全部收口到 CSS 变量（Design Tokens）。
- **中文友好**：内置手写体「凌」写（inkshou），针对中文排版重新调整了行高与字距。
- **浅色深色**：内置两套主题，跟随系统切换。
- **无障碍友好**：合理使用 `aria-label`、`:focus-visible`，并支持 `prefers-reduced-motion`。

## 快速开始

1. 下载或克隆本仓库：
   ```bash
   git clone https://github.com/wud1700722-rgb/ink-design.git
```

2. 在你的 HTML 入口中引入样式：
   ```html
   <link rel="stylesheet" href="./ink-design/style.css">
   ```
3. 开始写标签：
   ```html
   <button class="ink-btn ink-btn--primary">开始使用</button>
   ```

字体许可

本项目包含的字体文件（“凌”写（也称凌“写”，两者皆可） / inkshou）均以 SIL OFL 1.1 协议发布，可自由商用。
