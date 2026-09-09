# ClaudeCode_MyTools 專案規則

## 環境重掃（含每週三 23:00 自動重掃）
`ClaudeCode_MyTools.html` 的 `TOOLS` 陣列裡，**`type: "待試・未安裝"` 的條目是刻意保留的待辦清單，不是環境掃描結果**。

- 這些條目本來就沒裝，環境裡掃不到是正常的——**絕對不要因為掃不到就當「已移除」刪掉**，除非使用者當次明確要求移除。
- 每個這類條目的 `note` 開頭也會有防護句（「刻意保留的待辦條目…」），但那是給人看的雙重保險，不是唯一防線；這條規則本身才是真正的判斷依據。
- 新增待辦條目時，`note` 開頭請照既有格式加上同一句防護句，維持一致。

目前待辦條目：claude-seo（SEO 稽核 plugin）、Open Slide（投影片即程式碼框架）、phone-harness（讓 agent 操控真實 iPhone）、OfficeCLI（Office 文件自動化 CLI）。
