# Mock Interview

**For:** Anyone who's studied their concepts and wants to test interview readiness under realistic pressure  
**Use when:** You've done concept studying with `concept-mastery-guide` and want to know if you're ready for the real interview  
**Invocation:** `/mock-interview`

## What It Does

Real technical interview simulation. No teaching, no hints. You describe your project, I ask hard follow-ups, and we see if you can credibly explain and defend your work under pressure.

Output: Honest assessment of what you know, what needs work, and whether you're interview-ready.

## When to Use It

✅ **Use this if:**
- You've studied concepts from `concept-mastery-guide`
- You want to test how you'd do in a real interview
- You want honest feedback on gaps
- You have 30-45 minutes of focused time

❌ **Don't use if:**
- You haven't done concept studying yet (use `concept-mastery-guide` first)
- You just want gentle encouragement (this is tough, not friendly)
- You don't have specific project/story prepared (use `case-study-generator` first)

## How to Use It

1. Run `/mock-interview`
2. Tell Claude:
   - Which project you're interviewing about (your enhanced design from `gap-analyzer`)
   - Which role/company
   - How much time (15 min quick / 30 min full / 45 min deep)
   - Tone preference (realistic pressure or slightly gentler)
3. Claude asks follow-ups like a real interviewer
4. You answer under pressure (no hints, no teaching)
5. Get honest assessment: ✅ Ready / ⏳ Borderline / ❌ Needs work

## What You Get

**During the interview:**
- Real technical questions like a hiring manager would ask
- Follow-ups based on your answers (not scripted)
- Pressure that feels like the real thing

**After the interview:**
- **Assessment report** with:
  - What went well ✅
  - What needs review ❌
  - Specific gaps identified
  - Overall verdict: Ready / Borderline / Needs work
  - Next steps (study more or mock again)

## Example Flow

**Interview scenario:**

- Claude: "Walk me through your task management project from the top"
- You: [Explain your enhanced design]
- Claude: "You mentioned microservices. Why not keep it monolithic?"
- You: [Answer]
- Claude: "But load is 10x now. What breaks?"
- You: [Answer, but fumble on scaling details]
- Claude: [Mark that as a gap]
- ...interview continues...

**After interview:**

**Assessment:**
- ✅ Passed: System architecture explanation, API design rationale
- ❌ Needs review: Scaling/load concerns, debugging approach
- ⏭️ Not tested: Deployment/monitoring (time ran out)

**Verdict:** Borderline. You know your core design, but need to think more deeply about scaling and debugging.

**Next steps:** Review "System Scaling" and "Debugging Strategies" with `concept-mastery-guide`, then mock again.

## Key Principles

- **No teaching** — This is a test, not a learning session
- **No hints** — Real interviewers don't hint. Neither do I.
- **No softballing** — If you can't explain it clearly, that's a gap
- **Real pressure** — Should feel like a real interview
- **Exit anytime** — If it's going badly, you can stop. Better to know now than on the real day.

## The 3-Layer Interview

**Layer 1: Describe Your Work**
- "Walk me through your project"
- "What was your role?"
- "Why that tech choice?"
- Tests: Can you tell the story clearly?

**Layer 2: Defend Your Choices**
- "Why not [alternative]?"
- "That's risky. How'd you handle it?"
- "What would you change now?"
- Tests: Can you think critically about your decisions?

**Layer 3: Handle Edge Cases**
- "What if [constraint changes]?"
- "System at 10x load. What breaks?"
- "User reports [bug]. Debug it."
- Tests: Do you understand deeply or just the happy path?

## Assessment Rubric

The report will assess you on:

**Clarity** — Can you explain your work?
- Clear narrative
- Specific examples
- Technical choices explained

**Depth** — Do you understand it deeply?
- Answer probing questions confidently
- Think through edge cases
- Understand failure modes

**Defense** — Can you justify your choices?
- Explain why this over that
- Handle challenges
- Show critical thinking

**Scaling** — Understand system limits?
- What breaks at scale
- How to monitor/debug
- When to refactor

**Soft Skills** — Communicate like an engineer?
- Explain to non-experts
- Acknowledge unknowns
- Ask clarifying questions

## The Verdict

**✅ Ready** — "You demonstrated solid understanding. Move to next round."
- Clear explanations, good defense, understand edge cases
- A few small gaps but nothing disqualifying

**⏳ Borderline** — "You have foundation, but some gaps. Study these specific areas, then mock again."
- Know core material, but stumbled on some details
- Good strategy: review gaps with `concept-mastery-guide`, mock again in 2-3 days

**❌ Needs Work** — "Not ready yet. Significant gaps in understanding. Focus on [areas] before real interview."
- Can't clearly explain work or defend choices
- Go back to `concept-mastery-guide` for foundational learning

## The Learn-Test Loop

1. **Learn** with `concept-mastery-guide` (study 3-5 concepts deeply)
2. **Test** with `/mock-interview` (see what you actually know)
3. **Identify gaps** (interview reveals what you don't know)
4. **Review gaps** back to `concept-mastery-guide`
5. **Test again** with another mock interview
6. **Repeat** until ✅ Ready verdict

## Tips

1. **Prepare beforehand** — Know your project story from `case-study-generator`
2. **Be specific** — Vague answers will be challenged
3. **Acknowledge unknowns** — "I'm not sure, but I'd..." is better than making stuff up
4. **Think out loud** — Show your reasoning, not just conclusions
5. **Don't memorize answers** — Real interviews ask unexpected follow-ups

## Pressure Settings

**Realistic** (Default)
- Acts like a real hiring manager
- Will push on weak answers
- Challenging but fair
- Good if: You want to feel the real thing

**Slightly Gentler**
- Still tests thoroughly
- More collaborative tone
- Fewer trap questions
- Good if: You're very anxious about interviews

## Can You Do Multiple Interviews?

Yes, but with breaks:
- One interview = 30-45 min of focus
- Then take a break (review notes, study)
- Can do another in a few hours or next day
- Don't do 5 in a row (diminishing returns)

## What Happens Next

- **If ✅ Ready:** You're good to go. Do a few quick practice explanations and interview.
- **If ⏳ Borderline:** Take the feedback. Review with `concept-mastery-guide` for specific gaps. Mock again in 2-3 days.
- **If ❌ Needs Work:** Go back to `concept-mastery-guide`. Focus on foundational learning for flagged areas. Come back when more confident.

---

**Duration:** 15–45 minutes per interview (exit anytime)  
**Output:** Honest assessment + specific gaps identified + next steps  
**Pairs with:** `concept-mastery-guide` (learn) → `mock-interview` (test) → Identify gaps → Back to guide → Mock again
