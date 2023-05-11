# Fake_news_prediction

We developed a fake news prediction model using NLP.

The datasets used on the model training can be found at https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset. 

We performed so data analysis to have a better understanding of the data we were working with. We also performed data preparation in order to prepare the data for the model implementation.

In order to find the model with the best accuracy to be implemented we tested 3 different ones Linear SVC, Multinomial Naive Bayes and Logist Regression. 
The model with the best accuracy results is the Linear SVC therefore it was implemented. The Linear SVC gave a accuracy score around 99%.
To assure that the model was not being overfitted we analysed the training accuracy against the test accuracy. The conclusion of the analyses is that the model is not being overtitted.
