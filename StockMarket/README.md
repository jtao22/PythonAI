The closing price prediction notebook predicts the closing price of the SNP500 stock, or any other stock depending on input. The program implements a long short term memory network (LSTM), using training data from Yahoo detailing various characteristics of the specified stock over the past N years.

The sentiment analysis notebook is a bit of my experimentation with Natural Language Processing (NLP). In it, I created an architecture that was trained using daily news headlines as well as the corresponding prices of those days. vaderSentiment allowed me to generate the subjectivity (bias) as well as polarity (magnitude of opinionation) and I added those features to the model as well.

In the second version of the stock price predictor, I trained a model on data concerning the Tesla stock using three variations of Support Vector Regression. The model isn't very robust but it was good practice.

The third version of the close price predictor combines the SVR models as well as the pyplot graphing to visualize how well the model predicts prices. 

The stock movement classifier goes a little bit more into depth, but is a classification model as opposed to a regression model. By creating functions to calculate Simple Moving Average, Exponential Moving Average, Moving Average Convergence Divergence, Relative Strength Index, I attempt to provide the architecture with features that will help determine if the stock prices will rise or fall each day. THe architecture ended up being quite inaccurate, especially for a classification model but nonetheless it was a fun project.
