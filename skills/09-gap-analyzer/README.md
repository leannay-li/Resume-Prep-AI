# Gap Analyzer

**For:** Anyone doing deep interview prep with a target role  
**Use when:** You have a case study and a target JD. Want to know what gaps exist and what to learn.  
**Invocation:** `/gap-analyzer`

## What It Does

Analyzes the gap between your actual project experience and a target job description. Produces a comprehensive 6-part report including:
- Relevance assessment
- Gap breakdown
- Enhanced project design
- Learning roadmap
- Timeline
- Before/After comparison

## When to Use It

✅ **Use this if:**
- You've done a case study for a project
- You have a specific target JD
- You want to know what you need to learn
- You want to design a realistic learning plan

## How to Use It

1. Run `/gap-analyzer`
2. Provide:
   - Your case study (from `case-study-generator`)
   - Target job description
   - Your experience level
3. Get comprehensive gap analysis report
4. Next: Use learning checklist with `concept-mastery-guide`

## What You Get

**6-part diagnostic report:**

### 1. Relevance Assessment
Is this project worth improving for this role? (Highly relevant? Moderately? Too weak?)

### 2. Gap Breakdown
Every gap listed with severity:
- 🔴 Core gaps (must close)
- 🟡 Important gaps (should close)
- 🟠 Nice-to-have gaps (good to have)

### 3. Enhanced Project Design
Realistic upgrade of your same project (not a new project):
- Same business context
- Same project topic
- Deeper technical capabilities
- Reachable in 3-6 months

### 4. Learning Checklist
Every skill organized by priority:
- 🔴 Must-have (3-5) — Core JD requirements
- 🟡 Nice-to-have (2-3) — Bonus requirements
- 🤖 Ideal state (1-2) — Stretch goals
- 🤝 Soft skills (1-2) — Collaboration scenarios

### 5. Enhancement Timeline
3-6 month learning roadmap:
- Month 1: Foundations
- Month 2: Core implementation
- Month 3: Integration & polish

### 6. Before/After Comparison
- Positioning shift (what changes about you)
- Project maturity shift (architecture, practices, etc.)
- Resume bullets before/after

## Example

**Your project:**
- Task management app in JavaScript (React + Node.js)

**Target JD:**
- IBM Entry-Level Software Engineer (Java, distributed systems)

**What Gap Analyzer reveals:**

Relevance: Moderately relevant, on the weak side
- You have CI/CD and API experience ✅
- You're all JavaScript, they want Java 🔴
- You have monolith, they want distributed systems 🔴

**Enhanced version:**
- Same CloudStep company, same timeframe
- Backend rewritten in Java + Spring Boot
- Split into 3 microservices
- Add RabbitMQ for async communication
- Deploy to Kubernetes

**Learning checklist (Must-have):**
- Java + Spring Boot
- Microservice decomposition
- Message queues (RabbitMQ)
- Kubernetes deployment

**Before/After bullets:**

Before: "Built full-stack task platform with React and Node.js"

After: "Architected task management as 3 Java Spring Boot microservices, designed async messaging with RabbitMQ, deployed on Kubernetes—processing 100K+ task records with sub-200ms P95 latency"

## Key Principles

- **Enhanced, not new** — Same project, deeper
- **Same context** — Same company, role, timeframe
- **Realistic scope** — Actually reachable in 3-6 months
- **Believable narrative** — Reads like a real project evolution

## What Happens Next

The learning checklist from this report becomes input for `concept-mastery-guide`. You'll go through each concept one-by-one, learning it deeply.

## Timeline Reality Check

When you see the 3-6 month timeline, remember:
- This is LEARNING time, not implementation time
- You're building understanding, not rebuilding code
- Next step (`concept-mastery-guide`) compresses this into focused thought experiments

## Tips

1. **Honest relevance assessment** — If verdict is "weakly relevant," consider a different project
2. **Read the enhanced design carefully** — Does it feel believable? Reachable? If not, ask for revisions
3. **Trust the learning checklist** — This is your roadmap
4. **The timeline is guidance** — Adjust based on your actual pace

## Next Steps

1. Get the gap analysis report
2. Review the enhanced project design (is it believable?)
3. Take the learning checklist to `concept-mastery-guide`
4. Master each concept through guided learning
5. Test yourself with `mock-interview`
6. Rewrite bullets based on new understanding

---

**Duration:** 45-60 minutes  
**Output:** Complete 6-part gap analysis report + learning roadmap  
**Pairs with:** `case-study-generator` (input) → `concept-mastery-guide` (use learning checklist) → `mock-interview` (test)
