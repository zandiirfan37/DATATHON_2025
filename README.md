Hello, this is the instruction for the codes of Iris Avenger's Team.

First, we did some scrape by API Binance to get some offchain data(OHLCV) of bitcoin. The code is mentioned in folder 'Scraping Data' with name 'offchain_scraping'. For two other files, we downloaded onchain data from https://coinmetrics.io/community-network-data/ 'Download data for all assets as a ZIP file' and choosed for bitcoin file. for macro data we did scrape and the details are written in folder scrraping with name 'macro_scraping'

Second, we did some cleaning and indexing so each files is written in hourly timeframe before merge. The code is mentioned in folder 'Cleaning Data'.

Third, we did some feature engineering for each files before splitting process. the code is written in folder 'Feature Engineering & Splits Data'

Fourth, we did some model exploration. the code is written in folder 'Exploring Models'

Fifth, we mention our final models in folder 'Final Models & Specific Architecture'
