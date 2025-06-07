校園導覽遊戲 - 使用說明
====================

1. 解壓縮
   - 將下載的 ZIP 檔案解壓縮到任意資料夾
   - 建議使用英文路徑名稱

2. 運行遊戲（請按照以下步驟操作）：

   步驟一：安裝 Node.js
   - 前往 https://nodejs.org
   - 下載並安裝 LTS 版本（長期支援版）
   - 安裝時請勾選「Automatically install the necessary tools...」選項

   步驟二：安裝 http-server
   - 按 Windows 鍵 + R
   - 輸入 cmd 並按確定
   - 在命令提示字元中輸入：
     npm install -g http-server
   - 等待安裝完成

   步驟三：啟動遊戲
   - 在命令提示字元中，切換到遊戲資料夾
     例如：cd C:\Project1
   - 輸入：http-server
   - 在瀏覽器輸入：http://localhost:8080

3. 遊戲控制
   - 方向鍵：移動角色
   - 空白鍵/Enter：確認/對話
   - ESC：取消/選單

4. 常見問題解決：
   如果出現「無法辨識 http-server」錯誤：
   - 重新開啟命令提示字元
   - 或使用完整路徑：
     C:\Users\[使用者名稱]\AppData\Roaming\npm\http-server

   如果出現「無法讀取本地檔案」錯誤：
   - 確保使用 http-server 啟動遊戲
   - 不要直接點擊 index.html

5. 系統需求
   - Windows 10 或更新版本
   - 支援的瀏覽器：Chrome、Firefox、Edge 最新版本
   - 建議使用 1920x1080 或更高的螢幕解析度

如有任何問題，請聯繫遊戲開發者。 