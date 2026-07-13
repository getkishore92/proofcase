# Case-study rubric

Score each applicable dimension from 0 to 4. Cite a specific passage or artifact for every score. Do not reward length.

## Score anchors

Use the same anchors for every dimension:

| Score | Meaning |
|---:|---|
| 0 | Missing, misleading, or unusable |
| 1 | Weak signal with major gaps |
| 2 | Present but broad, partial, or inconsistent |
| 3 | Strong signal with one material gap |
| 4 | Clear, specific, defensible, and supported |

## Core dimensions

Score these for every case study. Interpret craft, outcomes, and seniority through the target role and project status.

| Dimension | 0 | 2 | 4 |
|---|---|---|---|
| Role fit | No target | Broadly relevant | Direct proof for the target job |
| Opening | Project name only | Context is clear | Change, ownership, scope, and proof are clear |
| Ownership | Unclear or inflated | Role stated | Boundaries and personal contribution stay clear throughout |
| Stakes | Generic problem | User or business need | Specific user, business, or technical tension appropriate to the project |
| Decisions | Activity list | Some rationale | Consequential choices, options, signals, and tradeoffs |
| Craft or technical depth | Final output only | Selected detail | Work quality and reasoning are visible at the right depth for the role |
| Evidence integrity | Unsupported claims | Mostly qualified | Sources, confidence, attribution, and limits are clear |
| Outcomes | Missing | Shipped result, observed response, decision enabled, or grounded learning | Defensible change with measure, observation, traceable effect, or bounded learning appropriate to project status |
| Counterevidence | Success-only promotion | A limit or learning appears | Material negatives, uncertainty, tradeoffs, and corrective action are clear |
| Seniority signal | Mismatched | Plausible | Scope, autonomy, influence, and accountability fit the target |
| Scan quality | Walls of text | Usable headings | Strong first screen and clear progressive detail |
| Voice | Generic AI prose | Mostly direct | Specific, natural, concise, and owned |
| Interview defense | Story breaks under questions | Main claims defensible | Tradeoffs, gaps, and attribution can withstand detailed review |

## Conditional dimensions

Score these when the role, project, and final artifact call for them:

| Dimension | Applicable when | 0 | 2 | 4 |
|---|---|---|---|---|
| Visual proof | Reviewers need screens, flows, research artifacts, charts, diagrams, code, or another visual record | Expected proof is absent or decorative | Relevant visuals appear | Visuals prove decisions and carry useful captions |
| Product demonstration | The project produced a shipped or testable interface, system, prototype, motion behavior, or code path | The case makes a static claim without showing expected behavior | Screens or code show selected output | Inspectable evidence shows the key behavior and status |

Use `N/A` only when the target role and project make a conditional dimension irrelevant. Missing expected evidence earns `0` in a completed case study.

Use `Pending` when the dimension applies but the user has supplied only a working draft, copy, outline, or planned implementation. A score with any pending dimension is provisional and cannot receive the `Ready for close review` label.

Examples:

- Keep product demonstration `N/A` for a pure research or organizational leadership case with no product artifact.
- Score product demonstration `0` when a product designer claims a shipped interaction but shows no inspectable behavior.
- Mark visual proof `Pending` when reviewing copy before the user supplies the planned screens.

## Overall rating

Keep AI and agent scannability outside the Proofcase score. Report them as separate diagnostics from [scannability.md](scannability.md).

```text
Proofcase score = round(points earned / (applicable dimensions × 4) × 100)
```

Report the applicable dimension count and any `N/A` or `Pending` decision beside the score.

| Score | Label |
|---:|---|
| 90–100 | Ready for close review |
| 75–89 | Strong with targeted gaps |
| 60–74 | Promising, needs structural work |
| 40–59 | Weak proof |
| 0–39 | Insufficient evidence |

A rating measures the submitted material against this rubric. It does not predict an interview, ATS result, or hiring outcome.

## Finding severity

Separate findings by consequence.

### Integrity blockers

Use `Unsafe to publish` when the case contains:

- invented or misleading evidence
- confidential material exposed without permission
- positive metrics that omit known context which changes their meaning
- fabricated or mislabeled research, participants, personas, or validation

Do not polish the affected claim. Remove it, qualify it, or ask the user for a defensible source.

### Publishability blockers

Use `Not ready to publish` when:

- ownership of major work remains unclear
- final work or claimed shipped behavior cannot be found
- the opening omits project status or the candidate's role
- a material claim cannot be checked from the supplied record

The numeric score may still help prioritize revisions. Keep the publishability label beside it.

### Role-fit gaps

Record a role-fit gap when the target job requires a capability the project does not show. Do not treat the candidate as dishonest or block a truthful case study. Recommend another project, a narrower claim, or a different target role when copy cannot repair the gap.

## Revision plan

Return findings in this order:

1. integrity blockers
2. publishability blockers
3. role-fit gaps
4. high-leverage structural changes
5. evidence to recover
6. visual changes
7. line edits

For each change, explain the hiring question it helps answer.

## Before-and-after comparison

When a revision is part of the task:

1. score the supplied version before editing
2. score the completed revision after editing
3. use the same applicable dimensions and target profile for both passes
4. show the raw score, applicable denominator, normalized rating, and delta
5. show separate AI and agent scannability deltas
6. name the exact changes responsible for each increase or decrease

Do not score a proposed outline as a finished revision. If the user has not applied or approved the revised version, report the baseline and mark the after score as pending.
