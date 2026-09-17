# hermes-crypto-watch-pages

**BTC / ETH 每日預測命中率熱力圖**

此 repo 為 [hermes-crypto-watch](https://github.com/JacobHsu/hermes-crypto-watch)（private）的公開展示頁，僅包含熱力圖前端。

## 🔗 Live Page

➡️ **https://jacobhsu.github.io/hermes-crypto-watch-pages/heatmap/**

## 功能

- 月曆式熱力圖，綠色 = 預測命中，紅色 = 未中
- BTC / ETH 各自顯示，並附整體 v2 命中率統計
- Hover tooltip 顯示基準價、結算價、漲跌幅
- 只計入 `v2_contract_aligned` + `accuracy_eligible=true` 正式列

資料來源：`reports/binance-daily-predictions/data/predictions.csv`（private repo）
