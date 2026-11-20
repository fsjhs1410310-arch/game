<div align="center">

# 🌦️ 小朋友下樓梯：天氣繪本 3X 極速版 (Weather Shaft)

**融合經典街機物理機制與動態天氣繪本的極限挑戰網頁遊戲**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Web Audio API](https://img.shields.io/badge/Audio-Web_Audio_API-blueviolet?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/API/Web_Audio_API)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

[🎮 線上試玩 (Live Demo)](#--快速開始-getting-started) • [📖 緣由與動機](#-開發緣由與動機-origin--motivation) • [🚀 開發歷程](#-開發進化歷程-development-journey) • [🌤️ 天氣世界觀](#-五大天氣區塊與專屬結局-weather-worlds)

</div>

---

## 📖 專案簡介 (Introduction)

**《小朋友下樓梯：天氣繪本 3X 極速版》** 是一款基於純前端技術開發的單頁式（Single-Page）網頁遊戲與互動展示平台。本專案在致敬經典街機遊戲《小朋友下樓梯 (NS-SHAFT)》的同時，打破傳統單一地牢的視覺框架，將**「動態天氣變換」**與**「碎片化繪本敘事」**融入高節奏的跳躍生存挑戰中。

> **核心理念：「你的每一次墜落都不是終點，而是寫進不同天氣裡的一頁故事。」**

---

## 💡 開發緣由與動機 (Origin & Motivation)

### 🌱 開發緣由
經典《小朋友下樓梯》以簡單直覺的操作與令人腎上腺素飆升的節奏深植人心，但傳統版本在視覺表現與失敗反饋上較為單一（通常僅顯示最終層數與 Game Over）。本專案希望在保留「純粹操作快感」的基礎上，為每一次的挑戰賦予情感溫度與視覺驚喜。

### 🎯 設計動機
1. **賦予「失敗」正向的情感價值**：透過「死在哪個天氣區塊，就解鎖該天氣專屬結局」的機制，將挫敗感轉化為收集不同天氣繪本卡片的探索動力。
2. **極限節奏與高密度策略的碰撞**：將階梯上升速度提升至 **300%**，同時將階梯生成密度提高至 **200%**，創造出「高風險、高容錯路徑選擇」的獨特爽快感。
3. **極致輕量化與零門檻體驗**：堅持單一 HTML 檔案架構（Zero-Dependency Build），不依賴外部圖片或音訊素材，確保在任何裝置上都能秒開即玩。

---

## 🚀 開發進化歷程 (Development Journey)

本專案經歷了四個關鍵階段的迭代與重構，逐步從單純的遊戲原型演進為完整的展示平台：

| 階段 | 里程碑名稱 | 核心演進內容 | 關鍵技術與設計突破 |
| :--- | :--- | :--- | :--- |
| **Phase 1** | 💡 **經典核心重構** | 還原《小朋友下樓梯》基礎物理碰撞、重力加速度與多樣化階梯機制。 | 使用 HTML5 Canvas 建立 60 FPS 遊戲主迴圈與 Web Audio 合成音效。 |
| **Phase 2** | 🌦️ **天氣繪本融合** | 導入依深度（B1 ~ B91+）劃分的五大天氣區塊與動態粒子氛圍。 | 實作「死亡區塊判定引擎」，在遊戲結束瞬間生成對應天氣的專屬結局卡片。 |
| **Phase 3** | ☀️ **亮采一頁式平台** | 將遊戲嵌入清新明亮（Light Mode）的日系玻璃擬態展示網頁中。 | 採用極簡文字與高對比圖示卡片設計，整合世界觀圖鑑與操作說明。 |
| **Phase 4** | ⚡ **3X 極速與高密度改版** | 全面升級遊戲數值平衡，將上升速度調升為 **3 倍**、階梯數量增加為 **2 倍**。 | 優化高幀率下的碰撞偵測防穿透演算法，確保高速移動時的操控精準度。 |

---

## ✨ 核心特色 (Key Features)

* **⚡ 300% 極限上升速度**：階梯與頂部尖刺以 3 倍速向上逼近，帶來極具張力的反應力考驗。
* **🧱 200% 高密度階梯矩陣**：雙倍密集的階梯分佈，考驗玩家在高速下墜中瞬間規劃最佳落點的能力。
* **🎨 明亮日系繪本視覺 (Light Theme)**：擺脫傳統暗黑介面，採用純白與柔和粉彩漸層搭配 Glassmorphism（玻璃擬態）卡片，呈現清新舒適的視覺體驗。
* **🔊 原生程式碼合成音效**：內建 Web Audio API 音效引擎，無需載入外部 `.mp3` 或 `.wav` 檔案即可享有彈跳、受傷、補血等動態音效（支援一鍵靜音）。
* **📱 全平台自適應操控**：完美支援電腦鍵盤與行動裝置觸控虛擬按鍵。

---

## 🌤️ 五大天氣區塊與專屬結局 (Weather Worlds)

隨著玩家不斷向地下深處探索，背景色調與階梯主題將隨層數即時漸變。當角色生命值歸零或墜落時，系統將依據**當下所在的天氣區塊**頒發專屬結局繪卡：

| 深度層數 | 天氣區塊 | 主題代表色 | 專屬繪本結局標題 | 結局故事摘要 |
| :--- | :--- | :--- | :--- | :--- |
| **B1 - B15** | ☀️ **晴天區** | 暖陽金 (`#F59E0B`) | **晴天的璀璨日光** | 溫暖的陽光穿透洞口，將太陽的熱度與希望永遠保留在記憶中。 |
| **B16 - B35** | ☁️ **陰天區** | 迷霧灰 (`#64748B`) | **陰天的微風沉思** | 雲霧輕輕環繞，在沉靜安詳的谷地裡學會休憩，等待下一次起飛。 |
| **B36 - B60** | 🌧️ **雨天區** | 沁涼藍 (`#2563EB`) | **雨天的庇護奏鳴曲** | 淅瀝雨聲宛如溫柔催眠曲，沖刷掉一路的疲憊，帶來純淨滋潤。 |
| **B61 - B90** | ❄️ **雪天區** | 冰晶青 (`#0284C7`) | **雪天的純白誓約** | 漫天飛舞的雪花覆蓋足跡，將冒險的故事凍結成永不褪色的水晶。 |
| **B91+** | 🌌 **星空區** | 星夜紫 (`#7C3AED`) | **星空的永恆夢境** | 抵達最深沉的星空極境，名字化為璀璨星宿，成為繪本中的傳奇篇章。 |

---

## 🪜 階梯與機關圖鑑 (Mechanics & Platforms)

| 階梯類型 | 視覺特徵 | 物理效果與應對策略 |
| :--- | :--- | :--- |
| **普通階梯** | 隨天氣區塊變色之實心平台 | 最穩健的基礎落腳點，適合用來調整呼吸與觀察下方路徑。 |
| **輸送帶階梯** | 帶有方向箭頭之灰藍平台 | 踩上後會強制將角色向左或向右推移，需反向微調走位避免滑落。 |
| **彈簧階梯** | 亮粉色高彈性平台 | 觸碰瞬間將角色高高彈起，可用於躲避下方尖刺或爭取思考時間（注意勿撞擊頂部尖刺）。 |
| **易碎階梯** | 橘黃色閃電標記平台 | 踩踏後會迅速碎裂消失，必須在第一時間跳往下一階。 |
| **尖刺階梯** | 佈滿紅色銳角之危險平台 | 踩中會扣除 **3 點 HP** 並產生小幅反彈，在 3 倍速下需極力閃避。 |
| **愛心階梯** | 翠綠色愛心標記平台 | 踩上後可恢復 **2 點 HP**，觸發後會轉化為普通階梯。 |

---

## 🕹️ 操作指南 (Controls)

* **電腦端 (Desktop)**：
  * 向左移動：`←` 方向鍵 或 `A` 鍵
  * 向右移動：`→` 方向鍵 或 `D` 鍵
* **行動端 (Mobile / Tablet)**：
  * 點擊或長按遊戲畫布下方的 **`◀ 左移`** 與 **`右移 ▶`** 觸控按鈕。

---

## 🛠️ 技術架構與專案結構 (Tech Stack & Architecture)

本專案遵循極簡單一檔案原則，所有結構、樣式與遊戲引擎邏輯皆高度內聚於單一檔案中：

```text
weather-shaft/
├── index.html          # 核心單一檔案（包含一頁式展示 UI、Tailwind 配置與 Canvas 遊戲引擎）
└── README.md           # 專案說明文件
```

* **渲染引擎**：HTML5 `<canvas>` 2D Context
* **UI 框架**：Tailwind CSS (via CDN) + FontAwesome 6 Icons
* **字體排版**：Google Fonts (`Fredoka` & `Noto Sans TC`)
* **音效系統**：Native Web Audio API (`OscillatorNode` & `GainNode` 即時波形合成)

---

## 🚀 快速開始 (Getting Started)

本專案無需安裝 Node.js、npm 或任何建置工具，您可以透過以下任一方式立即啟動：

1. **直接下載執行**：
   ```bash
   # 複製專案至本地端
   git clone https://github.com/anonymous-dev/weather-shaft.git

   # 進入專案目錄
   cd weather-shaft
   ```
   直接雙擊 `index.html`，即可使用預設瀏覽器（Chrome / Edge / Safari / Firefox）開啟並遊玩。

2. **使用本地伺服器預覽 (Optional)**：
   若您使用 VS Code，可安裝 **Live Server** 擴充套件，於 `index.html` 上點擊右鍵並選擇 `Open with Live Server`。

---

## 📄 授權條款 (License)

本專案採用 [MIT License](https://opensource.org/licenses/MIT) 開源授權，歡迎自由 Fork、修改與學習交流。

