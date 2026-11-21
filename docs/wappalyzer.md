# Wappalyzer - Technology profiler 簡介

- **工具類型**：Chrome 瀏覽器擴充功能（網站技術指紋辨識工具）
- **安裝連結**：[Chrome 線上應用程式商店 - Wappalyzer](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg?pli=1)
- **擴充功能 ID**：`gppongmhjkpfnbhagpmjfkannfbllamg`

---

## 一句話認識它

**Wappalyzer** 是一款能一鍵解析目標網站「背後用了哪些技術堆疊（Tech Stack）」的瀏覽器外掛。只要瀏覽網頁並點開工具列圖示，就能快速掌握該網站所使用的 CMS、前端框架、伺服器、CDN、分析追蹤工具與金流服務等資訊。

---

## 主要功能特色

1. **跨類別完整技術偵測**
   可辨識數千種常見網站技術，涵蓋類別包括：
   - **CMS 與電商平台**：如 WordPress、Drupal、Shopify、WooCommerce
   - **前端與後端框架／程式語言**：如 React、Vue.js、Next.js、PHP、Node.js
   - **網頁伺服器與基礎架構**：如 Nginx、Apache、Cloudflare、AWS
   - **分析、行銷與客服工具**：如 Google Analytics、Google Tag Manager、Meta Pixel、Intercom
   - **金流與安全機制**：如 Stripe、reCAPTCHA、HSTS 等

2. **一鍵即時檢視**
   瀏覽任何網頁時，無需手動檢視原始碼或開啟開發者工具（DevTools），點選擴充功能圖示即可看到分類清楚的技術清單與版本資訊（若有暴露）。

3. **結果匯出與介面客製**
   - 支援將偵測結果匯出為 **CSV** 檔案，方便整理報表或批次記錄。
   - 內建淺色／深色（Light / Dark）介面切換。

---

## 常見應用情境

- **網站開發與架構觀摩**：看到優秀的網站時，快速了解對方採用的前端框架、UI 套件與 CDN 服務。
- **WordPress／CMS 盤點與維運**：檢視自家網站是否不小心暴露過多外掛名稱或舊版本號，作為安全加固的參考。
- **資安情資蒐集（OSINT）**：在合法授權的滲透測試或弱點盤點前期，快速建立目標的技術指紋。
- **競品研究與行銷分析**：了解同業網站使用了哪些追蹤碼、行銷自動化與電商方案。

---

## 快速上手步驟

1. 前往 [Wappalyzer Chrome 線上應用程式商店頁面](https://chromewebstore.google.com/detail/wappalyzer-technology-pro/gppongmhjkpfnbhagpmjfkannfbllamg?pli=1) 並點選「**加到 Chrome**」。
2. 將 Wappalyzer 圖示釘選（Pin）在瀏覽器右上角工具列。
3. 開啟任意想分析的網站，待頁面載入完成後點擊圖示，即可檢視該網站的技術組成。

---

## 注意事項

- Wappalyzer 是透過網頁 HTML、HTTP 標頭（Headers）、Cookie、JavaScript 全域變數等公開特徵進行比對，屬於**被動式偵測**，不會對目標網站發動主動掃描。
- 若網站有經過 CDN、WAF 或刻意隱藏伺服器標頭與版本資訊，部分後端技術可能無法被辨識出來，這屬於正常現象。
