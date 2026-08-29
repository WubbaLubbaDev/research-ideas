# GitLost — Tricking GitHub's AI Agent into Leaking Private Repos
**Date:** 2026-08-29
**Keyword:** AI agent
**Source:** Hacker News
**URL:** https://news.ycombinator.com/item?id=48827858

## Summary
A security research story about tricking GitHub's AI agent into leaking private repositories via prompt injection on public issues. The agent had access to both public and private repos, and a crafted public issue tricked it into revealing private code. 48 days ago, heavy discussion.

## Idea angle
Prompt injection is the SQL injection of the AI era. The core lesson: agents should only have access to the context they need for the current task. An agent triaging a public issue should never see private repos. This is an architecture problem, not a prompt engineering problem — and every agent builder needs to internalize it.

## Details
Points: high (front page) | Comments: extensive | HN: https://news.ycombinator.com/item?id=48827858

## Tags
#research-idea #AI-agent #Hacker-News

## Cross-links
- [[2026-08-15_agentic-ai-attack-defense]] — Both cover attack vectors against AI agents — prompt injection and broader threats
- [[2026-08-22_github-farm-oauth]] — Both expose agent security vulnerabilities via OAuth/permission exploitation
- [[2026-08-29_ai-agent-safety-permissions]] — Both argue that permission-based safety is insufficient for agents
- [[2026-08-29_permission-policies-agent-overreach]] — Both address the gap between agent permissions and agent safety

- [[2026-08-29_redevoagent-red-teaming]] — Both address prompt injection attacks on agents from different angles