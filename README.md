**How to trade with Statistical Arbitrage Strategy?**

Statistical arbitrage strategy involves using statistical analysis to identify mispricings in financial markets and taking advantage of these discrepancies to make a profit. In short, the goal of statistical arbitrage is to generate profits by exploiting inefficiencies in the market, rather than by predicting future market movements.

I then choose two US stocks (randomly) - Meta and Azeta and test this strategy on them, to see how it well it identifies and tracks the mispricing between this two stocks. These are the steps I have taken to execute the strategy:

Step 1. Import libraries (numpy, pandas, matplotlib, sklearn) and data (historical prices of Meta and Azeta)

Step 2. Train the data using simple machine learning, and use linear regression to fit the trained data to the model

Step 3. Define the z-score and benchmark for long/short's position, and set a stop loss for it

Step 4. Execute the strategy and calculate the return (Chart 1)



**Chart 1**

![image](https://user-images.githubusercontent.com/121606452/211153192-0324810a-12f6-4cbc-802b-65a302b7aee0.png)
