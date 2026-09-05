# StockBench — LLM Agents Trading Benchmark
**Date:** 2026-09-05
**Keyword:** stock trading
**Source:** arXiv
**URL:** https://arxiv.org/abs/2510.02209

## Summary
A contamination-free benchmark evaluating LLM agents in realistic multi-month stock trading environments. Agents receive daily market signals (prices, fundamentals, news) and make sequential buy/sell/hold decisions. Most models struggle to beat buy-and-hold; some show potential for better risk management.

## Idea angle
This benchmark exposes the gap between LLM reasoning and profitable trading — most can't beat buy-and-hold. The opportunity is in specialized fine-tuning: taking a base LLM and training it on trading-specific reasoning chains (not just financial QA) could close the gap. Building on StockBench's open-source framework to test agentic trading strategies with cost constraints would be novel.

## Details
Authors: Yanxu Chen, Zijun Yao, et al. | Submitted: Oct 2025, revised Mar 2026 | arXiv:2510.02209 | Open-source: github.com/ChenYXxxx/stockbench | Finding: most LLMs fail to beat buy-and-hold baseline

## Tags
#research-idea #stock-trading #arxiv

## Cross-links
- [[2026-08-16_llm-trading-benchmark]] — Both benchmark LLM trading agents on stock markets — same research question, different approaches
- [[2026-08-29_llm-trading-memory-benchmark]] — Both evaluate LLM trading agents — StockBench focuses on profitability, the other on memory effects
- [[2026-08-29_finskillbench]] — Both are benchmarks for evaluating AI agents in investment/trading contexts
- [[2026-09-05_agentic-trading-survey]] — StockBench is one of the benchmark studies surveyed in the Agentic Trading survey
