# Perspectives (BABOK Chapter 11)

Five lenses for applying business analysis in particular contexts. They're not mutually exclusive; most real initiatives engage at least one, often two or three. A perspective shapes *who the stakeholders are*, *what techniques fit*, *what outputs look like*, and *how the work is organized*.

Each BABOK perspective has the same internal structure:
1. **Change Scope** — what parts of the enterprise are affected, what kinds of problems get solved
2. **Business Analysis Scope** — who the typical stakeholders are, what the BA's role looks like, what outputs are expected
3. **Methodologies/Approaches/Techniques** (Frameworks for BPM, Reference Models for BA) — domain-specific methods
4. **Underlying Competencies** — which competencies matter most in this perspective
5. **Impact on Knowledge Areas** — how each KA is applied or modified

Pick a perspective explicitly when the answer matters. If the user is building a Scrum-team product, applying the IT perspective alone is wrong — Agile is the right primary lens. If they're rolling out a new ERP, IT + Business Architecture is more appropriate than Agile alone.

---

## 11.1 The Agile Perspective

**When to apply**: iterative delivery, evolving requirements, empowered cross-functional teams, continuous stakeholder collaboration. Scrum, Kanban, XP, SAFe, LeSS, Crystal, FDD, DSDM all fit here.

**Change Scope**: incremental change, often product-focused. Scope is intentionally flexible — emerging clarity is expected, not a failure.

**Business Analysis Scope**:
- *Sponsor*: must understand and accept adaptive planning over predictive
- *Stakeholders*: empowered SMEs and customer reps with continuous engagement
- *BA position*: often shared — Product Owner, business analyst on team, sometimes the customer rep themselves. The BA role is distributed rather than singular
- *Outputs*: lightweight requirements (user stories, acceptance criteria), continuously refined backlog, working software at frequent intervals

**Methodologies/Techniques** (in addition to BABOK's 50): Behaviour-Driven Development (BDD), Story Mapping, Story Decomposition, Persona Analysis, Real Options, Backlog Refinement, Retrospectives, Spike, Velocity tracking, Burndown/Burnup charts, Lightweight Documentation patterns

**Key competencies**: Communication, Interaction Skills (especially facilitation), Adaptability, Continuous Learning, Behavioural Characteristics

**KA impact**:
- KA 3 (Planning): light upfront, continuous re-planning
- KA 4 (Elicitation): conversational, just-in-time, often co-located
- KA 5 (Lifecycle): backlog-centric; just-enough specification before each iteration
- KA 6 (Strategy): vision is set up front; objectives and success measures evolve
- KA 7 (Analysis & Design): minimum viable specification; designs emerge through iteration
- KA 8 (Evaluation): continuous through demos, retrospectives, customer feedback

**Facilitation tips**: many "BABOK vs Agile" debates are false dichotomies — BABOK is a body of knowledge, Agile is a delivery philosophy. The perspective explicitly bridges them. If a user thinks BABOK doesn't apply to their Scrum team, push back gently — the same six KAs apply, just differently expressed.

---

## 11.2 The Business Intelligence Perspective

**When to apply**: data and analytics initiatives — data warehouses, BI platforms, reporting solutions, KPI dashboards, ML/AI initiatives where the value is decision support.

**Change Scope**: typically cross-functional, info-centric. The change is about how the enterprise *uses information* to make decisions.

**Business Analysis Scope**:
- *Sponsor*: usually senior business leader who needs better information for decisions
- *Stakeholders*: data SMEs (source-system owners), business decision-makers, analytics teams, IT (for infrastructure), data governance
- *BA position*: bridges business understanding and technical implementation; often a "BI BA" specialty
- *Outputs*: data requirements, source-to-target mappings, semantic layer specs, KPI definitions, dashboard requirements, governance models

**Methodologies/Techniques**: Dimensional modelling (Kimball), Inmon-style data warehouse modelling, ETL/ELT pipeline design, Data Vault modelling, Master Data Management, Data Quality frameworks, Lineage analysis, Data governance frameworks

**Key competencies**: Analytical Thinking, Business Knowledge (especially industry/domain), Communication (translating business questions to data structures), Tools and Technology (BI/data tools)

**KA impact**:
- KA 4 (Elicitation): heavy use of Document Analysis (existing reports, source systems) and Data Mining
- KA 5 (Lifecycle): emphasis on Data Dictionary and traceability between source data, derived metrics, and business questions
- KA 6 (Strategy): often involves Business Capability Analysis around analytics maturity
- KA 7 (Analysis & Design): Data Modelling, Data Flow Diagrams, Decision Modelling are central
- KA 8 (Evaluation): KPI definition is core; performance of the BI solution itself often blurs with the business performance it measures

**Facilitation tips**: BI BAs often skip business-need clarity in favour of source-system mapping. Push for "what decision will this enable?" before "what tables do we need?". The data may be available — the question is whether anyone will act on the resulting insight.

---

## 11.3 The Information Technology Perspective

**When to apply**: IT-driven change — software delivery, system integration, infrastructure, technical architecture, IT operations.

**Change Scope**: any change where IT capability is the primary lever — building, buying, integrating, replacing, or operating IT systems.

**Business Analysis Scope**:
- *Sponsor*: often IT leadership, sometimes business leadership with strong IT dependency
- *Stakeholders*: IT architects, developers, ops, security, vendors, business users of the IT system
- *BA position*: bridges business and IT; often deeply technical; may overlap with systems analyst, solution architect, or product manager roles
- *Outputs*: functional specs, NFRs, integration specs, data flows, use cases, system context diagrams

**Methodologies**: SDLC variants (waterfall, V-model, iterative, Agile), DevOps, ITIL (for operations), TOGAF (for architecture), CMMI (for process maturity)

**Key competencies**: Tools and Technology (IT tools and concepts), Business Knowledge (to translate), Communication, Analytical Thinking

**KA impact**:
- KA 3 (Planning): often heavy upfront in regulated/safety-critical contexts; lighter in modern product orgs
- KA 4 (Elicitation): heavy use of technical document analysis, system observation, Interface Analysis
- KA 5 (Lifecycle): formal change control; traceability often required (especially in regulated environments)
- KA 7 (Analysis & Design): Use Cases & Scenarios, Sequence Diagrams, Interface Analysis, Non-Functional Requirements Analysis, State Modelling are workhorses
- KA 8 (Evaluation): performance, reliability, security metrics dominate

**Facilitation tips**: IT-perspective work easily becomes technique-driven and loses the business need. The BA's job is to keep the value question central even in deeply technical work. "What problem are we solving for the business?" is the recurring re-anchor.

---

## 11.4 The Business Architecture Perspective

**When to apply**: enterprise-wide change — capability mapping, value streams, organizational design, strategic alignment, business model transformation.

**Change Scope**: large, often spanning multiple business units, products, or processes. Long horizon. Cross-functional impact.

**Business Analysis Scope**:
- *Sponsor*: typically C-suite or strategic-level executive
- *Stakeholders*: enterprise architects, business unit leaders, strategy team, transformation office, sometimes external consultants
- *BA position*: often a "Business Architect" specialty; longer-horizon thinking; works at higher levels of abstraction; less involved in detailed implementation
- *Outputs*: capability maps, value stream maps, enterprise process models, organizational models, target operating models, transformation roadmaps

**Reference Models** (BABOK uses "reference models" here instead of "methodologies"): TOGAF, Zachman Framework, Business Architecture Body of Knowledge (BIZBOK), industry-specific reference models (eTOM for telco, BIAN for banking, ACORD for insurance)

**Key competencies**: Strategic thinking, Business Knowledge (industry, organization), Communication (executive-level), Analytical Thinking

**KA impact**:
- KA 3 (Planning): explicit, multi-year planning horizons
- KA 6 (Strategy): the dominant KA — current/future state, gap analysis, change strategy at enterprise scope
- KA 7 (Analysis & Design): Business Capability Analysis, Organizational Modelling, Process Modelling at high abstraction
- KA 8 (Evaluation): outcomes measured at strategic, not operational, level

**Facilitation tips**: this perspective often drifts into ungrounded abstraction — beautiful capability maps that no one operationalizes. Push for connection to real change initiatives. A capability map is only valuable if it informs decisions about investment, organization, or solution.

---

## 11.5 The Business Process Management Perspective

**When to apply**: process-centric change — process discovery, modelling, improvement, automation, governance. Lean Six Sigma, BPR, BPM platform implementation, RPA, process mining initiatives.

**Change Scope**: usually focused on a value stream or specific process; may span functions but is rarely enterprise-wide in the way Business Architecture is.

**Business Analysis Scope**:
- *Sponsor*: process owner; sometimes COO or operations leadership
- *Stakeholders*: process performers, process owners, IT (if automating), customers (if customer-facing process), compliance/audit
- *BA position*: often a "Process Analyst" specialty; deep familiarity with process notation; may use BPM platforms
- *Outputs*: as-is process models, to-be process models, process improvement recommendations, automation specs, process governance frameworks

**Frameworks** (BPM uses "frameworks" instead of "approaches"): Lean, Six Sigma, Lean Six Sigma, Business Process Reengineering (BPR), Theory of Constraints, Value Stream Mapping, BPMN as the dominant modelling notation, BPM Maturity Models

**Key competencies**: Analytical Thinking (especially data analysis for process performance), Communication, Tools and Technology (BPM/process modelling tools)

**KA impact**:
- KA 4 (Elicitation): heavy Observation, Process Modelling-as-elicitation, Document Analysis
- KA 6 (Strategy): Process Analysis is central to current-state analysis
- KA 7 (Analysis & Design): Process Modelling is *the* modelling technique; Decision Modelling for the rules embedded in processes
- KA 8 (Evaluation): process performance metrics (cycle time, throughput, error rate, cost per transaction) dominate

**Facilitation tips**: BPM work easily becomes "model the process, automate it, declare success" without addressing whether the process should exist at all. Push for the value question — sometimes process improvement is process elimination. Also: the gap between as-is and ideal is usually too large for one project. Identify a meaningful first step rather than the perfect end state.

---

## How to facilitate when applying a perspective

**Most initiatives need more than one.** A new internal app for a sales team might be Agile (delivery) + IT (build) + BPM (the sales process being supported). Name the relevant ones and weight them.

**The Agile perspective is the most-asked.** If the user is on a Scrum/SAFe/Kanban team, Agile is almost always the primary perspective. Don't fight the methodology — adapt the BA work to it.

**Perspectives change technique selection.** A Workshop in an Agile context (a sprint planning session) is different from a Workshop in a Business Architecture context (a multi-day capability mapping offsite). Same technique, different formality, scope, and output.

**Switching perspectives can unstick a conversation.** If a user is stuck in the IT perspective and the underlying problem is organizational, naming the Business Architecture perspective opens up new questions and stakeholders.
