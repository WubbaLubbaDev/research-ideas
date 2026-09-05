# OpenAgentFlow — Safety Boundaries for AI Agent Fleets
**Date:** 2026-09-05
**Keyword:** AI agent
**Source:** arXiv
**URL:** https://arxiv.org/abs/2609.03218

## Summary
A framework for enabling system-wide safety boundaries for heterogeneous AI agent fleets — managing agents with different capabilities, permissions, and risk profiles within a unified governance layer.

## Idea angle
Fleet-level safety is the multi-agent version of individual agent guardrails. The heterogeneous angle is key — different agents need different constraints (a research agent can read freely but not write; a deployment agent can write but only to staging). Building this as a policy-as-code layer (like OPA for agents) would be immediately useful for any team running multiple agents in production.

## Details
Authors: Dongsheng Chen, Xiangyu Zhao, Xin Yao, Xuetao Wei | Listed in arXiv cs.AI recent | Focus: system-wide safety, heterogeneous agent fleets

## Tags
#research-idea #AI-agent #arxiv

## Cross-links
- [[2026-08-15_agentic-ai-attack-defense]] — Both address AI agent security — OpenAgentFlow for fleet safety, this surveys the full attack/defense landscape
- [[2026-08-29_permission-policies-agent-overreach]] — Both implement agent safety via policy boundaries — fleet-level vs user-authored permission policies
- [[2026-08-29_guard-cried-wolf]] — Both deal with agent guardrails — OpenAgentFlow defines boundaries, this studies over-safety false positives
- [[2026-09-05_parallax-agents-must-never-act]] — Both address agent safety — Parallax at individual level, OpenAgentFlow at fleet level
