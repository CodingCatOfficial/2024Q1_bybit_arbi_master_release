# Bybit Spot-Futures Arbitrage

## 項目概述
此程式接受輸入Bybit 現貨/合約(含括USDC/USDT)的交易對，並且在偵測滿足價差的情況下使用api進行雙邊下單，以達成期現套利。

## 使用說明
1. 使用 `save_api` 檔案輸入api key及secret key 並點選保存，會自動儲存在 `config.json` 文件中。
2. 執行主程序 `client` 。
3. 待終端機開啟後，於終端機按要求輸入帳號密碼，成功驗證則等待主程式開啟。
4. 設定交易對及下單要求等，程式即會按條件進行api下單。

## 注意事項
1. `client` 及 `config.json` 需位於同一資料夾或路徑底下，zip整包下載後可將非自身電腦配置的檔案刪除。
2. `config.json` 在使用 `save_api` 後將儲存您的api金鑰，請妥善保管您的金鑰及程式，強烈建議在初始設置金鑰時綁定您的ip地址。

## 更新日誌
詳情請查看 [CHANGELOG.md](CHANGELOG.md)。

## 版權信息
Copyright (c) 2024 Murmurcats NFT 社團，所有權利保留 [LICENSE](LICENSE)。

## 免責聲明
本期現貨下單軟體及其提供的所有資料和服務僅供參考之用，並不構成任何投資建議。使用者應自行承擔使用本軟體進行交易的所有風險。我們對任何直接或間接使用本軟體所發生的損失或損害不承擔任何責任。在使用本軟體進行交易前，使用者應仔細考慮自身的投資目標、經驗水平和風險承受能力。使用本軟體即表示您已閱讀並同意本免責聲明的所有條款。摳頂貓團隊強烈建議在使用任何自動平衡下單程式時，都應該在電腦前以第一時間管理任何單邊曝顯風險。

## 開發者
[jeffrey1167](https://github.com/jeffrey1167)

## 協作者
[hyctw](https://github.com/hyc5566)
[RRRobert](https://github.com/yuying990718)
[godgiraffe](https://github.com/godgiraffe)
[0xCatduck](https://github.com/0xCatduck)
