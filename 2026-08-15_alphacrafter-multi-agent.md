# AlphaCrafter: Full-Stack Multi-Agent Framework for Cross-Sectional Quant Trading
**Date:** 2026-08-15
**Keyword:** stock trading
**Source:** arXiv
**URL:** https://arxiv.org/html/2605.05580v1

## Summary
A full-stack multi-agent framework that closes the gap between factor discovery and execution through three specialized agents: a Miner that expands the factor pool via LLM-guided search, a Screener that constructs regime-conditioned factor ensembles, and a Trader that translates ensembles into risk-constrained strategies.

## Idea angle
The three-agent pipeline (Mine → Screen → Trade) is a clean architecture for a production quant system. Could adapt this to emerging markets (IDX) where factor efficacy is less studied — the Miner agent could discover Indonesia-specific alpha factors that Western quant models overlook.

## Details
Authors: Yishuo Yuan et al. (Nanjing University) | Submitted: May 2026 | Tested on CSI 300 and S&P 500 with lowest cross-trial variance among baselines.

## Tags
#research-idea #stock-trading #arxiv

## Cross-links
- [[2026-08-16_TradingAgents]] — both use multi-agent frameworks for financial trading
- [[2026-08-16_AlphaSchema-alpha-mining]] — both involve LLM-guided alpha factor mining for trading
- [[2026-08-16_game-theoretic-stock-forecasting]] — both model cross-sectional stock interactions
