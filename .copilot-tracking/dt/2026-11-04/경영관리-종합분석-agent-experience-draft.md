<!-- markdownlint-disable-file -->

# Experience Draft: 경영관리 종합분석 Agent

> Draft for human review. This artifact synthesizes a simple user journey, experience overview, and pain points for the management-analysis scenario using the approved research and session artifacts. It is a working design scaffold, not validated user research.

## Session metadata

- Session name: 경영관리 종합분석 Agent
- Topic: 경영관리 종합분석 Agent
- Date: 2026-11-04
- Session context: .copilot-tracking/research/2026-11-04/경영관리-종합분석-agent-session-context.md
- Research artifact: .copilot-tracking/research/2026-11-04/경영관리-종합분석-agent-primary-research.md
- UX artifact source: .copilot-tracking/ux-artifacts/management-analysis-agent/business-management-analysis/frame-needs.md
- Approved evidence root: .copilot-tracking/research/workshop-input
- Experience diagram: [경영관리 종합분석 Agent 사용자 여정](https://www.figma.com/board/h9YzXCu1CSsmQZVSuFf1Ab?utm_source=other&utm_content=edit_in_figjam&oai_id=&request_id=46144653-e73b-44fd-b3c1-5e17659e6f33)

## 1. Experience overview

The intended experience is a business-facing management analysis workflow that helps users quickly understand performance signals, identify exceptions, and decide what deserves review or follow-up. The experience should feel structured and trustworthy rather than like a generic chatbot answer generator.

### Product intent

- Support business decision-making with clear, evidence-based summaries
- Reduce the time spent collecting and synthesizing management information
- Highlight exceptions, gaps, or unusual volatility that matter to decision-makers
- Preserve source traceability and keep assumptions clearly separated from facts
- Keep a human reviewer in the loop before the output is treated as trusted guidance

### Likely user profile

- Business managers who need a compact operational overview
- Department leads responsible for performance review and follow-up
- Analysts who consolidate and interpret multiple reporting inputs
- Governance or compliance reviewers who need explainability and traceability

### Core experience promise

Users should be able to ask a business question, review the approved evidence, and receive a concise summary that explains:

1. What the issue or topic is
2. What evidence is relevant
3. What is changing or deviating
4. What assumptions remain open
5. What a human should review before acting

## 2. Simple user journey

### Journey summary

1. Start with a management question
   - Example: "What is changing in performance this month?"
   - Example: "Which department or initiative is most at risk of variance?"
   - Example: "What should we review before the next management meeting?"

2. Define the decision frame and evidence boundary
   - The system checks the approved evidence source and proposes the relevant dataset or policy context.
   - The user confirms whether the output should be evidence-based and how much explanation is needed.

3. Review relevant evidence
   - The system gathers approved, synthetic or public workshop inputs.
   - It highlights KPI changes, exceptions, trends, or source references.
   - It identifies where the evidence is weak, incomplete, or conflicting.

4. See a structured summary
   - The system presents a concise overview of the issue, its impact, and the likely decision points.
   - It separates facts, assumptions, and proposed follow-up actions.

5. Validate before action
   - A human reviewer checks the evidence, the assumptions, and the recommended next steps.
   - If the output is uncertain, the system surfaces the risk and asks for more context or review.

6. Move to a decision or follow-up workflow
   - The user decides whether to escalate, investigate, or prepare a management brief.
   - The work product remains reviewable, explainable, and traceable.

## 3. Experience principles

- Evidence-first: do not hide uncertainty or invent confidence.
- Explainability: show why the summary matters and what source supports it.
- Human review: keep the human accountable for operational decisions.
- Clarity: use concise, structured summaries that a manager can scan quickly.
- Safety: avoid sensitive, confidential, or unsupported data in repo-local workshop artifacts.

## 4. Key pain points

### 1. Fragmented evidence and manual synthesis

Users likely spend too much time collecting information from multiple sources, comparing reports, and manually reconstructing the story behind a management issue. This creates delay before meaningful decisions can be made.

### 2. Unclear source trust and traceability

Without visible source attribution, it is hard for a manager to know whether the summary is grounded in approved evidence or weak assumptions. This reduces trust and increases the risk of acting on the wrong interpretation.

### 3. Strong need to separate fact from assumption

In management analysis, a confident answer can still be wrong if the model mixes observations, inferred causes, and policy assumptions. Users need a clear distinction between:

- confirmed facts
- inferred patterns
- assumptions
- recommended actions

### 4. Risk of over-automation

The scenario explicitly warns against treating the AI as an autonomous decision-maker. Users may be worried that a system could act too early or overstate certainty without a human review step.

### 5. Confidentiality and governance concerns

Because the repository requires a strong evidence boundary, the experience must avoid unsafe handling of production-sensitive or customer-confidential data. Any system that appears to ignore those boundaries will reduce trust quickly.

### 6. Slow review cycles when output is not easy to scan

Executives and managers need short, well-structured views of issues and trade-offs. If the experience is too verbose or opaque, users will bypass it and fall back to manual review or dashboards.

### 7. Missing domain clarity in the current workshop inputs

The reviewed materials do not yet confirm the exact management domain or decision path. This means the experience must remain flexible and avoid hard-coding a single business workflow before the actual user and domain are validated.

## 5. Experience summary

The ideal experience for this scenario is a trusted management-analysis assistant that acts as a structured briefing and review tool rather than a black-box decision engine. It should help users move from a broad business question to a clear, explainable summary while showing what is known, what is uncertain, and what requires human judgment.

This matches the repo’s evidence-first design posture: the system supports business understanding, but it does not replace authority, governance, or human accountability.

## 6. Validation note

This draft is intentionally scoped to the repository evidence and workshop-safe assumptions. It should be validated with real users and decision owners before being treated as a confirmed product experience or design requirement.

---

*Draft status: Human review required before this experience summary is used as a design baseline.*
