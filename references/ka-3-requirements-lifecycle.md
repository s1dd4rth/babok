# KA 5: Requirements Life Cycle Management

The work of managing requirements as living artefacts — tracing them, keeping them current, prioritizing, assessing changes, and approving them. This is the *governance* of requirements, distinct from eliciting them (KA 4) or analyzing/designing them (KA 7). Most modern teams do this loosely through tools like Jira or Linear; BABOK gives it structure.

## BACCM mapped to this KA

- **Change**: every requirement is an articulated piece of the change; managing them shapes the change
- **Need**: requirements are how needs are made actionable; lifecycle work keeps them aligned to needs over time
- **Solution**: requirements anchor the solution; tracing them to solution components proves the solution addresses the need
- **Stakeholder**: stakeholders propose, prioritize, and approve requirements; lifecycle work is collaborative
- **Value**: prioritization is the value-realization mechanism — sequence work to deliver highest-value items first
- **Context**: contextual changes (regulation, market, organization) cause requirements to change; lifecycle work absorbs that

## The five tasks

| Task | Purpose | Output |
|---|---|---|
| **5.1 Trace Requirements** | Maintain the lineage of each requirement to other requirements, designs, and solution components | Requirements (traced); Designs (traced) |
| **5.2 Maintain Requirements** | Keep requirements accurate and reusable over time | Requirements (maintained); Designs (maintained) |
| **5.3 Prioritize Requirements** | Rank requirements by relative importance | Requirements (prioritized); Designs (prioritized) |
| **5.4 Assess Requirements Changes** | Evaluate the implications of proposed changes | Requirements/Designs Change Assessment |
| **5.5 Approve Requirements** | Get stakeholder agreement that requirements are correct and ready to use | Requirements (approved); Designs (approved) |

---

## 5.1 Trace Requirements

**Purpose**: Ensure requirements at different levels stay aligned, and manage how a change to one cascades to related ones.

**Inputs**: Requirements; Designs

**Key elements**:
- **Level of formality**: how rigorous traceability needs to be — depends on size, complexity, regulatory exposure
- **Relationships**: the formal trace types — Derive (one requirement is derived from another), Depends (one needs another to make sense / be easier), Satisfy (an implementation element satisfies a requirement), Validate (a test validates a requirement)
- **Traceability repository**: where the traces live (often in a tool — Jira links, ALM tool, requirements DB)

**Techniques**: Business Rules Analysis, Functional Decomposition, Process Modelling, Scope Modelling

**Stakeholders**: Customers, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Sponsor, Suppliers, Tester

**Output**: Requirements (traced); Designs (traced)

**Facilitation tips**: traceability has high value in regulated/safety-critical contexts (medical, finance, aerospace) and low value in lightweight product teams. Help the user calibrate. The four trace types (Derive, Depends, Satisfy, Validate) are the technical core — name them when discussing what to trace.

---

## 5.2 Maintain Requirements

**Purpose**: Keep requirements accurate and consistent throughout the change — and beyond, supporting reuse in future solutions.

**Inputs**: Requirements; Designs

**Key elements**:
- **Maintain requirements**: keep current as the world shifts
- **Maintain attributes**: priority, status, owner, source — the metadata that makes a requirement findable and decisional
- **Reusing requirements**: identify what could be reused elsewhere; structure for it

**Techniques**: Business Rules Analysis, Data Flow Diagrams, Data Modelling, Document Analysis, Functional Decomposition, Process Modelling, Use Cases & Scenarios, User Stories

**Stakeholders**: Domain SME, Implementation SME, Operational Support, Regulator, Tester

**Output**: Requirements (maintained); Designs (maintained)

**Facilitation tips**: requirements rot is a real failure mode — a year-old PRD that no one trusts. Maintenance is unglamorous but cheap relative to re-elicitation. If the user has a graveyard of stale requirements, that's signal of skipped maintenance, not skipped elicitation.

---

## 5.3 Prioritize Requirements

**Purpose**: Rank requirements by relative importance so the right work gets done first.

**Inputs**: Requirements; Designs

**Key elements**:
- **Basis for prioritization**: Benefit, Penalty (of not doing it), Cost, Risk, Dependencies, Time Sensitivity, Stability, Regulatory/Policy Compliance
- **Challenges of prioritization**: stakeholder disagreement, shifting context, false precision
- **Continual prioritization**: it's not one-and-done — it's an ongoing rhythm

**Techniques**: Backlog Management, Business Cases, Decision Analysis, Estimation, Financial Analysis, Interviews, Item Tracking, **Prioritization** (the workhorse — MoSCoW, weighted scoring, kano, etc.), Risk Analysis & Management, Workshops

**Stakeholders**: Customer, End User, Implementation SME, Project Manager, Regulator, Sponsor

**Output**: Requirements (prioritized); Designs (prioritized)

**Facilitation tips**: prioritization conversations expose value disagreements that were previously hidden. That's the point. If everyone agrees on priorities, either you've just resolved a hidden disagreement or you haven't surfaced the real trade-offs yet. The eight bases (Benefit, Penalty, Cost, Risk, Dependencies, Time Sensitivity, Stability, Compliance) are the structured prompts — use them when "I just feel like X is important" doesn't hold up.

---

## 5.4 Assess Requirements Changes

**Purpose**: Evaluate the implications of proposed changes to requirements/designs *before* deciding to accept them.

**Inputs**: Proposed Change; Requirements; Designs

**Key elements**:
- **Assessment formality**: how rigorous the assessment process is
- **Impact analysis**: along Benefit, Cost, Impact (on customers/processes), Schedule, Urgency
- **Impact resolution**: the decision and its communication

**Techniques**: Business Cases, Business Rules Analysis, Decision Analysis, Document Analysis, Estimation, Financial Analysis, Interface Analysis, Interviews, Item Tracking, Risk Analysis & Management, Workshops

**Stakeholders**: Customer, Domain SME, End User, Operational Support, Project Manager, Regulator, Sponsor, Tester

**Output**: Requirements/Designs Change Assessment

**Facilitation tips**: every change request is also a learning signal. If lots of changes pour in, that's not a "process problem" — that's elicitation or context drift. Look upstream. Also: small changes individually look harmless; in aggregate they reshape scope. Encourage the user to spot patterns across change requests, not just process them serially.

---

## 5.5 Approve Requirements

**Purpose**: Get explicit stakeholder agreement that the requirements are correct and ready to be used downstream.

**Inputs**: Requirements (verified); Designs

**Key elements**:
- **Understand stakeholder roles**: who has approval authority for what
- **Conflict and issue management**: surface and work through disagreement
- **Gain consensus**: not unanimity — structured agreement
- **Track and communicate approval**: record decisions; let the right people know

**Techniques**: Acceptance & Evaluation Criteria, Decision Analysis, Item Tracking, Reviews, Workshops

**Stakeholders**: Customer, Domain SME, End User, Operational Support, Project Manager, Regulator, Sponsor, Tester

**Output**: Requirements (approved); Designs (approved)

**Facilitation tips**: approval theatre is common — sign-offs without real understanding. The approval *event* matters less than the approval *conversation*. If sign-offs are coming back without discussion, someone's not really reading the requirements. Push for active engagement: walkthroughs, demos, scenarios.

---

## How to facilitate this KA

**This KA is mostly invisible until it fails.** People don't celebrate good traceability or clean approvals — they just notice when stale requirements waste a sprint or when a change blew up the timeline. Frame this work as risk reduction, not bureaucracy.

**Tool fit matters a lot here.** Modern requirements tools (Jira, Linear, ADO, Polarion, DOORS) embed many of these decisions. Don't fight the tool — work with what the user has. If they're on sticky notes and a wiki, the practice has to compensate for the tool's looseness.

**Prioritization is the most-asked question.** If a user shows up with "help me prioritize this backlog," that's task 5.3, and it's where the highest-leverage technique work in this KA happens. Reach for Prioritization (the technique), Decision Analysis, MoSCoW, or weighted scoring.

**Mode guidance**:
- **Quick**: walk the user through "do you trace, maintain, prioritize, assess changes, and approve? Where's the friction?" Find the weakest task and recommend one improvement.
- **Working**: usually 5.3 Prioritize (live prioritization session), 5.4 Assess (one change request walked through), or 5.5 Approve (one approval cycle designed).
- **Full**: design the whole lifecycle for an initiative — what's traced, how it's maintained, how priorities are reviewed, how changes flow, how approvals work. This is core operating-model work.
