# Narrative and evidence

## Evidence ledger

Use this table while working:

| Claim | Source | Confidence | Ownership | Counterevidence or cost | Public wording |
|---|---|---|---|---|---|
| What the case study wants to say | Artifact, person, or dataset | Confirmed, attributed, estimated, unknown | User, team, partner, company | Negative result, limit, regression, or tradeoff | Exact safe claim |

### Confidence language

- **Confirmed:** "The experiment increased completed setup by 12%."
- **Attributed:** "The sales team linked the clearer demo flow to faster evaluations."
- **Estimated:** "Support volume fell by roughly one-third during the next release cycle."
- **Unknown:** omit the result or say what was observed without a number.

Use "contributed to" when several changes shipped together. Use "followed" or "coincided with" when causal evidence is weak.

For metrics, capture baseline, definition, population, time window, absolute or relative change, companion releases, and known regressions. If any field is unknown, avoid false precision.

## Narrative selection

List two or three plausible story angles. Score each for:

- relevance to the target role
- strength of evidence
- distinctiveness
- visual proof
- ability to defend in an interview

Choose the strongest total, not the grandest claim.

## Decision unit

Use this structure for each pivotal decision:

1. **Tension:** the concrete conflict or constraint
2. **Options:** credible alternatives considered
3. **Signal:** research, data, technical fact, or stakeholder input
4. **Choice:** what the user decided or influenced
5. **Tradeoff:** what the choice gave up
6. **Result:** shipped change and known evidence
7. **Visual:** artifact that proves the account
8. **Limit:** what remained unresolved, worsened, or could not be measured

Two strong decision units can carry a case study. Six weak units create noise.

## Visual evidence

Prefer:

- shipped interface, live product, or working demo
- before and after with a precise caption
- annotated flow showing the decision point
- rejected alternative with the reason it lost
- system diagram, architecture, or component relationship
- research excerpt connected to a product change
- outcome chart with source and time window
- prototype or code link that demonstrates behavior

Avoid decoration presented as evidence. Device mockups, sticky-note walls, personas, and process diagrams need a specific explanatory job.

Every caption should answer one of these:

- What changed here?
- What should the reviewer notice?
- Which decision does this prove?
- What constraint shaped it?
- What happened after it shipped?

## Common story failures

### Process inventory

Symptom: the case study lists methods in chronological order.

Fix: keep methods that changed a decision. Organize around the decision.

### Hero narrative

Symptom: the user appears to research, decide, design, build, launch, and measure alone.

Fix: name collaborators and boundaries. Explain the user's leverage inside the team.

### Metric laundering

Symptom: a company outcome appears as proof of one design change without causal evidence.

Fix: qualify the relationship and show the user's direct contribution.

### Retrofitted strategy

Symptom: language makes an execution task sound like an executive mandate.

Fix: describe the actual decision space and why the execution required judgment.

### Research theater

Symptom: personas, maps, or interviews appear without changing the work.

Fix: connect the evidence to a choice or remove it.

### Final-screen gallery

Symptom: polished screens appear without explaining the hard part.

Fix: pair key visuals with constraints, alternatives, and the reason for the final behavior.

### AI theater

Symptom: a list of AI tools stands in for skill.

Fix: show the task, prompt or workflow where useful, verification, human correction, and result.

### Success theater

Symptom: every decision works, every metric rises, and every stakeholder agrees.

Fix: recover failed tests, limits, disagreements, regressions, and follow-up work. Include only those that affected the project.
