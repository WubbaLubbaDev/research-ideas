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
