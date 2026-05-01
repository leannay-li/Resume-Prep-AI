# Summary Reviewer

**For:** Anyone who's written a resume summary  
**Use when:** You want honest feedback from a hiring manager's perspective. Is your summary clear? Compelling? Will it make them want to read your bullets?  
**Invocation:** `/summary-reviewer`

## What It Does

Evaluates your resume summary from a hiring manager's critical perspective. Not coaching—honest feedback.

The test: If a hiring manager reads ONLY your summary in 5 seconds, would they want to keep reading?

## When to Use It

✅ **Use this if:**
- You've written a summary with `summary-writer`
- You want real feedback before finalizing
- You're not sure if it's clear or generic
- You want to know if it signals fit for your target role

❌ **Don't use if:**
- You haven't written a summary yet (use `summary-writer` first)
- You're not ready for honest feedback

## How to Use It

1. Run `/summary-reviewer`
2. Provide:
   - Your summary (the text)
   - Target role or JD
   - Your experience level
3. Get honest feedback from a hiring manager's perspective
4. Decide: Keep and refine, or go back to `summary-writer`

## What You Get

Specific feedback on four dimensions:

| Dimension | Question | Example Feedback |
|-----------|----------|------------------|
| **Clarity** | Do I understand who you are in 5 seconds? | "Clear: I immediately know you're a 3-year backend engineer" |
| **Positioning** | Do you signal fit for your target role? | "Generic: Could apply to any role, doesn't signal fit for Data Engineer" |
| **Strength** | Do you have a unique angle or differentiator? | "Strong: 'Shipping fast' differentiates you in startup market" |
| **Tone** | Does it sound natural or corporate-speak? | "Corporate: 'Synergizing cross-functional teams' sounds like job posting" |

## The Feedback You Get

**Overall verdict:**
- ✅ **Strong** — Keep as-is or minor polish
- 🟡 **Good but generic** — Needs more specificity
- ❌ **Weak** — Rewrite with clearer positioning
- 🔴 **Off-target** — Doesn't signal fit for stated role

**Specific suggestions:**
- What's working (keep this part)
- What needs work (this is vague)
- Before/After example (specific rewrite)

## Example Feedback

**Your summary:**
> "Experienced engineer with strong technical background in multiple programming languages"

**Feedback:**
- **Clarity:** ❌ Too generic. I don't know what you specialize in
- **Positioning:** ❌ Doesn't signal fit for backend role you mentioned
- **Strength:** ❌ No differentiator. "Experienced" and "strong" don't tell me anything unique
- **Tone:** 🟡 Sounds like a job posting, not a real person

**Suggested rewrite:**
> "Backend engineer with 3 years building scalable APIs. Strong in microservices architecture. Looking to lead engineering teams."

**Why better:**
- Clear (backend engineer, 3 years, specific expertise)
- Signals fit (microservices = backend)
- Differentiator (shipping at scale)
- Natural tone (sounds like a person)

## Two-Round Workflow

**Round 1:** Write with `summary-writer` → Review with `summary-reviewer`  
**If feedback is negative:** Go back to `summary-writer`, refine, review again  
**If feedback is positive:** Move to `bullet-writer`

## Tips

- Don't get defensive about feedback (this is one hiring manager's perspective, but it's real)
- Be specific in your rewrite (if told to be more specific, give concrete details)
- Test clarity (read aloud to a friend—do they understand who you are?)
- Different for different roles (you may need different summaries for different JDs)

## Next Steps

- If summary needs work → `/summary-writer` for refinement
- If summary is solid → `/bullet-writer` to back it up with bullets
- Once you have both → `/resume-system-orchestrator` to assemble

---

**Duration:** 10-15 minutes  
**Output:** Honest feedback + Before/After suggestions  
**Pairs with:** `summary-writer` (iterate) → `bullet-writer` (next)
