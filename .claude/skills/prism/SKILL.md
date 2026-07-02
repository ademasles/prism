---
name: prism
description: Use when transforming vague requests for decks, presentations, executive updates, memos, strategy briefs, leadership communications, decision support, stakeholder alignment, technical briefings, or workshop plans into audience-outcome strategies, artifact recommendations, drafts, executive reviews, and revised outputs. Use especially when the user asks for a deck but the real need may be decision, alignment, confidence, understanding, or action. Not for broad-audience content such as marketing copy, public announcements, or user/product documentation — PRISM is for communication aimed at an identifiable audience who must decide, align, or shift.
---

# PRISM

PRISM is a **pre-artifact communication-strategy workflow**, not a slide generator. It refracts a messy communication request into structured strategic clarity: **P**erception (read the real situation) → **R**easoning (infer the true objective) → **I**ntent (define the audience outcome) → **S**trategy (choose the medium that maximises it) → **M**essage (draft, review, revise).

Most tools assume `prompt → presentation`. PRISM assumes `messy intent → outcome discovery → audience understanding → decision framing → transformation map → strategy → artifact recommendation → draft → executive review → revision`. The most important work happens **before the first slide exists.** PRISM's job is to help the user avoid building the wrong artifact quickly.

## The governing question

Every step, every section, every recommendation must answer one question:

> **How does this increase the probability that the desired audience outcome will happen?**

If a step, output, or template does not materially improve that probability, simplify it, cut it, or defer it. Beauty is not the goal; outcome probability is.

## When to Use

Trigger PRISM — or invoke it manually as `/prism` — whenever the user asks for any of: a deck, slides, a presentation, an executive update, a narrative, a memo, a brief, a one-pager, a workshop, an executive story, a strategy communication, "something to show leadership," or help getting a decision / alignment / buy-in / sponsorship.

**Never assume the artifact the user named is the correct artifact.** "Create a deck" is a request for an outcome wearing the costume of a format. Reason from the outcome first.

**Out of scope:** broad-audience content — marketing copy, public announcements, user/product documentation, generic "write X." PRISM is for communication aimed at an identifiable audience who must decide, align, or shift. If a request is really one of those, don't run the workflow.

**Output register:** the artifacts PRISM produces are deliverables headed for a real audience — always write them in normal, polished professional English, regardless of any terse or stylistic mode active in the conversation. Only the conversational scaffolding (questions, review commentary) may follow that mode.

## Core workflow

Run these steps in order. Steps 1–4 happen before any drafting.

1. **Restate** the messy request in one sentence, in your own words.
2. **Name what is unclear** — the gaps that would change the recommendation.
3. **Ask 5–7 high-value clarification questions** (see `templates/clarification-questions.md`). Never more.
4. **Set working assumptions** — if the user has not answered, proceed with assumptions **explicitly labelled as assumptions**. Never hide them.
5. **Infer the true objective** — the real audience outcome behind the request (not the topic, not the format).
6. **Classify the communication mode** (see below).
7. **Model the audience** — beliefs, incentives, risk perception, trust, attention (see `references/audience-psychology.md`).
8. **Define the current audience state** — what they believe, fear, misunderstand, resist, or ignore today.
9. **Define the desired future audience state** — what they must believe, feel, and be ready to do.
10. **Identify required belief shifts** — what they must stop and start believing.
11. **Identify required confidence (and trust) shifts** — the gap between "understands" and "confident enough to act."
12. **Name the required decision, action, approval, or alignment** — be specific about who does what.
13. **Anticipate objections and risks** — the reasons they will say no, delay, or disengage.
14. **Identify evidence needs and evidence gaps** — what will earn belief, and what you do not yet have.
15. **Recommend the best artifact** using the decision logic below.
16. **Justify it against the default** — explain why this beats the artifact the user asked for.
17. **Build a structured artifact plan** (see `templates/artifact-plan.md`).
18. **Draft the artifact** using the matching template.
19. **Review it like a senior consulting partner** (see `references/quality-gates.md`) — score it, give a verdict, be blunt.
20. **Revise conditionally** — if the verdict is below *strong*, rewrite the artifact fully in direct response to the review. If it is already *strong* or *executive_ready*, state the verdict and list any residual fixes inline; skip the full rewrite (a rewrite that doesn't raise outcome probability is waste).

## Communication modes

Classify the request into one primary mode. Do not collapse everything into "persuasion."

| Mode | Pick this when the audience must… |
|---|---|
| Education | understand something new before any decision is possible |
| Alignment | converge on a shared view / priority / definition |
| Decision support | approve, fund, sponsor, prioritise, or choose |
| Persuasion | change a held position or preference |
| Escalation | be made aware of a risk/problem they are underweighting |
| Enablement | be equipped to act, teach, or execute |
| Discovery | surface unknowns, options, or requirements together |

The mode determines the medium. Education ≠ decision support ≠ escalation, and they need different artifacts.

## Output structure

Produce these ten sections in order, unless the user explicitly asks for a smaller output:

1. **Clarification Questions**
2. **Working Assumptions**
3. **Strategic Communication Brief** (see `templates/strategic-communication-brief.md`)
4. **Audience Transformation Map** (see `templates/audience-transformation-map.md`)
5. **Recommended Artifact** (see `templates/artifact-recommendation.md`)
6. **Artifact Plan** (see `templates/artifact-plan.md`)
7. **First Draft** (use the matching artifact template)
8. **Executive Review** (see `templates/executive-review.md`)
9. **Revised Output** (see `templates/revised-output.md`) — full rewrite only if the review verdict is below *strong*; otherwise state the verdict and note residual fixes inline
10. **Next Actions**

Lead with the recommendation. Never bury it.

**Right-size the response.** The ten sections are the full workflow, not a minimum. Match effort to the request:
- If the request is already specific and answered, skip the questions, state assumptions inline, and go straight to Brief → Recommendation → Draft → short Review.
- If the ask is small (a quick memo, a single one-pager), collapse to the essentials — don't manufacture a transformation map for a request that doesn't need one.
- If the user already answered the clarifying questions (in the request or a prior turn), **do not re-ask** — use their answers and proceed.
Running the full machine on a trivial ask violates the governing question as surely as skipping strategy on a big one.

## Artifact decision logic

**Do not default to a deck. Do not default to PowerPoint.** Recommend from the audience outcome:

| If the audience must… | Recommend | Template |
|---|---|---|
| approve, fund, sponsor, prioritise, choose, decide | **Decision memo** | `templates/decision-memo.md` |
| grasp the situation fast, at exec altitude | **Executive one-pager** | `templates/executive-one-pager.md` |
| absorb strategic context, direction, narrative | **Strategy brief** | `templates/strategy-brief.md` |
| understand architecture, trade-offs, systems, risk | **Technical briefing** | `templates/technical-briefing.md` |
| co-create, align, resolve conflict, build buy-in | **Workshop plan** | `templates/workshop-plan.md` |
| be carried through a live story / facilitation | **Presentation outline** | `templates/presentation-outline.md` |
| (a slide artifact is genuinely, specifically required) | **Vendor-agnostic Deck IR** | `templates/deck-ir.md` |

Often the answer is a **primary artifact plus a secondary** (e.g. decision memo now, presentation outline for the meeting). Recommend the primary first.

When a deck is genuinely warranted, produce a **Deck IR** (intermediate representation), never a PPTX file. Each slide specifies: slide number, role, purpose, audience question answered, objection addressed, core message, evidence, visual intent, speaker notes. See `references/artifact-types.md` and `templates/deck-ir.md`.

## Clarification discipline

- Ask **5–7** high-value questions, not 20. Each question must be one whose answer would change the recommendation.
- **Ask, then stop.** On a vague or underspecified request, present the questions as a plain numbered list, then **end the turn and wait** for answers before drafting. Do not self-answer with assumptions in the same pass.
- **One-pass only when warranted.** Proceed straight through (self-answering gaps with labelled assumptions) only if the request is already specific, the user has already answered the questions, or the user tells you to just proceed. Never re-ask what the user has already answered.
- If the user answers, use their answers.
- If the user does not answer, proceed — but every gap becomes a **clearly labelled Working Assumption**. Never present an assumption as a fact.

## Quality gates (summary)

Review every draft against 14 gates and score 10 dimensions 1–5. Full rubric and worked examples: `references/quality-gates.md`.

The 14 gates, in short: objective clear · audience specific · decision/action explicit · current + desired states defined · belief shifts clear · confidence/trust gaps addressed · objections addressed · evidence sufficient · evidence gaps named honestly · artifact justified · narrative logical · output concise · exec-readable fast · **raises outcome probability**.

Scored dimensions: objective clarity · audience specificity · decision explicitness · objection coverage · evidence strength · narrative logic · medium fit · concision · executive readability · audience-transformation strength.

Verdict from the average score:

- `< 2.5` → **weak**
- `2.5–3.5` → **usable**
- `3.5–4.5` → **strong**
- `≥ 4.5` → **executive_ready**

The Executive Review must be direct and useful, not polite. Name what is strategically weak, unclear, unsupported, too generic, or missing — and what must be fixed before this reaches leadership.

## Anti-patterns

- Do not blindly create slides, or recommend PowerPoint by default.
- Do not treat "inform leadership" as a sufficient objective — that is a topic, not an outcome.
- Do not produce a generic 10-slide outline unless a deck is truly justified.
- Do not invent evidence, or present assumptions as facts. In drafts, any claim without a real source becomes a bracketed `[EVIDENCE NEEDED: …]` placeholder — never a confident assertion. Use labelled illustrative figures ("illustrative — replace with real data") only when the user explicitly asks for a worked example.
- Do not use empty consulting language ("leverage synergies," "unlock value") in place of specifics.
- Do not overproduce; do not ask 20 questions; do not bury the recommendation.
- Do not skip objections, and do not skip the decision or action.
- Do not confuse topic with outcome, or artifact with objective.
- Do not treat "PRISM" as cosmetic branding — actually refract vague intent into structured clarity.

## Reference & template index

**References** (read when you need depth):
- `references/schema.md` — the canonical conceptual schema behind every section. Read to keep fields consistent.
- `references/quality-gates.md` — full gate definitions, 1–5 anchors, verdict rules, weak-vs-strong examples. Read before every Executive Review.
- `references/artifact-types.md` — when to use / avoid each artifact, structure, failure mode. Read when choosing or justifying an artifact.
- `references/audience-psychology.md` — how to model audience state + diagnostic questions. Read at steps 7–13.
- `references/examples.md` — five worked requests → recommendations. Read to calibrate.

**Templates** (fill when producing that section/artifact):
- `templates/clarification-questions.md` · `templates/strategic-communication-brief.md` · `templates/audience-transformation-map.md` · `templates/artifact-recommendation.md` · `templates/artifact-plan.md`
- Artifacts: `templates/decision-memo.md` · `templates/executive-one-pager.md` · `templates/strategy-brief.md` · `templates/technical-briefing.md` · `templates/workshop-plan.md` · `templates/presentation-outline.md` · `templates/deck-ir.md`
- Review: `templates/executive-review.md` · `templates/revised-output.md`
