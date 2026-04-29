# Techniques Catalog (BABOK Chapter 10)

The 50 techniques BABOK names. Each entry is purpose + when to reach for it. For the formal mapping of which techniques pair with which task, see `techniques-to-task-map.md`.

Each technique in BABOK has the same internal structure: Purpose, Description, Elements, Usage Considerations. This catalog distils the first two — pull the BABOK source if you need depth on Elements (the sub-procedures) or Usage Considerations (where it works well/poorly).

The 50 techniques broken into rough functional groups:

**Elicitation aids**: Brainstorming, Collaborative Games, Document Analysis, Focus Groups, Interviews, Mind Mapping, Observation, Survey/Questionnaire, Workshops

**Modelling**: Concept Modelling, Data Dictionary, Data Flow Diagrams, Data Modelling, Decision Modelling, Functional Decomposition, Glossary, Process Modelling, Prototyping, Sequence Diagrams, State Modelling, Use Cases & Scenarios, User Stories, Organizational Modelling, Roles & Permissions Matrix, Scope Modelling, Interface Analysis

**Analytical lenses**: Benchmarking & Market Analysis, Business Capability Analysis, Business Cases, Business Model Canvas, Business Rules Analysis, Decision Analysis, Estimation, Financial Analysis, Process Analysis, Risk Analysis & Management, Root Cause Analysis, SWOT Analysis, Vendor Assessment, Data Mining

**Governance / management**: Acceptance & Evaluation Criteria, Backlog Management, Item Tracking, Lessons Learned, Metrics & KPIs, Non-Functional Requirements Analysis, Prioritization, Reviews, Stakeholder List/Map/Personas, Balanced Scorecard

---

## 10.1 Acceptance and Evaluation Criteria
**Purpose**: Define the requirements, outcomes, or conditions that must be met for a solution to be acceptable; or define measures used to choose between alternative solutions. **Use when**: closing on a requirement, validating a deliverable, or comparing solution options. Acceptance criteria belong on every requirement that needs a clear "done" definition.

## 10.2 Backlog Management
**Purpose**: Record, track, and prioritize remaining work items. **Use when**: more work exists than capacity to do it (almost always). Modern PM tools (Jira, Linear, ADO) embed backlog management; the technique is about the discipline, not the tool.

## 10.3 Balanced Scorecard
**Purpose**: Manage performance across financial, customer, internal-process, and learning-and-growth perspectives. **Use when**: defining holistic success measures for an enterprise or major initiative. Forces you beyond financial-only thinking.

## 10.4 Benchmarking and Market Analysis
**Purpose**: Compare a process/system/product/structure against external baselines (similar organizations or industry standards) to find improvement opportunities. **Use when**: validating ambition (are we behind / ahead?) or scoping change.

## 10.5 Brainstorming
**Purpose**: Generate many ideas in a short period and derive themes for analysis. **Use when**: divergent thinking is needed — early elicitation, options generation, risk identification. Defer judgment, encourage volume, build on others' ideas.

## 10.6 Business Capability Analysis
**Purpose**: Frame what an enterprise is able to *do* (not how) and assess each capability for performance, value, and risk. **Use when**: scoping change at the enterprise level, building a capability map, prioritizing investment.

## 10.7 Business Cases
**Purpose**: Justify a course of action based on benefits vs. cost, effort, and other considerations. **Use when**: a decision needs explicit reasoning that survives scrutiny — funding, project go/no-go, vendor selection.

## 10.8 Business Model Canvas
**Purpose**: Describe how an enterprise creates, delivers, and captures value, in nine connected blocks (customer segments, value propositions, channels, customer relationships, revenue streams, key resources, key activities, key partnerships, cost structure). **Use when**: aligning stakeholders on the business model, comparing models, or surfacing assumptions.

## 10.9 Business Rules Analysis
**Purpose**: Identify, express, validate, refine, and organize the rules that shape day-to-day business behaviour and decisions. **Use when**: rules are tangled with process, decisions are inconsistent, or the same logic shows up in multiple places.

## 10.10 Collaborative Games
**Purpose**: Use structured play to build joint understanding of a problem or stimulate creative solutions. **Use when**: stakeholders are stuck in their default frames, trust needs building, or normal conversation isn't surfacing the underlying ideas. Examples: Speedboat, Product Box, 20/20 Vision.

## 10.11 Concept Modelling
**Purpose**: Organize the business vocabulary needed to communicate domain knowledge consistently. **Use when**: terms are being used inconsistently, definitions are hidden in heads, or a glossary alone isn't enough — you need the relationships between terms.

## 10.12 Data Dictionary
**Purpose**: Standardize the definition of a data element and enable common interpretation. **Use when**: data is being used by multiple systems or teams; integration work; data governance.

## 10.13 Data Flow Diagrams
**Purpose**: Show where data comes from, what processes act on it, and where the results go. **Use when**: tracing information flow through processes; understanding system boundaries from a data perspective.

## 10.14 Data Mining
**Purpose**: Find useful patterns and insights in data to improve decisions. **Use when**: existing data can answer the question better than asking people; current-state analysis; performance evaluation.

## 10.15 Data Modelling
**Purpose**: Describe the entities, classes, or data objects in a domain, their attributes, and their relationships. **Use when**: building or integrating systems; understanding domain semantics; planning data structures.

## 10.16 Decision Analysis
**Purpose**: Formally assess a problem and possible decisions to determine the value of alternatives under uncertainty. **Use when**: decisions are high-stakes, alternatives are non-obvious, or stakeholders disagree on which option is better. Decision trees, expected value, multi-criteria decision analysis.

## 10.17 Decision Modelling
**Purpose**: Show how repeatable business decisions are made. **Use when**: decisions are repeated, encoded in rules, or being automated. DMN (Decision Model and Notation) is a common standard.

## 10.18 Document Analysis
**Purpose**: Elicit business analysis information by examining available materials (existing systems, contracts, procedures, policies, standards, regulations). **Use when**: information is already written down somewhere — usually it is, more than people realize. Cheap, fast, often skipped.

## 10.19 Estimation
**Purpose**: Forecast cost and effort of a course of action. **Use when**: any decision involves resources (time, money, people). Common approaches: top-down, bottom-up, parametric, three-point, Delphi, planning poker.

## 10.20 Financial Analysis
**Purpose**: Understand the financial aspects of an investment, solution, or solution approach. **Use when**: building a business case, comparing options, reporting to a finance-literate sponsor. NPV, IRR, payback period, ROI, total cost of ownership.

## 10.21 Focus Groups
**Purpose**: Elicit ideas and opinions about a specific product, service, or opportunity from an interactive group, guided by a moderator. **Use when**: you want grouped, discussion-based feedback rather than individual interviews. Different from a workshop — focus groups gather perceptions, workshops produce decisions.

## 10.22 Functional Decomposition
**Purpose**: Manage complexity by breaking processes/systems/areas/deliverables into simpler constituent parts. **Use when**: something is too big to think about as a whole; building a work breakdown structure; finding the right unit of analysis.

## 10.23 Glossary
**Purpose**: Define key terms relevant to a business domain. **Use when**: people are talking past each other or terms have multiple meanings. Lighter than a Concept Model — definitions only, no relationships.

## 10.24 Interface Analysis
**Purpose**: Identify where, what, why, when, how, and for whom information is exchanged between solution components or across boundaries. **Use when**: integration work, system boundaries matter, or the solution has multiple subsystems.

## 10.25 Interviews
**Purpose**: Systematically elicit information from a person or small group through asking questions and documenting responses. **Use when**: you need depth from one source, want to build relationship, or the topic is sensitive enough to need privacy. Most common, often over-used vs. observation or workshops.

## 10.26 Item Tracking
**Purpose**: Capture and assign responsibility for issues and stakeholder concerns affecting the solution. **Use when**: things keep coming up that need following — risks, issues, decisions, action items. Most teams use a tool (Jira, Linear) but the discipline is the technique.

## 10.27 Lessons Learned
**Purpose**: Compile and document what worked, what didn't, and what to change next time. **Use when**: ending a phase or project; before starting a similar one; periodically as a continuous-improvement rhythm. Most often skipped despite being cheap.

## 10.28 Metrics and Key Performance Indicators (KPIs)
**Purpose**: Measure performance of solutions, components, and matters of stakeholder interest. **Use when**: evaluating value (KA 8); setting targets; tracking change. KPIs need an owner, a target, a frequency, and a tied-to objective — without all four, they're vanity numbers.

## 10.29 Mind Mapping
**Purpose**: Articulate and capture thoughts, ideas, and information in a non-linear diagram. **Use when**: brainstorming individually or in small groups; structuring messy thinking; quick visual organization.

## 10.30 Non-Functional Requirements Analysis
**Purpose**: Examine requirements about *how well* the solution must perform — performance, reliability, security, usability, maintainability, scalability, compliance. **Use when**: anything beyond pure feature specification; quality attributes matter for any production system.

## 10.31 Observation
**Purpose**: Elicit information by viewing and understanding activities and their context. **Use when**: people can't fully articulate what they do, or what they say they do differs from what they actually do. Underused. Two modes: passive (watch) and active (do alongside).

## 10.32 Organizational Modelling
**Purpose**: Describe roles, responsibilities, and reporting structures, aligned with organizational goals. **Use when**: change involves how people work together, decision rights, or accountability shifts.

## 10.33 Prioritization
**Purpose**: Provide a framework for stakeholders to decide relative importance. **Use when**: you can't do everything (always). Common methods: MoSCoW (Must/Should/Could/Won't), weighted scoring, Kano model, voting, value vs. effort matrix.

## 10.34 Process Analysis
**Purpose**: Assess a process for efficiency, effectiveness, and improvement opportunities. **Use when**: a process is the change focus or a current-state pain point — slow, error-prone, expensive, inconsistent.

## 10.35 Process Modelling
**Purpose**: Show how work is carried out using standardized graphical notation. **Use when**: capturing current-state or future-state process flow; basis for analysis or automation. BPMN is the dominant notation.

## 10.36 Prototyping
**Purpose**: Elicit and validate stakeholder needs through an iterative model of requirements or designs. **Use when**: words aren't enough; stakeholders need to see/touch to react well. Low-fi (paper) to high-fi (functional) — match the fidelity to the question being answered.

## 10.37 Reviews
**Purpose**: Evaluate the content of a work product. **Use when**: any deliverable that needs quality verification or stakeholder confirmation. Walkthroughs, inspections, peer reviews, formal reviews — pick the formality based on stakes.

## 10.38 Risk Analysis and Management
**Purpose**: Identify, analyze, evaluate, and respond to areas of uncertainty that could negatively affect value. **Use when**: planning any non-trivial change. Responses: avoid, mitigate, transfer, accept (or, for opportunities: enhance, exploit, share).

## 10.39 Roles and Permissions Matrix
**Purpose**: Ensure activity coverage by mapping responsibility across roles; surface missing roles or overlaps. **Use when**: defining who does what; access control work; security analysis. Variants: RACI (Responsible/Accountable/Consulted/Informed) and similar.

## 10.40 Root Cause Analysis
**Purpose**: Identify and evaluate the underlying causes of a problem. **Use when**: symptoms are clear but causes aren't, or surface-level fixes keep failing. 5 Whys, fishbone (Ishikawa), Pareto.

## 10.41 Scope Modelling
**Purpose**: Define the nature of one or more limits or boundaries and place elements inside or outside them. **Use when**: boundary debates are stalling work, or stakeholders disagree on what's in/out. Use case diagrams, context diagrams, scope statements.

## 10.42 Sequence Diagrams
**Purpose**: Model the logic of usage scenarios by showing information passed between objects through a scenario. **Use when**: modelling time-ordered interactions between system components; UML standard.

## 10.43 Stakeholder List, Map, or Personas
**Purpose**: Analyze stakeholders and their characteristics to ensure all sources of requirements are identified and stakeholder engagement is well-targeted. **Use when**: starting any initiative; stakeholder shifts mid-engagement; persona work for design.

## 10.44 State Modelling
**Purpose**: Describe and analyze the different possible states of an entity, transitions between them, and what can happen in each state. **Use when**: an entity has meaningful states (orders, accounts, tickets, machines) and transitions matter.

## 10.45 Survey or Questionnaire
**Purpose**: Elicit information from a group in a structured way over a relatively short period. **Use when**: you need breadth not depth; want quantitative responses; can't gather people in real-time. Closed questions (categories) vs. open questions (text).

## 10.46 SWOT Analysis
**Purpose**: Evaluate an organization's Strengths, Weaknesses, Opportunities, and Threats — internal and external. **Use when**: framing strategic conversations; current-state assessment; entry into strategy work. Simple, fast, often shallow if rushed.

## 10.47 Use Cases and Scenarios
**Purpose**: Describe how a person or system interacts with the solution to achieve a goal. **Use when**: capturing user-system interactions; modelling functional behaviour. Use cases describe goal-oriented interactions; scenarios describe specific paths through them.

## 10.48 User Stories
**Purpose**: Represent a small, concise statement of functionality or quality needed to deliver value to a stakeholder. **Use when**: agile delivery; need just-enough specification with conversation around it. Format: As a [role], I want [goal], so that [benefit].

## 10.49 Vendor Assessment
**Purpose**: Assess a vendor's ability to meet commitments regarding delivery and consistent provision of a product or service. **Use when**: solution involves third-party components, services, or partnerships. RFI/RFQ/RFP, due diligence, certification checks.

## 10.50 Workshops
**Purpose**: Bring stakeholders together to collaborate on a predefined goal in a focused, facilitated session. **Use when**: decision needs broad agreement; cross-functional alignment matters; speed of consensus matters more than written documentation. Workshops produce decisions/artefacts; meetings just discuss.

---

## How to recommend techniques

1. **Start from the task.** Use `techniques-to-task-map.md` to find the formal pairings.
2. **Filter by situation.** Of the formally paired techniques, pick 2–4 that fit *this* user's situation (their tools, their stakeholders, their time, their familiarity).
3. **Briefly say why each one fits.** "Workshops because the decision needs cross-functional alignment in real time" beats "workshops are good for collaboration."
4. **Don't list 10.** Curation is the value. The user can always ask for more.
5. **If the user doesn't know a technique, name it but offer to walk through it.** Don't assume familiarity. Don't lecture if they already know it.
