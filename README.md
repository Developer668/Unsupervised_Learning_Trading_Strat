In this project, I have made use of yFinance in order to get and download the current price data for the
S&P 500, then calculate a wide variety of different indicators for the data ranging from the RSI to the 
Bollinger Bands and even the Garman-Klass Volitility. Which is calculated and looked at on a monthly basis
for the top 150 most liquid stocks of each month. Calculated the monthly returns for different time-horizons
and downloaded the Fema-French Factors and calculated the rolling factor betas for each stock.
For each month I fit a K-means clustering model to group stocks with similar features together. For each
month selected stocks based on the cluster and form a portfolio based on Efficient Frontier max sharpe 
ratio portfolio optimization. And finally visualized the returns comparing it to the S&P 500 index returns.

Warning!! The data used is currently the most recent so there is survivorship bias. This is not financial
advice don't not use this model to make money of off it or to invest it is for education purposes only!

This model was created during a course and helped me explore and learn the principles behind algorithmic 
trading and machine learning.

Thank you! I hope you find this useful!
