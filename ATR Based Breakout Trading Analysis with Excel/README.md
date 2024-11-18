### **ATR-Based Breakout Trading Strategy**
This project involves the development, simulation, and optimization of an **ATR-Based Breakout Trading Strategy**, which leverages Average True Range (ATR) for dynamic stop-loss and take-profit levels. The strategy is designed to identify breakout opportunities and manage trades systematically.

---

### **Strategy Overview**
1. **Breakout Signals**:
   - A **Buy Signal** is triggered when the price touches or exceeds the "x" candles high.
   - A **Sell Signal** is triggered when the price touches or falls below the "y" candles low.
   
2. **Exit Conditions**:
   - **Stop Loss (SL)**: Triggered if the price moves against the trade by "a" times the ATR.
   - **Take Profit (TP)**: Triggered if the price moves favorably by "b" times the ATR.

3. **Trading Rules**:
   - Only one position is held at a time.
   - Fixed position size of 1 unit is used for all trades.
   - Trades are tracked and analyzed for performance metrics.

---

### **Optimization and Breakout Information**
- **Optimization**: The strategy parameters (`x`, `y`, `n`, `a`, `b`) were **optimized using a data table** to identify the most profitable combinations. The optimization provided insights into:
  - Total profit or loss for each parameter set.
  - Sensitivity of performance metrics to changes in `x`, `y`, and ATR multipliers.
  - Identification of parameter combinations that maximize profit while managing risk.

- **Breakout Information Provided**:
   - **Signal Summary**: Number of buy/sell signals generated and executed trades.
   - **Profitability Analysis**: Total profit, profit from winning trades, and losses from losing trades.
   - **Trade Metrics**: Average holding period, maximum profit/loss per trade, and average profit per trade.
   - **Cost Adjustments**: Net profit after accounting for slippage and brokerage fees.
   - **Performance Sensitivity**: Impact of `x` and `y` parameter variations on profitability.
