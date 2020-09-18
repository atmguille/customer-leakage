# Customer leakage using ML techniques

This project was developed as part of the Artificial Intelligence course at UAM by [Daniel Gallo](https://github.com/daniel-gallo) and myself.

We were required to predict the 100 clients that were most likely to leave a telephone company, based on the provided data and using Machine Learning techniques. To do this task, we followed the following steps:

1. Preprocessing:
   1. Feature selection based on distribution plots, information gain, ...
   2. Standardization
2. Models: optimize the hyperparameters and train three main models (KNN, Decision Tree and MLP)
3. Predict the 100 clients: this predictions are stored in their correspondent `csv`. In addition to this, for the final prediction, we decided to combine the predictions of the models.

For the detailed and step-by-step implementation, check [customer_leakage.ipynb]()