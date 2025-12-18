# 🎨 個人作品集網站

一個現代化、響應式的個人作品集網站模板，使用純 HTML、CSS 和 JavaScript 打造。

![Portfolio Preview](https://via.placeholder.com/1200x600/6366f1/ffffff?text=Your+Portfolio)

## ✨ 特色功能

- 🎯 **現代化設計** - 採用最新的設計趨勢，包含漸層、動畫和玻璃擬態效果
- 🌓 **深色/淺色模式** - 支援主題切換，提供更好的閱讀體驗
- 📱 **完全響應式** - 在所有裝置上都能完美顯示（手機、平板、桌面）
- ⚡ **效能優化** - 快速載入，流暢的動畫效果
- 🎭 **平滑滾動** - 優雅的頁面導航體驗
- 🎨 **可自訂** - 易於修改顏色、內容和佈局
- ♿ **無障礙設計** - 符合 ARIA 標準

## 📂 專案結構

```
portfolio-website/
├── index.html          # 主要 HTML 檔案
├── css/
│   └── style.css       # 樣式表
├── js/
│   └── main.js         # JavaScript 互動功能
├── images/             # 圖片資源
└── README.md           # 專案說明文件
```

## 🚀 快速開始

### 1. 下載專案

```bash
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website
```

### 2. 開啟網站

直接在瀏覽器中開啟 `index.html` 檔案，或使用本地伺服器：

**使用 Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**使用 Node.js (http-server):**
```bash
npx http-server -p 8000
```

**使用 VS Code:**
安裝 "Live Server" 擴充功能，然後右鍵點擊 `index.html` 選擇 "Open with Live Server"

### 3. 在瀏覽器中查看

開啟瀏覽器並訪問 `http://localhost:8000`

## 🎨 自訂設定

### 修改個人資訊

1. **編輯 `index.html`**
   - 將 "Your Name" 替換為你的名字
   - 更新個人簡介和描述
   - 修改社群媒體連結
   - 新增你的專案資訊

2. **更新顏色主題**
   
   在 `css/style.css` 中找到 `:root` 區塊，修改顏色變數：
   
   ```css
   :root {
       --primary-color: #6366f1;      /* 主要顏色 */
       --secondary-color: #ec4899;    /* 次要顏色 */
       --accent-color: #14b8a6;       /* 強調顏色 */
   }
   ```

3. **新增專案**
   
   複製專案卡片的 HTML 結構並修改內容：
   
   ```html
   <div class="project-card">
       <!-- 專案內容 -->
   </div>
   ```

4. **更新技能**
   
   在技能區塊中新增或移除技能項目

### 新增圖片

1. 將圖片放入 `images/` 資料夾
2. 在 HTML 中更新圖片路徑：
   ```html
   <img src="images/your-photo.jpg" alt="描述">
   ```

## 📦 部署到 GitHub Pages

### 步驟 1: 建立 GitHub 儲存庫

1. 在 GitHub 上建立新儲存庫，命名為 `your-username.github.io`
2. 將專案推送到 GitHub：

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

### 步驟 2: 啟用 GitHub Pages

1. 前往儲存庫的 **Settings** > **Pages**
2. 在 **Source** 下選擇 `main` 分支
3. 點擊 **Save**
4. 你的網站將在 `https://your-username.github.io` 上線！

## 🛠️ 技術棧

- **HTML5** - 語意化標記
- **CSS3** - 現代化樣式（CSS Variables、Flexbox、Grid、Animations）
- **JavaScript (ES6+)** - 互動功能
- **Font Awesome** - 圖示
- **Google Fonts** - 字型（Inter、Noto Sans TC）

## 📋 功能清單

- [x] 響應式導航列
- [x] Hero 區塊與動畫背景
- [x] 關於我區塊
- [x] 技能展示
- [x] 專案作品集
- [x] 聯絡表單
- [x] 深色/淺色模式切換
- [x] 平滑滾動
- [x] 滾動動畫
- [x] 手機版選單
- [x] 社群媒體連結
- [ ] 部落格區塊（可選）
- [ ] 多語言支援（可選）

## 🎯 瀏覽器支援

- ✅ Chrome (最新版)
- ✅ Firefox (最新版)
- ✅ Safari (最新版)
- ✅ Edge (最新版)
- ⚠️ IE11 (部分功能不支援)

## 📝 授權

此專案採用 MIT 授權 - 詳見 [LICENSE](LICENSE) 檔案

## 🤝 貢獻

歡迎提交 Pull Request 或開啟 Issue！

## 💡 靈感來源

- [developerFolio](https://github.com/saadpasta/developerFolio)
- [MasterPortfolio](https://github.com/ashutosh1919/masterPortfolio)
- [devportfolio](https://github.com/RyanFitzgerald/devportfolio)

## 📧 聯絡方式

如有任何問題或建議，歡迎聯絡：

- Email: your.email@example.com
- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [Your Name](https://linkedin.com/in/yourusername)

---

⭐ 如果這個專案對你有幫助，請給個星星支持一下！

使用 ❤️ 和 ☕ 打造
