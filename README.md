# 𓃥 白六霓虹電漿燈 (Neon Plasma Text Display)

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-SVG%20%2F%20Canvas-orange.svg)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow.svg)
![Web%20Audio%20API](https://img.shields.io/badge/Web%20Audio-API-brightgreen.svg)

**𓃥 白六霓虹電漿燈** 是一個基於網頁前端技術（SVG Vector Graphics、Web Audio API 與動態樣式算牌）打造的視覺互動藝術專案。本專案模擬高壓氣體放電於霓虹燈管內激發、遊走的動態視覺效果，並結合真實電氣嗡鳴與火花音效，打造沉浸式的霓虹電漿字體展示。

---

## ✨ 專案特色 (Features)

* **⚡ 真實電漿遊走視覺 (Realistic Plasma Flow)**：
  * 電漿脈衝隨機於全畫面的燈管（字元與筆畫路徑）中激發與流動。
  * 具備平滑的進出場淡入淡出 (Fade-In / Fade-Out) 曲線，呈現高壓氣體放電的自然氣質。
* **📱 跨裝置螢幕自適應 (Responsive Layout)**：
  * 自動偵測裝置解析度與直立/橫向螢幕比例。
  * 內建字體大小自動縮放與勻稱分行演算法（Fit Algorithm），確保多字數輸入時也能完美呈現。
* **🎨 豐富控制面板 (Interactive UI Panel)**：
  * **動態文字輸入**：支援多行文字輸入與即時渲染。
  * **發光亮度調整**：可彈性控制霓虹燈管與 Glow 光暈強度。
  * **電漿段數控制**：支援動態調控畫面上同時遊走的電漿段數（可調至點綴式或熱鬧模式）。
* **🔊 沉浸式電氣音效 (Web Audio API)**：
  * 內建 60Hz 交流電嗡鳴底音 (Hum Noise)。
  * 隨機電漿激發時觸發微弱的高壓電火花音效 (Spark Sound)。
* **📦 零外部依賴 (Zero Dependencies)**：
  * 純粹使用原生 HTML5、CSS3 與 JavaScript 開發，單一 `.html` 檔案即可直接執行。

---

## 🚀 快速開始 (Quick Start)

1. **下載專案**：
   複製專案中的 `index.html` 檔案。

2. **直接開啟**：
   使用任何現代瀏覽器（Chrome, Edge, Safari, Firefox）雙擊開啟 `index.html` 即可體驗。

3. **啟用音效**：
   點擊頁面任意區域，即可解鎖並啟動 Web Audio 音效輸出。

---

## 🛠️ 技術架構 (Tech Stack)

| 技術模組 | 說明 |
| :--- | :--- |
| **SVG / Path / Text** | 提供多層次燈管構造（底層立體擋光、中層彩色常亮管身、頂層半透明玻璃管心）。 |
| **Web Audio API** | 利用 OscillatorNode 與 GainNode 實時合成電氣嗡鳴聲與隨機 Spark 音效。 |
| **Canvas 2D (Offscreen)** | 用於文字長度精確量測與自適應換行縮放計算。 |
| **CSS Filters** | 多重 `feGaussianBlur` 濾鏡混合，模擬霓虹燈管擴散光暈。 |

---

## 📄 授權條款 (License)

本專案採用 **MIT License** 授權，歡迎自由修改、分發與個人/商業使用。
