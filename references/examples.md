# Before and after examples

Every project below is a fictional composite created to teach the Proofcase method. Company names, people, metrics, timelines, and outcomes are invented. Do not present them as real work or reuse their numbers in a portfolio.

Use these examples to study structure:

- connect evidence to a decision
- separate personal ownership from team delivery
- qualify metrics and causal claims
- include tradeoffs, regressions, and limits
- choose proof that fits the role and project type

## 1. B2B SaaS: expose the operating workflow

### Before

> I led the redesign of a billing dashboard. We interviewed users, created personas, mapped the journey, and iterated on wireframes. The new experience was easier to use and increased efficiency by 58%.

### After Proofcase

> Finance admins exported four reports before approving an invoice because the product separated usage, contract terms, credits, and tax adjustments. I owned the reconciliation flow and worked with billing engineers and two customer-success leads to define which records needed an audit trail.
>
> We kept source data beside each adjustment and added a review state for finance approvers. In a six-account pilot, median invoice review time fell from 43 to 18 minutes. Exception cases generated more support requests during the first month, so the team added bulk resolution before wider rollout.

### Why it works

- It names the user roles and repeated task.
- It states the candidate's scope and partners.
- It links research to the audit-trail decision.
- It gives a pilot size, baseline, and measure.
- It includes the support regression and follow-up.

### Evidence to show

- role and permission map
- annotated before-and-after reconciliation flow
- audit-trail interaction or prototype
- pilot timing method and support categories

### Remaining limit

Six accounts cannot prove broad adoption. The case study should describe the result as pilot evidence.

## 2. B2C subscription: pair growth with user cost

### Before

> I redesigned onboarding for a streaming app. User research helped us simplify the experience and increase subscription conversion by 28%.

### After Proofcase

> New listeners often treated the seven-day trial as free catalogue access, then cancelled when locked episodes returned. I owned the plan explanation, trial states, and cancellation entry points across iOS and Android.
>
> Session replays and cancellation interviews showed that the price was visible, while the post-trial limit was not. The team moved the limit into plan selection and added a persistent trial-usage state. Trial-to-paid conversion rose 18% among returning listeners over eight weeks. Day-30 retention stayed flat, and notification opt-outs increased after a reminder experiment, so we removed the extra push before the next cohort.

### Why it works

- It identifies the misunderstanding behind the funnel drop.
- It separates the candidate's surfaces from the team's release.
- It names the segment and time window.
- It reports a flat retention result.
- It shows the notification reversal.

### Evidence to show

- lifecycle map for trial, paid, lapsed, and cancelled states
- plan-selection before and after
- recording of the persistent usage state
- cohort chart with conversion, retention, and opt-out definitions

### Remaining limit

The case study cannot assign the full conversion change to copy and interface changes if pricing or acquisition changed during the same period.

## 3. UX research: show the decision influence

### Before

> I conducted 20 interviews, built three personas, and presented insights to stakeholders. The research helped the team understand delivery drivers and informed the roadmap.

### After Proofcase

> The operations team planned to shorten the delivery-confirmation flow because they assumed drivers valued speed above detail. I led 12 contextual sessions across two depots and reviewed 140 disputed-delivery tickets with a support analyst.
>
> Drivers completed the flow fast, but they paused when a damaged package required proof. The evidence changed the roadmap: the team kept the normal confirmation short and added a separate damage path with photo quality checks and offline recovery. Dispute reviewers found the new evidence easier to verify in a four-week pilot. The sample did not include rural routes, so the offline design remained a risk for the next study.

### Why it works

- It starts with the decision under consideration.
- It explains why the methods fit the question.
- It names the researcher's partner.
- It connects the finding to a product change.
- It preserves the sample gap.

### Evidence to show

- research question and sampling plan
- anonymised observation pattern
- disputed-ticket analysis frame
- decision record linking findings to the roadmap

### Remaining limit

“Easier to verify” needs a defined measure or direct attribution to pilot reviewers. The case study should avoid claiming fewer disputes without data.

## 4. Software engineering: connect architecture to product behaviour

### Before

> I migrated our webhook service to an event-driven architecture using Kafka and Kubernetes. The new system improved performance, scalability, and reliability.

### After Proofcase

> Webhook processing reached 11 seconds at p95 during customer imports, and two providers disabled endpoints after repeated timeouts. I owned the ingestion boundary and rollout plan with one platform engineer.
>
> We kept synchronous signature verification at the edge, moved processing to replayable queues, and added idempotency keys before workers touched customer data. A staged rollout reduced p95 acknowledgement time to 1.8 seconds and stopped provider disablements during the next two import cycles. Worker memory rose 22%, which delayed regional expansion until we changed the event payload.

### Why it works

- It states the user-visible and partner-visible failure.
- It defines the candidate's architecture boundary.
- It explains the synchronous and asynchronous split.
- It names the rollout and reliability evidence.
- It includes the memory cost and delayed work.

### Evidence to show

- old and new request path
- timeout and acknowledgement traces
- idempotency and replay strategy
- rollout stages, rollback condition, and memory profile

### Remaining limit

Two import cycles show short-term stability. The case study should separate that observation from long-term reliability.

## 5. Design engineering: prove the system in production

### Before

> I created a scalable design system and reusable component library. This improved consistency, accessibility, and developer velocity across the organisation.

### After Proofcase

> Seven product teams maintained eleven date-picker variants with different keyboard behaviour, validation, and timezone handling. I designed and built one React component with a product designer and two accessibility specialists.
>
> The API separated display format from stored timezone, covered range and single-date modes, and exposed error states without replacing native form semantics. Seven teams adopted it over two quarters, and duplicate date-picker code fell across five repositories. The component added 12 kB to the shared bundle, so we split locale data before recommending it for low-traffic surfaces.

### Why it works

- It defines the system problem with real variation.
- It shows design and implementation ownership.
- It names API and accessibility decisions.
- It reports adoption instead of claiming consistency.
- It includes the bundle cost and mitigation.

### Evidence to show

- variant audit
- component API and state matrix
- keyboard and screen-reader recording
- repository adoption and bundle comparison

### Remaining limit

Code reduction does not prove developer velocity. The case study needs delivery-time evidence before making that claim.

## 6. AI product: show evaluation and human control

### Before

> I designed an AI assistant that summarised customer calls. We used prompt engineering and user feedback to improve accuracy and save account managers hours of work.

### After Proofcase

> Account managers spent the first ten minutes after each call turning notes into CRM updates. I owned the review experience for an AI-generated summary, while an applied-ML engineer owned retrieval and generation.
>
> A 200-call evaluation set showed that the model handled action items well and often assigned commitments to the wrong speaker. We highlighted speaker-linked source passages, required confirmation for owners and dates, and blocked automatic CRM writes. Review time fell from nine to four minutes in a 14-person pilot. Corrections remained high for calls with more than four speakers, so the team kept those calls in a manual-note path.

### Why it works

- It separates product-design ownership from model work.
- It names the evaluation set and failure mode.
- It shows human review and blocked automation.
- It reports pilot size and timing.
- It preserves the unsupported multi-speaker case.

### Evidence to show

- evaluation taxonomy and error examples
- source-linked review interaction
- confirmation and blocked-write states
- pilot timing and correction-rate breakdown

### Remaining limit

Time saved in a pilot does not prove better account management or customer outcomes.

## 7. Staff or design leadership: show leverage through teams

### Before

> I led a strategic redesign across three product teams. I aligned stakeholders, mentored designers, and introduced a shared vision that increased engagement by 35%.

### After Proofcase

> Three teams represented account status differently, which caused customers to see conflicting access, billing, and renewal states. As the staff designer, I set the cross-product state model and decision process. Product-team designers owned their flows and final interfaces.
>
> I ran weekly decision reviews with design, product, and platform leads, documented unresolved policy conflicts, and coached each designer through migration choices. Four launches reused the state model over nine months. Support escalations tied to account-status mismatch fell after the first two migrations. One team delayed adoption by a quarter because its permissions service could not represent the shared model.

### Why it works

- It defines the cross-team problem.
- It separates direction from hands-on interface ownership.
- It shows the mechanism used to influence teams.
- It gives evidence of reuse and operational effect.
- It includes the delayed team and technical constraint.

### Evidence to show

- old state conflicts and shared model
- decision log and ownership map
- examples from team-owned implementations
- adoption timeline and support classification

### Remaining limit

The case study should avoid claiming a 35% engagement result unless the state-model work can be separated from the four product launches.

## Reuse rule

Copy the structure, not the facts. Replace every invented detail with project evidence the user can defend. Remove a metric when its source, baseline, definition, or attribution cannot be established.
