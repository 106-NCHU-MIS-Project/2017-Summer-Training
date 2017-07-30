# Scrapy - 以蘋果新聞為例
[Scrapy Document](https://docs.scrapy.org/en/latest/)
## Requirements
* bs4
`pip install bs4`

## Installation
```shell=
pip install scrapy
```

## Usage

```shell=
cd ./Crawler/apple
scrapy crawl apple -o apple.json -t json
```
最後會輸出一個 apple.json ，可以發現這個output 會依照我在 items.py 中定義的 Schema 儲存，而這個file會以unicode編碼，可以再進行後續的處理。
