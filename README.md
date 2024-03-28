# VuePress-test
測試 VuePress

# 參考
https://vuepress.vuejs.org/zh/
https://github.com/vuejs/vuepress

主要 => https://vitepress.dev/guide/getting-started

# 安裝
```
npm add -D vitepress

// 安裝精靈
npx vitepress init
// 回答一些問題

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
│  ● Default Theme (Out of the box, good-looking docs)
│  ○ Default Theme + Customization
│  ○ Custom Theme
└

// 目錄結構

.
├─ docs
│  ├─ .vitepress
│  │  └─ config.js
│  ├─ api-examples.md
│  ├─ markdown-examples.md
│  └─ index.md
└─ package.json
```

# 執行
```
// 執行網站服務
npm run docs:dev

// 進入網站
http://localhost:5173/
```
