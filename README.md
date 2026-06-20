# 桃園市交通違規分析儀表板

桃園市交通違規舉發項目及地點（民國 109–114 年）互動視覺化儀表板。

## 功能

- 📅 年度下拉選單，預設顯示最新年度（114 年）
- 📊 各行政區違規件數橫條圖
- 📅 各月份違規趨勢折線圖
- ⚠️ 違規項目 Top 10 橫條圖
- 🕐 一日違規時段分布面積圖
- 🗺️ 違規地點熱點地圖（Leaflet + MarkerCluster）
- 📈 各行政區歷年違規件數比較折線圖（可選兩個行政區對比）

## 使用方式

直接用瀏覽器開啟 `dashboard.html`，無需伺服器。

## 資料來源

[政府開放資料平臺 — 桃園市交通違規舉發項目及地點](https://data.gov.tw/)

## 技術

- [Chart.js](https://www.chartjs.org/)
- [Leaflet.js](https://leafletjs.com/)
- [Leaflet.markercluster](https://github.com/Leaflet/Leaflet.markercluster)
