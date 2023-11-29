# ml-experiment-with-stock-price

Two experiments are included. One is experiment with stock data and another one is with image data.

The stock price data set we use here is a stock market index (composite stock price index of common stocks) in a country for the period between 2000 and 2022, consisting of four historical prices ('Open', 'High', 'Low', 'Close', which denote the opening, highest, lowest, and closing prices on the trading day, respectively) and trading volume. For the convenience, we have added some features to the data set. They are four technical indicators (RSI, SMA, BBP, ADX), 'Tomorrow', and 'Target'. 'Tomorrow' holds the closing price of next trading day, which we will use for price prediction, and 'Target' is a binary indicator (label), which takes 1 if 'Tomorrow' is higher than 'Close', 0 otherwise, which we will use for the prediction of movement direction.

We use a subset of the [Fashion MNIST Dataset](https://github.com/zalandoresearch/fashion-mnist) for experiment with image, which contains images of fashion products from ten categories (e.g. T-shirt and trousers). The ten categories are represented as integer numbers ($0,\ldots,9$) and they are referred to as classes. There are 1000 training instances and 200 test instances per class. Each instance is a 28-by-28 gray-scale image. Note that there exists some errors (e.g. incorrect labels) in the data set, but we use the data set as it is.

The datasets aren't included in this repository.

Related exploration and experiment will be conducted in python. Jupyter is recommended for reading.