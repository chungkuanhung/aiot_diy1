# 個人資訊與動態時間展示網頁 (Personal Info & Dynamic Time Webpage)

這是一個簡單的靜態網頁作品，主要展示個人中英文姓名以及即時更新的現在時間。此專案做為「智慧物聯網應用與實作」課程的基礎練習。

## 功能介紹 (Features)

*   **個人資訊展示**：顯示中文姓名「鍾冠泓」與英文姓名「KUAN HUNG CHUNG」。
*   **動態時鐘**：透過 JavaScript 自動獲取系統當前時間，並以「時:分:秒」的格式即時更新。
*   **動態日期**：在網頁載入時自動取得並顯示當天的詳細日期（例如：2026年3月3日 星期二）。
*   **現代化 UI 設計**：
    *   採用 Glassmorphism（玻璃擬物化）設計風格，呈現半透明且帶有模糊背景的質感卡片。
    *   動態全螢幕漸層背景，增添視覺豐富度。
    *   使用 Google Fonts (Outfit 與 Noto Sans TC) 以提升排版美感。

## 使用技術 (Tech Stack)

*   **HTML5**：負責建立網頁的基本骨架與語意。
*   **CSS3**：負責網頁的樣式設計、排版、漸層動畫以及玻璃擬物化特效。
*   **JavaScript (Vanilla JS)**：負責處理時間獲取邏輯，並透過 `setInterval` 每秒自動更新畫面。

## 如何執行 (How to Run)

這是一個純前端的靜態網頁，不需要安裝任何伺服器環境或依賴套件。

1.  在您的電腦中找到 `index.html` 檔案。
2.  對檔案連按兩下，即可透過您預設的網頁瀏覽器（如 Chrome, Edge, Firefox, Safari 等）開啟並檢視網頁效果。

## 檔案結構 (Project Structure)

```text
aiot_diy1/
└── index.html      # 主網頁檔案（包含 HTML、CSS 樣式與 JS 腳本）
└── README.md       # 專案說明文件
```
