# Education and Media Sector Investment Fund - MSDS 451 Term Project

## Overview
Quantitative investment fund analysis focused on education and media sectors using dual-signal trading strategy with backtesting and Monte Carlo simulation.

## Investment Strategy
- **Philosophy**: Behavioral finance, adaptive markets framework
- **Signals**: Mean reversion (Z-scores) + Momentum (252-day returns)
- **Buy**: Z-score < -2 OR momentum > 20%
- **Sell**: Z-score > 2 OR momentum < -10%

## Portfolio (10 Securities)
| Ticker | Company | Weight |
|--------|---------|---------|
| AMZN | Amazon | 15% |
| TGT | Target | 13% |
| COST | Costco | 12% |
| BNED | Barnes & Noble Education | 8% |
| SCHL | Scholastic | 9% |
| PSO | Pearson | 8% |
| NWSA | News Corp | 10% |
| NYT | New York Times | 10% |
| RELX | RELX Group | 8% |
| TRI | Thomson Reuters | 7% |

## Performance Results (2015-2025)
- **Annual Return**: 1.42%
- **Sharpe Ratio**: -0.04
- **Maximum Drawdown**: -23.04%
- **Win Rate**: 48.2%
- **Monte Carlo Profit Probability**: 53.5%

<img width="1189" height="790" alt="image" src="https://github.com/user-attachments/assets/ff850e3e-5495-44ee-89bc-1e721a0f9d42" />

## AI use
Claude was used to debug my code. 
