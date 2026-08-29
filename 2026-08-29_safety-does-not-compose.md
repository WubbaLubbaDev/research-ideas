# Safety Does Not Compose: Non-Decaying Loop State for Autonomous LLM Agents
**Date:** 2026-08-29
**Keyword:** AI agent
**Source:** arXiv
**URL:** http://arxiv.org/abs/2608.27141v1

## Summary
A paper showing that safety properties don't compose in autonomous LLM agent loops — each component may be individually safe, but the composed system can develop unsafe emergent behaviors. The 'non-decaying loop state' means errors accumulate over long-running agent sessions. Published Aug 27, 2026.

## Idea angle
This is the most important safety finding for production agents: you can't guarantee system safety by testing components individually. Long-running trading agents are exactly the scenario — a safe analyst agent + a safe execution agent can compose into an unsafe trading system. The implication: integration testing of agent pipelines is non-negotiable.

## Details
Authors: Chenhao Wu, Haoxuan Jia, Yang Liu | Published: 2026-08-27 | arXiv: 2608.27141

## Tags
#research-idea #AI-agent #arXiv

## Cross-links
- [[2026-08-29_intent-as-tool-agent-misalignment]] — Both address emergent safety failures in agent systems
- [[2026-08-29_nofx-ai-trading-kill-switch]] — The kill switch pattern directly addresses the safety composition problem this paper identifies
- [[2026-08-15_ai-agent-reliability-science]] — Both address agent reliability and safety as a science
- [[2026-08-29_disposable-sandboxes-agents]] — Sandboxing is one response to the safety composition problem
