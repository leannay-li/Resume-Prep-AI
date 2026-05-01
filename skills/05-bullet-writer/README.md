# Bullet Writer

**For:** Anyone with projects or work experience to showcase  
**Use when:** You want to turn a project description into 3-5 strong resume bullets  
**Invocation:** `/bullet-writer`

## What It Does

Transforms your project/job description into 3-5 high-quality, universal resume bullets using the formula: **Action + Technical Detail + Measurable Impact**.

These are "master bullets" before any JD-specific tweaking (that comes later with `bullet-reviewer`).

## When to Use It

✅ **Use this if:**
- You have a project or job experience to describe
- You want bullets that work across multiple applications
- Your current bullets are vague or lack impact
- You want to know the right level of specificity

❌ **Don't use if:**
- You're trying to optimize for a specific JD (use `bullet-reviewer` after)
- You don't have a specific project yet

## How to Use It

1. Run `/bullet-writer`
2. Be ready with:
   - Project description (what you built)
   - Technical stack (what technologies)
   - What YOU personally did (not team credit)
   - Outcomes/impact (numbers if possible)
   - Your experience level (affects verb choice)
3. Get 3-5 strong, universal bullets
4. Next: Use with `bullet-reviewer` to tailor for specific JDs

## What You Get

Strong bullets like:

> "Built real-time notification system using WebSockets and Redis, reducing message delivery latency from 5 seconds to 200ms, enabling 12M+ daily messages"

Key qualities:
- ✅ Strong action verb
- ✅ Specific technical detail
- ✅ Measurable impact (numbers or outcome)
- ✅ Honest and specific

## The Formula

**[Strong Action] [what you built] [technical approach] [specific impact]**

Examples:
- "Designed microservice architecture splitting monolith into 5 services, reducing deployment time from 2 hours to 15 minutes"
- "Optimized database queries using strategic indexing, improving P95 latency by 55%, enabling real-time dashboard"
- "Built Python data pipeline for customer analytics, processing 100M events/day, providing insights that improved retention by 8%"

## Action Verbs by Level

**New grad:** Built, Created, Developed, Implemented  
**Junior (1-3 yrs):** Designed, Architected, Optimized, Led  
**Mid (3-5 yrs):** Architected, Spearheaded, Scaled, Transformed  
**Senior (5+ yrs):** Led, Architected, Transformed, Pioneered

## Impact Hierarchy

1. **Measured Metrics** (Best)
   - "Reduced latency by 35%"
   - "Increased revenue by $2M/year"

2. **Calculated Estimates** (Good)
   - "Serving 10M+ users"
   - "Processing $50M annual volume"

3. **Qualitative** (Acceptable)
   - "Enabled real-time features"
   - "Unblocked team from 2-week blocker"

4. **None** (Not great, but honest)
   - Better to be honest with no impact than make up numbers

## Tips

1. **Lead with impact** — Put the number/outcome first
2. **Be specific** — "Reduced latency" beats "improved performance"
3. **Honest first** — Don't exaggerate or invent numbers
4. **Personal credit** — Even if part of a team, be clear on your contribution
5. **Strongest first** — If you have 6 bullets, cut to 4-5 strongest

## Common Mistakes to Avoid

- ❌ Vague impact ("Improved system")
- ❌ Tool-focused ("Used React and Node.js")
- ❌ Invented numbers ("Improved by 500%")
- ❌ Missing impact ("Built feature")
- ❌ Too many bullets (3-5 is ideal, 6+ is too many)

## Next Steps

1. Get bullets from this skill
2. For specific JD → `/bullet-reviewer` (optimize/tailor)
3. Once you have bullets + summary → `/resume-system-orchestrator`

---

**Duration:** 20-30 minutes  
**Output:** 3-5 strong, universal bullets per project  
**Pairs with:** `bullet-reviewer` (tailor for JD) → `resume-system-orchestrator` (assemble)
