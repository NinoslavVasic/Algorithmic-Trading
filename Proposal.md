
![image](bermuda.PNG)

# p2_team4
Bermuda 


## Team Members
Roger Hahn, Pedro Nunes, Ninoslav Vasic, Troy Draizen

## Description
Our proposal is to develop an algorithmic trading model that is trained on a combination of sentiment, technical, and macro indicators for the US equities market, specifically within the SP500 universe. We will obtain sentiment data from various sources including tweets from Trump, Kramer, and other market/political sources. The newsapi will also be used. Sentiment data will be processed using NLP, the polynomials library from sklearn, and other libraries as appropriate. We may leverage existing technologies such as Stocktwit. Technical indicators will be calculated from tick data obtained from IEXfinance and other sources. We will apply various machine learning models such as, but not limited to deep learning. Our benchmark will be the SP500.  Once trained, we will evaluate predictions using a confusion matrix. The results of our analyses will be displayed on a servable panel using Business Intelligence visualizations available on AWS. All code will be developed on Sagemaker and shared on our git repo. 

Our stretch goals are to deploy the model in an algorithm that monitors real-time tick data that can send buy/sell/hold instructions to a broker such as Interactive Brokers. If a signal is generated, the algorithm will send a buy/sell/short order to the broker via an API to execute the trade.

## Field
Algorithmic trading

## Data to Use and Possible Sources
Twitter, IEXFinance, Fred, Polygon, newsapi, reuters, yfinance


## Candidate ML or Statistical Models to Explore

Deep Learning, NLTK for sentiment analysis, Polynomials from sklearn
