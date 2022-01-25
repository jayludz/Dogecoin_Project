# Dogecoin-Project

Author: John Ludlum

Date: 1/24/2022

A multiple linear regression model is made to predict the price of Dogecoin from 2/24/2021 to 11/19/2021. The Raw Data folder contains the following files:

- **dogecoin_prices.csv**: Dogecoin price data downloaded from [CoinDesk](https://www.coindesk.com/price/dogecoin/).
- **google_trends_data.csv**: daily search trends for Dogecoin obtained from [Google Trends](https://trends.google.com/trends/explore?date=2021-02-24%202021-11-19&geo=US&q=dogecoin). Values close to 0 indicate few searches while values close to 100 indicate many searches on a given day compared to other days in the overall time period.
- **social_sentiment.txt**: social media sentiment (Twitter & Telegram) for Dogecoin scraped from [CoinDesk](https://www.coindesk.com/price/dogecoin/) using Google Chrome's developer tool.

The data was cleaned and assembled into the **dogecoin_dataset.csv** in the Clean Data folder. The analysis is carried out in the **dogecoin_project.ipynb** notebook.
