簡記 v3.7｜PWA 自動更新版

請將 ZIP 內全部檔案（index.html、manifest.json、icon.svg、sw.js）覆蓋 GitHub Pages 專案根目錄同名檔案並 Commit。

本版加入 Service Worker 主動更新檢查。GitHub Pages 發布新檔後，已安裝的 PWA 在下次連線開啟時會檢查新版，安裝完成後自動重新載入。離線時會使用快取版本。

不會清除 localStorage、IndexedDB 或 Supabase 雲端資料。第三方 CDN（Supabase JS、SheetJS）維持由網路載入，不會快取第三方 API 回應。
