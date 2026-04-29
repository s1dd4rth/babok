# KA 8: Solution Evaluation

The work of measuring whether a deployed solution actually delivers value — and figuring out what to do when it doesn't. This KA is downstream of delivery; it's where BA work meets the operational reality. Often skipped or under-resourced because the project is "done" — but this is where lessons become organizational learning.

## BACCM mapped to this KA

- **Change**: evaluating whether the change actually achieved its purpose
- **Need**: re-checking whether the original need was met (or whether it shifted)
- **Solution**: the focus is the deployed solution itself
- **Stakeholder**: stakeholders define what "working" means; they're the source of value judgments
- **Value**: this entire KA is about value — measuring it, analyzing it, and recovering it when it's blocked
- **Context**: enterprise limitations and external context can block value even when the solution itself works

## The five tasks

| Task | Purpose | Output |
|---|---|---|
| **8.1 Measure Solution Performance** | Define performance measures and use the data to evaluate effectiveness | Solution Performance Measures |
| **8.2 Analyze Performance Measures** | Provide insights into solution performance in relation to value | Solution Performance Analysis |
| **8.3 Assess Solution Limitations** | Identify factors *internal to the solution* that restrict value | Solution Limitation |
| **8.4 Assess Enterprise Limitations** | Identify factors *external to the solution* that restrict value | Enterprise Limitation |
| **8.5 Recommend Actions to Increase Solution Value** | Recommend what to do about the gaps | Recommended Actions |

---

## 8.1 Measure Solution Performance

**Purpose**: Define what "working" means for this solution, and collect the data that shows whether it's working.

**Inputs**: Business Objectives; Implemented (or Constructed) Solution

**Key elements**:
- **Define solution performance measures**: what to measure, in what units, against what target
- **Validate performance measures**: confirm they actually reflect value — not just convenience
- **Collect performance measures**: actually gather the data, not just plan to

**Techniques**: Acceptance & Evaluation Criteria, Benchmarking & Market Analysis, Data Mining, Decision Analysis, Focus Groups, Interviews, Metrics & KPIs, Non-Functional Requirements Analysis, Observation, Prototyping, Survey/Questionnaire, Vendor Assessment

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester

**Output**: Solution Performance Measures

**Facilitation tips**: most solutions ship without instrumented success metrics. The conversation has to start with "how will we know this is working in 90 days?" If the answer is vague, the measure design is the work. Avoid vanity metrics — usage doesn't equal value. KPIs are the workhorse technique here, but only if they're tied to business objectives.

---

## 8.2 Analyze Performance Measures

**Purpose**: Make sense of the measures — what story does the data tell about value delivered?

**Inputs**: Business Objectives; Solution Performance Measures

**Key elements**:
- **Solution performance versus desired value**: actual vs. intended
- **Risks**: what's emerging as the solution operates
- **Trends**: where things are heading, not just where they are
- **Accuracy of performance measures**: are we measuring the right things?

**Techniques**: Benchmarking & Market Analysis, Data Mining, Decision Analysis, Document Analysis, Focus Groups, Interviews, Item Tracking, Lessons Learned, Metrics & KPIs, Risk Analysis & Management, Root Cause Analysis, Survey/Questionnaire

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Sponsor, Supplier, Tester

**Output**: Solution Performance Analysis

**Facilitation tips**: numbers without interpretation aren't analysis. The skill is going from "this metric moved" to "this is what's happening and why." Root Cause Analysis comes back into play here. Also: trend lines beat snapshot numbers. A solution performing at 70% of target is one story if it's trending up, another if it's trending down.

---

## 8.3 Assess Solution Limitations

**Purpose**: Identify the factors *internal to the solution* that are blocking value.

**Inputs**: Implemented (or Constructed) Solution; Solution Performance Analysis

**Key elements**:
- **Identify internal solution component dependencies**: where issues cascade
- **Investigate solution problems**: what's actually broken or under-performing
- **Impact assessment**: how much value is being lost

**Techniques**: Acceptance & Evaluation Criteria, Benchmarking & Market Analysis, Business Rules Analysis, Data Mining, Decision Analysis, Item Tracking, Lessons Learned, Metrics & KPIs, Risk Analysis & Management, Root Cause Analysis, Survey/Questionnaire

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Sponsor, Supplier, Tester

**Output**: Solution Limitation

**Facilitation tips**: the discipline here is to *isolate* solution-internal causes. Lots of "the solution isn't working" complaints are actually enterprise-side issues (next task). Pushing to name what specifically *inside* the solution is failing helps separate the two. Root Cause Analysis is the workhorse.

---

## 8.4 Assess Enterprise Limitations

**Purpose**: Identify the factors *external to the solution* that are blocking value — culture, process, capability, market.

**Inputs**: Current State Description; Implemented (or Constructed) Solution; Solution Performance Analysis

**Key elements**:
- **Enterprise culture assessment**: people not adopting, even though the solution works
- **Stakeholder impact analysis**: which stakeholder groups are affected, how
- **Organizational structure changes**: needed but not made
- **Operational assessment**: process around the solution isn't supporting it

**Techniques**: Brainstorming, Business Capability Analysis, Decision Analysis, Document Analysis, Financial Analysis, Focus Groups, Interviews, Item Tracking, Lessons Learned, Metrics & KPIs, Observation, Organizational Modelling, Risk Analysis & Management, Root Cause Analysis, Survey/Questionnaire, SWOT Analysis, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester

**Output**: Enterprise Limitation

**Facilitation tips**: this is where many "failed solutions" turn out to be successful solutions in unsupportive environments. The failure mode looks the same from outside: "users aren't using it." But the remedy is completely different — solution-internal fixes vs. enterprise-side change management. Push hard to distinguish. Often a solution doesn't need to change at all; the org around it does.

---

## 8.5 Recommend Actions to Increase Solution Value

**Purpose**: Synthesize the findings and recommend what to do — fix, retire, redeploy, retrain, restructure.

**Inputs**: Business Objectives; Enterprise Limitation; Solution Limitation; Solution Performance Analysis

**Key elements**:
- **Adjust solution performance measures**: maybe we're measuring wrong
- **Approaches to increase solution value**: change the solution, change the environment, retire and replace, do nothing
- **Recommend actions**: explicit, prioritized, with owners

**Techniques**: Brainstorming, Decision Analysis, Financial Analysis, Focus Groups, Interviews, Lessons Learned, Organizational Modelling, Prioritization, Reviews, Risk Analysis & Management, Root Cause Analysis, Survey/Questionnaire, SWOT Analysis, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester

**Output**: Recommended Actions

**Facilitation tips**: recommendations without owners and dates are wishes. Push for crispness. Also: "do nothing" is a real option — sometimes accepting current performance is the right call, and naming that explicitly beats vague "we should improve this."

---

## How to facilitate this KA

**This KA is the most underdone in practice.** Project ends, team disbands, no one circles back. Surface this gap when you see it: a deployed solution without instrumented measurement is half-done.

**Two-by-two for diagnosing problems**: solution working / solution failing × enterprise supporting / enterprise blocking. Each quadrant has a different recommendation. Help the user place themselves before recommending action.

**Time horizons matter.** A solution at 30 days, 90 days, and 12 months tells different stories. If the user is impatient about results, ask "how long should it take to see value, and why?"

**Mode guidance**:
- **Quick**: 5-minute pass — "do you have measures, are you analyzing them, do you know what's solution-internal vs. enterprise-side, and are there explicit recommendations with owners?"
- **Working**: typically 8.3 + 8.4 (diagnose what's blocking value) or 8.5 (build out a recommendation set).
- **Full**: a complete post-launch evaluation cycle. Most products and major changes deserve this; few get it. If you're guiding a real evaluation, plan for multiple sessions over weeks (not days) — performance data needs time to accumulate.
