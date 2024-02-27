# Bybit Spot-Futures Arbitrage

## 項目概述
此程式接受輸入Bybit 現貨/合約(含括USDC/USDT)的交易對，並且在偵測滿足價差的情況下使用api進行雙邊下單，以達成期現套利。

## 使用說明
1. 使用 `save_api` 檔案輸入api key及secret key 並點選保存，會自動儲存在 `config.json` 文件中。
2. 執行主程序 `client` 。
3. 待終端機開啟後，於終端機按要求輸入帳號密碼，成功驗證則等待主程式開啟。
4. 設定交易對及下單要求等，程式即會按條件進行api下單。

## 注意事項
`client` 及 `config.json` 需位於同一資料夾或路徑底下，zip整包下載後可將非自身電腦配置的檔案刪除。

## 更新日誌
詳情請查看 [CHANGELOG.md](CHANGELOG.md)。

## 版權信息
Copyright (c) 2024 Murmurcats NFT 社團，所有權利保留 [LICENSE](LICENSE)。

## 開發者
Jeffery200140
