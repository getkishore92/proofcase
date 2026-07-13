# AI and agent scannability

These ratings measure whether automated systems can extract and operate the case study without guessing. They do not estimate ATS rank, recruiter preference, interview probability, or writing quality.

Score each check `0`, `1`, or `2`:

- `0`: missing, inaccessible, or misleading
- `1`: present but incomplete, ambiguous, or unverified
- `2`: clear and reliable

Normalize each rating:

```text
rating = round(points earned / 16 × 100)
```

## AI scannability

Score whether an LLM can build an accurate account from the available text.

| Check | What earns 2 points |
|---|---|
| Project identity | Product or system, company or context, role, timeframe, and shipped status are explicit. |
| Ownership | Owned, influenced, partnered, and team work are distinguishable. |
| Decision headings | Headings state the choice, tension, or result instead of generic process labels. |
| Claim context | Metrics and outcomes include definitions, populations, windows, attribution, and qualifications where needed. |
| Text equivalents | Important visuals, motion, prototypes, charts, and code have captions or nearby text that states what they prove. |
| Terms | Acronyms, product-specific language, and technical terms are defined on first use. |
| Consistency | Dates, numbers, ownership, status, and conclusions agree across summaries, body copy, captions, and presentations. |
| Information density | Short summaries and progressive detail expose key facts without repeated or generic prose. |

## Agent scannability

Score whether a browser or recruiting agent can navigate, extract, and verify the case.

Score an actual page, document, or implementation. When the user supplied only copy, an outline, or planned behavior, report agent scannability as `Pending` rather than assigning points.

| Check | What earns 2 points |
|---|---|
| Semantic structure | The page uses a coherent heading hierarchy, landmarks, lists, tables, and real text. |
| Stable navigation | Descriptive page title, section anchors, and stable URLs expose important sections. |
| Media labels | Images, charts, videos, and controls have useful alt text, captions, names, or transcripts. |
| Content availability | Core evidence exists in the document and is not trapped in canvas, hover states, autoplay, images, or inaccessible overlays. |
| Link meaning | Link text states the destination or evidence type; prototypes and demos state whether they are concept, validated, or shipped. |
| Fallbacks | The core story remains available during slow loading, media failure, reduced motion, small screens, and a static or script-limited read. Mark untested conditions as `1`, not `2`. |
| Operability | Keyboard focus, button names, dialog labels, controls, and reading order support non-pointer operation. |
| Machine metadata | Page title, description, canonical URL, social metadata, and project facts agree with the visible case. |

## Comparison rules

Use the same checks for the original and revision.

- Score the actual supplied case first.
- Score the revised copy or implementation only after it exists.
- Re-test live behavior when code or layout changed.
- Do not award implementation points to a copy-only draft.
- Use `1` for an implemented check that remains incomplete, ambiguous, or unverified. Use `Pending` when no implementation exists to inspect.
- Report negative deltas when a revision removes useful context, semantics, or accessibility.

Return a short explanation for every changed check. A delta without a reason does not help the user improve the case.
