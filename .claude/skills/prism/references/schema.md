# PRISM Schema

The canonical set of concepts PRISM reasons about. Every section of the output maps back to these fields. Keep them consistent across the brief, the transformation map, the recommendation, and the review. This is a thinking schema, not a data model — plain language, no tooling required.

## Fields

| Field | Question it answers | Notes |
|---|---|---|
| **Raw request** | What did the user literally ask for? | Quote or paraphrase faithfully. Preserve the format they named (deck, memo…) so you can later justify diverging from it. |
| **True objective** | What audience outcome is actually needed? | The outcome behind the request. Never a topic ("AI"), never a format ("a deck"). A verb applied to a specific audience: *"get the ExCo to fund a bounded pilot."* |
| **Communication mode** | Which mode dominates? | One of: education, alignment, decision support, persuasion, escalation, enablement, discovery. Pick one primary; note a secondary if real. |
| **Audience** | Exactly who receives this? | Name roles, seniority, number, and who actually decides. "Leadership" is too vague — CFO vs CTO vs the board need different things. |
| **Current state** | What does the audience believe / fear / ignore today? | The starting point of the transformation. Be honest and specific. |
| **Desired future state** | What must they believe, feel, and be ready to do? | The end point. Must be reachable from the current state via this artifact. |
| **Decision / action required** | What specifically must happen as a result? | Approve, fund, prioritise, assign, endorse, change course. Name the owner and the ask size. |
| **Belief shifts** | What must they stop and start believing? | Framed as stop-believing → start-believing pairs. |
| **Confidence shifts** | What raises them from "understand" to "confident enough to act"? | The confidence gap is where most communications fail silently. |
| **Trust shifts** | Whose credibility must rise, and how? | Only if trust is a live blocker (new team, prior failure, external source). |
| **Objections** | Why will they say no, delay, or disengage? | The real ones — cost, risk, timing, ownership, competing priorities, skepticism. |
| **Evidence needs** | What proof will *this audience* actually trust? | Match evidence to the audience (numbers for a CFO, references for a CTO, customer voice for a CPO). |
| **Communication strategy** | How will the message move them from current to desired state? | The spine: framing, sequence, what leads, what is held back, how objections are pre-empted. |
| **Recommended artifact** | Which format maximises outcome probability? | From the decision logic. Primary + optional secondary. Includes the justification vs the default. |
| **Artifact plan** | How is the artifact structured to execute the strategy? | Section/slide-level plan tying each part to an audience question or objection. |
| **Assumptions** | What are we treating as true without confirmation? | Every gap left by unanswered questions. Always labelled as assumptions. |
| **Open questions** | What still needs answering to de-risk this? | The unknowns that would most change the outcome. |
| **Quality review** | Does this raise the probability of the desired outcome? | The 14 gates, 10 scores, and verdict. See `quality-gates.md`. |

## Invariants

- **Outcome > topic > format.** The true objective is always an outcome. If you have written a topic, keep asking "so that the audience does what?" until you reach a verb.
- **Current and desired states are mandatory.** No transformation can be designed without both.
- **Every claim is either evidenced or marked as an assumption.** There is no third category.
- **The artifact is chosen last, from the outcome — never first, from the request.**
