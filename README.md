# VitePress 專案測試 🚀

這是一個用於測試與學習 **VitePress** 的練習專案。雖然專案名稱叫 `VuePress-test`，但目前主要實踐新一代的 **VitePress** 框架！✨

## 📚 參考資料
在開始探索之前，可以參考以下官方資源：
- [VuePress 中文文檔](https://vuepress.vuejs.org/zh/) 🛠️
- [VuePress GitHub 倉庫](https://github.com/vuejs/vuepress) 📦
- **核心指南：[VitePress 快速入門](https://vitepress.dev/guide/getting-started)** 💡

---

## ✨ VitePress 核心特色
為什麼選擇 VitePress？它不僅僅是 VuePress 的繼承者，更是基於 Vite 的次世代現代化靜態網站生成器：

- **⚡ 極速開發體驗**：基於 Vite，具備極短的啟動時間與瞬間的熱更新（HMR）。
- **🏗️ Vue 增強的 Markdown**：可以直接在 Markdown 中使用 Vue 元件，讓文件具備互動性。
- **🚀 卓越效能**：生成的頁面載入速度極快，且具備最輕量化的 JavaScript 傳輸量。
- **📝 強大的 Markdown 擴展**：
  - 內建代碼高亮（Shiki）、表格、目錄（TOC）與自定義容器。
  - 支持多種警告樣式（Alerts）與 Frontmatter。
- **🔍 內建搜尋與多語系**：輕鬆配置全文搜尋與多國語言支援。
- **🎨 簡約美觀的原生佈景**：預設主題經過精心設計，非常適合技術文件與部落格。

---

## 🛠️ 安裝步驟
請按照以下步驟快速搭建你的文件網站：

1. **安裝 VitePress 依賴** 📥
   ```bash
   npm add -D vitepress
   ```

2. **啟動初始化精靈** 🪄
   ```bash
   npx vitepress init
   ```
   *回答一些引導問題來設定你的專案：*

   ```text
   ┌  Welcome to VitePress!
   │
   ◇  Where should VitePress initialize the config?
   │  ./docs
   │
   ◇  Site title:
   │  My Awesome Project
   │
   ◇  Site description:
   │  A VitePress Site
   │
   ◆  Theme:
   │  ● Default Theme (內建美觀佈景)
   │  ○ Default Theme + Customization
   │  ○ Custom Theme
   └
   ```

## 📂 目錄結構
初始化完成後，你的專案目錄將呈現如下結構：

```text
.
├─ docs
│  ├─ .vitepress
│  │  └─ config.js       # 專案核心配置
│  ├─ api-examples.md    # API 使用範例
│  ├─ markdown-examples.md # Markdown 功能展示
│  └─ index.md           # 網站首頁
└─ package.json          # 專案腳本與依賴設定
```

## 🏃 如何運行
啟動開發環境進行預覽：

1. **啟動網站服務** 🔥
   ```bash
   npm run docs:dev
   ```

2. **瀏覽成果** 🌐
   打開瀏覽器訪問：[http://localhost:5050/](http://localhost:5050/) ✨
