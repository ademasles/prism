# Template — Technical Briefing

For an audience that must understand architecture, trade-offs, systems, or technical risk well enough to weigh in or decide. If the audience is non-technical and only needs the ask, translate to a decision memo instead.

## Instructions
- Depth in service of a decision — end with what you need from the reader, not just knowledge transferred.
- Be honest about trade-offs and failure modes; technical audiences trust candour and distrust one-sided cases.
- Separate "what's true" from "what we recommend."

## Structure

```
# Technical Briefing — <system / decision>

## Problem
<what's wrong or what decision is forced, in technical terms — 3–5 lines>

## Current state / architecture
<how it works today; the specific pain points, costs, or limits>

## Options
| Option | Approach | Trade-offs | Risk / failure modes | Effort |
|---|---|---|---|---|
| A (recommended) | … | … | … | … |
| B | … | … | … | … |

## Recommendation
<the option and the technical reasoning — why the trade-offs favour it>

## Risks & failure modes
<what could go wrong with the recommendation, and how it's contained>

## Migration / impact
<sequencing, blast radius, dependencies, rollback>

## What we need from you
<the specific input, approval, or resourcing required>
```
