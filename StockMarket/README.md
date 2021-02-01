The closing price prediction notebook predicts the closing price of the SNP500 stock, or any other stock depending on input. The program implements a long short term memory network (LSTM), using training data from Yahoo detailing various characteristics of the specified stock over the past N years.

The sentiment analysis notebook is a bit of my experimentation with Natural Language Processing (NLP). In it, I created an architecture that was trained using daily news headlines as well as the corresponding prices of those days. vaderSentiment allowed me to generate the subjectivity (bias) as well as polarity (magnitude of opinionation) and I added those features to the model as well.

In the second version of the stock price predictor, I trained a model on data concerning the Tesla stock using three variations of Support Vector Regression. The model isn't very robust but it was good practice.
