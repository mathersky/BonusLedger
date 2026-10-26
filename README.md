# 獎勵金計算系統

Windows Python 版獎勵金、所得稅與二代健保計算系統。

- 最新安裝包與版本資訊：[GitHub Releases](https://github.com/mathersky/BonusLedger/releases/latest)
- 客戶端自動檢查更新；套件須通過 Ed25519 簽章及 SHA-256 驗證。
- 公開客戶版不含員工名冊；首次啟動後請匯入本單位員工資料。
- 員工、帳號、身分證與獎金紀錄只保存於本機 `%LOCALAPPDATA%\\BonusLedger`。
- 主控端與簽章私鑰由發布者離線保管，不會放入公開倉庫。

## 安裝

從 Releases 下載 `client.zip`，解壓縮後執行 `啟動獎勵金系統.bat`。需安裝 Python 3.10 以上（建議 3.12，含 Tcl/Tk）；首次啟動會安裝必要套件。

## 自動更新

此版為含更新器的初始版本。先前舊版不含更新器，需先手動安裝此版本；之後會檢查 Releases 並驗證簽章，再提供更新。
