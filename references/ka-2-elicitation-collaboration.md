# KA 4: Elicitation and Collaboration

The work of drawing information out of people, documents, and experiments — and managing the human collaboration around that work. This is "discovery" in agile-speak, "requirements gathering" in older PM-speak, and "research" in design-speak — but BABOK separates the *act of getting information* (Elicitation) from the *act of confirming and communicating it* (Collaboration), which is a useful distinction.

The five tasks are concurrent and reentrant, not a sequence. You'll often loop through them many times in a single engagement.

## BACCM mapped to this KA

When you're inside elicitation work, the six core concepts show up like this:

- **Change**: elicit the characteristics of the change and stakeholder concerns about it
- **Need**: elicit, confirm, and communicate the underlying needs (which keep evolving)
- **Solution**: elicit and confirm desired characteristics of proposed solutions
- **Stakeholder**: actively manage the collaboration — different stakeholders show up at different times in different roles
- **Value**: collaborate with stakeholders to assess and confirm the value of what's been elicited
- **Context**: surface the contextual factors that affect the change

## The five tasks

| Task | Purpose | Output |
|---|---|---|
| **4.1 Prepare for Elicitation** | Scope the activity, pick techniques, line up resources | Elicitation Activity Plan |
| **4.2 Conduct Elicitation** | Draw out, explore, and identify information relevant to the change | Elicitation Results (unconfirmed) |
| **4.3 Confirm Elicitation Results** | Check what was gathered for accuracy and consistency | Elicitation Results (confirmed) |
| **4.4 Communicate Business Analysis Information** | Get the right information to the right stakeholders at the right time | Business Analysis Information (communicated) |
| **4.5 Manage Stakeholder Collaboration** | Maintain trust-based, productive relationships with stakeholders | Stakeholder Engagement |

---

## 4.1 Prepare for Elicitation

**Purpose**: Understand the scope of the elicitation activity, select appropriate techniques, and plan for supporting materials and resources.

**Inputs you need before starting**:
- A clear sense of the needs being explored and what's already known (Business Analysis Information)
- The Stakeholder Engagement Approach from KA 3 (who, how, when)

**Key elements to walk through**:
- **Understand the scope**: what business outcomes does this elicitation feed? What's in and out of bounds?
- **Select techniques**: pick from the 50 — usually 2–4 in combination. Brainstorming + Workshops, or Document Analysis + Interviews, etc. Match technique to the kind of information needed.
- **Set logistics**: location, timing, duration, participants, materials, tools, recording approach
- **Secure supporting materials**: pre-read, templates, reference docs, prototypes, anything that primes participants

**Techniques most often used here** (from BABOK's formal mapping): Brainstorming, Document Analysis, Estimation, Interviews, Mind Mapping, Risk Analysis & Management, Stakeholder List/Map/Personas

**Stakeholders to involve**: Domain SMEs (to scope the right info), Sponsor (to authorize), End User (if their voice is the target), Project Manager (to align on timing)

**Output**: Elicitation Activity Plan — describes what's being elicited, from whom, how, with what materials, on what schedule

**Facilitation tips**: people often skip this step and go straight to Conduct. The cost shows up later as wasted sessions and re-work. A 20-minute Prepare conversation is almost always worth it. If the user is heading into a workshop or interview unprepared, slow them down here first.

---

## 4.2 Conduct Elicitation

**Purpose**: Draw out, explore, and identify information relevant to the change.

**Three kinds of elicitation**:
- **Collaborative**: direct interaction with stakeholders — Interviews, Workshops, Focus Groups
- **Research**: studying materials and existing data — Document Analysis, Data Mining, Benchmarking & Market Analysis
- **Experiments**: controlled tests when the information can't be drawn from people or docs — Observation, Prototyping, proofs of concept

Most real elicitation activities mix all three.

**Inputs you need**: the Elicitation Activity Plan from 4.1; existing BA information; the Stakeholder Engagement Approach; supporting materials

**Key elements**:
- **Guide the activity**: keep it focused on the agreed scope and outcomes; in-the-moment decisions about scope drift are part of the work
- **Capture outcomes**: record what was elicited, in a form that supports the next step (often that's confirmation in 4.3 or modelling in KA 7)

**Techniques formally paired with this task** (a long list — pick 2–4): Benchmarking & Market Analysis, Brainstorming, Business Rules Analysis, Collaborative Games, Concept Modelling, Data Mining, Data Modelling, Document Analysis, Focus Groups, Interface Analysis, Interviews, Mind Mapping, Observation, Process Analysis, Process Modelling, Prototyping, Survey/Questionnaire, Workshops

**Stakeholders**: Customer, Domain SME, End User, Implementation SME, Sponsor, plus any stakeholder with relevant knowledge

**Output**: Elicitation Results (unconfirmed) — captured information, in whatever format the activity produced

**Facilitation tips**: when you're coaching someone *through* an elicitation session, the technique selection matters more than execution mechanics. Most people default to Interviews when Observation or a Workshop would be richer. Push back on technique defaults if they seem reflexive. Also: in-the-moment scope management is a skill — when stakeholders go off-topic, the BA's job is to recognize whether the new direction is more valuable than the planned one.

---

## 4.3 Confirm Elicitation Results

**Purpose**: Check the gathered information for accuracy and consistency *before* anyone commits resources to acting on it.

This is a lighter review than the Verify/Validate work in KA 7 — it's a quality gate on the elicitation itself, not on the requirements that emerge from it.

**Inputs**: Elicitation Results (unconfirmed) from 4.2

**Key elements**:
- **Compare against source**: did we capture what the source actually said?
- **Compare against other elicitation results**: are the multiple sources consistent? Where they disagree, the inconsistency itself is a finding worth surfacing

**Techniques**: Document Analysis, Interviews, Reviews, Workshops

**Stakeholders**: Domain SMEs (to confirm correctness), any stakeholder whose input is being confirmed

**Output**: Elicitation Results (confirmed)

**Facilitation tips**: this step gets skipped most often. It feels redundant — "I already heard them say it." But errors, omissions, and contradictions are routinely caught here. If the user is rushing past this, ask "what would it cost if this turned out to be wrong?" — usually that surfaces the value.

---

## 4.4 Communicate Business Analysis Information

**Purpose**: Get business analysis information to stakeholders in a form they can actually use, at a time when it's useful.

**Inputs**: Business Analysis Information (whatever needs communicating); the Stakeholder Engagement Approach

**Key elements**:
- **Determine objectives and format**: what does the audience need to do with this? Different audiences need different formats — execs want summary + recommendation; engineers want detailed specs; users want examples
- **Communicate the BA package**: deliver it. Could be a document, a workshop, an email, a slide deck, a model walkthrough
- **Confirm understanding**: don't assume "sent" = "received" = "understood." Validate that the intended message landed

**Techniques**: Interviews, Reviews, Workshops; plus formats like User Stories, Use Cases & Scenarios, Mind Mapping, Process Modelling, Data Modelling depending on what's being communicated

**Stakeholders**: anyone who needs the information — varies entirely by what's being communicated

**Output**: Business Analysis Information (communicated)

**Facilitation tips**: communication failures masquerade as BA failures all the time. If someone says "they didn't deliver what we asked for," ask first whether the ask was communicated in a form that audience could use. Format matters as much as content.

---

## 4.5 Manage Stakeholder Collaboration

**Purpose**: Build and maintain trust-based, productive working relationships with stakeholders. This isn't a one-time task; it runs continuously alongside everything else.

**Inputs**: Stakeholder Engagement Approach (from KA 3); BA Performance Assessment

**Key elements**:
- **Gain agreement on commitments**: stakeholders are committing time and attention. Make the ask explicit early, even if informal.
- **Monitor stakeholder engagement**: are the right people still showing up? Are attitudes holding or improving? Are commitments being honored?
- **Collaboration**: support free-flowing, bi-directional communication. Stakeholders need to feel heard, not just polled.

**Techniques**: Collaborative Games, Lessons Learned, Risk Analysis & Management, Stakeholder List/Map/Personas

**Stakeholders**: all of them, but especially Sponsor (to keep authority engaged) and Domain SMEs (the ones whose time you're consuming most)

**Output**: Stakeholder Engagement — a sustained working relationship, not a document

**Facilitation tips**: this is where BA work succeeds or fails. The user might not see it as a "task" — it's "just relationships." Surface it explicitly. Bad signs to flag: SMEs going dark, sponsors becoming hard to reach, approvals taking longer than they used to, stakeholders contradicting each other in writing but not in meetings. Each of these is a managed-collaboration failure mode.

---

## How to facilitate this KA

**The biggest mistake**: jumping straight to 4.2 Conduct without doing 4.1 Prepare. The second-biggest: skipping 4.3 Confirm. Both look like time-saving moves; both create rework.

**Technique selection is the real expertise**. Anyone can run an interview. The hard skill is knowing *when* an interview is wrong and a workshop is right. Push the user to articulate why they picked the techniques they picked.

**Mode guidance**:
- **Quick**: walk the user through "do you know what you're trying to elicit, who from, how, and how you'll confirm it?" That's a Quick-mode pass through 4.1 + 4.2 + 4.3 in 5 minutes.
- **Working**: pick one task and run it end-to-end. Most common Working-mode targets are 4.1 (prep for an upcoming session) or 4.2 (conduct one specific session live).
- **Full**: design and run a multi-session elicitation campaign — Prepare, Conduct (multiple), Confirm, Communicate, Manage Collaboration — across all the stakeholder groups. This is the bulk of a typical discovery phase.
