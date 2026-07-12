# DD — 併購標的盡職調查總覽

靜態網站，收錄各併購標的公司之盡職調查（Due Diligence）報告。

## 結構

- `index.html` — 主頁，列出所有公司與查核日期
- `companies/<company-slug>/index.html` — 各公司獨立 DD 報告頁
- `assets/style.css` — 共用樣式

## 新增公司

1. 於 `companies/` 下新增資料夾（英文 slug 命名）
2. 複製既有公司頁面結構，填入新內容
3. 於 `index.html` 的 `.company-list` 區塊新增一張 `.card`

## 免責聲明

本站內容依公開資訊查詢彙整，僅供內部評估參考，不構成投資或法律建議。
