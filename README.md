**Dataset Information**: I have analyzed historical trade data from various Binance accounts over 90 days, containing: <br>
Port_IDs: Unique identifiers for accounts. <br>
Trade_History: Historical trades With <br>
details like timestamp, asset, side (BUY/SELL), price, and more. <br>


**Objective**:<br> Analyzed the dataset to calculate financial metrics for each account, ranked them, and provided a top 20 list. <br>
**Metrics Calculated**: <br>
ROI (Return on Investment) <br>
PnL (Profit and Loss) <br>
Sharpe Ratio <br>
MDD (Maximum Drawdown) <br>
Win Rate <br>
Win Positions <br>
Total Positions <br>

**Data Exploration and Cleaning:** <br>
Load and inspect the dataset, handle missing values.<br>
**Feature Engineering:** <br>
Determined feature importance and created a scoring system with weighted scores. <br>
**Ranking Algorithm:** <br>
Developed an algorithm to rank accounts based on calculated metrics. <br>
