
# Algorithmic Trading Strategy Whitepaper: QQQ ETF  
**Date**: 2025-04-10  

## Performance Summary  
- **Total Return**: 45.00%  
- **Annualized Sharpe Ratio**: 1.55  
- **Maximum Drawdown**: -11.17%  
- **Win Rate**: 55.56%  

## Risk Analysis  
### Monte Carlo Simulation  
- **5th Percentile (Worst Case)**: $1412.40  
- **95th Percentile (Best Case)**: $2488.51  

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
This strategy achieved a positive return of 45.00% with moderate risk (Sharpe: 1.55).  
