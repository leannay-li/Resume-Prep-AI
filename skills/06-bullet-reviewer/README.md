# Bullet Reviewer

**For:** Anyone with bullets from `bullet-writer`  
**Use when:** You're targeting a specific job and want to optimize your bullets for that JD  
**Invocation:** `/bullet-reviewer`

## What It Does

Fine-tunes your universal bullets for a specific job description. Not rewriting—strategic tweaks for keyword alignment, emphasis, and showing transferability.

The principle: Same bullets, different emphasis. Move metrics around, highlight transferability, adjust keywords to match JD language.

## When to Use It

✅ **Use this if:**
- You have universal bullets from `bullet-writer`
- You're targeting a specific job with a known JD
- You want to show fit without lying
- You want to highlight transferable skills (AWS → GCP, React → Vue, etc.)

❌ **Don't use if:**
- You don't have specific bullets yet (use `bullet-writer` first)
- You're not targeting a specific JD yet

## How to Use It

1. Run `/bullet-reviewer`
2. Provide:
   - Your universal bullets (from `bullet-writer`)
   - Target job description
   - Your experience level
3. Get optimized bullets for this JD
4. Apply to your resume for this application

## What You Get

Before/After optimizations like:

**Original bullet:**
> "Built event processing system handling 10M events/day"

**For JD emphasizing latency:**
> "Built event processing system with sub-100ms delivery latency, handling 10M events/day"

**For JD emphasizing reliability:**
> "Built event processing system maintaining 99.99% delivery guarantee, handling 10M events/day"

Same project, different emphasis based on what THIS JD values.

## The Optimization Lens

| JD Emphasis | Bullet Adjustment |
|-------------|-------------------|
| **Performance/Latency** | Move speed metrics to front |
| **Scale** | Emphasize user/volume numbers |
| **Reliability** | Emphasize uptime/SLA numbers |
| **Cost** | Show cost savings if applicable |
| **Testing/Quality** | Mention test coverage if relevant |

## Transferability Mapping

Help them show fit even when tech doesn't exactly match:

| Their Experience | JD Wants | Transferability |
|------------------|----------|-----------------|
| AWS | GCP | Cloud concepts transfer, mention it |
| React | Vue | Frontend framework concepts transfer |
| PostgreSQL | MySQL | SQL fundamentals transfer |
| Kubernetes | ECS | Container orchestration patterns |

## Tips

1. **Tweaks, not rewrites** — Small changes have big impact
2. **Emphasis first** — Reorder metrics before changing wording
3. **Highlight transferability** — AWS to GCP is totally fair to mention
4. **Don't keyword-stuff** — Natural language, not spam
5. **Keep it honest** — Transferability yes, lying no

## Common Changes

**Keyword alignment:**
- JD says "event-driven" → Change "async" to "event-driven"
- JD says "microservices" → Emphasize service decomposition

**Emphasis reordering:**
- Original: "Reduced costs, improved latency by 35%"
- For latency-focused JD: "Improved latency by 35%, reducing costs"

**Adding context:**
- Original: "Built on AWS"
- For GCP JD: "Built on AWS (cloud concepts directly transfer to GCP)"

## What You DON'T Do

- ❌ Add false claims
- ❌ Invent numbers
- ❌ Oversell skills you don't have
- ❌ Completely rewrite (tweaks only)

## Next Steps

1. Get optimized bullets from this skill
2. Use in your resume for this specific application
3. If you're targeting multiple roles → Create different versions with this skill

---

**Duration:** 15-20 minutes per JD  
**Output:** Optimized bullets for specific JD, with Before/After  
**Pairs with:** `bullet-writer` (create master bullets) → `resume-system-orchestrator` (assemble final resume)
