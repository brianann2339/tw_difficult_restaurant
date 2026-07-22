# 台灣預約困難餐廳圖鑑 tw_difficult_restaurant

40 間台灣預約困難餐廳的互動圖鑑(2026 年 7 月查證):訂位平台、放位規則(每月幾號幾點開搶)、價位、米其林/500盤紀錄,可依縣市/類型/放位方式篩選。

🌐 網頁:https://brianann2339.github.io/tw_difficult_restaurant/

## 資料

- `data.json` — 結構化資料(欄位:name, city, cat, type, price, level 難度, platform, url 訂位連結, rule 放位規則, ruleType, ruleKey, phone, awards, status, src 來源)
- `index.html` 內亦內嵌同一份 JSON(`<script id="data" type="application/json">`),供後續快速預約提醒程式直接讀取

## 難度分級

傳說級(熟客/引薦制)/秒殺級(開放即搶空)/困難(需提前數週至數月)/熱門(需預約但可訂)

## 免責

各店放位規則、價格、營業狀態隨時可能調整,請以官方 IG/FB/官網最新公告為準。資料彙整自 Marie Claire、KKTL 越境食旅、愛飯團、台灣米其林指南、500盤及各店官方頁面(來源附於各卡片)。
