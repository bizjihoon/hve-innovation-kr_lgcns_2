<!-- markdownlint-disable-file -->

# UX Artifact: 경영관리 종합분석 Agent 사용자 니즈

## Artifact Context

* Project: management-analysis-agent
* Subject: 경영관리 종합분석 Agent 사용자 니즈
* Mode: frame-needs
* Status: partial
* Sources:
  * `.copilot-tracking/research/2026-11-04/경영관리-종합분석-agent-session-context.md` (session context; 2026-11-04)
  * `.copilot-tracking/research/2026-11-04/경영관리-종합분석-agent-primary-research.md` (SME research synthesis; 2026-11-04)
  * `.copilot-tracking/research/2026-11-04/경영관리 test-session-context.md` (session context; 2026-11-04)
  * `.copilot-tracking/research/workshop-input/generation_manifest.csv` (synthetic-data manifest; 2026-11-04)

## Observed

* The session context sets `.copilot-tracking/research/workshop-input/` as the approved workshop evidence root and prohibits copying production-sensitive, personal, customer-confidential, or credential data into the repository. Source: session context, 2026-11-04.
* The workshop manifest marks the listed datasets as fully synthetic. It describes organizational, management-performance, budget-versus-actual, project, metric-definition, data-quality, and access-example data. Source: `generation_manifest.csv`, 2026-11-04.
* The manifest says access-policy and audit examples are simulated and do not enforce platform security. Source: `generation_manifest.csv`, 2026-11-04.
* The SME research artifact identifies unresolved questions about management domain, supported decisions, evidence sources, primary users and authority, rule strictness, and traceability. Source: primary research artifact, 2026-11-04.
* No interview records, participant details, usability observations, or screen sketches, annotated mockups, wireframes, or Figma links were supplied in the reviewed context package. Sources reviewed: session context, primary research artifact, and workshop input file list, 2026-11-04.

## Reported

* None from end users or directly observed user research. The SME artifact is a repository-context synthesis, not a record of user interviews or observation.

## Assumed

* Candidate users may include business managers, department leads, analysts, and governance reviewers. The SME artifact lists these as likely roles, not confirmed participants; validate the roles with the responsible business owner and users. Source: primary research artifact, 2026-11-04.
* A plausible need is to understand management performance and investigate variances using approved evidence, so a human decision-maker can assess what to do next. This is inferred from the scenario topic and synthetic dataset contents, not a user-stated need. Validate through interviews and workflow observation before using it as a product or design requirement. Sources: primary research artifact and `generation_manifest.csv`, 2026-11-04.

## Unresolved

* Which management domain is in scope: finance, operations, HR, sales, portfolio, or cross-functional performance?
* Which decision or decisions should be supported, and who holds decision authority?
* What triggers the task, how often does it occur, and what is the consequence when it is delayed or wrong?
* What do users do today, where do they get stuck, and what workarounds have they adopted? No current workflow or pain point has been evidenced.
* Which approved evidence sources can users access, and what source attribution, confidence, and audit trail do they need?
* Which management rules are mandatory versus advisory?
* What devices and environments are used, and are there known accessibility needs? No user evidence was supplied; do not infer a specific user cohort.
* Does primary user research exist in an approved external location? If so, record a non-sensitive reference to that location; do not copy protected content into this repository.

## Current Context

The workshop scenario concerns a management-analysis agent and includes fictional organizational, project, budget, and performance data. The trigger, actual decision workflow, represented user population, and current alternatives are unknown. This context supports framing research questions only; it does not establish a validated user need or an interface requirement.

## User Needs

### Candidate need: assess management performance

* Context: A management decision-maker is reviewing organizational or project performance; the trigger and cadence are unknown.
* Need: Understand relevant performance evidence and investigate material variance without losing its source or limitations.
* Outcome: A human decision-maker can make an informed assessment; the decision and success measure are not yet defined.
* Basis: Assumed.
* Source: Scenario topic and synthetic dataset manifest, 2026-11-04. No user statement or observed behavior supports this need yet.

## Current Approach and Workarounds

Unknown. The reviewed materials do not describe an incumbent dashboard, BI workflow, spreadsheet, manual report, or other user workaround. Establish this through user interviews and observation before recommending a design direction.

## Research Readiness

* Research objective: Identify the real users, decision situations, current workflow, friction and workarounds, evidence needs, and consequences of an incorrect or delayed analysis.
* Participants: None identified, recruited, or reported in the supplied materials. Candidate roles in `Assumed` are hypotheses, not a participant sample.
* Key observations: None. No direct interviews, contextual inquiry, usability sessions, or behavioral analytics were supplied.
* Current insight: The evidence package is suitable for a synthetic-data workshop scenario, but it does not establish user behavior or validate a user need.
* Next research questions: Resolve the items in `Unresolved`; prioritize interviews and observation with users who perform the target management decision, then validate the workflow and evidence expectations.

## Visual References

* Screen sketches, annotated mockups, wireframes, and Figma links: None supplied as of 2026-11-04. No visual reference is being inferred or presented as research evidence.
* When a reference is added, record its type, date, source or approved external pointer, and evidence status (`Observed`, `Reported`, `Assumed`, or `Unresolved`). Keep protected data in its approved source system and link to it without copying sensitive content here.

## Boundaries

* In scope: Evidence-first discovery using the approved workshop root and synthetic or public materials; documenting user needs as hypotheses until validated.
* Out of scope: Production-sensitive data in this repository; treating simulated access examples as real controls; asserting user research that did not occur; or positioning the agent as an autonomous decision-maker.

## Human Review

> [!CAUTION]
> **Disclaimer:** This agent is an assistive coaching tool only. It does not conduct user research, observe stakeholders, or speak for the people whose problems you are designing for, and it does not replace primary research, direct stakeholder contact, design review, or product and strategy decision authority. Personas, problem statements, journey maps, empathy maps, concept tests, and other Design Thinking artifacts produced with this tool are scaffolding for your own research and synthesis — not substitutes for real stakeholder voice or observed behavior. Validate all AI-generated assumptions, personas, themes, and insights against actual stakeholders before treating any Design Thinking artifact as a basis for product, design, or strategy commitments. Outputs from this tool do not constitute validated research findings or design approval.

- [ ] Reviewed and validated by a qualified human reviewer
