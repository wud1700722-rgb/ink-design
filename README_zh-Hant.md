<div align="center">

**語言**

[English](README.md) | [简体中文](README_zh.md) | [繁體中文（台灣）](README_zh-Hant.md)

</div>

# Ink · 一套克制的中文設計系統

不追求花俏的配色，不做多餘的動畫。Ink 提供一組語意清晰的設計 token 與元件，讓介面回歸內容本身。

## 線上預覽

由於目前入口檔案為 `home.html`，請點擊下方連結體驗：

**[https://wud1700722-rgb.github.io/ink-design/home_tw.html](https://wud1700722-rgb.github.io/ink-design/home_tw.html)**

## 特性

- **零依賴**：純 CSS 實現，不依賴任何框架，無需建置步驟。
- **語意 Token**：顏色、間距、圓角、動畫效果全部收斂到 CSS 變數（Design Tokens）。
- **中文友善**：內建手寫體「凌」寫（inkshou），針對中文排版重新調整了行高與字距。
- **淺色深色**：內建兩套主題，跟隨系統切換。
- **無障礙友善**：合理使用 `aria-label`、`:focus-visible`，並支援 `prefers-reduced-motion`。

## 快速開始

1. 下載或複製本倉庫：
   ```bash
   git clone https://github.com/wud1700722-rgb/ink-design.git
   ```

2. 在你的 HTML 入口引入樣式：
   ```html
   <link rel="stylesheet" href="./ink-design/style.css">
   ```
3. 開始寫標籤：
   ```html
   <button class="ink-btn ink-btn--primary">開始使用</button>
   ```

字型授權

本專案包含的字型檔案（「凌」寫 / inkshou）均以 SIL OFL 1.1 授權發布，可自由商用。
