# 部署到 iPhone 的說明

## 方法 1: 添加到主畫面 (推薦)

### 步驟：
1. 將 `index.html` 檔案傳送到你的 iPhone
   - 用 AirDrop 傳送
   - 用 Email 傳送
   - 用 iCloud Drive 同步

2. 在 iPhone 上開啟 Safari
3. 開啟 `index.html` 檔案
4. 點擊分享按鈕 (方形箭頭)
5. 選擇 "加入主畫面"
6. 命名為 "KMB Opener"
7. 點擊 "加入"

現在你就有了一個主畫面圖示，點擊就能直接開啟 KMB 網站開啟器！

## 方法 2: 部署到網路 (最佳分享方式)

### 使用 GitHub Pages (免費):

1. 在 GitHub 建立新的 repository
2. 上傳 `index.html` 檔案
3. 在 Settings > Pages 中啟用 GitHub Pages
4. 你的應用程式就會在 `https://你的用戶名.github.io/repository名稱` 上線

### 使用 Netlify (免費):

1. 前往 [netlify.com](https://netlify.com)
2. 拖拽 `index.html` 檔案到部署區域
3. 獲得一個免費的網址
4. 在 iPhone 上開啟該網址並添加到主畫面

### 使用 Vercel (免費):

1. 前往 [vercel.com](https://vercel.com)
2. 連接你的 GitHub 帳號
3. 選擇包含 `index.html` 的 repository
4. 自動部署並獲得網址

## 方法 3: 本地網路分享

如果你有電腦和 iPhone 在同一個 WiFi 網路：

1. 在電腦上安裝 Python
2. 在包含 `index.html` 的資料夾中開啟終端機
3. 執行：`python -m http.server 8000`
4. 在 iPhone 上開啟：`http://你的電腦IP:8000`
5. 添加到主畫面

## 推薦使用方法 1

對於個人使用，**方法 1 (添加到主畫面)** 是最簡單的：
- 不需要網路連線
- 載入速度快
- 使用體驗像原生 App
- 設定簡單

選擇最適合你的方法吧！
