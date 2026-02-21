# Purri

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-blue)](https://github.com/wupingju/purri-releases/releases)
[![Latest Release](https://img.shields.io/github/v/release/wupingju/purri-releases)](https://github.com/wupingju/purri-releases/releases/latest)

一個安靜住在選單列的 macOS 語音轉文字 App，只要按住快捷鍵、說話、放開，等幾秒，就會自動貼上潤飾好的文字。


---

## 核心特色

- **簡單，但夠用**：
  沒有複雜的模式，只有單純的語音輸入與轉錄，只要按住快捷鍵、說話、放開，潤飾過的文字會自動貼到游標位置。
- **為台灣用戶打造**：
  轉錄與潤飾的預設語言都是繁體中文，不用擔心不小心跑出簡體中文。
- **重視隱私，開箱即用**：
  不要求多餘權限、不需要註冊帳號、你的 API key 存在自己電腦，所有轉錄都不會傳送給 Purri，只會給你指定的轉錄服務提供廠商。
- **用多少，付多少**：
  Purri 免費下載使用，自己用自己的 API key，轉錄多少就付多少，不用被訂閱制綁住。


---

## 主要功能

### 兩種錄音模式

依你的習慣選擇最順手的方式。

- **長按模式** — 按住快捷鍵說話，放開即停止錄音。
- **短按模式** — 按一下快捷鍵開始說話，再按一下就停止錄音，也可以在靜音幾秒後自動停止。


### AI 文字潤飾

零散的口語可以在 AI 潤飾後直接送出，還可以重新潤飾成其他情境的版本。

- Purri 內建專門的潤飾 prompt，會自動幫你把口語的語音轉錄結果，整理成通順文字，但不會魔改到完全認不出來。
- 內建多種潤飾情境：通用、會議記錄、Email 草稿、技術文件


### 歷史紀錄

每一次轉錄都完整保留，隨時回顧。

- 瀏覽所有轉錄紀錄：原始語音、轉錄文字、潤飾結果
- 重新潤飾 — 對結果不滿意？換個情境重跑一次
- 匯出文字檔，方便歸檔或分享

### 用量追蹤

清楚掌握 API 使用狀況。

- 每月 token 用量與估計費用一目瞭然
- 按月瀏覽歷史用量

### 自帶 API Key

使用你自己的 OpenAI API Key，沒有訂閱費、沒有中間商。

- API Key 安全儲存在 macOS Keychain
- 語音只傳送到 OpenAI 處理，不經過任何第三方伺服器
- 你完全掌控自己的資料與費用

---

## 安裝方式

### 下載

從 [Releases](https://github.com/wupingju/purri-releases/releases/latest) 下載最新的 `.dmg` 檔案。

### 系統需求

- macOS 14.0 (Sonoma) 或更新版本
- Apple Silicon 或 Intel Mac
- OpenAI API Key（[在這裡取得](https://platform.openai.com/api-keys)）

### 首次啟動

1. 打開 `.dmg`，將 Purri 拖曳至「應用程式」資料夾
2. 啟動 Purri — 選單列會出現一隻貓的圖示
3. 依引導設定 API Key、授權麥克風和輔助使用權限
4. 試錄一段話，確認一切正常
5. 開始使用！

---

## 定價

### BYOK 版（目前）

**永久免費** — 使用你自己的 OpenAI API Key，所有功能皆可使用。

你只需支付 OpenAI 的 API 使用費用（通常每次轉錄不到 $0.01 USD）。

---

## 隱私與安全

Purri 以隱私為核心設計原則：

| 項目 | Purri 的做法 |
|------|-------------|
| **語音資料** | 僅傳送至 OpenAI API，不經過其他伺服器 |
| **API Key** | 儲存在 macOS Keychain，不會上傳到其他任何地方 |
| **需要帳號** | 否 |
| **分析/追蹤** | 無 |
| **第三方伺服器** | 無 |

你的語音和文字資料只會在你的電腦和 OpenAI 之間傳輸，Purri 不會收集或儲存任何資料。

---

## 支援

有任何問題、功能建議或回饋，歡迎寫信聯絡: [pj@purri.app](mailto:pj@purri.app)
