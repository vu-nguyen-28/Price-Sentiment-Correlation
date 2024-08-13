# Price-Sentiment-Correlation

Overview
This project is designed to understand the correlation between stock price and news sentiment in real-time for S&P 500 companies and determine the investment strategy based on the found correlation. The program fetches recent news for the companies, performs sentiment analysis on the articles, monitor the price from the associated tickers for 5 minutes, and then plots the sentiment score against the stock price change in real-time. In the output as shown in the Jupyter Notebook, there are a total of 4 quadrants. We are mainly focusing on the top-right and the bottom-left quadrants, where the top-right quadrant tells us that as the sentiment score is positive, the stock price increases. It means that this stock is worth investing in, due to its reaction to good news. The bottom-left quadrant is good for shorting the stock, since the price change also correlates with the sentiment score. As the sentiment score is negative, the price also decreases. The other two quadrants are not worthing investing in, because they do not show any correlation between the sentiment score and the stock price. 

Features
- Fetches news articles for S&P 500 companies using Yahoo Finance and Finviz.
- Performs sentiment analysis using VADER (Valence Aware Dictionary and sEntiment Reasoner).
- Monitors stock prices over a 5-minute interval.
- Plots sentiment scores vs. price changes in real-time.
- Continuously updates the plot with new data every 5 minutes.

How to run the code:
This project operates solely on a single Google Colab notebook, so to run this, you can simply download the Jupyter Notebook in this repository and run it on your computer. Keep in mind that this project uses Finviz Elite to fetch news and monitor stock data, therefore you will also need an active Finviz Elite membership in order to successfully run this.

Future Improvements
- Incorporate more news sources for a diverse range of sentiment data.
- Implement a more sophisticated sentiment analysis method.
- Allow for custom stock ticker input for non-S&P 500 companies.
- Add a historical analysis feature to visualize sentiment and price changes over longer periods.
  
Contact
For any questions or issues, please reach out at vqn5079@psu.edu.
