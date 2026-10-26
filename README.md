# 獎勵金計算系統

Windows Python 版獎勵金、所得稅與二代健保計算系統。

Copyright © 2026 TienHsien LIU. All rights reserved. 本軟體為專有軟體，未經著作權人書面授權，不得免費或商業使用；首次安裝提供 3 個月、綁定本機的試用。詳見 [LICENSE](LICENSE)。

- 授權版初次安裝包：[下載 setup.zip](https://github.com/mathersky/BonusLedger/raw/refs/heads/main/updates/licensed/setup.zip)。
- 客戶端更新檔與簽章清單：[授權版更新通道](https://github.com/mathersky/BonusLedger/tree/main/updates/licensed)。
- 客戶端會自動檢查版本，更新包須通過 Ed25519 簽章及 SHA-256 驗證。
- 公開客戶版不包含員工名冊；首次啟動後請匯入本單位員工資料。
- 員工、帳號、身分證與獎金紀錄只保存於本機 `%LOCALAPPDATA%\BonusLedger`。
- 主控端及簽章私鑰請另行保管，不要上傳到此儲存庫。
- 主控端可簽發 1 個月、3 個月、1 年或永久授權；授權綁定單一電腦。

## 安裝

下載 `setup.zip`，解壓縮後雙擊 `SETUP安裝軟體.bat`。需安裝 Python 3.10 以上（建議 3.12，含 Tcl/Tk）。首次啟動會自動安裝必要套件，並在桌面及軟體資料夾建立使用主題圖示的捷徑。`client.zip` 僅供程式自動更新。
