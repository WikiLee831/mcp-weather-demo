# MCP 怎麼幫 AI 查天氣？

生成式AI導論課程用的 MCP（Model Context Protocol）互動示意圖。

線上版：https://wikilee831.github.io/mcp-weather-demo/

## 兩種模式

- **📘 範例**：固定的示範資料，不需網路。
- **🌐 真實資料**：由瀏覽器直接呼叫[中央氣象署氣象資料開放平臺](https://opendata.cwa.gov.tw/index)的「今明 36 小時天氣預報」（F-C0032-001）。
  第一次使用請點「🔑 授權碼」輸入自己的授權碼（免費註冊取得），授權碼只存在你自己的瀏覽器（localStorage），不會上傳到這個網站。

網址加 `?mode=real` 可直接開啟真實資料模式，加 `#3` 可直接跳到第 3 步。
