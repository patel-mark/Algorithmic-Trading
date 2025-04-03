
# Algorithmic Trading Strategy Whitepaper: QQQ ETF  
**Date**: 2025-04-04  

## Performance Summary  
- **Total Return**: 29.62%  
- **Annualized Sharpe Ratio**: 0.50  
- **Maximum Drawdown**: -34.55%  
- **Win Rate**: 55.56%  

## Risk Analysis  
### Monte Carlo Simulation  
- **5th Percentile (Worst Case)**: $985.50  
- **95th Percentile (Best Case)**: $2065.95  

### Key Drivers  
The model prioritized these indicators (top 3):  
1. **Open**  
2. **High**  
3. **Low**  

## Limitations & Recommendations  
1. **Post-2023 Underperformance**: Accuracy dropped due to Fed rate hikes impacting tech/growth stocks.  
2. **Improvement Strategies**:  
   - Add earnings calendar data for tech giants (AAPL, MSFT).  
   - Incorporate short-term Treasury yields (2Y) for rate sensitivity.  
3. **Risk Controls**: Implement trailing stop-loss (5%) instead of fixed.  

## Conclusion  
This strategy achieved a positive return of 29.62% with moderate risk (Sharpe: 0.50).  
