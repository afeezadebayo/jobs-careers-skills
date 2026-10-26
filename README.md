# Jobs and Careers Skills for AI Agents

[![10 skills](https://img.shields.io/badge/skills-10-0b7285)](#all-skills)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free **Agent Skills** (`SKILL.md`) that turn Claude, Claude Code, OpenAI Codex and other AI agents into a careful job-search assistant. They find fresh, verified roles, judge fit honestly, write truthful CVs and cover letters, optimise your LinkedIn profile, plan referral outreach, prepare you for interviews, and help you negotiate the offer.

Every skill works from your own **career profile** and **job search profile**, so the agent uses your real facts and never invents experience.

By [**Afeez Adebayo**](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/productivity/jobs-careers/) · [LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon)

Part of the [Productivity skills](https://github.com/afeezadebayo/productivity-skills) library.

## All skills

| Skill | What it does |
|---|---|
| [`daily-job-opportunities`](daily-job-opportunities) | Daily verified roles from employer ATS pages, no repeats, no scams |
| [`job-fit-evaluation`](job-fit-evaluation) | Deal-breaker gates, evidence map and A to F grade for one posting |
| [`cv-writer`](cv-writer) | The strongest truthful CV for a specific job |
| [`cover-letter-writing`](cover-letter-writing) | Specific letters built on two or three pieces of real evidence |
| [`linkedin-profile`](linkedin-profile) | Headline, About and experience that recruiters search for |
| [`networking-referral-outreach`](networking-referral-outreach) | Referral and hiring-manager messages that get replies |
| [`interview-preparation`](interview-preparation) | Predicted questions, research and an evidence map for each |
| [`interview-answers`](interview-answers) | True STAR stories and answers to the hard questions |
| [`salary-negotiation`](salary-negotiation) | Market research, target, walk-away and the counter-offer |
| [`remote-international-jobs`](remote-international-jobs) | Remote eligibility, EOR and contractor pay, visas and scams |

Six more are planned: job search strategy, career profile, application tracker, career change and others. See the [full set online](https://afeezadebayo.com/skills-md/productivity/jobs-careers/).

## Install

```bash
git clone https://github.com/afeezadebayo/jobs-careers.git
# Claude Code
cp -r jobs-careers/cv-writer ~/.claude/skills/
# Codex and other agents
cp -r jobs-careers/cv-writer ~/.agents/skills/
```

In Claude.ai or Claude Desktop, zip a single skill folder and upload it under **Settings → Capabilities → Skills**.

Then ask your agent, for example: *"Here is the job description. Tailor my CV."* or *"Find me new remote product marketing roles posted this week."*

## Start here

1. Write your **job search profile** and **career profile** once. Both `daily-job-opportunities` and `cv-writer` include the templates.
2. Run `daily-job-opportunities` each morning, or schedule it.
3. Send the roles you pick to `cv-writer` and `cover-letter-writing`.

## Licence

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/). Use, share and adapt, including commercially, with credit to Afeez Adebayo and a link to the source page in each file.
