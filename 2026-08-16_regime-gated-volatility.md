# Regime-Gated Residual Mixture-of-Experts for Cross-Sectional Volatility Forecasting
**Date:** 2026-08-16
**Keyword:** finance
**Source:** arXiv
**URL:** http://arxiv.org/abs/2608.12251v1

## Summary
This paper studies how to incorporate regime information into neural network-based volatility forecasting without destabilizing training. It uses a mixture-of-experts architecture with regime-gated routing to forecast five-day realized volatility for 1,027 US stocks.

## Idea angle
Apply regime-gated MoE to Indonesian market volatility — IDX has distinct regimes (commodity cycles, political events, rupiah swings) that US-trained models miss. The gap: emerging market volatility is more regime-dependent than developed markets, making regime-aware models particularly valuable for IDX options pricing and risk management.

## Details
- Authors: Junyi Ye, Gargi Vijay Borde
- Architecture: Residual mixture-of-experts with regime gating
- Forecast horizon: 5-day realized volatility, 1,027 stocks

## Tags
#research-idea #finance #arxiv

## Cross-links
- [[2026-08-16_financial-network-balance]] — both study cross-sectional dynamics in financial markets
- [[2026-08-16_qlib]] — both involve ML for financial market modeling
- [[2026-08-16_calibration-bets-quantization]] — both address production deployment of financial ML models
- [[2026-08-16_Doji-options-trading]] — both relate to options pricing and volatility forecasting
- [[2026-08-15_strat-llm-trading]] — both address regime-dependent trading strategy alignment
- [[2026-08-15_generating-alpha-hybrid-ai]] — both incorporate regime detection into trading strategies
- [[2026-08-22_m3-market-microstructure]] — Both model market microstructure dynamics for predictive trading
- [[2026-09-05_spx-vix-calibration]] — Both address volatility modeling — this paper calibrates SPX-VIX smiles, the other gates volatility by regime
