# leadership-playbook

A Claude skill that coaches team leads who are accountable for results without full authority: frontline leads, coordinators, program leads. It routes common situations to a framework from *Good to Great*, *Traction*, *The Compound Effect* or leadership research, then answers with clear ownership and an honest split between facts, interpretation and unknowns.

## What it helps with

- Staffing or coverage gaps and readiness before an event or deadline
- Delegating and developing other leads so work doesn't depend on you
- Problems that keep coming back
- Competing priorities and deciding what to stop doing
- Weekly reviews and planning rhythms
- Rolling out a change to your team
- Getting another department to act when you have no authority over it
- Writing an escalation to management
- Your own leadership development plan

## Example prompts

- "Two people dropped out of Saturday's event and I'm the only backup again. What should I do?"
- "Payroll errors keep happening every week. How do I fix this for good?"
- "Help me write an escalation to my manager about unconfirmed coverage for next weekend."
- "I want to build a weekly review I'll actually keep doing."

## Install

**Claude apps (web, desktop, mobile):** download `leadership-playbook.zip` from the [latest release](../../releases/latest) and upload it in your Skills settings.

**Claude Code:**

```bash
git clone https://github.com/Brendan2002/leadership-playbook ~/.claude/skills/leadership-playbook
```

## What's inside

```
SKILL.md                      # when to use it, the situation router, how to answer
references/
├── good-to-great.md
├── traction.md
├── compound-effect.md
└── research-and-tools.md     # evidence checks, influence without authority, fairness, routines
```

Reference files load only when a situation needs them, so the main instructions stay small.

## Personalize it

Fill in the "Your context" section of `SKILL.md` with your role, team size, what you decide versus what goes to management, and the tools your team uses. It works without this but gives sharper answers with it.

## Notes

- The reference files are original paraphrased summaries written for practical use, with caveats where the evidence is weak. They don't replace the books and articles listed in `references/research-and-tools.md`.
- Not affiliated with or endorsed by the authors or publishers of the sources.
- MIT licensed.
