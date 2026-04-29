# KA 6: Strategy Analysis

The work of figuring out *why* a change is needed, *what* the change is, and *how* to get there. This is the most strategic KA — it lives upstream of detailed requirements work and shapes everything downstream. The four tasks form a tight loop: understand current state → define future state → assess risks → define how to bridge the gap.

## BACCM mapped to this KA

- **Change**: this KA literally defines the change strategy
- **Need**: business needs are surfaced and articulated here, in current-state work
- **Solution**: the future state describes what the solution must achieve
- **Stakeholder**: identified as part of current-state and future-state analysis; their needs shape the strategy
- **Value**: the future state is defined in terms of value; risk is loss of value
- **Context**: current-state analysis *is* contextual analysis

## The four tasks

| Task | Purpose | Output |
|---|---|---|
| **6.1 Analyze Current State** | Understand why change is needed and what would be affected | Current State Description; Business Requirements |
| **6.2 Define Future State** | Determine the necessary conditions to meet the business need | Future State Description; Business Objectives |
| **6.3 Assess Risks** | Understand the uncertainties that could derail the change | Risk Analysis Results |
| **6.4 Define Change Strategy** | Define how to move from current to future, given the risks | Change Strategy; Solution Scope |

These four tasks interleave. Don't run them as a strict sequence — finding a risk often reshapes the future state; a future state realization shifts current-state focus.

---

## 6.1 Analyze Current State

**Purpose**: Understand why the enterprise needs to change and what would be directly or indirectly affected.

**Inputs**: Elicitation Results; Needs

**Key elements** (lots of them — current state is wide):
- **Business needs**: surface from top-down (strategic goals), bottom-up (process problems), middle-management (info gaps), or external drivers (market/customer/competition)
- **Organizational structure and culture**: how the org is shaped and how it actually behaves
- **Capabilities and processes**: what the enterprise can currently do
- **Technology and infrastructure**: what's running, what's supporting it
- **Policies**: rules in place
- **Business architecture**: capability map, value streams, organizational alignment
- **Internal assets**: what the enterprise owns and uses
- **External influencers**: industry structure, competitors, customers, suppliers, political/regulatory environment, technology trends, macroeconomic factors

**Techniques** (a long list — this is the most technique-rich task in BABOK): Benchmarking & Market Analysis, **Business Capability Analysis**, **Business Model Canvas**, Business Cases, Concept Modelling, Data Mining, Document Analysis, Financial Analysis, Focus Groups, Functional Decomposition, Interviews, Item Tracking, Lessons Learned, Metrics & KPIs, Mind Mapping, Observation, Organizational Modelling, **Process Analysis**, Process Modelling, Risk Analysis & Management, **Root Cause Analysis**, Scope Modelling, Survey/Questionnaire, **SWOT Analysis**, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester — basically everyone

**Outputs**: Current State Description; Business Requirements (the problem/opportunity stated as a need)

**Facilitation tips**: this is where most strategy work fails by skipping. Teams jump to future-state design without understanding why the current state isn't already good enough. The single best probing question: "what specifically about today is unacceptable, and to whom?" If the user can't answer that crisply, they're not done with current state. SWOT, Business Capability Analysis, and Root Cause Analysis are the highest-leverage techniques for getting unstuck.

---

## 6.2 Define Future State

**Purpose**: Determine the set of necessary conditions to meet the business need.

**Inputs**: Business Requirements

**Key elements**:
- **Business goals and objectives**: SMART goals — create new capability, improve revenue, increase satisfaction, comply with regulation, improve safety, reduce time-to-market
- **Scope of solution space**: what's in / out of bounds
- **Constraints**: what limits the solution
- **Organizational structure and culture** (future): how it needs to change
- **Capabilities and processes** (future)
- **Technology and infrastructure** (future)
- **Policies** (future)
- **Business architecture** (future)
- **Internal assets** (future)
- **Identify assumptions**: what we're betting on
- **Potential value**: tangible and intangible, in absolute or relative terms

**Techniques**: Acceptance & Evaluation Criteria, Balanced Scorecard, Benchmarking & Market Analysis, Brainstorming, Business Capability Analysis, Business Cases, Business Model Canvas, Decision Analysis, Decision Modelling, Financial Analysis, Functional Decomposition, Interviews, Lessons Learned, Metrics & KPIs, Mind Mapping, Organizational Modelling, Process Modelling, Prototyping, Scope Modelling, Survey/Questionnaire, SWOT Analysis, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Project Manager, Regulator, Sponsor

**Outputs**: Future State Description; Business Objectives; Potential Value

**Facilitation tips**: future state is where wishful thinking lives. Push for measurability: "how will you know you got there?" Without explicit business objectives and a sense of value (even rough), future state descriptions become aspirational paragraphs no one can hold themselves to. Business Model Canvas and Balanced Scorecard are excellent forcing functions here.

---

## 6.3 Assess Risks

**Purpose**: Understand the uncertain forces that could derail the change.

**Inputs**: Business Objectives; Elicitation Results; Future State Description; Influences (internal/external); Potential Value; Requirements; Stakeholder Engagement Approach

**Key elements**:
- Identify uncertainties affecting the change, the solution, the value, or the enterprise
- Analyze probability and impact
- Plan responses: avoid, mitigate, transfer, or accept

**Techniques**: Brainstorming, Business Cases, Decision Analysis, Document Analysis, Financial Analysis, Interviews, Lessons Learned, Mind Mapping, **Risk Analysis & Management** (the workhorse), Root Cause Analysis, Survey/Questionnaire, Workshops

**Stakeholders**: Domain SME, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier

**Output**: Risk Analysis Results

**Facilitation tips**: most risk registers are theatre — long lists no one acts on. Push for the top 5 risks, ranked, with named owners and responses. Quality > quantity. Also: many "risks" are actually assumptions that haven't been tested. Reframing assumptions as risks (or as items to test before commitment) often clears up vague risk lists.

---

## 6.4 Define Change Strategy

**Purpose**: Define the approach for moving from current state to future state, considering the risks and constraints.

**Inputs**: Current State Description; Future State Description; Risk Analysis Results; Stakeholder Engagement Approach

**Key elements**:
- **Solution scope**: what the solution will and won't do
- **Gap analysis**: what needs to change between current and future
- **Enterprise readiness assessment**: can the org actually do this?
- **Change strategy**: phasing, sequencing, transition states, dependencies

**Techniques**: Benchmarking & Market Analysis, Brainstorming, Business Capability Analysis, Business Cases, Decision Analysis, Estimation, Financial Analysis, Focus Groups, Functional Decomposition, Interviews, Lessons Learned, Mind Mapping, Organizational Modelling, Process Modelling, Scope Modelling, SWOT Analysis, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Project Manager, Regulator, Sponsor, Supplier

**Outputs**: Change Strategy; Solution Scope

**Facilitation tips**: gap analysis is the literal mechanism — what's the delta between current and future, and how do we close it? If the user has a future state but no clear gap analysis, push back. Also: most change strategies underweight enterprise readiness. The org may not be able to absorb the change at the proposed pace, and that's a real constraint.

---

## How to facilitate this KA

**Strategy Analysis is upstream of everything.** When detailed requirements work feels confused, the cause is almost always missing or unclear strategy work. If a user is mid-elicitation and stuck, it's worth asking "what's the future state we're working toward?" — half the time, the answer reveals the confusion.

**The four tasks loop.** Don't enforce a sequence. A risk surfaced in 6.3 may reshape the future state (6.2). A capability gap noticed in current-state work (6.1) may shift the change strategy (6.4).

**This is where the BACCM is most useful.** Walking Change/Need/Solution/Stakeholder/Value/Context across these four tasks gives a quick diagnostic on whether the strategic work is coherent.

**Mode guidance**:
- **Quick**: 10 minutes to do a BACCM gut-check on the current strategic frame. "Is the change clear, the need articulated, the future state described, the value identified, the risks named, the strategy plausible?"
- **Working**: pick one task. Most often: 6.1 (current state for a fresh problem), 6.2 (future state when sponsors disagree on outcomes), or 6.4 (define a change strategy when the team is ready to start moving).
- **Full**: run all four tasks for a real strategic initiative. This is consulting-grade work and deserves multiple sessions, with named outputs at each stage.
