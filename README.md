# Echoes of Emotion (EoE)

[![English](https://img.shields.io/badge/Language-English-blue)](#)
[![中文繁體](https://img.shields.io/badge/Language-%E7%B9%81%E9%AB%94%E4%B8%AD%E6%96%87-orange)](README-zh_hk)

---

歡迎來到 Echoes of Emotion（EoE）專案主頁。

此檔為主導覽頁，請點選上方語言連結閱讀完整文件（英文 / 中文）。如欲貢獻請參閱 CONTRIBUTING.md，授權條款請參閱 LICENSE。

---

# Echoes of Emotion (EoE)

A website combining contemporary ceramic art with modern digital interactive technology.

## Overview
- Entry point: `index.html`
- Static resources: `assets/`, `include/`
- Build metadata: `needle.buildinfo.json`
- Current status: Early prototype (static front-end, JavaScript + HTML)

## Quick start (local)
1. Open `index.html` directly in your browser for a quick preview.
2. Or run a simple static server:
   - Python 3:
     ```
     python -m http.server 8000
     ```
     then visit `http://localhost:8000`.
   - Node (live-server / http-server):
     ```
     npx live-server
     ```

## Build & Deploy
- If you have a build step, add `package.json` and scripts (`build`, `start`) and document them here.
- To publish via GitHub Pages:
  - Place a site in `docs/` or use `gh-pages` branch and enable Pages in repository settings.
  - Optionally add a GitHub Actions workflow to automate build + deploy.

## Repository layout
- `index.html` — Site entry page
- `assets/` — Images, audio, video, other static assets
- `include/` — Shared HTML fragments or modules
- `needle.buildinfo.json` — Build metadata

## Contributing
See `CONTRIBUTING.md` for how to contribute, branch naming, PR process and code style.

## Contact / Maintainer
- Repository: https://github.com/snowfallsout/EoE
- Maintainer: Xueyi Huang (github: snowfallsout)、SINWU LOK (github: sinwulok）


---
# README-zh_hk
# Echoes of Emotion（EoE）

Echoes of Emotion（EoE）是一個結合當代陶藝與數位互動技術的網站展示專案。

## 概要
- 入口：`index.html`
- 靜態資源：`assets/`、`include/`
- 建置資訊：`needle.buildinfo.json`
- 專案狀態：原型 / 早期開發（靜態前端為主，JavaScript + HTML）

## 本地快速啟動
1. 可直接雙擊 `index.html` 開啟快速預覽。
2. 或使用簡易靜態伺服器：
   - Python 3：
     ```
     python -m http.server 8000
     ```
     然後開啟 `http://localhost:8000`。
   - Node（live-server / http-server）：
     ```
     npx live-server
     ```

## 建置與部署
- 若有建置流程，建議加入 `package.json` 並定義 `build`、`start` 等 script，並在此處補上指令。
- 若要使用 GitHub Pages：
  - 可把靜態站放在 `docs/` 或使用 `gh-pages` branch，並在 Settings → Pages 啟用。
  - 可使用 GitHub Actions 自動化 build 並部署到 Pages。

## 目錄說明
- `index.html` — 網站入口
- `assets/` — 圖片、音訊、影片等靜態資源
- `include/` — 可重複使用的 HTML 片段或模組
- `needle.buildinfo.json` — 建置相關資訊

## 貢獻
請參考 `CONTRIBUTING.md` 了解貢獻流程、分支命名與 PR 規範。

## 維護人員 / 聯絡
- Repository: https://github.com/snowfallsout/EoE
- 維護人員: Xueyi Huang (github: snowfallsout)、SINWU LOK (github: sinwulok）
