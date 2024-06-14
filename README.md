# **Abstract:**
**Welcome to the project!  This section gives an overview of the project.**

 In quantitative trading, stock prediction plays an important role in developing an effective trading strategy to achieve a substantial return. Also the prediction outcomes are the prerequisites for active portfolio construction and optimization. However, the stock prediction is a challenging task because of the diversified factors involved such as uncertainty and instability, sentiments of the traders and investors etc. Hence prediction of the stock prices are important to enter into the trade for which one of the most important part is extracting relevant features which can be used for forecasting. 
 
 In this project, we will be extracting various nancial features from the raw downloaded stocks data such as **Bollinger Bands**, **Rate-of-change (ROC)**,**Average Directional Index (ADX)**, **William's % R**, **Stochastic %K** and many others. After extracting various financial features we will move on to the prediction part in which we will be using Machine Learning models such as  **Linear regression**, **Random Forrest**, **XgBoost** and do a comparative study.
 Here, we downloaded and used real life stocks data of di erent domain on which we implemented several models.We choose five sectors namely **Cipla(pharmaceutical)**, **Coromandel(Agriculture)**, **HDFC Bank(Banking)**, **TCS(IT)**, **Bharat Petroleum(oil and petroleum)**.


 # **Downloading Data**
 To get started with the project, you need to download the necessary data files. The data for the Stocks specified above are downloaded through **Yahoo Finance** by the yahoo finance package in python. 
 
 For downloading the data for the stocks please go to [data extraction.ipynb](https://github.com/srirup11/Prediction_of_multiple_stock_prices_using_features_from_technical_indicators/blob/main/codes/data%20extraction.ipynb)

 # **Feature Engineering**
 This section provides details on the technical indicators used as the features and some other features for prediction in the project. Technical indicators are mathematical calculations based on the price, volume, or open interest of a security or contract. For constructing the features please see [Feature Extraction.ipynb](https://github.com/srirup11/Prediction_of_multiple_stock_prices_using_features_from_technical_indicators/blob/main/codes/Feature%20Extraction.ipynb) and covariate data for the each stock are saved in the folder [Data_of_stocks].
