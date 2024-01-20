# Cuisine Prediction based on Ingredients
Based on the Ingredients of a reciepe, we try to classify the cuisine. <br >
We tried out different models to find the best. In the list below are name of the models and corresponding accruacy.

## Accuracies
MLP:           0.76 <br >
LSTM:          0.73 <br >
MultinomialNB: 0.74 <br >
XGBoost:       0.79 <br >
CNN:           0.71 <br >
RandomForest:  0.74 <br >
logisticReg:   0.44 <br >
lineraSVC:     0.39 <br >

For all models CountVectorizer was used as tokenization.

## Conclusion
With the XGBoost we achieved the best accuracy. To achieve better result other tokenization techinqes should been testet.  
