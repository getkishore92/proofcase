# Industry patterns and project routes

Use this reference to decide what proof belongs. Do not apply every pattern to every case study.

## Design for three reading speeds

### Fast scan

A reviewer should find these without reading paragraphs:

- what shipped or changed
- what the candidate owned
- why the work was difficult or relevant
- strongest outcome with qualification
- one or two high-quality visuals

Use informative headings, short summaries, visible role metadata, strong captions, and a clear section order.

### Focused review

A reviewer should be able to inspect two or three decisions, the final work, evidence, tradeoffs, and outcome without reading every detail.

Use decision-led sections, before-and-after pairs, annotated flows, metric callouts with context, and progressive disclosure.

### Interview depth

Keep enough material to defend the work:

- alternatives and rejected directions
- research or technical detail
- metric definitions and caveats
- edge cases and failure states
- implementation, rollout, or migration detail
- what the user would change

Place this in deeper sections, expandable details, backup slides, or linked artifacts.

## Cut over-explanation

Remove a section when it repeats the heading, describes a standard method, or does not change the reviewer's view of the candidate.

Keep process only when it answers:

- Why did the team choose this method?
- What did it reveal?
- Which decision changed?
- What would have happened without it?

Replace long paragraphs with an annotated artifact when the artifact carries the explanation. Do not use a wall of screenshots without captions.

## Reject portfolio theater

Treat these as evidence only when they are real and consequential:

- card sorting
- personas
- journey maps
- affinity diagrams
- workshop photos
- sticky-note walls
- polished double-diamond diagrams
- generic wireframe progressions

Do not backfill research after the design. A self-initiated project can use desk research, expert review, public data, prototype tests, or clearly labeled assumptions. State what was simulated. Never invent participants, quotes, sample sizes, usability findings, or validation.

## Show the whole result, including friction

A credible case study does not read like a launch announcement. Include material evidence from these categories when available:

- flat or negative experiment result
- segment that did not improve
- regression or new support burden
- usability issue that survived launch
- technical debt or performance cost
- scope cut and value lost
- stakeholder concern that remained valid
- metric the team could not measure
- uncertainty in causal attribution
- follow-up work or reversal

Explain the corrective action or current decision. Do not add a failure for drama. Do not hide one that changes the interpretation of success.

## Metrics without spin

For each metric, ask:

- What was the baseline?
- Which population and time window does it cover?
- Is the number absolute or relative?
- What else shipped at the same time?
- Did another metric worsen?
- Was the effect sustained?
- Who owns the company-level outcome?

Show a small set of decision-relevant metrics. Avoid a wall of positive numbers. Pair leading indicators with retention, quality, trust, cost, or reliability measures where the project requires them.

## B2B route

B2B reviewers often need proof of complex workflows and organizational fit. Show:

- user roles, buyers, admins, operators, and approvers
- permissions, auditability, governance, and exception handling
- dense information and repeated expert tasks
- integrations, data models, migration, or implementation limits
- sales, solutions, customer success, support, and engineering input
- time to value, task completion, adoption by account or role, support load, expansion, retention, or sales enablement
- long feedback cycles and small samples with honest confidence

Use workflow diagrams and role maps when they explain complexity. Show enough interface detail to prove information architecture and interaction craft.

Avoid presenting one buyer interview or one enterprise logo as broad validation.

## B2C route

B2C reviewers often need proof of behavior at scale and product quality. Show:

- audience segments, contexts, and market differences
- discovery, onboarding, habit, retention, monetization, and re-engagement
- experimentation and cohort behavior
- accessibility, localization, trust, safety, consent, and abuse cases
- performance and platform constraints
- conversion, adoption, engagement, retention, revenue, satisfaction, complaints, or opt-out behavior with metric context

Show the full lifecycle and important states, not one ideal path. Pair growth results with user cost, trust, or long-term behavior when relevant.

Avoid treating a large aggregate number as proof that every segment improved.

## Engineering route

Build the story around a technical or product decision. Include:

- system context and user or business effect
- constraints and non-functional requirements
- architecture and data flow
- credible alternatives and why they lost
- security, privacy, accessibility, reliability, and failure handling
- tests, observability, rollout, migration, compatibility, and rollback
- performance, cost, incident, quality, or delivery evidence
- code, API, CLI, repository, benchmark, or running demo when safe
- technical debt accepted and follow-up work

Explain specialized terms. Diagrams should reveal boundaries and tradeoffs, not decorate the page. Show production behavior and operating evidence where possible.

Avoid a code dump, technology list, or architecture diagram with no decision attached.

## Design-engineering route

Show how design and implementation informed each other:

- prototype fidelity and what it allowed the team to learn
- component API, states, tokens, motion, responsiveness, and accessibility
- implementation constraint that improved or reduced the design
- production details and collaboration with other engineers or designers
- speed, consistency, quality, adoption, or maintenance effect

Link to a live component, Storybook, playground, repository, or recording when public.

## Images and prototypes

Use the strongest artifact early. Prefer real product imagery over generic device frames. For each image:

- render it large enough to inspect
- crop around the relevant evidence
- annotate only the decision point
- provide a caption with the claim
- include useful alt text
- keep sensitive data removed

Use a working prototype when interaction is central. State whether it is exploratory, validated, production-like, or shipped. A prototype is evidence of behavior and craft, not proof of customer impact.

## Motion

Use motion to show:

- state transition
- hierarchy or continuity
- direct manipulation
- system feedback
- loading, interruption, error, and recovery
- gesture or spatial model

Prefer short, focused recordings or live demos. Provide controls, captions where needed, a poster frame, and a reduced-motion or static alternative. Do not let autoplay or decorative motion block reading.

## Interaction

Useful interactions include:

- before-and-after comparison
- annotated flow with optional detail
- prototype or component playground
- expandable evidence and metric definitions
- timeline tied to product changes
- theme, locale, or responsive-state demonstration
- code and design shown side by side

The core story must still work with JavaScript unavailable, on a small screen, by keyboard, and in a static export. Test loading and interaction before delivery.

## Easter eggs and personality

Small details can make a portfolio memorable and show care. Use them after the main story works. Good examples include a relevant keyboard shortcut, project-specific microcopy, a subtle interaction tied to the product, or a hidden note that rewards exploration.

Keep easter eggs:

- optional and fast
- relevant to the author's taste or the project
- accessible by more than precise pointer input when practical
- safe for reduced-motion users
- free of important information that reviewers could miss

Do not let a novelty interaction delay the work, hide navigation, or compete with the final product.
