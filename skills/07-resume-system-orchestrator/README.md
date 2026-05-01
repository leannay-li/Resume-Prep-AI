# Resume System Orchestrator

**For:** Anyone with summary + bullets ready to assemble  
**Use when:** You want to create a complete, modular resume system (not just one resume)  
**Invocation:** `/resume-system-orchestrator`

## What It Does

Guides you to build a MODULAR RESUME SYSTEM where you mix and match:
- Multiple summaries (for different role directions)
- Universal bullets (per project)
- Education + Skills sections

Result: Creating a new tailored resume takes 15 minutes instead of starting from scratch.

## When to Use It

✅ **Use this if:**
- You have summaries and bullets written
- You want to understand how to organize your materials
- You're targeting multiple role types (different summaries needed)
- You want to avoid duplicating work for each application

## How to Use It

1. Run `/resume-system-orchestrator`
2. Provide:
   - Your summaries (from `summary-writer`)
   - Your bullets (from `bullet-writer`)
   - Your education, skills, other info
3. Get guidance on assembly + organization
4. Walk away with complete resume + system strategy

## What You Get

1. **Complete assembled resume** — Ready to use/customize
2. **File organization guide** — How to store and organize your materials
3. **Multiple version strategy** — When/how to create different summaries or emphasis
4. **Maintenance approach** — How to update as you grow

## The Modular System

Instead of one resume, build reusable pieces:

**Your Material:**
```
Summaries:
- Backend Engineer (for SDE roles)
- Data Engineer (for Data roles)
- Startup Builder (for startup roles)

Bullets:
- Project A (internship)
- Project B (side project)
- Work Experience X (full-time role)

Education:
- BS Computer Science, State University, 2022

Skills:
- Languages: Python, JavaScript, Java
- Tools: React, Django, PostgreSQL, AWS
```

**Combined into resumes:**

For Backend SDE application:
- Backend Engineer summary + Project A + Project B + Work Experience X + Education + Skills

For Data Engineer application:
- Data Engineer summary + different emphasis on Project B + Work Experience (if data-related) + Education + Skills

For Startup application:
- Startup Builder summary + Project B (side project emphasis) + Work Experience (leadership aspects) + Education + Skills

## Key Principles

- **Summaries change per direction** — Not "experienced engineer" for all, but "backend engineer" vs "data engineer"
- **Bullets can stay universal** — Same bullet, just reordered emphasis per company
- **Skills can be organized differently** — One list or customize per role
- **Education usually stays the same** — Unless you're hiding/emphasizing GPA for different roles

## File Organization (Recommended)

```
resume-project/
├── summaries/
│   ├── backend-engineer.md
│   ├── data-engineer.md
│   └── startup-founder.md
├── bullets/
│   ├── project-a.md
│   ├── project-b.md
│   └── work-experience.md
├── content/
│   ├── education.md
│   └── skills.md
└── resumes/
    ├── amazon-sde.md
    ├── google-data-eng.md
    ├── startup-engineer.md
    └── generic.md
```

**Benefits:**
- Not duplicating text across resumes
- Easy to update one bullet and have it reflected everywhere
- Quick to assemble new resume (pick pieces, paste together)

## Tips

1. **Don't duplicate bullets across roles** — If you mention Project A twice, keep one version, reference it
2. **Summaries are your customization hook** — Different direction = different summary, sometimes same bullets
3. **Create new versions, not edits** — `amazon-sde.md`, not `amazon-sde-v2.md`
4. **Update bullets as you grow** — Achievement-focused updates, not constant rewrites
5. **Keep one "master" resume** — Generic version, then customize from there per application

## Customization Strategy

**When to use different summaries:**
- Different role types (Backend vs Data vs Product)
- Different company sizes (Startup vs BigTech vs Scale-up)
- Different career angles (IC contributor vs Technical leader vs Full-stack)

**When to use different bullets:**
- Same bullets work for most roles
- OR use `bullet-reviewer` to fine-tune per specific JD
- Don't create 10 versions—max 3-5

**When to use different skills:**
- One list usually works
- OR highlight top 5 skills per role (lead with what's relevant)

## Next Steps After This

1. Save your materials in organized structure (see above)
2. For each new application:
   - Pick appropriate summary
   - Select relevant bullets (use `bullet-reviewer` if customizing for JD)
   - Assemble resume
   - Apply

3. As you grow:
   - Add new summaries for new directions
   - Add new bullet projects
   - Update existing bullets (achievements grow, refine wording)
   - Don't recreate—update the system

---

**Duration:** 30 minutes  
**Output:** Complete resume + system organization guide  
**Pairs with:** All previous skills (everything comes together here)
