# SML312FinalProject

## Overview
Predicting the price of financial assets is a challenging task that is of great interest to investors, traders, and researchers for reasons such as risk management, portfolio optimization, and profit maximization. Market participants are constantly seeking new ways to predict the price of financial assets, in which randomness and uncertainty play a significant role especially when it comes to the short-term (intra-day) price or price movement. In this effort, machine learning methods have become increasingly popular in this regard. At the same time, it is well-known that the price of financial assets is influenced by (or at least hypothesized to being influenced by) a variety of factors, including macroeconomic data, technical indicators, and market sentiment.

In this project, I am interested in predicting the price of index-tracking ETFs (primarily the Invesco QQQ Trust that tracks the NASDAQ index) using macroeconomic data, technical indicators, volatility indices etc. of previous 30-trading-day period (for simplicity, the term "trading-day" will be referred to as "day"). The main research questions are as follows:
\begin{enumerate}
    \item What factor(s) play the most prominent role in accurately predicting the ETF price or price movement for the next day?
    \item What is the model/method most suited for this purpose?
    \item Can we develop a (intra-day) trading strategy based on the optimal model/method and outperform the market?
\end{enumerate}
To answer these questions, two more questions will also be asked:
\begin{enumerate}
    \item What is the most suitable output variable for the model?
    \item What is the most suitable metric to evaluate the model?
\end{enumerate}
The main types of analysis would be feature engineering and selection, model evaluation using cross validation, and backtesting.
