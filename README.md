## Finance Data Project

## Link for BlogPost: https://medium.com/@negi.gaurav2/stock-price-analysis-afc61ebdcde1
**Libraries Used in project:**
1. Numpy & Pandas
2. GLOB
3. csv
4. OS
5. functools
6. seaborn
7. datetime
8. matplotlib

**Motivation:**

The NASDAQ stock market is an American stock exchange. It is the second largest exchange in the world by market capitalization, behind only New York Stock Exchange located in the same city. The exchange platform is owned by Nasdaq.Inc
In this post, we will analyse 3 years of NASDAQ100 data (from 2014 to mid 2017). This data set includes stock prices for following companies:
```
FB — Facebook
GOOG — Google class C
AAPL — Apple
TSLA — Tesla
MSFT — Microsoft
NVDA — NVidia
AMZN — Amazon
CRM — Salesforce
GOOGL — Google class A
ADBE — Adobe
NFLX — Netflix
INTC — Intel
BIDU — Bai
```

**Dataset:**

Data set was gathered from below mentioned Kaggle linked. The dataset was cleaned according the requirement.
https://www.kaggle.com/daytrader/ema-65-crossover

**Files Description:**
daytrader.ai dataset.ipynb: Following file is an ipython notebook which contains a detailed level analysis of the dataset along with the required comments to explain each step.

**Missing Data and Categorical Values:**
I did not used any Machine learning models so there was no need of categorical variable data handling and as for missing data. The orignal data that I gathered was for 5 years but since majority of companies were missing data due to joining them, I only considered 3 years of data i.e. 2014 to 2017 for my exploratorty data analysis.

This was a good approach for this situation as imputing so many values at such large scale would have affected my analysis and it was possibly making data more dirty and unreliable.

**Summary of the Results**

In this project, we took a look at stock price data of some companies over a 3 year time period to understand stock price fluctuations and answered some question which will help a day trader to make better day trading strategies.
We observed how Amazon , Google and Microsoft keep on increasing their technological performance and which resulted in higher stock prices than ever before. Also, we noticed that Netflix seems to be the most riskiest stock with a gradually increasing but very fluctuating graph(high standard deviation) and Adobe with the most stable growth and least standard deviation.
