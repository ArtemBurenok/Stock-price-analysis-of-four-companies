# Stock price analysis of four companies
This paper analyzes the behavior of stocks in the future with Monte Carlo method. An optimal portfolio is also compiled based on the classical Markowitz theory.

## Technology

Libraries are used for visualization: 
+ seaborn
+ matplotlib 

Libraries are used for analysis: 
+ numpy
+ pandas

## Contains

This repository contains a .pynb file with stock price analysis.

The first step is to download the data. The yfinance library was used for this purpose. After that, price charts and moving average charts with intervals of 10, 20 and 30 were plotted.

![image](https://github.com/user-attachments/assets/ba9a9946-20cc-487d-a496-7d4647a41e51)


Histograms and density plots for daily profits for each stock were also plotted.

![image](https://github.com/user-attachments/assets/8245bfe8-58f1-41f0-b3fa-c493b9001340)


The next step is to identify the relationship between the share prices. For this purpose the correlation coefficient was calculated, and graphs of dependencies were plotted.

![image](https://github.com/user-attachments/assets/ac33397f-e49b-47ba-86d5-9a1e8f3d6d85)

