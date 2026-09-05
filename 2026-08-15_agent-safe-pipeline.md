# Agent Safe Pipeline — Intent Capture, Policy Verdict, and Safe Execution
**Date:** 2026-08-15
**Keyword:** AI agent
**Source:** GitHub trending
**URL:** https://github.com/decionis/agent-safe-pipeline

## Summary
A reference architecture for AI agents that propose actions but cannot authorize them — featuring immutable intent capture, an independent Decionis policy verdict (ALLOW/ESCALATE/BLOCK), verified human approval, and a SafeExecutor that consumes a single-use intent-bound grant.

## Idea angle
This is the gold standard for agent safety — separating 'thinking' from 'doing' with a cryptographic guarantee. Could implement this pattern for financial agents where the policy engine enforces risk limits, position size constraints, and regulatory compliance before any trade is executed.

## Details
Stars: 376 | Language: TypeScript | Architecture: Intent → Policy Verdict → Human Approval → Single-use SafeExecutor grant.

## Tags
#research-idea #AI-agent #github-trending

## Cross-links
- [[2026-08-15_parallax-ai-agents-must-never-act]] — both propose separation of agent thinking and acting
- [[2026-08-16_ai-agent-bankrupted-operator]] — both address the dangers of uncontrolled agent execution
- [[2026-08-15_ai-agent-deleted-database]] — both are cautionary tales driving the need for agent safety pipelines
- [[2026-08-22_longhorizon-harness]] — Both address agent safety and control during task execution

- [[2026-08-29_governed-pass-agent-certification]] — Both address agent safety governance and certification
- [[2026-08-29_permission-policies-agent-overreach]] — Both implement policy/permission systems for agent safety
- [[2026-09-05_auditmind-regulatory-agent]] — Both implement agent safety via structured compliance pipelines
- [[2026-09-05_parallax-agents-must-never-act]] — Both propose think-act separation for agent safety — propose but don't authorize