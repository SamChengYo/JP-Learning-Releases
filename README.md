# Kotoba · ことば

每天，懂一點日文。Windows x64 桌面日語學習應用程式。

## 下載

前往 [最新版本](https://github.com/SamChengYo/JP-Learning-Releases/releases/latest)，下載 `Kotoba-Setup-版本.exe`。安裝後，程式會從這個倉庫自動檢查新版本、背景下載，並讓你選擇重新啟動的時間。

## 第一版內容

- 平假名、片假名、濁音、半濁音與拗音。
- 24 堂原創入門 / N5 基礎課、單字例句與聽力練習。
- 起點診斷、五十音測驗、混合練習與弱點加強。
- 答錯後安排再練習，答對後逐步拉長複習間隔。
- 個人學習紀錄、本機備份與匯入。
- AI 日語老師：使用自己的供應商模型與 API 金鑰，也可使用本機 Ollama。透過官方 LiteLLM SDK 直接呼叫；必要執行環境已隨安裝檔附上。

## 使用提醒

安裝包已內建離線日語聲音、字典、Python 和 LiteLLM，安裝完成即可學習與播放，不必再安裝 Windows 日語語音。聲音使用 HTS Voice “Mei”（MMDAgent Project Team / Nagoya Institute of Technology，CC BY 3.0，模型未修改）；完整授權隨安裝檔附上。

AI 雲端模型使用你自己的供應商帳戶和金鑰，不需另外安裝 SDK；對話與必要學習摘要會傳送到該供應商。金鑰以 Windows 加密儲存，學習資料保存在本機。Ollama 是連接既有服務與模型的選用功能，安裝包不附大型本機 LLM。

目前是可學習、可練習的基礎版本，尚未包含完整 N4～N1、口說評分或漢字筆順評分。測驗是學習診斷，不是官方 JLPT 認證。首版安裝檔未經商業程式碼簽署。

這個倉庫僅提供下載、更新資訊與版本紀錄。原始碼倉庫是私人倉庫。

Copyright © SamChengYo. All rights reserved. Installers are provided for personal use; no source-code license is granted.