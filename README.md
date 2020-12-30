# Crypto-Wallet-data
The raw data collect for [Crypto-Wallet](https://d50000.github.io/Crypto-Wallet/).  
Run the crawler to get the cryto data in [CoinMarketCap](https://coinmarketcap.com/) and save it in CSV file.
All the data will assume be static and changeless(not often change).  
example:  
- full_name
- symbol
- officail_website
- white_paper
- rank
- icon

## Crawler (pyhon3 scrapy)
- Require Python 3.6+
- Setup ```pip install scrapy```
- Create project ```scrapy startproject cryptoData```
![](https://github.com/D50000/Crypto-Wallet-data/blob/main/workflow.png)  

## Reference:
https://coinmarketcap.com/  
https://github.com/scrapy/scrapy  
https://www.maxlist.xyz/2018/08/25/python_scrapy_ptt/  
White Paper and technical document will all from their own official website.
