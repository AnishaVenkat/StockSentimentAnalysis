# StockSentimentAnalysis
This project gives the idea of stock prices going up and down depending on various factors

There are 2 labels 0 and 1 '0' indicates stock prices going up and 1 indicates stock prices going down.

Here in this dataset , we use regular expressions to eliminate extra words and punctuations and Natural Language processing techniques to find relationship between the features.

For Model building we use RandomForestClassfier which gives better accuracy , Precision and Recall score for stock prices going up and down:

Accuracy:0.5158730158730159
********************************************************************************
              precision    recall  f1-score   support

           0       0.53      0.15      0.23       186
           1       0.51      0.88      0.65       192
