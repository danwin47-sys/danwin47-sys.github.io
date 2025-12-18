# 🚀 Derek Shih 作品集網站部署指南

## 📋 專案資訊

- **姓名**: Derek Shih
- **專長**: Vibe Coding 實踐者 | Python 開發者 | AI 工具愛好者
- **專案數量**: 3 個（Boardgame-Web、PaddleOCR Toolkit、Whisper Desktop）

## 🌐 部署到 GitHub Pages

### 步驟 1: 建立 GitHub 儲存庫

1. 前往 [GitHub](https://github.com) 並登入你的帳號
2. 點擊右上角的 `+` 號，選擇 `New repository`
3. **重要**：儲存庫名稱必須是 `danwin47-sys.github.io`（你的 GitHub 使用者名稱 + `.github.io`）
4. 設定為 `Public`
5. **不要**勾選 "Initialize this repository with a README"
6. 點擊 `Create repository`

### 步驟 2: 推送程式碼到 GitHub

在專案目錄中執行以下命令（已經初始化完成）：

```powershell
# 設定遠端儲存庫（替換為你的 GitHub 使用者名稱）
git remote add origin https://github.com/danwin47-sys/danwin47-sys.github.io.git

# 設定主分支名稱
git branch -M main

# 推送到 GitHub
git push -u origin main
```

### 步驟 3: 啟用 GitHub Pages

1. 前往你的 GitHub 儲存庫頁面
2. 點擊 `Settings`（設定）
3. 在左側選單中找到 `Pages`
4. 在 **Source** 下拉選單中選擇 `main` 分支
5. 點擊 `Save`
6. 等待幾分鐘，你的網站就會在 `https://danwin47-sys.github.io` 上線！

## ✅ 已完成的設定

- ✅ Git 儲存庫已初始化
- ✅ 所有檔案已加入版本控制
- ✅ 初始 commit 已完成
- ✅ 個人資訊已更新為 Derek Shih
- ✅ 三個專案已加入作品集
- ✅ Vibe coding 理念已融入網站

## 📝 下一步建議

### 立即執行

```powershell
# 1. 設定 Git 使用者資訊（如果還沒設定）
git config --global user.name "Derek Shih"
git config --global user.email "derek.shih@example.com"

# 2. 新增遠端儲存庫
git remote add origin https://github.com/danwin47-sys/danwin47-sys.github.io.git

# 3. 推送到 GitHub
git push -u origin main
```

### 自訂網域（選用）

如果你有自己的網域名稱：

1. 在專案根目錄建立 `CNAME` 檔案
2. 在檔案中輸入你的網域（例如：`derekshih.com`）
3. 在你的網域服務商設定 DNS：
   - 新增 CNAME 記錄指向 `danwin47-sys.github.io`
4. Commit 並 push 到 GitHub

## 🎨 後續優化建議

### 內容更新
- [ ] 更新統計數據（完成專案數、技能數、經驗年數）
- [ ] 新增個人照片到 `images/` 資料夾
- [ ] 新增專案截圖
- [ ] 更新真實的 Email 地址

### 功能擴展
- [ ] 整合 Google Analytics 追蹤訪客
- [ ] 新增部落格區塊分享 vibe coding 心得
- [ ] 整合聯絡表單後端（EmailJS、Formspree）
- [ ] 新增履歷下載功能

### SEO 優化
- [ ] 更新 meta description
- [ ] 新增 Open Graph tags（社群媒體分享預覽）
- [ ] 新增 favicon
- [ ] 建立 sitemap.xml

## 📊 專案統計

- **HTML**: 1 個檔案（完整的作品集結構）
- **CSS**: 1 個檔案（1000+ 行精心設計）
- **JavaScript**: 1 個檔案（完整的互動功能）
- **總行數**: 約 2000+ 行
- **開發時間**: 透過 vibe coding 快速完成！

## 🎯 專案特色

1. **Vibe Coding 理念**
   - 所有內容都強調 vibe coding 的開發方式
   - 專案描述突出靈感驅動的開發過程

2. **真實專案展示**
   - Boardgame-Web：桌遊管理系統（270+ 測試）
   - PaddleOCR Toolkit：OCR 工具（391 個測試，84% 覆蓋率）
   - Whisper Desktop：語音轉錄應用

3. **現代化設計**
   - 深色/淺色模式切換
   - 響應式設計
   - 流暢動畫效果
   - 專業配色系統

## 🔗 重要連結

- **GitHub**: https://github.com/danwin47-sys
- **作品集網站**: https://danwin47-sys.github.io（部署後）
- **專案儲存庫**:
  - Boardgame-Web: https://github.com/danwin47-sys/boardgame-web
  - PaddleOCR Toolkit: https://github.com/danwin47-sys/paddleocr-toolkit
  - Whisper Desktop: https://github.com/danwin47-sys/whisper-desktop

## 💡 疑難排解

### 問題：推送時要求輸入帳號密碼

**解決方案**：GitHub 已不支援密碼驗證，需要使用 Personal Access Token

1. 前往 GitHub Settings > Developer settings > Personal access tokens
2. 點擊 "Generate new token (classic)"
3. 勾選 `repo` 權限
4. 複製生成的 token
5. 推送時使用 token 作為密碼

### 問題：網站沒有顯示

**解決方案**：
1. 確認儲存庫名稱是 `danwin47-sys.github.io`
2. 確認 GitHub Pages 設定正確
3. 等待 5-10 分鐘讓 GitHub 建置網站
4. 清除瀏覽器快取後重新載入

### 問題：樣式沒有載入

**解決方案**：
1. 確認所有檔案都已推送到 GitHub
2. 檢查檔案路徑是否正確（相對路徑）
3. 查看瀏覽器開發者工具的 Console 是否有錯誤

---

**準備好了嗎？執行上面的命令，讓你的作品集上線吧！** 🚀

使用 ❤️ 和 ☕ 打造 | Powered by Vibe Coding
