# Artificial Neural Networks Final Project: Resturant Reviews
### By Nick McGeveran and Kayln Washington

## Our Motivation
Decoding restaurant reviews on Yelp or Google is a simple affair. The reviewer assigns a star rating and elaborates on it. Whether you choose to read the review or not, there is a numeric value at the top to gauge the general sentiment of customer. 

But what about food critics? Travel bloggers? Reddit commenters?

To gauge their general sentiment about a spot, you must read the whole review. We want to make it easier to gather information from different sources without reading everything yourself. 

***How can neural networks be leveraged to perform sentiment analysis on Yelp reviews? Can these results be extended to longer/more complicated reviews?***

## Methodology
We used a Yelp Dataset from Kaggle to train our model with simpler and labeled data. We had two models - a logisitic regression model using Term Frequency, Inverse Document Frequency features and a long short term memory model. Then, we applied these trained models on a new dataset containing New York Times articles, which are notably longer.

## Results
We measured the efficacy of the models using the precision, recall, and f1-score. The following are graphical representations of these measures:


<img src="blog_figures/Yelp%20Overall%20Performance.png" alt="Alt text" width="300"/> <img src="blog_figures/NYT%20full%20metrics.png" alt="Alt text" width="300"/>

The graph of performance metrics on the Yelp dataset is found in code block 2 of "Graphical_Representations.ipynb", while the graph for the NYT dataset is found in code block 3 of the same file. The numbers for these datasets are sourced from the classification reports in the other files. For the logistic regression model, the classification report for the Yelp data is located in code block 5 of "Logistic_Regression_TFIDF", and for the NYT data in code block 7 of the same file. For the LSTM, the Yelp data is found in code block 8 of "LSTM.ipynb", and the NYT data is located in code block 10 of "LSTM.ipynb."
# Thanks for reading!

