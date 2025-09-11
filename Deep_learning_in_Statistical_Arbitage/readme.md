# Deep Learning Statistical Arbitrage

## Overview
Implementation of a statistical arbitrage framework on U.S. equities, combining residual portfolio construction with deep learning–based signal extraction.

## Methodology
- **Portfolio Construction**: Residual returns from Fama–French / PCA / IPCA factors  
- **Signal Extraction**: CNN + Transformer filters vs. OU and Fourier benchmarks  
- **Trading Allocation**: Neural network mapping signals to portfolio weights  

## Dataset
- Daily returns of ~550 largest U.S. equities (1998–2016)  
- Factor models: Fama–French, PCA, IPCA  

## Results (as reported in literature)
- Annualized Sharpe ratio: > 4  
- Annual mean return: ~20%  
- Outperformance vs. OU and Fourier filters, robust under transaction costs  

## Repo Structure
- `data/` : Data preprocessing scripts  
- `models/` : CNN, Transformer, and baseline signal models  
- `backtests/` : Trading strategy backtests and evaluation metrics  
- `notebooks/` : Exploratory analysis and visualization  

## Next Steps
- Extend to other markets (crypto / international equities)  
- Add transaction cost and slippage modeling  
- Hyperparameter tuning for Transformer depth and filter size  
