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

## 2. Microsoft 365 Copilot 통합 시 기대되는 최종 사용자 가치

Microsoft 365 Copilot이 이 시나리오에 통합될 때, 최종 사용자는 단순한 챗봇 응답 대신 관리 의사결정에 바로 사용할 수 있는 요약, 근거, 후속 조치 제안을 받는 경험을 기대할 수 있습니다. 가장 큰 가치 포인트는 다음과 같습니다.

### 2.1 의사결정 속도 향상

- 이메일, 회의 메모, 보고서, 대시보드, Excel 데이터 등 여러 소스를 빠르게 통합하여 핵심 이슈를 정리해 줍니다.
- 관리자가 직접 정보를 수집하고 조립하는 시간을 줄여 매일 반복되는 업무를 감소시킵니다.
- 월간 경영 리뷰, 예산 검토, 성과 점검 시 가장 먼저 필요한 핵심 질문과 차이점을 신속하게 제시합니다.

### 2.2 신뢰 가능한 근거 기반 요약

- 실제 데이터와 승인된 문맥을 기반으로 통찰을 제시하므로, 사용자는 “추측”이 아니라 “근거 기반 서술”을 확인할 수 있습니다.
- 사실, 가정, 미해결 이슈를 구분해 보여주기 때문에 의사결정자가 책임 있는 판단을 내리기 쉽습니다.
- 경영진은 더 짧은 시간 안에 인사이트를 확인하고, 필요한 경우 추가 검토를 결정할 수 있습니다.

### 2.3 업무 수행의 일관성 향상

- 동일한 질문을 여러 사람이 반복적으로 정리하는 대신, 표준화된 형식으로 요약과 액션 아이템을 제공합니다.
- 보고서 작성, 브리핑 준비, 대시보드 검토, 리스크 점검 등의 반복 업무를 줄여 팀의 일관성을 확보합니다.
- 부서 간 협업에서도 각 팀이 같은 근거를 공유하고 검토할 수 있는 공통 언어를 제공합니다.

### 2.4 이동 중에도 의사결정 지원

- Outlook, Teams, Word, PowerPoint, Excel, SharePoint를 오가며 필요한 문맥을 연결할 수 있어 관리자가 사무실이나 회의실 밖에서도 작업을 계속할 수 있습니다.
- 브리핑 자료 생성, 액션 메모 작성, 회의 전 체크리스트 준비를 한 번에 지원할 수 있습니다.
- 경영진은 회의 전에 핵심 사실과 불확실성을 빠르게 검토할 수 있습니다.

### 2.5 인간 통제와 책임 유지

- AI가 최종 결정권을 갖는 것이 아니라, “의사결정에 필요한 요약과 리스크 안내”를 제공하는 역할로 설계되면 사용자 신뢰를 높일 수 있습니다.
- 위험, 예외, 의심 지점, 검토가 필요한 부분을 분명히 보여주는 구조는 보안 및 거버넌스 요구사항에 부합합니다.
- 최종 사용자는 AI를 보조 도구로 활용하면서도 책임은 인간이 유지할 수 있습니다.

## 3. 검증을 위해 필요한 연구

M365 Copilot 통합의 실제 가치를 검증하려면, 단순한 기능 평가를 넘어 사용자의 업무 맥락과 성과 변화를 확인하는 연구가 필요합니다.

### 3.1 사용자 행동 및 업무 연구

- 경영관리, 부서 리더, 분석 담당자, 거버넌스 담당자가 현재 어떤 정보를 수동으로 조합하는지 관찰합니다.
- 소요 시간, 반복 빈도, 오류 포인트, 의사결정 전에 필요한 확인 절차를 측정합니다.
- AI를 활용한 흐름이 실제 업무 시간 단축과 의사결정 속도 향상으로 이어지는지 확인합니다.

### 3.2 가치 검증 지표 설계

- 평균 리포트 작성 시간 감소분
- 회의 전 준비 시간 절감
- 정보 수집 및 요약 작업의 반복 횟수 감소
- 근거 기반 브리핑 품질 개선률
- 의사결정자가 AI 요약을 신뢰하고 후속 조치를 취하는 비율

### 3.3 신뢰와 거버넌스 연구

- 사용자가 AI가 제시한 요약을 얼마나 신뢰하는지, 어떤 부분에서 불신이 생기는지 측정합니다.
- 근거 출처 표시, 불확실성 표기, 가정 구분, 인간 검토 요구사항이 실제로 신뢰를 높이는지 확인합니다.
- 민감 데이터 보호, 정보 접근 권한, 보안 정책 준수 여부를 검증해야 합니다.

### 3.4 실제 사용성 및 작업 흐름 연구

- M365 앱을 넘나드는 워크플로우가 관리자가 실제로 자연스럽게 사용하는지 검증합니다.
- Outlook에서 받은 이메일, Teams 회의 메모, Excel KPI, PowerPoint 보고서가 단일 흐름으로 연결되는지를 확인합니다.
- 사용자는 “인사이트를 보는 속도”와 “결정 후 행동의 용이성” 측면에서 얼마나 만족하는지 평가해야 합니다.

### 3.5 실패 사례와 대안 검토

- AI가 지나치게 확신적인 답변을 내거나, 보조 근거를 누락하는 경우를 확인합니다.
- 너무 많은 정보, 우선순위 없는 요약, 민감한 데이터 노출, 정책 위반 가능성에 대한 테스트가 필요합니다.
- 대안으로는 단순 요약형 Copilot, 규칙 기반 대시보드, 또는 인간 중심 검토 워크플로우가 어떤 상황에서 더 나은지 비교해야 합니다.

### 3.6 실험 설계 권장안

- 3~5개 사용자 그룹으로 사전/사후 비교 실험을 구성합니다.
- A/B 비교: 기존 수동 요약 프로세스 vs M365 Copilot 기반 요약 및 브리핑 지원
- 측정 항목: 시간 절감, 의사결정 품질, 사용자 신뢰도, 재사용성, 검토 빈도
- 최종적으로는 “AI가 실제 업무를 더 빠르게 만들었는가”뿐 아니라 “더 나은 판단을 더 안전하게 지원했는가”를 확인합니다.

## 4. Simple user journey

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
