<!-- markdownlint-disable-file -->

# Session Context Draft

> Draft for human review. This artifact is the required context for all later workflow agents in this session.

## Session Metadata

- Session name: 경영관리 종합분석 Agent
- Topic: 경영관리 종합분석 Agent
- Date: 2026-11-04
- Evidence location: ./copilot-tracking/research/workshop-input
- Evidence boundary: This repository-local workshop directory is the approved source for synthetic or public workshop inputs. Do not copy production-sensitive data, customer secrets, or confidential material into the repository.

## Objective

This session establishes the shared context for a partner workshop scenario focused on 경영관리 종합분석 Agent. All downstream agents should use this document as the authoritative source for topic, evidence location, scope, and output roots before drafting requirements, plans, or backlog items.

## Evidence Boundary

- Approved evidence root: ./copilot-tracking/research/workshop-input
- Allowed inputs: workshop materials, synthetic data, approved public documentation, and clear business context relevant to the session
- Forbidden inputs: production data, personal data, customer secrets, credentials, or confidential records not approved for this workshop
- Handling requirement: when real evidence is needed, keep it in a controlled external system and reference the managed location rather than copying it into the repository

## Production Output Roots

The following production output roots are the expected destinations for later workflow artifacts:

- Research: .copilot-tracking/research/
- BRD output: .copilot-tracking/brd-sessions/
- PRD output: .copilot-tracking/prd-sessions/
- Implementation plans: .copilot-tracking/plans/
- Detailed design notes: .copilot-tracking/details/
- Design and UX artifacts: .copilot-tracking/dt/
- GitHub backlog artifacts: .copilot-tracking/github-issues/

## Required Usage

All later agents in this session should:

1. Read this session context first.
2. Use the same topic and evidence boundary unless a human updates this file.
3. Keep the session grounded in evidence rather than assumptions.
4. Save all workflow outputs under the approved artifact roots above.
5. Mark any newly created outputs as draft until reviewed by a responsible human.

## Notes

- This document is intentionally minimal and intentionally acts as a session guardrail.
- Do not begin research, BRD/PRD drafting, backlog creation, or sensitive evidence copying before this context is reviewed and accepted.   
- 수정
