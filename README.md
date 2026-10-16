<div align="center">

**Language**

[English](README.md) | [简体中文](README_zh.md) | [繁體中文（台灣）](README_zh-Hant.md)

</div>

# Ink · A Restrained Chinese Design System

No flashy colors, no excessive animations. Ink provides a set of semantically clear design tokens and components, returning the interface to the content itself.

## Live Preview

Since the entry file is currently `home.html`, please click the link below to experience it:

**[https://wud1700722-rgb.github.io/ink-design/home.html](https://wud1700722-rgb.github.io/ink-design/home.html)**

## Features

- **Zero Dependencies**: Pure CSS, no frameworks, no build step required.
- **Design Tokens**: Colors, spacing, radii, and motion are all standardized in CSS variables.
- **Chinese Friendly**: Includes the handwriting font "Ling" (inkshou), with line-height and letter-spacing specifically tuned for Chinese text.
- **Light & Dark Themes**: Built-in themes that adapt to system preferences, with contrast-checked components.
- **Accessibility Ready**: Proper use of `aria-label`, `:focus-visible`, and support for `prefers-reduced-motion`.

## Quick Start

1. Clone this repository:
   ```bash
   git clone https://github.com/wud1700722-rgb/ink-design.git
   ```

2. Include the stylesheet in your HTML entry:
   ```html
   <link rel="stylesheet" href="./ink-design/style.css">
   ```

3. Start writing Ink tags:
   ```html
   <button class="ink-btn ink-btn--primary">Get Started</button>
   ```

Font License

The included fonts ("Ling" / inkshou) are released under the SIL OFL 1.1 license, free for commercial use.
