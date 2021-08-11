# AIAdvisor-StockPrediction
Stock prediction using Sentiment Analysis, Time-series Analysis and Topic Modelling.
The models have been built based on the data for "Facebook".
Gave an error of around $5 in the prediction.

## Testing for Amazon:

Average absolute error = $293.243323

Output is subject to the articles scraped by the GoogleNews API.

Only the data sources need to be changed.

* googlenews.search("Amazon") - gave 69345 articles on scraping and 17114 on filtering by source popularity
* AMZN.csv is uploaded for historical data - 6025 rows
* Change the URLs for Macro-trends attributes and change the column name of the URL scraped.
1) [PE Ratio](https://www.macrotrends.net/stocks/charts/AMZN/amazon/pe-ratio)
2) [ROA](https://www.macrotrends.net/stocks/charts/AMZN/amazon/roa)
3) [Net Income](https://www.macrotrends.net/stocks/charts/AMZN/amazon/net-income)

[Link to modified Google Colaboratory file](https://colab.research.google.com/drive/1LgLD2Zg8twNlxcHJITipKrGyRk57WA7P?usp=sharing)

## Testing for Microsoft:

* Average absolute error = $18.7756492
* Method testing is similar to above. MSFT.csv is used for historical data - 8926 rows
* 56940 news articles scraped out of whicj 8421 are from popular sources
* Macro-trends URLs:
1) [PE Ratio](https://www.macrotrends.net/stocks/charts/MSFT/microsoft/pe-ratio)
2) [ROA](https://www.macrotrends.net/stocks/charts/MSFT/microsoft/roa)
3) [Net Income](https://www.macrotrends.net/stocks/charts/MSFT/microsoft/net-income)

[Link to modified Google Colaboratory file](https://colab.research.google.com/drive/1ERufMLmkJc5DEVfeJ6R5VDNAQts3zv7W?usp=sharing)

# Drive Link for Models and Files 
The code reads files from a Drive location. Link for that location is:
[Link to Drive folder](https://drive.google.com/drive/folders/1-93t2iua9ay94NTHCCQPVo2Xe-WG3W_B?usp=sharing)
