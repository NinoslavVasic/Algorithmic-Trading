
![image](bermuda.PNG)

# p2_team4
Bermuda 


## Team Members
Roger Hahn, Pedro Nunes, Ninoslav Vasic, Troy Draizen

## Description
Our proposal is to develop an algorithmic trading model that is trained on a combination of sentiment and technical and macro indicators for the US equities market, specifically the SP500 universe. We will obtain sentiment data from various sources including Twitter from Trump, Karmer and other market and political sources. The newsapi will also be used. The sentiment data will be processed using NLP and polynomials library from sklearn and other libraries as appropriate. We may leverage existing technologies such as Stocktwit. Technical indicators will be calculated from tick data obtained from IEXfinance and other sources. We will apply various machine learning models such as, but not limited to deep learning. Our benchmark will be the SP500.  Once trained, we will evaluate predictions using a confusion matrix. The results of our analyses will be displayed on a servable panel and possibly using Business Intelligence visualizations available on AWS. All code will be developed on Sagemaker. 

Our stretch goals are to deploy the model in an algorithm that monitors real-time tick data and make buy/sell/hold instructions based on the algorithm. If a signal is generated, the algorithm will send a buy/sell/short order to a broker via an API to execute the trade.

## Field
Algorithmic trading

## Data to Use and Possible Sources
Twitter, IEXFinance, Fred, Polygon, newsapi, reuters, yfinance


## Candidate ML or Statistical Models to Explore

ARIMA for time series, Deep Learning, NLTL for sentiment analysis
