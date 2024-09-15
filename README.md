# Stock price analysis of four companies
This paper analyzes the behavior of stocks in the future with Monte Carlo method. An optimal portfolio is also compiled based on the classical Markowitz theory.

## Technology

Libraries are used for visualisation 
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

The next part of the analysis is the construction of the optimal portfolio. This approach is based on random generation of proportions of stocks in the portfolio and subsequent selection of the portfolio with the lowest risk and highest return. 

The expected return of the portfolio is the total expected return of the securities included in it, weighted taking into account their share in the portfolio:

$$ E (R_p) = \\sum_{i=1}^n w_i E(R_i) $$

The basic formula for calculating risk is based on the relationship between the shares in the portfolio and the covariance associated with each of the securities in the portfolio:

$$ p_{\pi} = \\sqrt{\\sum_{i=1}^n \\sum_{j=1}^n X_i X_j \sigma_{ij}} $$

Graph of generated portfolios, the red dot marks the most optimal portfolio.

![image](https://github.com/user-attachments/assets/cdd63dbb-0ccb-447b-9eea-c5e2d6449938)

Further stock price behavior is then generated using the Monte Carlo method.

![image](https://github.com/user-attachments/assets/758ed469-823d-44b9-84c0-12596b902f67)



