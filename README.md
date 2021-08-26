# predictingDowJones1-D_CNN_RNN
Use Reddit News Headlines to predict the movement of Dow Jones Industrial Average.

## Problem Statement & Reference Architecture

* **Aim**: Use Reddit News Headlines to predict the movement of Dow Jones Industrial Average.   

* **Data Source**: https://www.kaggle.com/aaron7sun/stocknews 


* **Data Description**: Dow Jones details on Open, High, Low and Close for each day from 2008-08-08 to 2016-07-01 and headlines for those dates from Reddit News. 


* **Methodology**: For this project, we will use GloVe to create our word embeddings and CNNs followed by LSTMs to build our model. This model is based off the work done in this paper https://www.aclweb.org/anthology/C/C16/C16-1229.pdf.


We'll use a stock market price index data to implement the 1D CNN-RNN architecture. Generally speaking, a **stock market index**, along with a multitude of other factors, also gets affected by the news headlines that run daily on television and newspapers. Highly negative news impacts the stock market negatively and positive news impacts the stock market positively.
 In this session, we'll try to model this relationship between the news and the stock market price of an index. Our assumption in modelling the stock price in this exercise is that **news headlines that run on a particular day affect the opening stock price of an index the very next morning.**
 
That being said, the **important thing** to keep in mind while doing this exercise is to focus on the process of extracting textual features using 1D CNN and then feeding them to an RNN.

The dataset consists of two CSV files:  
1.	The first file contains the stock market data that belongs to the Dow Jones Industrial Average index.  
2.	The second file contains a series of dates and the corresponding American news headlines from major news sources of the country.  
 
We'll use the above data to model the effect of the news of a particular day on the opening price of the Dow Jones index on the next day.  


