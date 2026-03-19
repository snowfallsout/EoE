# Echoes of Emotion (EoE)

> A website combining contemporary ceramic art with modern digital interactive technology.

簡介
----
Echoes of Emotion（EoE）是一個以當代陶藝為核心、結合數位互動的展示專案。網站目前以靜態前端為主（HTML + JavaScript），資源位於 `assets/` 與 `include/` 資料夾，入口為 `index.html`。

專案狀態（截至 2024-07-11）
-------------------------
- 開發階段：原型 / 早期開發
- 主要語言：JavaScript、HTML
- 已有內容：`index.html`、靜態資源 (assets)、build metadata (`needle.buildinfo.json`)
- 問題追蹤：目前無開啟的 Issue 與 PR

目錄結構（說明）
----------------
- index.html
  - 專案入口頁（靜態 HTML）
- assets/
  - 圖片、音訊、影片或其他靜態資源
- include/
  - 可放置共用的 HTML 片段或模組
- needle.buildinfo.json
  - 建置相關資訊（視專案流程使用）

快速上手（本地測試）
-------------------
此專案目前為靜態網站，以下為幾種本地測試方式：

1. 直接開啟（適合快速查看）
   - 在檔案管理器中雙擊 `index.html` 開啟即可。

2. 使用簡易靜態伺服器（建議）
   - 使用 Python（在專案根目錄執行）：
     - Python 3: `python -m http.server 8000`
     - 然後在瀏覽器開啟 `http://localhost:8000`
   - 使用 Node 套件（例如 `live-server` 或 `http-server`）：
     - `npm install -g live-server`
     - `live-server` 或 `npx http-server . -p 8000`

建置與部署
-----------
- 專案含有 `needle.buildinfo.json`，若你使用某個自動化 / 建置流程，請補上具體的 build 指令與工具（例如 npm script、Makefile、或 CI 設定���。
- 若想使用 GitHub Pages：
  - 可在 repo 設定中啟用 Pages（branch: `main`、root 或 `docs/`），或將靜態輸出內容放到 `gh-pages` branch。
  - 若使用自動部署，建議建立 GitHub Actions Workflow 自動將 build 輸出部署到 gh-pages。

建議的下一步（短列表）
----------------------
- 加入 README（本檔案）並補上專案 Logo / 截圖 / Demo 連結（若有）。
- 新增 LICENSE（例如 MIT、Apache-2.0）以明確授權。
- 在根目錄加入 `package.json`（如果需要管理工具、套件與腳本）。
- 如果有 build step，將 `build` 與 `start` npm script 明確化。
- 設定 CI（GitHub Actions）做自動檢查與自動部署（如 GitHub Pages）。
- 建立 Issue 與 PR 模板、CONTRIBUTING.md 以利團隊協作。
- 若會公開展示，填寫網站 meta、SEO 與 accessibility（a11y）檢查。

貢獻指南
--------
- Fork → 建立 feature branch（例如 `feat/your-feature`）→ PR → 透過 code review 與合併。
- 提交訊息範例：`feat: add interactive gallery`、`fix: correct image path`、`docs: update README`
- 若專
