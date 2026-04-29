# KA 7: Requirements Analysis and Design Definition

The work of turning elicited information into structured requirements and designs that solution teams can actually use. This is the largest KA — six tasks, the broadest set of techniques. It's where modelling lives, where verification and validation happen, where solution options are weighed and recommendations made.

A useful distinction BABOK draws: when the focus is on *understanding the need*, the output is called a **requirement**. When the focus is on *what the solution does*, the output is called a **design**. Both use the same techniques and the same task structure — they're points on a spectrum, not different artefacts.

## BACCM mapped to this KA

- **Change**: requirements and designs make the change concrete
- **Need**: requirements articulate the need in usable form
- **Solution**: designs describe the solution's behaviour and structure
- **Stakeholder**: requirements are validated against stakeholder needs; stakeholders verify that requirements are well-formed
- **Value**: solution recommendations are made on the basis of value vs. cost vs. risk
- **Context**: the requirements architecture must fit the organizational and technical context

## The six tasks

| Task | Purpose | Output |
|---|---|---|
| **7.1 Specify and Model Requirements** | Analyze, synthesize, and refine elicitation results into requirements and designs | Requirements (specified and modelled) |
| **7.2 Verify Requirements** | Ensure specifications meet quality standards and are usable | Requirements (verified) |
| **7.3 Validate Requirements** | Ensure requirements deliver business value and meet the need | Requirements (validated) |
| **7.4 Define Requirements Architecture** | Ensure requirements collectively support each other to fully achieve objectives | Requirements Architecture |
| **7.5 Define Design Options** | Define the solution approaches that could meet the requirements | Design Options |
| **7.6 Analyze Potential Value and Recommend Solution** | Estimate value of each option and recommend the best | Solution Recommendation |

---

## 7.1 Specify and Model Requirements

**Purpose**: Analyze, synthesize, and refine elicitation results into requirements and designs. This is where modelling happens.

**Inputs**: Elicitation Results (any state)

**Key elements**:
- **Model requirements**: choose the right representation. Models can be matrices, diagrams, or text. Different models capture different facets — People & Roles, Rationale, Activity Flow, Capability, Data & Information, etc.
- **Analyze requirements**: surface gaps, conflicts, ambiguities, dependencies
- **Represent requirements and attributes**: structure them with the metadata defined in 3.4
- **Implement appropriate levels of abstraction**: not every requirement needs the same granularity

**Techniques** (this is the most technique-rich task — almost every modelling technique applies): Acceptance & Evaluation Criteria, Business Capability Analysis, Business Model Canvas, Business Rules Analysis, Concept Modelling, Data Dictionary, Data Flow Diagrams, Data Modelling, Decision Modelling, Functional Decomposition, Glossary, Interface Analysis, Non-Functional Requirements Analysis, Organizational Modelling, **Process Modelling**, Prototyping, Roles & Permissions Matrix, Root Cause Analysis, Scope Modelling, Sequence Diagrams, Stakeholder List/Map/Personas, **State Modelling**, **Use Cases & Scenarios**, **User Stories**

**Stakeholders**: any stakeholder — modelling is collaborative

**Output**: Requirements (specified and modelled)

**Facilitation tips**: technique selection is the real skill. People reach for the modelling tool they know best, not the one the situation calls for. A simple rule: if the question is "what happens when?", use Process Modelling, State Modelling, or Sequence Diagrams. If it's "what data?", use Data Modelling or Data Dictionary. If it's "who can do what?", use Roles & Permissions or Use Cases. If it's "should we even build this?", use Business Model Canvas. Match the model to the question.

---

## 7.2 Verify Requirements

**Purpose**: Ensure that requirements and designs *as specifications* meet quality standards — clear, complete, consistent, correct, feasible, modifiable, unambiguous, testable.

**Inputs**: Requirements (specified and modelled)

**Key elements**:
- **Characteristics of requirements quality**: atomic, complete, consistent, concise, feasible, unambiguous, testable, prioritized, understandable
- **Verification activities**: peer reviews, walkthroughs, inspections, automated checks
- **Checklists**: standard quality dimensions to apply

**Techniques**: Acceptance & Evaluation Criteria, Item Tracking, Metrics & KPIs, **Reviews** (the workhorse)

**Stakeholders**: any stakeholder — but especially Tester, Implementation SME, Domain SME

**Output**: Requirements (verified)

**Facilitation tips**: verification ≠ validation. Verification is "is this requirement well-formed?" — a quality check on the artefact. Validation (next task) is "does this requirement actually deliver value?" — a relevance check. Conflating them is the most common error here.

---

## 7.3 Validate Requirements

**Purpose**: Ensure that the requirements deliver business value and meet the business need.

**Inputs**: Requirements (any state)

**Key elements**:
- **Identify assumptions**: about value delivery, stakeholder behaviour, market response
- **Define measurable evaluation criteria**: how will we know it actually delivered value?
- **Evaluate alignment with solution scope**: does it fit?

**Techniques**: Acceptance & Evaluation Criteria, Document Analysis, Financial Analysis, Item Tracking, Metrics & KPIs, Reviews, Risk Analysis & Management

**Stakeholders**: Customer, Domain SME, End User, Sponsor — the people who define value

**Output**: Requirements (validated)

**Facilitation tips**: validation is where wishful requirements get caught. "Will this actually move the metric?" is the right framing. If the user can't answer, validation hasn't happened. Acceptance & Evaluation Criteria is the workhorse — without explicit criteria, validation is just opinion.

---

## 7.4 Define Requirements Architecture

**Purpose**: Ensure the requirements collectively cohere and support each other to achieve the business objectives — no gaps, no overlaps, no conflicts.

**Inputs**: Information Management Approach; Requirements (any state); Solution Scope

**Key elements**:
- **Requirements viewpoints and views**: the lens(es) used to organize and present requirements
- **Template architectures**: industry/methodological starting points (e.g., TOGAF, Zachman)
- **Completeness**: do we have everything?
- **Relate and verify requirements relationships**: how do they connect?
- **Business analysis information architecture**: how the whole body of work is organized

**Techniques**: Data Modelling, Functional Decomposition, Interface Analysis, Organizational Modelling, Scope Modelling, User Stories

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Sponsor, Tester

**Output**: Requirements Architecture

**Facilitation tips**: most teams have *requirements*; few have a *requirements architecture*. The difference is whether the requirements collectively make sense, with clear relationships and no gaps. When stakeholders complain "we keep finding new requirements late," it's almost always missing architecture, not missing elicitation.

---

## 7.5 Define Design Options

**Purpose**: Define the solution approaches that could meet the requirements. Multiple options, evaluated against each other.

**Inputs**: Change Strategy; Requirements (validated, prioritized)

**Key elements**:
- **Define solution approaches**: build, buy, modify, rent, retire — and combinations
- **Identify improvement opportunities**: where the design unlocks more value than the strict requirements demand
- **Allocate requirements**: which requirements does each option address, and how completely

**Techniques**: Benchmarking & Market Analysis, Brainstorming, Document Analysis, Interviews, Lessons Learned, Mind Mapping, Prototyping, Reviews, SWOT Analysis, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester

**Output**: Design Options

**Facilitation tips**: a single design option is not really design — it's foregone conclusion. Push for at least 2–3 distinct options that genuinely differ in approach. If the user immediately jumps to one design, ask "what's the option you're rejecting and why?" That surfaces the implicit comparison.

---

## 7.6 Analyze Potential Value and Recommend Solution

**Purpose**: Estimate the potential value of each design option and recommend the best one.

**Inputs**: Design Options; Potential Value

**Key elements**:
- **Expected benefits**: tangible and intangible
- **Expected costs**: development, deployment, operation, opportunity
- **Determine value**: per option, in stakeholder terms
- **Assess design options and recommend solution**: with explicit reasoning and trade-offs

**Techniques**: Acceptance & Evaluation Criteria, Backlog Management, Business Cases, Decision Analysis, Decision Modelling, Estimation, Financial Analysis, Focus Groups, Metrics & KPIs, Risk Analysis & Management, SWOT Analysis, Vendor Assessment, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Operational Support, Project Manager, Regulator, Sponsor, Supplier, Tester

**Output**: Solution Recommendation

**Facilitation tips**: this is where business cases live. A weak business case usually traces to weak value estimation, not weak math. Push for explicit value drivers, even if rough — "$2M revenue uplift in year 1, with 60% confidence" beats "improved revenue." Decision Analysis and Financial Analysis are the workhorses.

---

## How to facilitate this KA

**This is the largest KA.** Six tasks, dozens of techniques. Don't try to cover everything in one session — pick the task that's actually blocking the user.

**The Verify-Validate distinction is essential.** A user complaining "the requirements were wrong" is usually conflating these. Help them name which: were they badly written (verification failure) or did they not deliver value (validation failure)? Different problems, different remedies.

**Modelling is over-applied and under-applied.** Some teams model everything as ceremony; others avoid modelling because it feels heavy. The right level is "the simplest model that resolves the ambiguity." If the conversation is clear without a model, don't model. If you're going in circles, model.

**Solution recommendation requires options.** If the user is recommending one option, the work of generating alternatives wasn't done. Push back to 7.5.

**Mode guidance**:
- **Quick**: walk the user through "is your specification clear, verified, validated, architecturally coherent, with options considered, and a recommendation reasoned?" Six checks; usually one is the bottleneck.
- **Working**: typically 7.1 (model one specific thing) or 7.6 (build out the recommendation reasoning for one decision).
- **Full**: run the chain — specify and model, verify, validate, architect, define options, recommend. This is a full requirements engagement, often a multi-week piece of work.
