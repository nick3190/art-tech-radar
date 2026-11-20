# 藝術科技雷達

展覽、徵件、駐村、新媒體職缺、產業情報與 AI Agent 專案分析。靜態網站，部署於 Vercel。

- `index.html`：頁面
- `data/items.json`：所有項目（不刪除過期項目，頁面預設隱藏）
- `data/analysis.json`：最新一份 AI Agent 專案分析
- `data/analysis/<date>.json`：分析歷史

資料由排程任務每週一、週五更新並 commit，Vercel 自動部署。
