# 📋 OpenClaw 工作看板

一個簡單的 Kanban 看板，用於追蹤 OpenClaw 工作任務。

## 🌐 網址

https://shoung.github.io/kanban-board/

## 📋 工作流程

| 欄位 | 說明 |
|------|------|
| 📝 Ready | 任務放置區（Shoung 或 TT 放置） |
| 📋 To Do | 確認要執行的任務 |
| 🔥 In Progress | TT 正在執行 |
| 👀 Checking | 等待 Shoung 確認 |
| ✅ Finished | 已完成確認 |
| ⏸️ Waiting | 卡關中（需加備註說明問題） |

## 🎯 功能

- ✅ 拖曳式卡片管理
- 💾 資料自動儲存（localStorage）
- 👤 創建者欄位（Shoung / TT）
- 💬 備註功能（溝通用）
- ✏️ 卡片編輯功能
- 📅 創建時間戳
- 🔄 定期任務管理
- 📱 響應式設計
- 🌙 深色主題

## 👥 使用方式

### 新增任務
- **Shoung**: 在 Ready 欄新增任務
- **TT**: 可在 Ready 欄新增自己的想法（選擇「TT」為創建者）

### 移動任務
- 拖曳卡片到不同欄位
- TT 遇到問題時：加入備註 → 移至 Waiting

### 定期任務
- 預設開啟「每2小時檢查看板」
- 預設開啟「每週 ProductHunt 靈感搜尋」
- 可自行新增/刪除/開關

## 💾 資料備份

點擊「匯出」按鈕可下載 JSON 備份檔案
