# Memory-Controlled Benchmark for LLM Trading Agents on Stock Markets
**Date:** 2026-08-16
**Keyword:** stock-trading
**Source:** arXiv
**URL:** http://arxiv.org/abs/2605.28359v1

## Summary
This paper benchmarks LLM trading agents on stock markets, revealing that end-to-end trading evaluation is vulnerable to two failures: long backtests overlap training data, and random market regimes can mask agent quality. It introduces a memory-controlled benchmark that separates knowing (market knowledge) from doing (trading decisions).

## Idea angle
Use this benchmark methodology to properly evaluate LLM trading agents on IDX data. The gap: most LLM trading evaluations are flawed by data leakage or regime bias. Applying this rigorous benchmark to Indonesian stocks would produce the first credible evaluation of whether LLMs can actually trade profitably in emerging markets.

## Details
- Key concepts: knowing vs. doing separation, memory control, regime-aware evaluation
- Addresses: evaluation failures in LLM trading research
- Contribution: rigorous benchmarking framework

## Tags
#research-idea #stock-trading #arxiv

## Cross-links
- [[2026-08-16_llm-small-cap-trading]] — both evaluate LLM-based trading on stock markets
- [[2026-08-16_llm-stock-investing-human-factor]] — both evaluate LLM stock prediction quality
- [[2026-08-16_AlphaSchema-alpha-mining]] — both involve LLM-based trading systems
- [[2026-08-15_llm-agent-trader]] — both involve LLM-based trading agent evaluation and backtesting
- [[2026-08-15_strat-llm-trading]] — both evaluate LLM-based trading agents across market conditions
- [[2026-08-15_ai-agent-reliability-science]] — both address reliability and evaluation of LLM agents in high-stakes tasks
- [[2026-08-22_llm-calibration-degeneracy]] — Both evaluate the reliability and pitfalls of LLM-based trading predictions
- [[2026-08-22_finskillbench]] — Both benchmark LLM/AI agent capabilities for trading and investment

- [[2026-08-29_reading-not-using-ai-finance]] — Both evaluate LLM capabilities in financial decision-making beyond simple comprehension
- [[2026-08-29_llm-trading-memory-benchmark]] — Both benchmark LLM agents in trading contexts