# Proofcase

[![skills.sh](https://skills.sh/b/getkishore92/proofcase)](https://skills.sh/getkishore92/proofcase)

**Case studies that hold up under scrutiny.**

Proofcase is an open Agent Skill that turns rough project material into a credible portfolio case study for product designers, UX researchers, product managers, software developers, and design engineers.

It can audit an existing case study, interview you to recover missing context, rewrite the story, tailor it to a job description, or create an interview presentation. It adjusts the expected proof for junior, mid-level, senior, staff, lead, and manager roles.

## What it checks

- role fit and seniority signal
- ownership and team attribution
- decisions, constraints, and tradeoffs
- visual or technical evidence
- outcomes and claim integrity
- negative results, tradeoffs, and missing evidence
- AI use, verification, and provenance
- scan quality and interview defense
- direct, natural copy

The package also includes permissioned before-and-after examples from real Pocket FM and Togai case studies. Each example explains the structural or editorial decision behind the revision.

It routes B2B, B2C, engineering, and design-engineering work through different proof standards. It also covers prototypes, motion, interactive explanations, and small portfolio details such as easter eggs without letting presentation hide weak evidence.

The skill does not invent metrics, research, impact, or ownership. It flags missing proof and suggests honest ways to recover or represent it.

## Install

Install it for Codex, Claude Code, Cursor, Windsurf, and other supported agents with the Skills CLI:

```bash
npx skills add getkishore92/proofcase
```

The CLI detects the available agent and installs the root `SKILL.md` with its references. Installs made through the CLI contribute anonymous aggregate telemetry to the [skills.sh listing](https://skills.sh/getkishore92/proofcase). Review any skill before installing it because agent skills run with the permissions of the host agent.

You can also clone the repository into a tool-specific skills directory.

### Codex

```bash
git clone https://github.com/getkishore92/proofcase.git ~/.codex/skills/proofcase
```

### Claude Code

```bash
git clone https://github.com/getkishore92/proofcase.git ~/.claude/skills/proofcase
```

Restart the tool if it does not detect the new skill.

## Use

```text
Use $proofcase to audit this case study for a senior product designer role: [URL or file]
```

```text
Use $proofcase to turn these project notes and screenshots into a web case study. Ask me for any facts you cannot verify.
```

```text
Use $proofcase to tailor my existing case study to this job description without changing the facts.
```

```text
Use $proofcase to convert this case study into a 20-minute portfolio presentation.
```

## Why this exists

AI can generate polished prose, process diagrams, and interface concepts in minutes. Hiring teams still need evidence of what a candidate owned, how they made decisions, what shipped, and what changed. This skill helps candidates make that evidence easy to inspect without turning every project into the same process template.

The skill rejects fabricated research and decorative process artifacts. Card sorts, personas, journey maps, and workshop photos belong only when they are real and changed the work. A credible case study includes limits, failed or flat results, and the next decision when those facts affected the project.

## Credits

The copy review adapts principles from [stop-slop](https://github.com/hardikpandya/stop-slop) by Hardik Pandya, used under the MIT License.

The narrative approach responds to Fabricio Teixeira's critique in [The case study factory](https://essays.uxdesign.cc/case-study-factory/) and draws on current portfolio and skills-based hiring research listed in [references/research.md](references/research.md).

The initial [before-and-after examples](references/examples.md) use Kishore Sundarajan's public Pocket FM and Togai case studies with permission. Contributions from other authors require explicit permission or a compatible license.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for the stop-slop copyright and license notice.

## License

MIT. See [LICENSE](LICENSE).
