# 資工所考試準備網站

準備資工所考試的筆記網站，每個科目一頁，整理考試範圍、重點整理、考古題解析與易錯題。
純 HTML + CSS，部署於 GitHub Pages。

本專案同時是 CLAUDE.md 的規則示範：AI 讀完 `CLAUDE.md` 後，可依同一套規則新增科目頁面。

## 檔案結構

```
/
├── CLAUDE.md                          ← AI 工作規則（以此為準）
├── README.md                          ← 本檔
├── index.html                         ← 首頁：科目列表
├── style.css                          ← 全站唯一樣式表
├── template/
│   └── subject-template.html          ← 新增科目時複製的模板
└── subjects/
    └── data-structures.html           ← 資料結構
```

## 如何新增科目

請依照 [CLAUDE.md 第 8 節「新增一個科目的標準步驟」](CLAUDE.md) 操作：
複製模板到 `subjects/`、填入內容、在 `index.html` 新增卡片、更新日期並自我檢查。
