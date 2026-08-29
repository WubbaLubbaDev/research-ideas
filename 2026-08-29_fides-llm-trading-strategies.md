# FIDES: Concordance Protocol for LLM-Generated Trading Strategies
**Date:** 2026-08-29
**Keyword:** stock trading
**Source:** arXiv
**URL:** http://arxiv.org/abs/2608.23308v1

## Summary
FIDES is a protocol for checking concordance between what an LLM says about a trading strategy, what it implements in code, and what the backtest actually shows. When an LLM generates a trading strategy, it produces a rationale, an implementation, and a track record — FIDES checks whether these three artifacts agree. Published Aug 24, 2026.

## Idea angle
The three-artifact problem (rationale vs. code vs. backtest) is the silent failure mode of LLM-generated trading strategies. The LLM might say 'mean reversion' but code momentum, and the backtest might pass by luck. FIDES is the first systematic approach to catching these inconsistencies — essential infrastructure for any AI trading system.

## Details
Authors: Arther Tian, Alex Ding, Simon Wu | Published: 2026-08-24 | arXiv: 2608.23308

## Tags
#research-idea #stock-trading #arXiv

## Cross-links
- [[2026-08-29_dsa-evidence-aware-stock-research]] — Both address trustworthiness of LLM-generated financial analysis
- [[2026-08-29_auditable-llm-enterprise-finance]] — All three address trust/audit of LLM outputs in finance
- [[2026-08-15_strat-llm-trading]] — Both concern LLM-based stock trading strategy generation and evaluation
