# Bybit Spot-Futres Arbitrage

## 項目概述
此程式接受輸入Bybit 現貨/合約(含括USDC/USDT)的交易對，並且在偵測滿足價差的情況下使用api進行雙邊下單，以達成期限套利。

## 安裝指南
1. 確保 Python (推薦 3.7 或以上版本) 已安裝在您的系統上。
2. 下載或克隆本項目到本地目錄。
3. 在項目根目錄下打開終端或命令提示符。
4. 安裝所需的依賴包：
```
pip install -r requirements.txt
```

## 使用說明
1. 在 config.json 文件中填寫必要的配置信息，如 API 密鑰等。
2. 執行主程序：
```
python client.py
```
3. 於終端機按要求輸入帳號密碼
4. 設定交易對及下單要求等，程式即會按條件進行api下單。

## 更新日誌
詳情請查看 [CHANGELOG.md](CHANGELOG.md)。

## 版權信息
Copyright (c) 2024 Murmurcats NFT 社團，所有權利保留 [LICENSE](LICENSE)。

## 開發者
Jeffery200140


