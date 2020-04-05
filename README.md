![image](bermuda.png)



# p2_team4
Columbia Finance


## Team Members
Roger Hahn, Pedro, Nino Vasic, Troy Draizen


## Description
Our proposal is to develop an algorithmic trading model that is trained on a combination of sentiment and technical indicators for the US equities market, specifically the SP500 universe. We will obtain sentiment data from various sources including Twitter and newsapi. The sentiment data will be processed by NLTK and other libraries as appropriate. We may leverage existing approaches such as Stocktwit. Technical indicators will be calculated directly from tick data obtained from Polygon or IEXfinance. We will apply various machine learning models including deep learning, LTSM, and others. Once trained, we will evaluate the predictions using a confusion matrix. As a benchmark, we will also compare the ML approach to standard trading strategies such as a Moving Crossover Strategy. The results of our analyses will be displayed on a servable panel deployed as an EC2 instance. All code will be developed on AWS Sagemaker. 

Our stretch goals are to deploy the model in a bot that monitors real-time tick data and make periodic predictions based on our model. If a signal is generated, the bot will send a buy/sell order to a broker to execute the trade.

## Field
Algorithmic trading

## Data to Use and Possible Sources
Twitter, IEXFinance, Fred, Polygon, newsapi, reuters, yfinance


## Candidate ML or Statistical Models to Explore

ARIMA for time series, Deep Learning, NLTL for sentiment analysis