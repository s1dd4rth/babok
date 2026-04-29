# babok-facilitator

A Claude Agent Skill for facilitating business analysis work using **IIBA's BABOK Guide v3**.

Walks you through BA work the way a thoughtful BA peer would — picks the right depth, uses BABOK's structure to keep nothing dropped, recommends techniques that fit your situation rather than reciting the textbook.

## What it covers

- **6 Knowledge Areas, 30 tasks** — Planning & Monitoring, Elicitation & Collaboration, Requirements Lifecycle Management, Strategy Analysis, Requirements Analysis & Design Definition, Solution Evaluation
- **All 50 techniques** from BABOK Chapter 10, with purposes and when-to-use guidance
- **All 5 perspectives** — Agile, Business Intelligence, Information Technology, Business Architecture, Business Process Management
- **The BACCM™ frame** as the always-on diagnostic — Change, Need, Solution, Stakeholder, Value, Context
- **The 6 underlying competencies** for BA capability and role design
- **BABOK Appendix B** as a working cross-reference — both task→techniques and technique→tasks

## How it works

Three engagement modes the skill picks based on your situation:

- **Quick (5–10 min)** — gut-check via the BACCM lens, name the relevant Knowledge Area(s), recommend 1–3 techniques, flag a perspective if obvious. The default for "where do I start?" or "is this approach right?" questions.
- **Working (30–60 min)** — runs *one* task end-to-end using BABOK's 8-section structure. Produces real artefacts: a stakeholder map, a prioritized list, a model sketch, a draft requirement set.
- **Full (multi-session)** — walks a whole knowledge area or chained set of tasks, with a perspective applied throughout. For real BA engagements.

It coaches rather than recites. It respects your time. It uses BABOK's structure as a checklist (so nothing gets dropped), not as a script.

## Install

```bash
npx skills add s1dd4rth/babok-skill
```

(Or download the `.skill` file from Releases and load it in your Claude environment.)

## Try it

After installing, try prompts like:

- "I'm starting a discovery for a new internal tool. Where do I begin?"
- "Help me prioritize this backlog of 30 features — stakeholders disagree."
- "We deployed our portal 90 days ago and adoption is below target. What now?"
- "Translate what my Scrum team is doing into BABOK terms."
- "What technique should I use for [your problem]?"

The skill triggers on BA-shaped problems even when you don't say "BABOK".

## Structure

```
babok-skill/
├── SKILL.md                                  ← orchestrator (lean)
└── references/
    ├── ka-1-planning-monitoring.md           ← 5 tasks
    ├── ka-2-elicitation-collaboration.md     ← 5 tasks
    ├── ka-3-requirements-lifecycle.md        ← 5 tasks
    ├── ka-4-strategy-analysis.md             ← 4 tasks
    ├── ka-5-requirements-analysis-design.md  ← 6 tasks
    ├── ka-6-solution-evaluation.md           ← 5 tasks
    ├── techniques-catalog.md                 ← all 50 techniques
    ├── perspectives.md                       ← all 5 perspectives
    ├── competencies.md                       ← 6 underlying competencies
    └── techniques-to-task-map.md             ← Appendix B cross-reference
```

The orchestrator is intentionally lean. Reference files load only when a piece of the work is actively being walked through.

## Coexists with

- **[ooux-skill](https://github.com/s1dd4rth/ooux-skill)** — BABOK is the wider business-analysis frame; OOUX is one structured approach for the modelling work that happens inside BABOK's *Requirements Analysis & Design Definition* knowledge area. Use whichever fits the moment; they don't compete.

## Credits

- Source methodology: [IIBA BABOK Guide v3](https://www.iiba.org/career-resources/a-business-analysis-professionals-foundation-for-success-the-babok-guide/) (2015), © IIBA
- The skill paraphrases and applies the methodology — it doesn't reproduce the source. For full BABOK content, get the guide from IIBA.
- Built using the Anthropic [skill-creator](https://github.com/anthropics/skills) framework.

## License

MIT — see [LICENSE](./LICENSE)
