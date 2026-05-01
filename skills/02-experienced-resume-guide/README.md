# Experienced Resume Guide

**For:** People with 1-5 years of professional work experience  
**Use when:** You're building or revamping a resume and want to shift from describing job duties to showing impact  
**Invocation:** `/experienced-resume-guide`

## What It Does

Provides strategic guidance for someone with professional work experience. The core shift: from "Here's what I did" to "Here's what happened because I did it."

Key questions it answers:
- What goes where on a resume for someone with experience?
- How do I find and quantify impact?
- How do I position the same experience differently for different roles?
- Should I have multiple resume versions?
- What are the biggest mistakes experienced hires make?

## When to Use It

✅ **Use this if:**
- You have 1-5 years of full-time work experience
- Your current resume lists job duties instead of impact
- You want to position your experience for different role types
- You're unsure how to quantify your contributions

❌ **Don't use if:**
- You're a new grad (use `new-grad-resume-guide` instead)
- You have 5+ years (you likely know the fundamentals, just refine with other skills)
- Your resume already emphasizes impact clearly

## How to Use It

1. Run `/experienced-resume-guide`
2. Answer the questions:
   - How many years experience? What roles?
   - What's your strongest achievement?
   - Do you have measured impact numbers?
   - Are you targeting different role types?
   - Do you have an existing resume?
3. Get tailored strategy for impact-driven resume
4. Next: Move to `summary-writer` or `bullet-writer`

## What You Get

A framework including:
- **Structure guidance** — For experienced hires (Work Experience moves to top)
- **Impact extraction** — How to find measured, estimated, or qualitative impact
- **Quantification strategies** — Examples of strong metrics
- **Role-specific positioning** — How to tell different stories for Backend vs Data vs Product
- **Multi-resume strategy** — When and how to create different versions
- **Before/After examples** — Duty-focused vs impact-focused bullets

## Example Guidance

**You tell it:** "I have 3 years as a backend engineer, led a database optimization project"

**It responds:**
```
Current approach:
❌ "Led database optimization project"

Better:
✅ "Redesigned database schema and optimized queries, reducing P95 latency from 800ms to 150ms, enabling real-time features now used by 10M+ monthly users"

Key shift: Lead with impact (latency improvement), show scale (10M users), explain what it enabled (real-time features)

Do you have the latency numbers? If not, can you estimate:
- How many users were affected?
- What business value resulted?
- Was revenue impacted? Cost savings?

For multi-resume: If you're targeting Data roles, emphasize the data pipeline aspects. For SRE roles, emphasize monitoring/reliability. Same project, different emphasis.
```

## Key Principles

- **Impact beats job duties** — "Improved X" beats "Responsible for Y"
- **Quantify when possible** — Measured > Estimated > Qualitative, but all beat vague
- **Find the business angle** — Users affected, revenue, cost savings, time saved
- **Same experience, different stories** — Tailor emphasis for different role targets
- **Own your contribution** — Even if it was a team effort, show your role clearly

## Hierarchy of Impact Numbers

1. **Measured Metrics** (Best)
   - "Reduced customer churn by 12%"
   - "Improved latency by 35%"
   
2. **Calculated Estimates** (Good)
   - "Impact X people/features"
   - "Estimated $500K annual cost savings"
   
3. **Qualitative Impact** (Acceptable)
   - "Unblocked team from 2-week blocker"
   - "Shipped 3 weeks ahead of schedule"

## Tips

1. **Numbers first** — Put the metric in the first line
2. **Estimate if needed** — Better to estimate than vague
3. **Ask your manager** — They may have impact data you forgot
4. **Look at tools you used** — Often hidden in tooling is business impact
5. **Impact > implementation detail** — Don't focus on tech, focus on result

## Common Mistakes to Avoid

- ❌ Listing tools without impact ("Used Kubernetes")
- ❌ Vague claims ("Improved performance")
- ❌ Burying impact ("Did X, Y, Z, and also reduced costs by 30%")
- ❌ Underestimating scope ("Worked on API")
- ❌ Not enough bullets (3-5 per role is good)

## Next Steps After This

1. If you're targeting a specific role direction → `/summary-writer`
2. For your work experiences → `/bullet-writer`
3. For optimization with a target JD → `/bullet-reviewer`
4. To assemble everything → `/resume-system-orchestrator`

---

**Duration:** 20-30 minutes  
**Output:** Resume structure framework + impact strategy + examples  
**Pairs with:** `summary-writer` → `bullet-writer` → `resume-system-orchestrator`
