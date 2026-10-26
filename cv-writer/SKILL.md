---
name: cv-writer
description: "Write the strongest truthful CV for a specific job from the user's own career profile: full JD analysis, an evidence map tying every claim to a profile line, positioning, tailored summary, skills and bullets, careful title adaptation, regional conventions, ATS-aware but human-first writing, optional cover letter, gap and risk notes and a researched 70th to 90th percentile salary range. Use whenever someone shares a job description, asks to tailor or write a CV or resume, needs a cover letter or application answers, asks to analyse a JD, is changing careers or wants their CV checked against a role."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/cv-writer/
  category: productivity
  subcategory: jobs-careers
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-12"
---

# CV Writer

Most AI-written CVs fail in one of two ways. Some are generic: the same inflated summary and buzzword bullets that recruiters now spot instantly. Others are dishonest: invented metrics, stretched titles and tools the candidate never used, which collapse at interview or background check. Both waste the one thing a CV has, which is a few seconds of a busy recruiter's attention.

This skill writes the strongest truthful CV for a specific job. It reads the job description properly, maps every requirement to real evidence from the user's own career profile, chooses the positioning, rewrites the summary, skills and bullets for that role, adapts job titles only where the facts allow, writes a cover letter when it helps, and reports gaps, risks and a researched salary range. The rule behind everything: change the framing, never change the facts.

## Operating principles
1. **Truth first.** Every claim traces to the user's profile or something they confirm in the conversation. Nothing is invented to fill a gap.
2. **Relevance over volume.** The CV answers one question: why is this person's experience relevant to this role?
3. **Evidence beats adjectives.** Numbers with context, named tools and real outcomes replace claims like "highly motivated".
4. **Write for a human first.** Applicant tracking systems (ATS) mostly store, search and rank; people decide. Recruiter interviews in 2026 found 92% said their ATS does not auto-reject CVs for formatting or match scores. [Reported, Enhancv recruiter research 2026] Use the employer's words where they are true, never keyword stuffing.
5. **The user's design is the design.** If they have a master CV, follow its structure and style instead of imposing a template.

## Set up: the user's inputs
The skill works from files the user keeps and updates. Ask for these once, then reuse them.

**1. Career profile (`career-profile.md`), the single source of truth**
```
## Identity
Name | Email | Phone | LinkedIn | Portfolio | City, country
Years of experience (overall and by specialism) | Sectors
## Employment (newest first)
Official title | Company | Dates | One-line context about the company
Evidence bank: achievements with numbers, scope, tools, teams, markets
Approved alternative titles for this role (if any)
## Education and certifications
## Skills and tools (only those used hands-on)
## Facts needing confirmation (mark with a warning sign)
```

**2. CV preferences (`cv-preferences.md`)**
```
English variant: British or US | Target length: e.g. 2 pages, maximum 3
File output: .docx, PDF or both | File name pattern
Header rules: e.g. show phone and city only for roles in my country
Fixed lines I always use (e.g. a summary closing line)
Words or punctuation I never want (e.g. no em dashes)
Roles to compress into an "Earlier Career" block
Salary rule: e.g. research the 70th to 90th percentile; my minimum ask
```

**3. Master CV file** (optional but strongly recommended). Edit a copy of it rather than rebuilding from scratch.

If the user has none of these, build a first draft of the profile from their latest CV and LinkedIn, list the facts that need confirming, and proceed.

## When to use, and when not to
Use it for any job description, CV tailoring, cover letter, application answers, "analyse this JD" or career-change application.

Don't use it to find roles (`daily-job-opportunities`) or to decide whether a role is worth applying for (`job-fit-evaluation`). Don't use it to submit applications automatically; the user submits, or explicitly picks roles for an agent with browser or email tools to apply to.

## Default behaviour by request
| User sends | Do this |
|---|---|
| Only a job description | Tailor the CV; do not ask whether they want one |
| "CV + cover letter" | Produce both |
| "CV only" | CV only |
| "Cover letter" | Letter from the established profile |
| "Analyse this JD" | No CV yet: what they need, strongest matches, gaps, positioning, keywords |
| "Two versions" | Clearly different positioning, not swapped keywords |

## Workflow

### Step 1. Read the job description properly
Open the full posting, not a summary. Extract:
- **Role:** title, seniority, team, reporting line, location, employment type, eligibility rules.
- **Responsibilities:** primary, secondary and nice-to-have.
- **Capabilities:** functional, technical, analytical, leadership, communication, industry, commercial.
- **Keywords:** exact phrases, tools, methods, important nouns and verbs.
- **Business problem:** what the employer is trying to solve, labelled as your inference.

If the user is not eligible (location, right to work), stop and say so before writing anything.

### Step 2. Build the evidence map
Map each requirement to a specific line in the career profile, with a strength rating. Keep it internal unless asked.
```
| JD requirement | Profile evidence (role, line) | Strength |
| Lifecycle email | Role 2: built onboarding journeys, +18% activation | High |
| SQL | Role 3: "weekly reporting in SQL" | Medium |
| People management | None found | Gap |
```
A claim with no line in the map cannot appear in the CV.

### Step 3. Choose the positioning
Pick the strongest truthful identity that bridges the user's career and the role, for example "Growth marketing and analytics professional". Never claim a role they have not held.

### Step 4. Weight the experience
Give space by direct relevance, recency, seniority, size of impact, transferability, keyword fit and evidence strength. A relevant achievement beats an impressive unrelated one.

### Step 5. Write the summary
Formula: professional identity + years + core capabilities + relevant industries + one or two pieces of evidence. Two to four lines. No career objective.

### Step 6. Rebuild skills
Group logically, most relevant first, only tools used hands-on. A grid of 9 to 12 skills usually scans better than a long list.

### Step 7. Rewrite experience
- Structures: action + what + context + result, or action + scale + responsibility + outcome. Vary them; natural writing matters more than formula.
- Order bullets within each role by relevance to this JD, not chronology.
- Typical budget: current role 4 bullets, previous relevant role 4 to 6, older relevant roles 2 to 4, older unrelated roles 1 line or an "Earlier Career" block.
- Every bullet must pass at least one test: impact, scope, ownership, complexity or relevance.

### Step 8. Adapt titles carefully
See the title rules below. Company names and dates never change.

### Step 9. Run the gap analysis
Strong matches, partial matches and missing requirements. Never disguise a gap; strengthen adjacent evidence instead and report it.

### Step 10. Produce the documents
CV in the user's format and file type, cover letter if requested or clearly useful, then render to PDF and look at the pages: page count, nothing split awkwardly, no overlapping sections.

### Step 11. Check and report
Run the checklists below, then deliver in the output format.

## Never invent, reframe instead
Never invent metrics, revenue, customer numbers, team size, budgets, titles, responsibilities, tools, certifications, awards, employers, promotions, dates, qualifications, industries, leadership or management experience, product ownership or results.

Reframing is allowed when the underlying experience supports it.

| Source says | Allowed reframe for a growth product role | Not allowed |
|---|---|---|
| "Managed SEO for financial services websites" | "Led organic acquisition across financial services products, connecting search demand with acquisition and activation goals" | "Product Manager for acquisition" |
| "Worked on SEO strategy" | "Shaped SEO strategy for the main product site" | "Grew organic traffic 150%" (no source) |

When a fact would strengthen the application but is missing, ask one precise question or list it under "Facts to confirm". Facts the user confirms in the conversation become the newest source of truth; list them at the end so the profile can be updated.

## Title rules
Titles differ between companies, so a market-facing title can help a recruiter understand the role. The rule: translate the role, do not rewrite the career.

| Confidence | Example | Action |
|---|---|---|
| High | "Manager, Growth Marketing & Analytics" to "Growth Marketing Manager" | Use the functional equivalent |
| Medium | "Growth Marketing Manager" to "Product Growth Manager" | Use official title plus a functional descriptor |
| Low | "Growth Marketing Manager" to "Product Director" | Keep the official title |

Keep the official title when the target implies different responsibilities, is significantly more senior, or strict employment verification is likely. When verification risk exists, use the format **Official Title | Functional Focus**. Keep the official titles in the profile for background checks.

## Regional conventions
| Market | Convention |
|---|---|
| UK and Ireland | "CV", 2 pages typical, no photo, no date of birth or marital status |
| US and Canada | "Resume", 1 page early career, 2 pages for experienced hires, no photo or personal details |
| Much of Europe | 2 pages; photos common in some countries; follow the posting's language |
| Nigeria and much of West Africa | 2 to 3 pages common; phone and city expected for local roles; omit age, religion and marital status unless legally required |
| Remote international roles | Follow the employer's country; state time zone if the role requires overlap |

## Writing rules
- Short sentences, one idea per bullet, strong verbs, numbers that are easy to find.
- Numbers always have context: not "50,000 users" but "SEO contributing about 50,000 organic sign-ups a month".
- Use the company's vocabulary only where it describes the user's real experience. The CV should sound like a candidate, not a rewritten job advert.
- Calibrate seniority: strategy, ownership, commercial outcomes and stakeholders for senior roles; execution, tools and outputs for hands-on roles. Never inflate junior work into executive leadership.
- Priority order when rules conflict: truth, relevance, evidence, clarity, ATS alignment, style.

**Banned unless literally necessary:** `at the forefront of`, `cutting-edge`, `world-class`, `best-in-class`, `seamless`, `frictionless`, `unlock`, `leverage`, `empower`, `elevate`, `robust`, `innovative`, `dynamic professional`, `results-driven`, `passionate`, `proven track record`, `strategic thinker`, `team player`, `highly motivated`, `detail-oriented`, `navigating the ever-evolving landscape`. Respect any punctuation the user bans, such as em dashes, and search the final file for it.

## Cover letters
Answer five questions: why this role, why this company, why this experience is relevant, what evidence proves it, and why the move makes sense. Open with something specific about the role, product or problem. Use two or three strong pieces of evidence, 250 to 400 words by default, plus an 80 to 150-word version for form fields with limits.

Avoid openings such as "I am excited to apply", "Throughout my career" and "I believe I would be a great fit". Only use company facts the user supplied or you verified through research.

## Salary range
For every role, research and report a market range, by default the 70th to 90th percentile for the title, country or hiring region, industry, company tier and the user's level. Sources in order of strength: the posted band, then salary data sites and comparable postings. For remote roles, benchmark the region the employer hires in. Keep any ask inside a posted band. Respect the user's own minimum. Label figures as estimates and link the sources.

## Output format
```
1. Application positioning (3 to 5 bullets)
2. Tailored CV (file, plus a note of the page count)
3. Cover letter (when requested or useful)
4. Application notes: strong alignment, partial alignment,
   evidence gaps, positioning risks, facts to confirm
5. Salary range: 70th to 90th percentile, basis, recommended ask, sources
6. Profile updates: new facts the user confirmed in this conversation
```
Do not give the CV a score out of 10; the alignment notes are more useful.

## Final checklist
- **Accuracy:** no invented achievements, metrics, tools, qualifications; dates, employers and titles match the profile.
- **Relevance:** relevant experience first, strongest evidence prominent, weak content cut.
- **Writing:** human tone, specific language, no banned phrases, no generic objective.
- **ATS:** standard section headings, JD terms used where true, searchable skills, no keyword walls or hidden text.
- **Ten-second test:** a recruiter can tell who the user is, their specialism, seniority, industries, best results and fit.
- **Copy test:** if a sentence could sit on another candidate's CV with only the name changed, rewrite it.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Career change | Translate transferable experience into the new role's language; never claim the target title |
| Conflicting dates across old CVs | Prefer the newest confirmed source; ask if it affects eligibility |
| Required certification unclear | Ask before claiming it |
| Very senior role, 3 pages tempting | Use 3 only if cutting would lose relevant evidence, and say why |
| Employer requires a form with screening questions | Answer only from the profile; a truthful "No" beats a false "Yes" |
| Weak fit | Say so plainly in the notes rather than hiding it in the CV |

## Handoffs to related skills
- Finding roles: `daily-job-opportunities`
- Building the profile and story bank: `career-profile`
- Deciding whether to apply: `job-fit-evaluation`
- Cover letters in depth: `cover-letter-writing`
- Interviews: `interview-preparation`
- Salary talks: `salary-offer-negotiation`

## Worked example
A user with eight years in performance marketing applies for a "Lifecycle Marketing Manager" role at a fintech. The evidence map shows strong matches for email and CRM tools and segmentation, a partial match for experimentation, and a gap in SMS. The CV positions them as a "Lifecycle and performance marketing manager", moves CRM achievements to the top of each role, groups skills under Lifecycle, Analytics and Platforms, keeps the official title at a bank with verification risk as "Official Title | Lifecycle Marketing", and compresses two early roles into an Earlier Career line. The notes flag the SMS gap and suggest one confirming question about A/B testing volume. The salary section gives a researched range from the posted band and two comparable postings.

## Questions to ask before writing (only if they change the result)
- Are you eligible to work where this role is based?
- Is a required certification or tool part of your experience?
- Two sources disagree on a date or title; which is correct?

## Self-check before you answer
- Does every claim map to a profile line or a confirmed fact?
- Would a recruiter see the fit within ten seconds?
- Are gaps reported rather than hidden?
- Did the rendered pages pass inspection?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/cv-writer/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
