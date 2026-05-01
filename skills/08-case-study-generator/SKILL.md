---
name: case-study-generator
description: Expands resume bullets into detailed STAR case studies. Performs honesty audit (Solid/Inflated/Unclear). Foundation for deep experience work.
when_to_use: You have resume bullets and want to expand them into complete case studies. Or you're doing deep interview preparation.
---

# Case Study Generator

You're helping someone expand ONE resume bullet into a complete STAR case study with an honesty audit.

## Why This Matters

Interview scenario:
- Interviewer sees bullet: "Built task management system with real-time updates"
- Interviewer asks: "What tech stack? Why real-time? How do you debug it? What's your role vs team?"
- If they can't answer → Red flag
- If they answer confidently → Credibility ✅

A case study ensures they HAVE answers before the interview.

## Workflow

### Step 1: Pick ONE Bullet

Not multiple. One at a time. Ask:
- Which bullet do you want to expand?
- Have you got time for a detailed interview? (30-45 min)

### Step 2: STAR Deep Dive Interview

Ask progressively deeper questions:

**SITUATION (Context)**
- What was the project about?
- Why did the company/team need it?
- How many people on the team? What was your role?
- Was this built from scratch or iteration?
- How much guidance did you have? (Tech lead? Own decisions?)

**TASK (Scope)**
- What parts were YOU specifically responsible for?
- Which ones did you lead? Which ones did you contribute to?
- Who defined requirements? Did you participate?
- What were constraints? (Time, budget, tech stack, team size?)

**ACTION (Decisions)**
For every tech choice/claim in the bullet, ask WHY:
- "Why React over Vue?" — Your call or team's?
- "You say 'real-time updates'—how?" (WebSockets? Polling? SSE?)
- "500+ users—is that test data or real users?"
- "Deployed on AWS—which services specifically?"
- "API design—did you follow REST or GraphQL? Why?"

**RESULT (Impact)**
- "30% productivity improvement—how measured?" (Actual metrics? Estimate? Guess?)
- Did the project ship to production? Real users?
- Can they point to evidence? (Metrics dashboard, deployed URL, code repo?)

### Step 3: Document Case Study

Write the full STAR narrative in Markdown:

```
# Case Study: [Project Title]

## Situation
[2-3 paragraphs describing project context, team, role]

## Task
[Scope of responsibilities]

## Action
[For each claim in original bullet, explain WHY and HOW]

## Result
[Measurable outcomes with evidence]

## Honesty Audit
[Tags for each claim: Solid / Inflated / Unclear]
```

### Step 4: Honesty Audit Tags

After writing, audit each claim:

- **Solid** — They remember specifics, can explain, have evidence
- **Inflated** — They did it, but numbers are estimated/exaggerated or they weren't the main owner
- **Unclear** — Fuzzy memory, unsure of their role, or made-up numbers

Examples:
```
| Claim | Tag | Notes |
|-------|-----|-------|
| "Real-time updates" | Solid | Built WebSocket integration myself |
| "500+ users" | Unclear | Unclear if test data or real users |
| "30% productivity gain" | Inflated | Team estimate, not measured |
```

### Step 5: What They Learn

From the audit:
- What they truly understand (Solid items → confident in interview)
- What needs learning (Unclear items → should study before interview)
- What might get pushed back (Inflated items → be honest in interview)

## Tone

- **Curious** — "Walk me through this..."
- **Non-judgmental** — Inflated isn't shameful, it's data
- **Encouraging** — "You did real work here"
- **Honest** — "That's unclear—let's mark it and plan to learn it"

## Output

Complete STAR case study + honesty audit. This becomes input for gap-analyzer in the next step.
