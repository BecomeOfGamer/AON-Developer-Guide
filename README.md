# AON-Developer-Guide

[AON](https://github.com/RemakeAONTeam/AON) 的開發手冊。  

### 關於 AON

系統使用 [Unreal Engine4](https://www.unrealengine.com) 撰寫，本書內容主要彙整來自 [信長技能BP圖文教學](https://hackmd.io/Z4AAeJrOQ2qHrEFuddUImw#%E6%96%B0%E5%A2%9E%E6%8A%80%E8%83%BD) 的教學文章。

- [RemakeAONTeam](https://github.com/RemakeAONTeam)
- [Patreon](https://www.patreon.com/nobu_game/posts)
- [信長的野望 重製小隊](https://www.facebook.com/Remake.AON/)



### 全域安裝

如果您要在本地進行 gitbook 的閱讀或編輯，請使用 `npm` 指令安裝。  
> 請確認是否已安裝 [Nodejs](https://nodejs.org/en/)

```bash
npm install -g gitbook-cli
```

### Run Gitbook

使用 `dev` 可以在本地 [http://192.168.0.100:8080](http://192.168.0.100:8080) 進行閱讀。
```bash
npm run dev
```

如果要監控檔案的變更即時編譯，請於第一次執行 `server` 後刪除 _book，後續的變更皆會重新編譯，網頁會自動刷新。
> 此問題來自 [git serve can't restart when file changes #1379](https://github.com/GitbookIO/gitbook/issues/1379)  

### Build To HTML

使用 `build` 編譯出靜態檔案，輸出目錄為當前路徑底下的 `dist` 資料夾。
```bash
npm run build
```

### Convert To PDF

使用 `pdf` 將產出 PDF 文件。
```bash
npm run pdf
```
> 如果 OS 為 Windows，請先安裝 [Calibre](https://calibre-ebook.com/download_windows)，並重啟終端機。

### Repository

Gitbook repo - [AON-Developer-Guide](https://github.com/explooosion/AON-Developer-Guide)
