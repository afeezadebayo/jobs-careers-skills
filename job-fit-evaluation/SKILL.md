---
name: job-fit-evaluation
description: "Evaluate one job posting before writing a CV: deal-breaker gates for work rights, location, level, pay and hard requirements, an evidence map against the career profile, stretch, fit or overqualified level, legitimacy checks, weighted scoring only after the gates, A to F grades with clear decisions and an application plan. Use whenever someone asks whether to apply, how well they fit a role, to compare job postings, which roles deserve a tailored application, or to prepare for a recruiter screening call."
license: CC-BY-4.0
metadata:
  author: Afeez Adebayo
  author_url: https://afeezadebayo.com
  author_linkedin: https://www.linkedin.com/in/afeez-adebayo/
  author_x: https://x.com/za_icon
  source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/job-fit-evaluation/
  category: productivity
  subcategory: jobs-careers
  version: "1.0.0"
  created: "2026-10-10"
  updated: "2026-10-12"
---

# Job Fit Evaluation

Applying to everything feels productive but wastes the hours that matter. Each tailored application takes time, and most rejections come from roles that were never a real fit: wrong level, wrong location rules, pay far below expectations, or requirements the candidate cannot evidence. The opposite mistake is just as costly: skipping a strong role because the title looked unfamiliar.

This skill evaluates one job posting before any CV is written. It checks deal-breakers first, maps each requirement to real evidence in the user's career profile, judges level and pay, checks the posting is legitimate, grades the fit and gives a clear decision: apply, apply with a plan for the gaps, or skip. The approach borrows a lesson from open-source job tools such as career-ops: a weighted average quietly rewards roles that are mediocre at everything, so fatal flaws are checked separately before any score.

## Operating principles
1. **Gates before scores.** Eligibility, location, minimum pay and hard requirements are pass or fail; a high score cannot rescue a failed gate.
2. **Evidence, not vibes.** Every "strong match" points to a line in the career profile.
3. **Honest gaps.** Missing requirements are listed with how much they matter.
4. **Decision-ready.** The output ends with a clear recommendation and the next step.
5. **Cheap to run.** Keep research brief, for example up to five searches about the company per role.

## Inputs
- The full job posting (URL or text).
- The user's career profile (`career-profile.md`) or CV.
- The job search profile (`job-search-profile.md`) with deal-breakers: work rights, locations, minimum pay, seniority, contract types, excluded industries.
- Optional: what the user wants next (growth, pay, stability, remote) to weight the score.

## When to use, and when not to
Use it for "should I apply?", "how well do I fit this role?", comparing two or three postings, deciding which roles from a daily list deserve tailored applications and preparing for a recruiter call.

Don't use it to write the CV (`cv-writer`) or to search for roles (`daily-job-opportunities`).

## Workflow

### Step 1. Summarise the role
Title, seniority, team, reporting line, location rules, contract type, salary if posted, and the main problem the role exists to solve (labelled as inference).

### Step 2. Check the gates
| Gate | Pass when |
|---|---|
| Work rights and location | The user can legally work where the role is based, or the remote rules include their country or setup |
| Seniority | Within one level of the user's current or target level |
| Pay | Posted pay, or a researched estimate, is at or above the user's minimum |
| Hard requirements | Licences, clearances, degrees or languages marked essential are met |
| Contract type | Matches what the user accepts |
| Exclusions | Not an excluded industry or company |

Any failed gate ends the evaluation with "Skip" and the reason, unless the user asks to continue.

### Step 3. Map requirements to evidence
```
| Requirement | Essential? | Profile evidence (role, line) | Strength |
| Lifecycle email at scale | Essential | Role 2: onboarding journeys, +18% activation | Strong |
| SQL | Essential | Role 3: weekly reporting in SQL | Partial |
| Team management | Desirable | None | Gap |
```

### Step 4. Judge the level
Classify the move as **stretch** (one level up; apply with strongest evidence first), **fit** (same level) or **overqualified** (below the user's level; check pay and growth before applying).

### Step 5. Check legitimacy and quality
| Signal | Meaning |
|---|---|
| Posting only on boards, no employer page | Verify before investing time |
| Reposted for months with no change | Possible ghost job |
| Fees, chat-app-only contact, ID requests early | Scam; skip |
| Recent layoffs or funding trouble in the news | Ask about stability in the first call |
| Vague duties with very high pay | Treat with caution |

### Step 6. Score the fit (only after the gates)
| Dimension | Weight (default) |
|---|---|
| Match to essential requirements | 30% |
| Match to desirable requirements | 10% |
| Seniority and scope fit | 15% |
| Pay versus market and minimum | 15% |
| Industry and domain match | 10% |
| Growth and learning | 10% |
| Work style, location and hours | 10% |
Adjust weights to the user's priorities and say so.

### Step 7. Grade and decide
| Grade | Score | Decision |
|---|---|---|
| A | 85 and above | Apply now, tailor fully |
| B | 70 to 84 | Apply; plan how to address the main gap |
| C | 55 to 69 | Apply only if the user wants this company or field |
| D | 40 to 54 | Usually skip |
| F | Below 40, or any failed gate | Skip |

### Step 8. Plan the application
For A and B grades: the positioning angle, the two or three results to lead with, how to address each gap, questions for the recruiter, and whether a cover letter is worth writing.

### Step 9. Add to the story bank
Note two or three achievements this role would make the user talk about at interview, so `interview-preparation` can use them.

## Output format
```
Grade: B (76) | Decision: Apply with a plan for the SQL gap
1. Role summary
2. Gates: pass/fail with reasons
3. Evidence map (essential and desirable)
4. Level: stretch, fit or overqualified
5. Legitimacy and company notes
6. Score breakdown with weights used
7. Application plan: angle, lead results, gap handling, recruiter questions
8. Story bank additions
```

## Comparing several roles
Evaluate each, then show a table of grade, decision, biggest strength and biggest risk, sorted by grade, with a recommendation on where to spend tailoring time first.

## Questions for the recruiter call
- What is the main problem this hire should solve in the first six months?
- Which requirements are essential and which are flexible?
- What is the pay range, and is it fixed by location?
- How is the team structured, and who does the role report to?
- What does the interview process look like, and how long does it take?
- For remote roles: which countries and setups can you hire in?

## Reading requirements realistically
Many postings list every skill the team could ever use. Treat a requirement as essential when it appears in the title, the first responsibilities, or is described as required, must-have or minimum. Treat the rest as desirable unless the posting says otherwise. Meeting most essential requirements and some desirable ones is usually enough to apply.

## Re-scoring after new information
Update the evaluation when a recruiter shares the pay range, the team structure or flexible requirements. A role can move from C to B after one call, or fail a gate it seemed to pass. Keep the earlier version so the user can see what changed and why.

## Edge cases and judgement calls
| Situation | What to do |
|---|---|
| Unfamiliar job title | Judge by responsibilities, not the title |
| Posting lists 20 requirements | Separate essential from desirable; most lists are wish lists |
| No salary posted | Estimate from market data and label it |
| Internal referral available | Note it; referrals can justify applying to B and C roles |
| Career change | Weight transferable evidence; expect more partial matches |
| User insists on applying to an F | Explain the failed gate, then help if they still want to |

## Handoffs to related skills
- Finding roles: `daily-job-opportunities`
- Writing the application: `cv-writer`, `cover-letter-writing`
- Remote eligibility questions: `remote-international-jobs`
- Referrals: `networking-referral-outreach`
- Interviews: `interview-preparation`

## Worked example
A user evaluates three roles from the morning list. Role one fails the location gate (US-only remote) and is skipped. Role two scores 81 (B): strong lifecycle evidence, a partial SQL match and pay inside the user's range; the plan leads with the activation result and addresses SQL with a reporting example. Role three scores 63 (C): a strong company but a junior level and pay below the minimum, so the user keeps it only as a referral target. Tailoring time goes to role two first.

## Common mistakes
- Scoring before checking deal-breakers.
- Treating every listed requirement as essential.
- Calling something a match without a profile line.
- Ignoring pay until the offer stage.
- Skipping roles because of an unfamiliar title.

## Self-check before you answer
- Were all gates checked first?
- Does every strong match cite profile evidence?
- Are weights stated and adjusted to the user's priorities?
- Is there a clear decision and next step?

---
Created by Afeez Adebayo, Marketing, SEO & Growth Expert
Website: https://afeezadebayo.com
LinkedIn: https://www.linkedin.com/in/afeez-adebayo/
X: https://x.com/za_icon
Source: https://afeezadebayo.com/skills-md/productivity/jobs-careers/job-fit-evaluation/

Licence: CC BY 4.0 (https://creativecommons.org/licenses/by/4.0/). You may copy, share and adapt this skill, including for commercial use, as long as you credit Afeez Adebayo and link to the source URL above. Keep this notice in any copy or adapted version.
