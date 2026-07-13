# Output templates

## Coach

Use this for a first case study, an early-career candidate, or a user who wants guided improvement:

1. Likely recruiter takeaway
2. Strongest evidence already present
3. Largest credibility or clarity gap
4. Hiring question behind that gap
5. One or two questions for the user
6. Revised excerpt after the user answers
7. Next two actions

Review one section at a time. Keep the scorecard optional unless the user asks for an audit.

## Audit

1. Target role and inferred level
2. Hiring verdict in three sentences
3. Integrity blockers, publishability blockers, and role-fit gaps
4. Overall Proofcase rating with rubric evidence
5. AI and agent scannability ratings
6. Top five changes in priority order
7. Missing proof and recovery options
8. Rewritten opening
9. Before-and-after scorecard when a completed revision exists

## Rating scorecard

```markdown
| Rating | Before | After | Change |
|---|---:|---:|---:|
| Proofcase score | [0–100] | [0–100 or Pending] | [delta or Pending] |
| AI scannability | [0–100] | [0–100 or Pending] | [delta or Pending] |
| Agent scannability | [0–100] | [0–100 or Pending] | [delta or Pending] |
```

Follow the table with the specific edits that changed each rating. Keep unresolved evidence gaps in the after score.

## Revision trail

Use this for a substantial rewrite, job-tailored version, or file edit. Prefer the host tool's native diff when it is available. Use the formats below when the host cannot show a useful diff.

### Source map

```markdown
| ID | Claim | Source or artifact | Confidence | Ownership | Limitation |
|---|---|---|---|---|---|
| S1 | [claim] | [file, URL, screenshot, note, or dataset] | [confirmed, attributed, estimated, or unknown] | [user, team, partner, or company] | [counterevidence, cost, or missing context] |
```

### Change review

```markdown
## [Section or file location]

**Original**
[original text]

**Revised**
[revised text]

**Reason**
[hiring question, clarity problem, or structural reason]

**Source**
[source-map ID, or `No new factual claim`]

**Status**
[proposed, applied, accepted, or rejected]
```

For a file edit, finish with:

```markdown
Original: [preserved path or version]
Revised: [new path or working-tree file]
Revert through: [host checkpoint, editor history, Git reference, or preserved original]
```

Name the available revert route. Do not claim that Proofcase supplies rollback, and do not run a revert without the user's request.

## Full web case study

```markdown
# [Specific change or outcome]

[One sentence: who moved from what state to what state, the user's contribution, and the defining constraint.]

Role: [role and ownership]
Team: [functions and size if safe]
Timeframe: [dates or duration]
Status: [shipped, pilot, concept, sunset]
Outcome: [defensible result or current evidence]

![Strongest proof]
Caption: [what this proves]

## Context
[Why the work existed and why it mattered.]

## My scope
[Owned, influenced, partnered, and out of scope.]

## [Decision-led section title]
[Tension, options, signal, choice, tradeoff, result.]

## [Second decision-led section title]
[Tension, options, signal, choice, tradeoff, result.]

## Shipped work
[Final system or behavior with visual proof.]

## Outcome
[Confirmed result, baseline, population, time window, attribution, negative or flat results, limits, and follow-up.]

## Reflection
[A specific lesson, what did not work, and what the user would change.]
```

## Recruiter skim

Keep to one screen or a short project card:

- outcome-led title
- one-line context
- role and scope
- two proof points
- one strong visual
- link to the full account or demo

## Interview presentation

Aim for a coherent spoken story, commonly 10 to 15 slides for one project:

1. result and final work
2. context, stakes, role, and team
3. defining constraint
4. first pivotal decision
5. evidence and alternatives
6. shipped result
7. second pivotal decision
8. evidence and alternatives
9. final system or implementation
10. outcome, limits, and reflection

Add backup slides for detailed research, architecture, metrics, and edge cases. Do not read the web case study aloud.

## Job-tailored variant

Keep the facts and project sequence stable. Change:

- title and summary emphasis
- capability labels
- which decisions receive detail
- visual order
- vocabulary that truthfully matches the job description
- interview questions and proof gaps

Do not insert job-description keywords that the project cannot support.
