---
name: daily-job-opportunities
description: "Run a daily search for new roles that fit the user: three qualifying routes (remote, senior home-country roles at strong employers, sponsored roles abroad), an affordability gate, ATS-first searching with verification on the employer's own page, freshness and repeat logs, scam checks, ranking, compact or detailed lists and a scheduled-task setup. Use whenever someone asks to find jobs, wants a daily job list or job alert, new roles today, remote or visa-sponsored job searches, ATS job searches or a scheduled job search task."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/daily-job-opportunities/
  category: productivity
  subcategory: jobs-careers
  version: "1.1.0"
  created: "2026-10-12"
  updated: "2026-10-12"
---

# Daily Job Opportunities

Job hunting by scrolling boards every morning is slow and leaky. The same roles reappear under different links, stale postings sit beside fresh ones, scams slip in, and the best roles get missed because they were only posted on a company's own careers page. Applying early matters: in recent recruiter interviews, about half said applying within the first 48 to 72 hours makes a CV much more likely to be reviewed. [Reported, Enhancv recruiter research 2026]

This skill runs a daily search for new roles that fit the user, checks each one on the employer's own applicant tracking system (ATS) or careers page, removes repeats, scams and roles the user cannot take, keeps only employers likely to pay well, ranks what is left and delivers a short list with direct application links. It runs on request or as a scheduled daily task. It never applies to anything; the user picks.

## Operating principles
1. **Fresh and real.** Every role is opened on the employer's own page, confirmed open and dated before it is listed.
2. **Never repeat.** Nothing sent before appears again unless the employer has truly republished it.
3. **Gates before scores.** Eligibility, location route, seniority, affordability and platform rules remove roles first; ranking happens only among roles that pass.
4. **Direct links only.** Job boards can help discovery, but the link given is the company's own ATS or careers page for that exact role.
5. **The user decides.** The list is a shortlist, not an application run.

## Set up: the user's search profile
Ask once, save as `job-search-profile.md`, and reuse it every day.
```
## Who I am (used to judge fit)
Headline: years of experience, specialism, home city and country
Current and recent roles with 1 to 3 results each
Strongest areas, sectors, tools, highest qualification
## Roles to find
Titles and close variants | Minimum seniority (e.g. Manager and above)
Work types: full-time, contract, freelance, consulting
## Where the role must be (a role qualifies through any one route)
1. Remote: open to worldwide, my region or my country
   Accept employer of record (EOR) or contractor setups: yes/no
2. Home country: only if title is <levels> AND company is <quality bar>
3. Other countries: only with visa sponsorship or relocation support
## Affordability
Company types that pay my level | Types to skip | Minimum pay
## Rules
Freshness window (default 7 days, prefer 72 hours) | Repeat window (default never)
Platforms to skip (e.g. Workday) | English variant | Banned punctuation
Output mode: compact or detailed | List size (default 10 to 20)
Delivery: chat, email or messaging tool, time and time zone
## Logs
Shortlist log: job-shortlist-log.md
```
If the user gives only a title and location, start with sensible defaults, state them, and ask for the rest after the first list.

## When to use, and when not to
Use it for "find me jobs", a daily job list or alert, new roles today, remote, home-country or visa-sponsored searches and scheduled job searches.

Don't use it to write CVs (`cv-writer`), to judge one role in depth (`job-fit-evaluation`) or to submit applications. Never create accounts on job sites or sign up to talent pools without asking.

## The three qualifying routes
A role qualifies if it meets any one route in the profile.

| Route | Include | Exclude |
|---|---|---|
| 1. Remote | Open worldwide, to the user's region (e.g. EMEA, Africa) or country; full-time, contract, freelance or consulting | Remote limited to countries the user cannot work from, unless the company accepts EOR or contractor setups and the user does too |
| 2. Home country | Remote, hybrid or on-site roles that meet the seniority bar (e.g. Head, Senior, Lead, Director) and the company bar (e.g. well-funded or well-known startup, listed company, 100+ employees) | Junior titles; small or unproven employers |
| 3. Other countries | Postings that state visa sponsorship or relocation support, or companies with a public sponsorship record (e.g. the UK Home Office register of licensed sponsors) | Postings saying sponsorship is unavailable or that candidates must already have the right to work |

Mark route 3 roles with the sponsorship country.

## Affordability gate
Keep employers likely to pay the user's level: funded startups (seed with strong backing, Series A or later, or known revenue), profitable bootstrapped companies, public companies, large established firms, or roles with a competitive posted salary. Skip low-paying agencies, unfunded pre-revenue startups and vague gig listings. When funding is unclear, check the company site and recent news briefly; if still unclear, leave it out.

## Where to search
Use site: searches combining role keywords with location terms ("remote", "EMEA", "worldwide", the home country and city, "visa sponsorship", "relocation").

| ATS | Domains |
|---|---|
| Greenhouse | boards.greenhouse.io, job-boards.greenhouse.io, job-boards.eu.greenhouse.io |
| Lever | jobs.lever.co, jobs.eu.lever.co |
| Ashby | jobs.ashbyhq.com |
| Workable | apply.workable.com, jobs.workable.com |
| SmartRecruiters | jobs.smartrecruiters.com |
| Recruitee, Teamtailor, Breezy | *.recruitee.com, *.teamtailor.com, *.breezy.hr |
| BambooHR, JazzHR, Zoho Recruit | *.bamboohr.com, *.applytojob.com, *.zohorecruit.com |
| `SeamlessHiring` | `*.seamlesshiring.com`, used by many Nigerian employers |
| Workday | *.myworkdayjobs.com, *.myworkdaysite.com (skip if the profile excludes it) |

Also check careers pages of target employers. Boards such as LinkedIn, Indeed, Glassdoor, Jobberman, MyJobMag, Wellfound and remote boards are for discovery only; follow every role back to the employer's page, and never send a board or aggregator link.

## Workflow

### Step 1. Read the log
Open `job-shortlist-log.md` first. If the file or memory tools are unavailable, say so in the last line instead of guessing.

### Step 2. Search within a budget
Run queries per title variant, route and location term, for example up to 15 searches and 25 page opens per run, so scheduled runs stay quick and cheap.

### Step 3. Open and verify each role
On the employer's page, confirm the role is open, read the posted date from the page or its structured data (datePosted), and note location rules, contract type, sponsorship wording and any salary. Drop roles older than the freshness window; list a role with an unconfirmed date only as "date unconfirmed". Drop any role without a working direct link.

### Step 4. Remove repeats
A role is a repeat if its job ID or link matches the log, or company and title match a logged line ignoring small wording changes. The only exception is a true new listing: republished on the employer's ATS with a new ID and a later posted date. Mark it "New listing".

### Step 5. Check legitimacy
Drop postings that ask for fees or equipment purchases, use only WhatsApp, Telegram or personal email, have no real company site, or request ID or bank details before an interview. Flag pay far above market with vague duties, and adverts reposted for months as possible ghost jobs.

### Step 6. Apply the gates
Remove roles that fail the qualifying routes, seniority, affordability, skipped platforms, excluded companies or the user's minimum pay.

### Step 7. Rank
Rank survivors by match to the user's strongest experience and sectors, seniority fit, company quality and ability to pay, and strength of eligibility (open remote access or confirmed sponsorship first).

### Step 8. Estimate salary (detailed mode)
Give the posted band if any, plus a researched 70th to 90th percentile range for that title, hiring region, industry, company tier and the user's level, with a recommended ask at or above the user's minimum. Label it an estimate.

### Step 9. Deliver
Use the chosen output mode. Aim for the list size; repeats never count towards it. If fewer than 5 roles qualify, send what you found and add one line saying so.

### Step 10. Log what was sent
Append each role straight after sending: `- listed YYYY-MM-DD | Company | Job title | Direct link`

## Output modes
**Compact** (one line per role, nothing else):
```
1. Company | Job title | Direct application link
2. Company | Job title | Direct application link | Visa sponsorship, <country>
```
**Detailed** (adds context for each role):
```
1. Company | Job title | Direct link | Location and type | Posted <date> |
   Recommended ask: <figure> (70th to 90th pct <range>) | Why it fits: <one line>
Flags: <eligibility or legitimacy notes>
Next: reply with the numbers you want CVs for.
```
Follow the profile's language rules, such as British English or no em dashes, in every list.

## Running it as a daily scheduled task
Create a daily task in Claude, Codex or another agent with a prompt like:
```
Run the daily-job-opportunities skill with my job-search-profile.md.
Read job-shortlist-log.md first; never repeat a role.
Search employer ATS pages directly; verify each role is open,
posted within 7 days (prefer 72 hours) and has a direct link.
Apply my three qualifying routes, affordability gate and skipped
platforms, rank the rest and send 10 to 20 roles in compact mode
using my delivery channel. Log every role sent. Do not apply.
```
Scheduled runs often lack a browser or account access. Still search and verify with web tools, say which checks could not be done, and never claim an application was submitted.

## After the user picks
Send picked roles to `cv-writer`. Check the application log so no role is applied to twice. An agent may submit only roles the user explicitly picked, with tools to do it properly, and must stop for logins, CAPTCHAs, payments, ID documents or any question it cannot answer truthfully.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Few matches | Widen title variants or regions and say what was widened |
| Hundreds of matches | Tighten freshness or seniority; keep the best |
| Remote role open to "EMEA" but excluding some countries | Check the user's country against the list |
| Sponsorship not mentioned | Include only if the company has a public sponsorship record |
| Board-only posting | Skip, or mark "unverified" if the profile allows |
| User changes preferences | Update the profile file and confirm |

## Handoffs to related skills
- Tailoring documents: `cv-writer`
- Judging one role in depth: `job-fit-evaluation`
- Tracking applications: `application-tracker`
- Search strategy and target companies: `job-search-strategy`
- Remote and international rules: `remote-international-jobs`

## Worked example
A growth marketer wants manager-level roles: remote roles open to their region, home-country roles only at Head or Director level with funded or listed employers, and overseas roles with sponsorship. They skip Workday and want 10 to 20 roles in compact mode by 7:30. The run reads the log, searches Greenhouse, Lever, Ashby, Workable and `SeamlessHiring`, opens 28 roles, drops 6 repeats, 3 older than 7 days, 2 remote roles limited to the US, 1 Workday role, 1 unfunded startup and 1 asking for a fee, then sends 14 ranked lines, two marked "Visa sponsorship, United Kingdom", and logs them.

## Common mistakes
- Sending board or aggregator links.
- Calling a role fresh without checking the date.
- Sending the same role again under a new link.
- Ranking before applying routes and gates.
- Padding the list with weak or old roles.

## Self-check before you answer
- Was the log read first, and will every role be logged?
- Is every link the employer's own page, open and dated?
- Does every role pass a qualifying route, the affordability gate and the platform rules?
- Does the output match the chosen mode exactly?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/daily-job-opportunities/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
