# Build a screener for stocks

The strategy workflow is as follows:-
    • Convert 1 minute timeframe data 15 minutes
    • If low of candle is less than previous low we enter short position, with 2 exit criteria’s
        ◦ Exit at end of day
        ◦ Exit if the high of previous candle is broken

Computed the profit/loss(entry price – exit price)


1. Run the Part1.ipynb 
2. Run the Part2.ipynb

After that you will get Profit-Loss-Per-Day.xlsx file with Date and Values.
(Positive means Profit and Negative means Loss)


