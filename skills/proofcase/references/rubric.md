# Case-study rubric

Score each dimension from 0 to 4. Cite a specific passage or artifact for every score. Do not reward length.

| Dimension | 0 | 2 | 4 |
|---|---|---|---|
| Role fit | No target | Broadly relevant | Direct proof for the target job |
| Opening | Project name only | Context is clear | Change, ownership, scope, and proof are clear |
| Ownership | Unclear or inflated | Role stated | Boundaries and personal contribution stay clear throughout |
| Stakes | Generic problem | User or business need | Specific user, business, and technical tension |
| Decisions | Activity list | Some rationale | Consequential choices, options, signals, and tradeoffs |
| Craft or technical depth | Final output only | Selected detail | Work quality and reasoning are visible at the right depth |
| Evidence integrity | Unsupported claims | Mostly qualified | Sources, confidence, attribution, and limits are clear |
| Outcomes | Missing | Shipped result or learning | Defensible change with measure, observation, or traceable effect |
| Counterevidence | Success-only promotion | A limit or learning appears | Material negatives, uncertainty, tradeoffs, and corrective action are clear |
| Visual proof | Decorative or absent | Relevant visuals | Visuals prove decisions and carry useful captions |
| Product demonstration | Static claim only | Screens or code show output | Prototype, motion, interaction, or production evidence shows key behavior |
| Seniority signal | Mismatched | Plausible | Scope, autonomy, influence, and accountability fit the target |
| Scan quality | Walls of text | Usable headings | Strong first screen and clear progressive detail |
| AI scannability | Core facts are ambiguous or trapped in media | Most facts can be extracted | Role, decisions, evidence, outcomes, and limits can be extracted without guesswork |
| Agent scannability | The case requires visual inference or fragile interaction | Core content is reachable | Semantic structure, labels, fallbacks, and stable navigation make the case reliably operable |
| Voice | Generic AI prose | Mostly direct | Specific, natural, concise, and owned |
| Interview defense | Story breaks under questions | Main claims defensible | Tradeoffs, gaps, and attribution can withstand detailed review |

## Overall rating

The rubric has 17 dimensions and a maximum raw score of 68.

```text
Proofcase score = round(raw score / 68 × 100)
```

Use these labels:

| Score | Label |
|---:|---|
| 90–100 | Ready for close review |
| 75–89 | Strong with targeted gaps |
| 60–74 | Promising, needs structural work |
| 40–59 | Weak proof |
| 0–39 | Insufficient evidence |

Keep blockers visible beside the number. When a blocker exists, label the result `Blocked` regardless of the numeric score. A rating measures the submitted material against this rubric. It does not predict an interview, ATS result, or hiring outcome.

For detailed AI and agent ratings, use [scannability.md](scannability.md).

## Severity rules

Treat these as blockers regardless of total score:

- invented or misleading evidence
- unclear ownership of major work
- confidential material exposed without permission
- target role requires a capability the case study does not show
- final work or shipped behavior cannot be found
- positive metrics omit known context that changes their meaning
- research, participants, personas, or validation were fabricated or mislabeled

## Revision plan

Return findings in this order:

1. blockers
2. high-leverage structural changes
3. evidence to recover
4. visual changes
5. line edits

For each change, explain the hiring question it helps answer.

## Before-and-after comparison

When a revision is part of the task:

1. score the supplied version before editing
2. score the completed revision after editing
3. show the raw score, normalized rating, and delta
4. show separate AI and agent scannability deltas
5. name the exact changes responsible for each increase or decrease

Do not score a proposed outline as a finished revision. If the user has not applied or approved the revised version, report the baseline and mark the after score as pending.
