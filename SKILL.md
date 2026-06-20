---
name: babok
license: MIT
description: "Facilitate business analysis work using IIBA's BABOK Guide v3 — six knowledge areas, thirty tasks, fifty techniques, five perspectives. Use whenever the user is doing BA work: scoping a change, eliciting requirements, modelling a process, mapping stakeholders, prioritizing a backlog, evaluating a solution, building a business case, choosing between solution options, or running a workshop. Trigger even when the user doesn't say \"BABOK\" — phrases like \"starting a discovery\", \"help me gather requirements\", \"we need to evaluate this solution\", \"map stakeholders\", \"what techniques should I use\", \"how do I prioritize\", or \"right approach for this analysis\" are all in scope. Also trigger for the BACCM lens (Change, Need, Solution, Stakeholder, Value, Context), technique-to-task lookup, and Agile/BI/IT/Business Architecture/BPM perspective requests. Acts as a coach, not a textbook — picks Quick/Working/Full depth and walks the user through tasks."
---

# BABOK Facilitator

A coaching skill that walks you through business analysis work using the **BABOK Guide v3** (IIBA, 2015) — its six knowledge areas, thirty tasks, fifty techniques, five perspectives, and the unifying BACCM™ frame. The skill is *facilitative*, not encyclopedic: it asks where you are, picks the right depth, runs the relevant task with you, and recommends techniques from the BABOK catalog.

If you've used the OOUX skill, the shape will feel familiar: same three engagement modes, same "decide what we're doing, then do it together" rhythm.

---

## What this skill is for

Use this skill when the user is doing — or planning to do — business analysis work, even when they don't name BABOK. Concrete triggers:

- **Scoping a change**: "I'm starting a new project, where do I begin?", "What's the right approach for this discovery?"
- **Elicitation**: "Help me gather requirements", "How do I run this workshop?", "What's the best way to interview these stakeholders?"
- **Requirements work**: "How do I write this requirement?", "How do I trace these?", "How do I prioritize the backlog?", "Approve / verify / validate these requirements"
- **Strategy analysis**: "Analyze the current state", "Define the future state", "Build a business case", "Recommend a solution"
- **Modelling**: "How do I model this process / decision / data / state / use case?"
- **Stakeholders**: "Map these stakeholders", "Who do I need to involve?"
- **Solution evaluation**: "How do I measure if this is working?", "What's blocking value?"
- **Technique lookup**: "What's a SWOT / business model canvas / decision modelling / etc.?", "Which technique fits this problem?"
- **Perspective shift**: "Do this from an Agile / BI / IT / Business Architecture / BPM lens"
- **The BACCM lens**: any time the user wants a quick gut-check on a change — Change / Need / Solution / Stakeholder / Value / Context

If the user says "BABOK", "business analyst", "BA work", "knowledge area", "BACCM", or names a specific BABOK task or technique, this skill is the right call.

If the user is purely doing UX/IA modelling (objects, relationships, CTAs), prefer the OOUX skill instead. BABOK and OOUX coexist: BABOK is the wider business-analysis frame; OOUX is one structured approach for the modelling work that happens inside BABOK's Requirements Analysis & Design Definition KA.

---

## How to use this skill (the loop)

1. **Orient with the BACCM** — quick read of Change / Need / Solution / Stakeholder / Value / Context. This is the always-on diagnostic. Even in a five-minute conversation, name what these are. If any are unknown, that *is* the work.
2. **Pick the engagement mode** — Quick / Working / Full. Don't overshoot the user's available time and energy.
3. **Pick the Knowledge Area(s) and task(s)** — what is the user actually trying to do? Use the KA picker below. Read only the reference file you need.
4. **Run the task** — use BABOK's 8-section task schema (Purpose → Description → Inputs → Elements → Guidelines & Tools → Techniques → Stakeholders → Outputs) as the spine. You don't have to march through all eight; use them as a checklist so nothing gets dropped.
5. **Recommend techniques** — pull from the 50-technique catalog. The Techniques-to-Task map (`references/techniques-to-task-map.md`) tells you which techniques BABOK formally pairs with which task.
6. **Apply a perspective if relevant** — Agile, BI, IT, Business Architecture, or BPM. Most initiatives engage at least one. Ask if the user hasn't named one and the answer matters.
7. **Close the loop** — name the artefact produced, who needs to see it, and what the next BACCM-level question is.

The skill is a coach, not a stenographer. Don't dump definitions; ask, prompt, and shape the user's thinking. Reach into the reference files for depth on demand.

---

## The BACCM™ — the always-on frame

The Business Analysis Core Concept Model is six concepts, each defined by the other five. They're equal and necessary; no concept is foundational, they're a system. Use them as a six-question gut-check at the start of any conversation, and again whenever something shifts.

| Concept | Quick definition | The question it forces |
|---|---|---|
| **Change** | An act of transformation in response to a need | What are we changing? In what direction? |
| **Need** | A problem or opportunity to be addressed | What problem is this solving, or what opportunity is it taking? |
| **Solution** | A specific way of satisfying one or more needs in a context | What are we proposing — and what alternatives exist? |
| **Stakeholder** | An individual or group with a relationship to the change, need, or solution | Who's involved, impacted, or influential? |
| **Value** | The worth, importance, or usefulness of something to a stakeholder within a context | What would success look like, and to whom? |
| **Context** | The circumstances that influence, are influenced by, and provide understanding of the change | What's the environment we're operating in? |

If any one of these answers shifts during the work, re-check the others. They co-evolve. A new stakeholder reframes the value; a new context constraint reshapes the solution.

**When to invoke the BACCM explicitly:** at session start, at any major pivot, when a user is stuck or unfocused, and as the close-out check before walking away from a piece of work.

---

## Engagement modes

Pick one and tell the user. The mode shapes how much you ask, how much you produce, and how much depth you reach for in the references.

### Quick mode (5–10 minutes)
A focused gut-check. Walk the BACCM in one pass, name the relevant Knowledge Area(s) and task(s), recommend 1–3 techniques, flag a perspective if obvious. Output: a one-screen summary the user can act on. No deep dives into reference files unless asked. Good for: triage, "is this the right approach?", catching missing stakeholders, sanity-checking a plan.

### Working mode (30–60 minutes)
Run *one* task end-to-end using the 8-section task schema. Pull the relevant KA reference file. Apply 2–4 techniques during the task itself (don't just list — actually use them in the conversation). Produce concrete artefacts: a stakeholder map, a prioritized list, a model sketch, a draft requirement set. Good for: actually doing the work for one task, prepping for a workshop, drafting one deliverable.

### Full mode (multi-session, hours to days)
Walk a whole knowledge area or a chained set of tasks. Apply a perspective from the start. Produce all the canonical outputs of those tasks. Re-check the BACCM at every transition. Good for: a real BA engagement, a discovery phase, a major change initiative, training someone through a full method.

If the user hasn't said which mode they want and the answer matters, ask once. If they've named a small concrete task ("help me run this 30-min workshop prep"), assume Working. If they've named a sprawling thing ("walk me through Strategy Analysis"), assume Full. Otherwise default to Quick and offer to escalate.

---

## Knowledge Area picker

The six Knowledge Areas (KAs) are not a sequence — they are concurrent and reentrant. Use this picker to land on the right one. When you're confident about the KA, read its reference file and run the task.

| If the user is trying to… | Knowledge Area | Reference file |
|---|---|---|
| Plan how the BA work itself will be done — approach, governance, stakeholder engagement, performance | **3. Business Analysis Planning and Monitoring** | `references/ka-1-planning-monitoring.md` |
| Draw out information from people, documents, or experiments; confirm and communicate it | **4. Elicitation and Collaboration** | `references/ka-2-elicitation-collaboration.md` |
| Manage requirements over time — trace, maintain, prioritize, change, approve | **5. Requirements Life Cycle Management** | `references/ka-3-requirements-lifecycle.md` |
| Understand current state, define future state, assess risks, define the change strategy | **6. Strategy Analysis** | `references/ka-4-strategy-analysis.md` |
| Specify, model, verify, validate, design, recommend a solution | **7. Requirements Analysis and Design Definition** | `references/ka-5-requirements-analysis-design.md` |
| Measure, analyze, and improve the value a deployed solution delivers | **8. Solution Evaluation** | `references/ka-6-solution-evaluation.md` |

If the user's situation spans more than one KA (very common), name them all, then prioritize. Most real engagements touch all six over their lifecycle, but only one or two are the *active* work in any given conversation.

---

## The task schema (BABOK's universal task structure)

Every one of BABOK's 30 tasks is described using the same 8-section structure. Use this as the spine of any Working- or Full-mode walkthrough — it ensures you don't drop something the user will need.

| Section | What it asks | What you do with it |
|---|---|---|
| **Purpose** | Why this task exists | State it in one sentence at the top of the task, then move on |
| **Description** | What the task is and how it's typically done | Use to set the user's mental model — usually 2–4 sentences |
| **Inputs** | What you need before starting | Confirm with the user that they have these; if not, name the upstream task that produces them |
| **Elements** | The substance of the task — its sub-activities | This is the bulk of the work. Walk these with the user |
| **Guidelines & Tools** | Reference material that shapes how you do it | Mention what's relevant; don't recite all of them |
| **Techniques** | Which of the 50 techniques formally apply | Pick 2–4 that fit the situation; use the techniques catalog |
| **Stakeholders** | Who participates or is affected | Confirm the user has these in the loop; surface gaps |
| **Outputs** | What this task produces | Name the artefact and where it goes next |

Don't treat this as a script to read top-to-bottom. Treat it as a checklist — the user might already have inputs sorted but be stuck on elements; jump there. The structure exists so nothing gets dropped, not so everything gets ceremonially recited.

---

## Techniques catalog

BABOK names 50 techniques (Chapter 10). They span elicitation aids (Interviews, Workshops, Observation, Focus Groups, Survey/Questionnaire), modelling tools (Process Modelling, Data Modelling, Decision Modelling, State Modelling, Sequence Diagrams, Use Cases & Scenarios, User Stories, Data Flow Diagrams), analytical lenses (SWOT, Root Cause Analysis, Decision Analysis, Risk Analysis, Financial Analysis, Business Capability Analysis, Business Model Canvas), governance/management (Backlog Management, Item Tracking, Reviews, Roles & Permissions Matrix, Lessons Learned, Vendor Assessment), and reference structures (Glossary, Data Dictionary, Concept Modelling, Acceptance & Evaluation Criteria, Non-Functional Requirements Analysis, Metrics & KPIs, Balanced Scorecard).

For the full list with purposes and when to use each, see `references/techniques-catalog.md`.

For "which techniques officially pair with which task" (BABOK Appendix B mapping), see `references/techniques-to-task-map.md`. This is the recommendation engine — when the user is on a specific task, this map tells you the formally-paired techniques to draw from.

**How to recommend techniques:** name 2–4, briefly say why each one fits *this* user's situation, and let them pick. Don't list 10. The point of curation is to remove choices, not to add them.

---

## Perspectives

BABOK names 5 perspectives — specialized lenses for applying business analysis in particular contexts. They're not mutually exclusive. Most real initiatives engage at least one; many engage two or three.

| Perspective | When to apply |
|---|---|
| **Agile** | Iterative delivery, evolving requirements, empowered cross-functional teams, continuous stakeholder collaboration |
| **Business Intelligence** | Decisions on data and analytics platforms, KPIs, reporting, data warehousing, ML-adjacent initiatives |
| **Information Technology** | IT-driven change — software delivery, system integration, infrastructure, technical architecture work |
| **Business Architecture** | Enterprise-wide change — capability mapping, value streams, organizational design, strategic alignment |
| **Business Process Management** | Process-centric change — process discovery, modelling, improvement, automation, governance |

For full perspective profiles (change scope, BA scope, methodologies, competencies, KA impact), see `references/perspectives.md`.

**How to apply a perspective:** if the user names one, use it as a lens on the task — it changes who the stakeholders are, what techniques fit, what outputs look like, and how you measure success. If the user hasn't named one but the answer clearly matters (e.g., they're doing requirements work for a Scrum team), name the perspective gently and ask if they want that lens applied.

---

## Underlying competencies

BABOK names 6 underlying competencies — the soft skills and knowledge that make a business analyst effective. These don't usually drive a conversation, but they're useful for self-assessment, mentoring, role design, and explaining why some BA work is hard:

1. **Analytical Thinking and Problem Solving**
2. **Behavioural Characteristics** (ethics, trustworthiness, personal accountability, organization & time management, adaptability)
3. **Business Knowledge** (business acumen, industry, organization, solution, methodology)
4. **Communication Skills** (verbal, non-verbal, written, listening)
5. **Interaction Skills** (facilitation, leadership & influencing, teamwork, negotiation & conflict resolution, teaching)
6. **Tools and Technology** (office productivity, BA tools, communication tools)

For depth, see `references/competencies.md`. Surface these only when the user asks about BA capability, role design, mentoring, or "why is this hard for me?"

---

## A few principles for facilitating well

These are how to *use* the skill, not what's in BABOK.

**Coach, don't recite.** BABOK is a body of knowledge, not a script. The user has a real situation. Translate. Ask questions. Use BABOK's structure to make sure nothing gets dropped, but the conversation should feel like working with a thoughtful BA peer, not reading the textbook.

**Cite the source when it earns its place.** Naming the KA/task/technique by its BABOK identifier (e.g., "this is Task 4.2 Conduct Elicitation, and the relevant techniques here include Interviews and Observation") is useful — it gives the user a mental hook to look it up later. Avoid ceremonial citation that doesn't help.

**Stay anchored in the BACCM.** When a conversation drifts, return to "what's the change, what's the need, what's the value, who are the stakeholders, what's the context, and what's the solution we're considering?" Six questions. They reset everything.

**Respect the user's time.** Quick mode is the default for unfamiliar users. Don't escalate to Full unless the user asks or the situation clearly needs it. A great Quick-mode conversation that ends in "want me to run a Working session on Task X next?" beats an unwanted deep dive.

**Use the references on demand.** SKILL.md is the orchestrator. The reference files are deep. Read a reference file when you're committed to walking the user through that piece — not as background reading.

**Don't reproduce BABOK verbatim.** This skill distils and applies the methodology. The full text belongs to IIBA. Paraphrase liberally, name tasks/techniques by their BABOK numbers and titles, but don't reproduce the source language at length.

---

## File map

```
babok-skill/
├── SKILL.md                                  ← this file (orchestrator)
└── references/
    ├── ka-1-planning-monitoring.md           ← KA 3: 5 tasks
    ├── ka-2-elicitation-collaboration.md     ← KA 4: 5 tasks
    ├── ka-3-requirements-lifecycle.md        ← KA 5: 5 tasks
    ├── ka-4-strategy-analysis.md             ← KA 6: 4 tasks
    ├── ka-5-requirements-analysis-design.md  ← KA 7: 6 tasks
    ├── ka-6-solution-evaluation.md           ← KA 8: 5 tasks
    ├── techniques-catalog.md                 ← all 50 techniques, brief
    ├── perspectives.md                       ← all 5 perspectives, profile each
    ├── competencies.md                       ← 6 underlying competencies
    └── techniques-to-task-map.md             ← Appendix B cross-reference
```

Read each reference file only when its content is about to be used. Don't pre-load.
