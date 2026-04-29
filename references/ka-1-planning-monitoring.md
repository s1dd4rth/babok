# KA 3: Business Analysis Planning and Monitoring

The work of planning *how the BA work itself will be done* — and then watching how it's actually going. This KA is about the analyst's own approach, not about the change being analyzed. Easy to underdo (just dive in), easy to overdo (paralyse-by-planning). The right amount usually feels uncomfortably small.

## BACCM mapped to this KA

- **Change**: define the kind, scope, and complexity of the change so the BA approach fits it
- **Need**: ensure the BA work actually serves the business need it's supposed to
- **Solution**: plan how solution decisions will be made and approved
- **Stakeholder**: identify and plan engagement with everyone who'll participate or be affected
- **Value**: plan how the value of BA work itself will be measured
- **Context**: tailor the approach to the organizational, methodological, and cultural context

## The five tasks

| Task | Purpose | Output |
|---|---|---|
| **3.1 Plan Business Analysis Approach** | Define the method for doing BA work on this initiative | Business Analysis Approach |
| **3.2 Plan Stakeholder Engagement** | Plan how to establish and maintain working relationships | Stakeholder Engagement Approach |
| **3.3 Plan Business Analysis Governance** | Define how decisions are made — reviews, change control, approvals, prioritization | Governance Approach |
| **3.4 Plan Business Analysis Information Management** | Define how BA information will be stored, accessed, structured | Information Management Approach |
| **3.5 Identify Business Analysis Performance Improvements** | Monitor the BA work and find improvements | BA Performance Assessment |

---

## 3.1 Plan Business Analysis Approach

**Purpose**: Define how the BA work will be done on this initiative — predictive vs. adaptive, formal vs. informal, what gets produced when.

**Inputs**: Needs (the problem/opportunity)

**Key elements**:
- **Planning approach**: predictive (plan-driven, comprehensive upfront) vs. adaptive (iterative, evolving) — and where on the spectrum
- **Formality and level of detail of BA deliverables**: how rigorous? Visual sketch or formal spec?
- **Business analysis activities**: what tasks will actually be done
- **Timing of BA work**: front-loaded vs. spread across the lifecycle
- **Complexity and risk**: shape the approach to match
- **Acceptance**: who agrees that this approach is right

**Techniques**: Brainstorming, Business Cases, Document Analysis, Estimation, Financial Analysis, Functional Decomposition, Interviews, Item Tracking, Lessons Learned, Process Modelling, Reviews, Risk Analysis & Management, Scope Modelling, Survey/Questionnaire, Workshops

**Stakeholders**: Domain SME (risk source if disengaged), Project Manager (alignment with project plan), Regulator, Sponsor

**Output**: Business Analysis Approach

**Facilitation tips**: most teams skip this and improvise. The cost shows up as inconsistent deliverables, missed stakeholders, and rework. A 30-minute conversation here prevents days of churn later. If the user says "we use [Scrum/SAFe/PMI]," that's a starting point, not the whole answer — methodology shapes the approach but doesn't *be* the approach.

---

## 3.2 Plan Stakeholder Engagement

**Purpose**: Plan how to establish and sustain working relationships with each stakeholder group.

**Inputs**: Needs; Business Analysis Approach

**Key elements**:
- **Perform stakeholder analysis**: who are they, what's their interest/influence, what attitudes do they hold
- **Define stakeholder collaboration**: how each group will work with the team
- **Stakeholder communication needs**: format, frequency, channel per group

**Techniques**: Brainstorming, Business Rules Analysis, Document Analysis, Interviews, Lessons Learned, Mind Mapping, Organizational Modelling, Process Modelling, Risk Analysis & Management, Scope Modelling, **Stakeholder List/Map/Personas** (the workhorse for this task), Survey/Questionnaire, Workshops

**Stakeholders**: everyone — but specifically Customers, Domain SMEs, End Users, Project Manager, Regulator, Sponsor, Suppliers

**Output**: Stakeholder Engagement Approach

**Facilitation tips**: a stakeholder list and a stakeholder map are not the same thing. The list is who; the map shows interest/influence/attitudes. Both are useful. If the user has a list but not a map, the gap is usually invisible-but-important stakeholders. Ask "who is missing from this list who could derail the change?"

---

## 3.3 Plan Business Analysis Governance

**Purpose**: Define how decisions will be made — reviews, change control, approvals, prioritization.

**Inputs**: Business Analysis Approach; Stakeholder Engagement Approach

**Key elements**:
- **Decision making**: who decides what
- **Change control process**: how changes to requirements/designs are requested, evaluated, decided
- **Plan prioritization approach**: who prioritizes and how
- **Plan for approvals**: which artefacts need formal approval, from whom

**Techniques**: Brainstorming, Document Analysis, Interviews, Item Tracking, Lessons Learned, Organizational Modelling, Process Modelling, Reviews, Survey/Questionnaire, Workshops

**Stakeholders**: Domain SME, Project Manager, Regulator, Sponsor

**Output**: Governance Approach

**Facilitation tips**: ungoverned BA work means every decision becomes a debate. Over-governed BA work means every decision becomes a meeting. The right level depends on initiative size, regulatory context, and organizational culture. For most agile teams, a lightweight governance plan ("PO decides scope; team decides how; sponsor approves at end of each release") is enough.

---

## 3.4 Plan Business Analysis Information Management

**Purpose**: Decide how BA information (requirements, designs, models, decisions) will be organized, stored, and accessed.

**Inputs**: Business Analysis Approach; Governance Approach; Stakeholder Engagement Approach

**Key elements**:
- **Organization of BA information**: by feature? by epic? by component?
- **Level of abstraction**: what level of detail at what stage
- **Plan traceability approach**: how requirements link to each other, to designs, to tests
- **Plan for requirements reuse**: how and when reuse will be sought
- **Storage and access**: where it lives, who can see/edit
- **Requirements attributes**: what metadata each requirement carries (priority, source, status, owner, complexity, risk, urgency, stability, etc.)

**Techniques**: Brainstorming, Interviews, Item Tracking, Lessons Learned, Mind Mapping, Process Modelling, Survey/Questionnaire, Workshops

**Stakeholders**: Domain SME, Regulator, Sponsor

**Output**: Information Management Approach

**Facilitation tips**: this is dry but consequential. Bad info management → can't find anything → re-elicitation → frustrated stakeholders. Modern tools (Jira, Confluence, Linear, Notion, ALM tools) embed many of these decisions; if the user is on one of these, the question becomes "are you using it the way the tool wants you to, and is that working?"

---

## 3.5 Identify Business Analysis Performance Improvements

**Purpose**: Monitor and improve the BA work itself. Continuous improvement loop on the analyst's own practice.

**Inputs**: Business Analysis Approach; Performance Objectives (external)

**Key elements**:
- **Performance analysis**: what's actually happening vs. what was planned
- **Assessment measures**: accuracy/completeness, effectiveness, organizational support, significance, strategic alignment, timeliness
- **Analyze results**: what's the gap and why
- **Recommend actions for improvement**: preventive, corrective, or improvement actions

**Techniques**: Brainstorming, Interviews, Item Tracking, Lessons Learned, Metrics & KPIs, Observation, Process Analysis, Reviews, Risk Analysis & Management, Root Cause Analysis, Survey/Questionnaire, Workshops

**Stakeholders**: Domain SME, Project Manager, Sponsor, plus anyone consuming BA outputs

**Output**: Business Analysis Performance Assessment

**Facilitation tips**: usually neglected because BA work doesn't fail loudly — it fails as friction, rework, missed needs. Surface the failure modes: "what's been frustrating about how we've worked?" beats "rate our performance 1–5." Lessons Learned is the workhorse technique here.

---

## How to facilitate this KA

**Most users underdo planning.** The cost of skipping it is invisible until rework hits. A useful frame: "we're not planning the project, we're planning *how we'll figure out the project*."

**Most users overdo governance.** Especially in agile contexts, heavy governance feels safe but creates drag. Right-size it.

**The five tasks are coupled.** A change in approach (3.1) cascades into stakeholder engagement (3.2), governance (3.3), and information management (3.4). When something changes, re-check the others.

**Mode guidance**:
- **Quick**: a 5-minute pass — "what's your approach, who are your stakeholders, who decides, where does the info live, how will you know it's working?" Five questions, five answers.
- **Working**: pick one task and produce its artefact. Most common: 3.1 (Approach) at the start of an initiative, or 3.2 (Stakeholder Engagement) when expanding scope.
- **Full**: all five artefacts at the start of a real engagement. Most consulting and product-discovery engagements deserve this.
