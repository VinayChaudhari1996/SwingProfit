# SwingProfit
Timeseries buy and sell strategy for maximum profits 
> Indian stocks example : Note Only for educational purposes and self-use


![image](https://github.com/VinayChaudhari1996/SwingProfit/assets/42869040/612e8b80-37cf-49cc-83e5-da4267188304)

![image](https://github.com/VinayChaudhari1996/SwingProfit/assets/42869040/1e226514-b405-4148-bd44-96f9a7073d56)


____

> For Nerds


![image](https://github.com/VinayChaudhari1996/SwingProfit/assets/42869040/dab6e01a-3111-4b6b-a238-47765cd07bd7)

### Example:

Let's consider a simplified example:

- Initial Capital: $50,000
- Buy Signal Condition: RSI < 50 and Close < Lower Bollinger Band
- Sell Signal Condition: RSI > 50 and Close > Upper Bollinger Band

```python
# Sample Data (Closing Prices)
data = [100, 110, 95, 120, 130, 90, 80, 110, 115, 125]

# Example Buy and Sell Signals
Buy_Signal = [0, 0, 1, 0, 0, 1, 0, 0, 0, 0]
Sell_Signal = [0, 0, 0, 0, 0, 0, 0, 0, 1, 0]

# Example Trades
Trades = [('Buy', '2023-01-01', 95, 10), ('Sell', '2023-01-05', 130, 10)]
```

This example assumes a simple list of closing prices and manually generated buy and sell signals for illustration purposes. In a real-world scenario, these signals would be generated by the strategy based on the calculated RSI and Bollinger Bands.

The Gradio interface allows you to input a stock symbol, period, and interval to analyze the strategy's performance for a specific stock. The output includes metrics such as profitability, buy and sell counts, net profit, ROI, and a visual representation of the strategy's execution.
