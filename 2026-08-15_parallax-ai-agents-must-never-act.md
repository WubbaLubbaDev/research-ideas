# Parallax: Why AI Agents That Think Must Never Act
**Date:** 2026-08-15
**Keyword:** AI agent
**Source:** arXiv
**URL:** https://arxiv.org/abs/2604.12986

## Summary
A paper demonstrating that 40% of AI agent frameworks contain exploitable prompt injection flaws in tool-execution logic. Proposes Parallax, an architecture where thinking agents are architecturally separated from acting agents, blocking 98.9% of attacks with zero false positives.

## Idea angle
The separation of thinking and acting is the most promising agent safety architecture. Could implement a Parallax-style system for financial agents where the analysis agent generates trade recommendations but a separate, locked-down execution agent with no LLM access handles the actual broker API calls.

## Details
Authors: Not specified | 280 adversarial test cases in 9 attack categories | 98.9% attack blocking rate, 100% in max-security mode.

## Tags
#research-idea #AI-agent #arxiv

## Cross-links
- [[2026-08-15_agent-safe-pipeline]] — both propose separation of agent thinking and acting
- [[2026-08-15_agentic-ai-attack-defense]] — both identify prompt injection as a primary agent attack vector
- [[2026-08-22_ai-agent-hit-piece-2]] — Both argue for guardrails on autonomous agent actions
- [[2026-08-22_ai-agent-bankrupted-2]] — Both demonstrate the need for cost/safety guardrails on autonomous agents

- [[2026-08-29_nofx-ai-trading-kill-switch]] — Both address the danger of autonomous agents acting without safety constraints
- [[2026-08-29_disposable-sandboxes-agents]] — Both address the danger of giving agents unrestricted system access
- [[2026-08-29_ai-agent-safety-permissions]] — Both argue for consequence-aware safety, not just access control