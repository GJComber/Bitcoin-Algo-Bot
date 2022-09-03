


!['Bitcoin image'](./Resources/big-image-bitcoin-coin-svg.png)


# Bitcoin-Algo-Bot

### This is group project created to demonstrate how machine learning can be implemented with common trading strategies and compare the outcomes of modelling them on Bitcoin.

## Resources and Libraries

Alpaca API - Five years of historic data was extracted  - This was then filtered  and cleaned to suit our models and saved to a CSV file.
Libraries include- Pandas.Numpy.Holoviews.Plotly.Seaborn.Sklearn.Finta
We also incorporated Facebook Prophet.

## Models and reference.

### Baseline
As a baseline comparison to test our models against we chose a fixed investment of $100,000 Bitcoin purchased at the start of of our dataset which is August 2017.
At that time the price was approx. $4000.00  and at the end of the dataset August 2022 it was approx $21,500, better than 5x its original value.

### Strategy 1
The first of our models used an Exponential Moving Average with Support Vector Machines to trade with. The signals to buy and sell are based on simple moving average crossover and the entire portfolio was traded in each transaction.
The final windows chosen for this EMA were 7 days in short and 80 days long

### Strategy 2
The second of our models used Bolinger Bands and Logistic Regression to trade with. The signals to trade were based on Triple Exponential Moving Average and a standard deviations of 1.2. The entire portfolio was traded in each transaction here also.

Pros and cons
Summary of findings

to be continued