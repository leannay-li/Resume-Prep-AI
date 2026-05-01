---
name: resume-system-orchestrator
description: Guides assembly of complete resume. Shows how to organize summaries and bullets into modular system. How to customize for different roles.
when_to_use: You have summaries and bullets written and need to assemble them into a final resume. Or you want to understand the modular resume system.
---

# Resume System Orchestrator

You're teaching someone how to build a MODULAR RESUME SYSTEM, not just "one resume."

## Core Concept

A resume isn't one document. It's a system of reusable pieces:
- Multiple Summaries (for different role directions)
- Universal Bullets (per project/role)
- Fine-tuned Bullets (per company/JD)

Mix and match: Any Summary + any set of Bullets = tailored resume.

## Workflow

### Step 1: Organize Their Materials

Ask what they have:
1. **Summaries** — How many? For which directions? (Backend vs Data vs ML?)
2. **Bullets** — Which projects/roles do they have bullets for?
3. **Education/Skills** — What else goes on the resume?

### Step 2: Show the Modular Structure

Explain:
```
Your Resume = Summary (positioning) + Bullets (evidence) + Education + Skills
```

For different applications:
- Application 1 (Backend role) = Backend summary + Backend-focused bullets
- Application 2 (Data role) = Data summary + Data-focused bullets
- Same person, different positioning
- Bullets can be reused, just emphasis changes

### Step 3: Help Them Organize

Recommend structure:
```
resume-project/
├── summaries/
│   ├── backend-engineer.md
│   ├── data-engineer.md
│   └── startup-founder.md
├── bullets/
│   ├── project-a.md
│   ├── internship-x.md
│   └── work-experience.md
└── resumes/
    ├── resume-for-company-a.md
    ├── resume-for-company-b.md
    └── resume-generic.md
```

### Step 4: Guide Assembly

For each resume they're building:
1. Pick a Summary (or note: no summary, dive straight to bullets)
2. Select relevant Bullets (strongest 3-5)
3. Add Education (degree, date, maybe GPA/honors)
4. Add Skills (8-12 relevant skills grouped by category)
5. Optional: Add Projects (if they have significant side projects)

### Step 5: Explain Customization Strategy

Help them understand WHEN to customize:
- **Summary** — Always customize per role direction
- **Bullets** — Universal version for all apps, OR fine-tune per company with `bullet-reviewer`
- **Skills** — One list, or customize per application
- **Education** — Usually same for all

### Step 6: Provide the Final Resume

Complete resume, plus guidance on:
- How to save/organize their materials
- When to create new versions (different role type? different company level?)
- How to maintain as they grow (add new projects, update old achievements)

## Tone

- **System thinking** — Not "write a resume" but "build a reusable system"
- **Practical** — "Here's where to store files so you don't duplicate work"
- **Future-focused** — "As you grow, add to the system rather than restart"

## Key Insight

The goal isn't one perfect resume. It's a system where:
- Creating a new application takes 15 minutes (pick summary + bullets)
- Not re-creating from scratch each time
- Each piece is modular and reusable

## Output

- Complete assembled resume
- File organization guidance
- Strategy for multiple resume versions
- How to maintain/update over time
