
![image](bermuda.PNG)

# p2_team4
Bermuda 


## Team Members
Roger Hahn, Pedro Nunes, Ninoslav Vasic, Troy Draizen

## Description
Our proposal is to develop an algorithmic trading model that is trained on a combination of sentiment, technical, and macro indicators for the US equities market, specifically within the SP500 universe. We will obtain sentiment data from various sources including tweets from Trump, Kramer, and other market/political sources. The newsapi will also be used. Sentiment data will be processed using NLP, the polynomials library from sklearn, and other libraries as appropriate. We may leverage existing technologies such as Stocktwit. Technical indicators will be calculated from tick data obtained from IEXfinance and other sources. We will apply various machine learning models such as, but not limited to deep learning. Once trained, we will evaluate predictions using a confusion matrix. We will benchmark against the SP500. We will tune hyperparameters and finally select an optimal model for production. The results of our analyses will be displayed on a servable panel and contain relevant Business Intelligence visualizations using hvplot and pyviz. All code will be developed on AWS Sagemaker Studio and shared on our git repo. 

Our stretch goal is to deploy the trained model into production with appropriate risk mitigation and monitoring tools. The trained model will be incorporated into a trading algorithm that monitors real-time tick data. The trading algorithm will use the trained model to generate buy/sell/hold signals. The trading algorithm will then send signals to a broker such as Interactive Brokers via an API to execute the trade. Prior to implementation, we will backtest our approach against historical data and make changes to either the trained model or trading algorithm, or both, as necessary. 

## Field
Algorithmic trading

## Data to Use and Possible Sources
Twitter, IEXFinance, Fred, Polygon, newsapi, reuters, yfinance


## Candidate ML or Statistical Models to Explore

Deep Learning, NLTK for sentiment analysis, Polynomials from sklearn
