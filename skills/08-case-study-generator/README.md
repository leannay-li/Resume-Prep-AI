# Case Study Generator

**For:** Anyone wanting to deepen understanding of their project experience  
**Use when:** You have resume bullets and want to expand them into detailed narratives  
**Invocation:** `/case-study-generator`

## What It Does

Expands ONE resume bullet (1-2 lines) into a complete STAR case study. Also performs an honest audit: what do you truly understand vs what needs learning?

Foundation skill for interview prep and deep experience work.

## When to Use It

✅ **Use this if:**
- You have resume bullets you want to deepen
- You're doing serious interview prep
- You want to know what you truly understand about your projects
- You're preparing to talk about projects in detail

## How to Use It

1. Run `/case-study-generator`
2. Pick ONE bullet to expand
3. Answer detailed questions about that project:
   - What was the context?
   - What did YOU specifically do?
   - Why did you make each technical choice?
   - How did you measure impact?
4. Get complete STAR case study + honesty audit
5. Next: Use with `gap-analyzer` to find learning gaps

## What You Get

**Complete STAR case study:**
- **Situation:** Project context, team, your role
- **Task:** Scope of your responsibilities  
- **Action:** Every technical decision explained (why? how?)
- **Result:** Measurable outcomes with evidence

**Honesty audit** with tags:
- ✅ **Solid:** You remember specifics, can explain, have evidence
- 🟡 **Inflated:** You did it, but numbers are estimated/exaggerated or you weren't the main owner
- ❓ **Unclear:** Fuzzy memory, unsure of role, or made-up numbers

## Example

**Your bullet:**
> "Built real-time task management system using React and Node.js, improving team productivity by 30%"

**Case study captures:**
- Why real-time? (WebSockets? Polling?)
- How many team members? Your specific role?
- Did you own frontend, backend, or both?
- The 30% improvement—measured or estimated?
- Is it in production? Real users?
- What challenges came up?

**Audit might show:**
- ✅ Solid: "Built WebSocket integration myself"
- 🟡 Inflated: "30% productivity improvement" (team estimate, not measured)
- ❓ Unclear: "Real-time updates" (don't fully understand failure modes)

## Why This Matters

In an interview:
- Interviewer asks: "Walk me through how real-time updates work"
- You hesitate because you don't truly understand it
- Red flag 🚩

With a case study:
- You've already thought through the details
- You can explain confidently
- No red flags ✅

## Key Principle

**Marking something "Inflated" or "Unclear" is NOT bad.** It's data for what you need to learn before the interview. The point is to expose gaps early, then fill them.

## The Honesty Tags

| Tag | Meaning | Next Step |
|-----|---------|-----------|
| ✅ Solid | You truly understand this | Confident in interview |
| 🟡 Inflated | Numbers estimated, not exact | Be honest about how you measured |
| ❓ Unclear | You don't fully understand | Study this before interview |

## Tips

1. **Be thorough** — Answer every question fully, messy is fine
2. **Be honest** — Don't gloss over what you don't know
3. **Get specific** — "API" is vague; "REST API with 50 endpoints" is specific
4. **Go deep on decisions** — "Why X not Y?" is the interview question
5. **Gather evidence** — Can you show metrics? Code? Users?

## What Happens Next

1. This case study becomes input for `gap-analyzer`
2. Gap analyzer compares your project to a target job
3. Identifies what you need to learn
4. `concept-mastery-guide` teaches those gaps
5. `mock-interview` tests your new knowledge

## Standalone or Part of Deep Work

Can use just for clarity (one-off expansion), OR as Step 1 of the full deep learning system:
1. case-study-generator (expand bullet)
2. gap-analyzer (find gaps vs target JD)
3. concept-mastery-guide (study the gaps)
4. mock-interview (test yourself)

---

**Duration:** 30-45 minutes per bullet  
**Output:** Complete STAR case study + honesty audit  
**Pairs with:** `gap-analyzer` → `concept-mastery-guide` → `mock-interview`
