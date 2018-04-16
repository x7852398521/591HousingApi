591 租屋網資訊API
==================

## 說明
給他一個 591 的網址，他會將租屋資訊轉成 JSON 格式給你。提供一個 cli 工具以及一個基於 flask 的 api 介面。

## 使用方式
### 安裝
1. 先 clone 一份 repo 到本地端
```sh
git clone git@github.com:frankurcrazy/591HousingApi.git
cd 591HousingApi
```

2. 安裝 python 的 dependencies
```bash
pip install -r requirements.txt
```

3. 使用指令介面或 API 介面
如果要使用指令介面請直接輸入
```bash
python ./parsing.py [591 租屋網網址]
```

如果要使用 API 介面，請輸入
```bash
python ./app.py
```
打開瀏覽器輸入網址: http://localhost:5000/591/[591 租屋網網址]

### 線上使用
https://frankchang.me/591/[591 租屋網網址]
