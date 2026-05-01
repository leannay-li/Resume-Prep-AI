# Concept Mastery Guide

**For:** Anyone with a learning checklist who wants to master each concept deeply  
**Use when:** You have concepts from `gap-analyzer` and want interview-ready understanding, not just surface knowledge  
**Invocation:** `/concept-mastery-guide`

## What It Does

Takes ONE concept from your learning checklist and teaches it deeply through thought experiments. Not reading docs—actually thinking through how the concept works in your specific project.

Output: Clear understanding + study notes you can use for interview prep.

## When to Use It

✅ **Use this if:**
- You have a learning checklist from `gap-analyzer`
- You want to move from "heard of it" to "can explain and apply"
- You have time for deep learning (1-2 hours per concept)
- You want interview-ready understanding, not surface knowledge

❌ **Don't use if:**
- You just need a quick refresher (use a reference doc instead)
- You're 5 minutes before an interview (too late)
- You don't have a specific learning checklist yet (start with `gap-analyzer`)

## How to Use It

1. Run `/concept-mastery-guide`
2. Pick ONE concept from your learning checklist
3. Tell Claude:
   - What you already know about it
   - How it applies to your enhanced project
   - Your current level (🟢 Already know / 🟡 Know basics / 🔴 Completely new)
4. Work through plain-language explanation + thought experiments
5. Get study notes to save for interview prep
6. Come back for next concept when ready

## What You Get

**For each concept:**

- **Plain-language explanation** — What the concept is, why it matters, common misconceptions
- **Project application** — Exactly how you'd use it in your enhanced design
- **Thought experiment walkthrough** — Normal case → edge case → scaling case
- **Study notes** (markdown):
  - One-paragraph plain English summary
  - 3-5 key concepts
  - Project application details
  - Common gotchas and gotcha fixes
  - Interview talking points (how to explain confidently)

## Example

**Your concept:** "Microservices decomposition"

**You currently:** "Know the idea but haven't designed one"

**What happens:**

1. **Plain explanation** — What microservices are, why companies use them, what breaks when done wrong
2. **Project connection** — "Your task management system would split into: User Service, Task Service, Notification Service. Why? Because they scale independently and fail independently."
3. **Thought experiments:**
   - Normal case: User creates task → Task Service stores it → Notification Service sends email
   - Edge case: Notification Service is down. Do tasks get created? (Yes. Do users get emails? No. Is that acceptable?)
   - Scaling: 1M concurrent users. Which service hits the bottleneck first? How do you know?
4. **Study notes** — You save these for interview prep

**Interview scenario (later):**
- Interviewer: "Walk me through how you'd decompose this system"
- You: *Confidently explains microservice split, why you chose those boundaries, what would break without them*
- No red flags ✅

## Key Principles

- **Thought experiments over reading** — You learn by thinking, not consuming docs
- **Always project-specific** — Abstract concepts are confusing; concrete examples unlock understanding
- **Edge cases matter** — Happy path doesn't test understanding; edge cases do
- **Interview-focused** — Study notes directly become your talking points
- **One concept at a time** — Depth over breadth. Master each before moving on.
- **Pauseable** — Study one concept, take a break, come back for the next

## The Learning Layer System

Pick which layer matches your baseline:

**🟢 Already Know** (~30 min)
- You can explain the concept
- Focus: Application scenarios and edge cases
- What you'll learn: Advanced nuance and gotchas
- Study notes: Short + focused

**🟡 Know Concept, Need Practice** (~1-1.5 hours)
- You've heard of it, understand basics
- Focus: Deeper understanding + multiple project scenarios
- What you'll learn: How to apply, edge cases, when NOT to use
- Study notes: Comprehensive with examples

**🔴 Completely New** (~1.5-2 hours)
- Never used it, don't fully understand it
- Focus: First principles → plain explanation → project connection → thought experiments
- What you'll learn: Solid foundational understanding
- Study notes: Detailed with analogies and gotchas

## Tips

1. **Be honest about your baseline** — Saves time and sets expectations
2. **Work through thought experiments yourself first** — Then discuss with Claude
3. **Save study notes after every concept** — These become your interview study deck
4. **Compile notes as you go** — By the time you finish the checklist, you have a complete study guide
5. **Use these notes with `mock-interview`** — Test your understanding after 3-5 concepts

## Typical Workflow

1. Finish `gap-analyzer` → Get learning checklist (🔴 Core + 🟡 Important items)
2. Pick first concept (usually a 🔴 Core item)
3. Run `/concept-mastery-guide` for that concept
4. Get study notes, save them
5. Repeat for 3-5 concepts
6. Run `/mock-interview` to test your understanding
7. Identify weak areas → Come back to `concept-mastery-guide` for those gaps
8. Repeat until confident

## What Happens Next

- After 3-5 concepts: Run `mock-interview` to test understanding under pressure
- Interview doesn't go well on a topic? Come back here for that gap
- Keep building your interview study notes across all concepts
- By interview time, you have deep understanding + notes to study from

---

**Duration:** 30 minutes–2 hours per concept (depends on baseline)  
**Output:** Clear understanding + study notes for interview prep  
**Pairs with:** `gap-analyzer` (input: learning checklist) → `concept-mastery-guide` (learn) → `mock-interview` (test) → Back to this if gaps found
