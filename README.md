### README.MD


strategies of ml 

1. image classification of 3 candlesticks

2. LSTM RNN time series (OHLC ONLY vs market mapping)

3. NLP news analysis





### what decides bitcoin price:
 The supply of Bitcoin and the market's demand for it
 The cost of producing a bitcoin through the mining process
The rewards issued to Bitcoin miners for verifying transactions to the blockchain
The number of competing cryptocurrencies
Regulations governing its sale and use and the state of its internal governance
News developments

Technical Analysis Indicators in Pandas
https://towardsdatascience.com/trading-technical-analysis-with-pandas-43e737a17861
Bollinger Bands is used to define the prevailing high and low prices in a market to 
characterize the trading band of a financial instrument or commodity. Bollinger Bands are 
a volatility indicator. Bands are consists of Moving Average (MA) line, a upper band and lower 
band. The upper and lower bands are simply MA adding and subtracting standard deviation. Standard 
deviation is a measurement of volatility. That’s why it’s a volatility indictor. 
Upper Band = (MA + Kσ)
Lower Band = (MA − Kσ)
MA =20 K = 2


Becoming Trader Data Scientist:
https://medium.com/coinmonks/becoming-a-trader-data-scientist-transforming-bollinger-bands-part-4-8aab6fbc2f2d




#### See Below for a simple working model   example 1
Github: https://github.com/bnsreenu/python_for_microscopists/blob/master/181_multivariate_timeseries_LSTM_GE.py
Youtube: https://youtu.be/tepxdcepTbY



#### Stock_prediction_hybrid_model   example 2
A hybrid of ANN, RNN and Regressor models to predict stock prices

Det_added.csv has records of events which has significance in Amazon's history. These events may be marked as we know deals and product launches and legal matters 
often regulate a stock.


Future possible work(data is available):
Impact of financial news and traders sentiment analysis, which is not possible right now due to data inavalability. This results combined with the events can be fed to the covering nueral network to provide more robustness.

Description at: https://towardsdatascience.com/stock-price-prediction-based-on-deep-learning-3842ef697da0



#### my previous bitcoin prediction model on tf ibmplatform of data pak example3 
this video explains the common mistakes when stocking price predicting
https://www.youtube.com/watch?v=Vfx1L2jh2Ng
Predicting Stock Prices with LSTMs: One Mistake Everyone Makes (Episode 16)
by Lazy Programmer

highlight: 
this video: min-max scalling
other videos: 1. using price as inputs; 2. using prices as targets; 3. incorrect train-test split (using test data to make predictions);
4. no baseline (does your model beat the naive forecast?); 5. ***NEW IN 2020*** using LSTMs with sequence length of 1


