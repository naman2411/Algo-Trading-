# Intraday Trading Strategy Development

## Project Overview
In this project, we aim to develop an intraday trading strategy for selected stocks based on their price variations throughout the trading day. The strategy involves analyzing open, high, low, and close prices of stocks using different threshold limits.

## Methodology

### Threshold Limits
We are considering the following threshold percentages:
- \( k = 1\%, 2\%, 3.5\%, 0.5\%, 0.35\% \)

### Calculations
For each stock and each threshold \( k \):
1. Calculate the number of times the stock's high and open values exceed the threshold percentage within different weeks.
2. Multiply these occurrences by weights to derive values:
   - \( P035, P1, P2, P35, P05 \) corresponding to different values of \( k \).

### Worst Time Calculation
Determine the "worst time" for each stock, which is the point after which the stock does not cross the threshold value \( k \).

### Optimization
Utilize the collected data to optimize the entry and exit times for stocks, aiming to maximize returns.

## File Structure
- **data/**: Contains the raw data files.
- **scripts/**: Includes scripts for data processing and calculation.
- **results/**: Stores the output results and visualizations.

## Conclusion
By implementing these strategies and optimizations, we aim to enhance the profitability of intraday trading for the selected stocks.

