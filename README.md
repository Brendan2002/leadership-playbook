# leadership-playbook

A Claude skill that coaches team leads who are accountable for results without full authority — frontline leads, coordinators, program leads. It routes common situations (staffing gaps, readiness, delegation, recurring problems, priorities, weekly reviews, escalations, rolling out change) to a framework from *Good to Great*, *Traction*, *The Compound Effect* or leadership research, and answers with clear ownership and an honest split between facts, interpretation and unknowns.

## What's inside

```
leadership-playbook/
├── SKILL.md                      # when to use it, the router, how to answer
└── references/
    ├── good-to-great.md
    ├── traction.md
    ├── compound-effect.md
    └── research-and-tools.md     # evidence checks, influence without authority, fairness, routines
```

Reference files are loaded only when a situation needs them, so SKILL.md stays small.

## Install

- **Claude apps:** zip the `leadership-playbook` folder (so the zip contains `leadership-playbook/SKILL.md`) and upload it under Settings → Capabilities → Skills.
- **Claude Code:** copy the folder to `~/.claude/skills/leadership-playbook/`.

## Personalize it

Add a short "Your context" section to SKILL.md: your role, team size, what you decide versus what goes to management, and the tools your team uses. The skill works without it but gives sharper answers with it.

## Notes

The reference files are original summaries and paraphrases of the frameworks, written for practical use, with caveats about where the evidence is weak. They aren't a substitute for the books and articles listed in `references/research-and-tools.md`.
