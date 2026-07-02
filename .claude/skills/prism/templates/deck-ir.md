# Template — Deck IR (vendor-agnostic slide intermediate representation)

Use only when a slide artifact is genuinely required. **Never emit a PPTX file in Phase 1** — emit this IR so the thinking is inspectable before any pixels exist. Slides are the most expensive artifact to do well; the IR keeps the argument visible instead of hidden behind a template.

## Instructions
- One block per slide. Every slide must answer an audience question or address an objection — if it does neither, cut it.
- Keep the deck as short as the outcome allows. Fewer, load-bearing slides beat a long tour.
- `visual intent` describes what the slide should show (chart type, diagram, comparison), not styling.
- `speaker notes` carry the argument the slide implies but doesn't print.

## Structure

```
# Deck IR — <title>
**Audience:** <who>  **Forum:** <where/how long>  **Outcome:** <decision/shift sought>
**Spine:** <the argument in one line, slide-to-slide>

---
### Slide 1
- **Role:** <title / context / problem / evidence / recommendation / ask / appendix>
- **Purpose:** <why this slide exists>
- **Audience question answered:** <"what am I looking at / why care?">
- **Objection addressed:** <the objection, or "none">
- **Core message:** <the one sentence this slide makes land>
- **Evidence:** <the proof shown; note any gap>
- **Visual intent:** <chart / diagram / table / image concept>
- **Speaker notes:** <what the presenter says around it>

---
### Slide 2
<same fields>

... (repeat; keep it lean)
```
