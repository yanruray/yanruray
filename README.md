# Ray | 個人網站與作品集履歷 (Personal Portfolio & Resume)

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Font Awesome](https://img.shields.io/badge/Font_Awesome-528DD7?style=flat-square&logo=font-awesome&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat-square&logo=github&logoColor=white)

這是一個採用現代 **Bento Grid（便當盒網格）** 與 SaaS 極簡視覺風格設計的個人品牌與履歷網站。透過清爽的卡片式佈局與響應式設計（RWD），集中展示個人背景、學歷、競賽成果、社團經歷、MBTI 人格深度剖析、精選開發作品集以及學期互動課表。

🔗 **線上預覽 (Live Demo)**：[https://yanruray.github.io/profile/](https://yanruray.github.io/profile/)

---

## ✨ 網站架構與頁面導覽

本專案由 4 個核心頁面組成，彼此透過流暢的卡片導覽互相串聯：

### 1. 🏠 個人主頁與履歷總覽 (`index.html`)
- **個人名片與社群連結**：整合頭像、目前身分狀態、聯絡信箱以及 GitHub、Instagram、Discord 快速跳轉按鈕。
- **關於我與語言能力**：簡述個人學習目標與語言能力標籤。
- **學歷時間軸**：以視覺化時間軸呈現淡江大學資訊工程學系與新北市立三重高級中學之就學歷程。
- **比賽經歷**：收錄 **2026 和泰 AI 黑客松**、**金象盃全國大數據實務能力競賽**（北區初賽及全國決賽佳作）、數學科學藝競賽與國語文競賽等獲獎紀錄。
- **社團與組織經歷**：紀錄於淡江大學新創社（人資與 AI 部）及高中模擬聯合國社（副社長、網管、文書）之幹部與實務歷練。
- **作品集精選與興趣偏好**：首頁直接預覽精選上線專案，並展示個人喜愛之遊戲卡片（Valorant、Minecraft、雀魂）。

### 2. 💻 作品集與專案展覽 (`portfolio.html`)
獨立的專案展示頁面，詳細列出各項專案的核心功能、技術標籤、線上 Demo 與 GitHub 原始碼倉庫：

| 專案名稱 | 狀態 | 專案簡介 | 技術標籤 | 連結 |
| :--- | :---: | :--- | :--- | :---: |
| **校園資產管理系統** | 🟢 Live | 校園與組織設備資產清冊檢視、借調歸還追蹤與庫存狀態管理平台 | `HTML5` `Tailwind CSS` `JavaScript` | [網站](https://yanruray.github.io/SchoolAsset/) / [GitHub](https://github.com/yanruray/SchoolAsset) |
| **新創 MBTI 人格測試** | 🟢 Live | 為淡江大學新創社量身打造的互動式 MBTI 測驗與性格特質視覺化分析 | `Interactive UI` `Tailwind CSS` `JavaScript` | [網站](https://yanruray.github.io/Startup_Club_MBTI_Interactive/) / [GitHub](https://github.com/yanruray/Startup_Club_MBTI_Interactive) |
| **請假系統** | 🔵 Live | 組織內部差勤線上請假申請、狀態追蹤與簽核流審批系統（自建伺服器與動態 DNS 部署） | `Full Stack` `Self-Hosted` `Database` | [網站](http://leaverequest.yanru0418.dpdns.org/) / [GitHub](https://github.com/yanruray/LeaveRequest) |
| **Discord 機器人** | 🟣 Open Source | 多功能 Discord 社群自動化與互動管理機器人，支援斜線指令與事件監聽回應 | `Discord API` `Chat Bot` `Automation` | [GitHub](https://github.com/yanruray/DiscordChat) |

### 3. 🧠 MBTI 人格特質分析 (`mbti.html`)
- **INFJ-T（提倡者 Advocate）專屬剖析**：以翠綠漸層主視覺呈現核心性格介紹。
- **五維度量化進度條**：視覺化展示內向（63%）、天馬行空（51%）、情感細膩（53%）、運籌帷幄（74%）、情緒易波動（71%）等特質比例。
- **價值觀與人際風格**：涵蓋名言佳句、「追尋使命」、「人際交往與自我呵護」與「個人使命」等深度內容卡片。

### 4. 📅 115 第一學期課表與修課分析 (`1151schedule.html`)
- **修課數據儀表板**：統計本學期總修習課程數（12 門課 / 31 節）、資工核心必修、跨域通識與上課教學大樓分佈。
- **全週節次互動課表**：
  - 採用色票系統區分「資工核心」、「數學與實驗」、「跨域與應用」、「全民國防」、「通識與未來學」及「語文與體育」。
  - 完美支援連堂跨節次（`rowspan`）高度對齊，並標示授課教師、開課序號與教室代碼。
  - **當日課表自動高亮**：透過 JavaScript 自動判斷造訪當下的星期，動態高亮當日課表欄位並更新頂部狀態標籤。
- **課程分類導覽與校園大樓對照**：分類整理各科修課學分與時段，並附上淡江大學教學大樓代碼對照表（`G` 驚聲紀念大樓、`E` 工學大樓、`B` 商管大樓、`SG` 紹謨紀念體育館）。

---

## 🛠️ 技術棧與設計特色

- **前端核心**：HTML5、CSS3、Vanilla JavaScript（ES6+）
- **樣式框架**：[Tailwind CSS (CDN)](https://tailwindcss.com/) — 自訂 `brand`（Teal 湖水綠）品牌色階與響應式斷點
- **圖示與字型**：
  - [Font Awesome 6.4.0](https://fontawesome.com/)
  - [Google Fonts - Inter](https://fonts.google.com/specimen/Inter) 搭配系統無襯線中文字體
- **設計亮點**：
  - **Bento Grid 響應式佈局**：在手機、平板與桌面端皆能自動排列出流暢緊湊的視覺動線。
  - **細膩微互動 (Micro-interactions)**：包含卡片懸停上浮（Hover Lift）、狀態呼吸燈（Pulse Indicator）、漸層背景滑入特效與自訂極簡捲軸。
  - **圖片容錯機制**：頭像與插圖皆配置 `onerror` 備援佔位圖，確保離線或圖片缺失時版面依然完整。

---

## 📂 專案目錄結構

```text
profile/
├── index.html          # 個人網站與履歷首頁 (Bento Grid 主視圖)
├── portfolio.html      # 作品集與專案展覽頁 (展示 4 項精選開發專案)
├── mbti.html           # MBTI (INFJ-T 提倡者) 人格特質深度分析頁
├── 1151schedule.html   # 淡江資工 115 學年度第一學期互動課表與修課統計頁
├── IMG_3222.jpeg       # 個人大頭貼照片
├── INFJ-T.jpg          # MBTI 提倡者代表圖片
└── README.md           # 專案說明文件
```

---

## 🚀 本地運行與部署

本專案採用純靜態網頁架構，無須安裝任何打包工具或編譯環境即可直接運行：

### 1. 取得專案原始碼
```bash
git clone https://github.com/yanruray/profile.git
cd profile
```

### 2. 本地預覽
- **方式一（直接開啟）**：直接雙擊開啟專案目錄下的 `index.html`。
- **方式二（使用本地伺服器）**：使用 VS Code 的 **Live Server** 擴充套件，或透過終端機啟動簡易 HTTP 伺服器：
  ```bash
  # 使用 Python 3
  python -m http.server 8000
  ```
  接著於瀏覽器開啟 `http://localhost:8000` 即可預覽。

---

## 📬 聯絡資訊 (Contact)

- **Author**：Ray
- **Email**：[raylin070418@gmail.com](mailto:raylin070418@gmail.com)
- **GitHub**：[@yanruray](https://github.com/yanruray)
- **Instagram**：[@confucianism18](https://www.instagram.com/confucianism18/)
- **Discord**：[User Profile](https://discordapp.com/users/989135882428768326)
