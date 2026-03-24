# EWOR Knowledge Base Skill

A Claude Code skill that gives any LLM instant access to the full EWOR entrepreneurship curriculum — 10 learning modules and 10 resource categories.

## Installation

Copy the `ewor-skill/` folder into your Claude Code skills directory:

**Personal (available in all your projects):**
```bash
cp -r ewor-skill ~/.claude/skills/ewor-skill
```

**Project-level (available to everyone on this project):**
```bash
cp -r ewor-skill .claude/skills/ewor-skill
```

## Usage

Once installed, Claude will automatically load this skill when you ask questions related to the EWOR curriculum. You can also invoke it directly:

```
/ewor-knowledge-base
```

### Example prompts

```
How much should I raise in my pre-seed round?
```
```
What slides does my investor deck need?
```
```
How do I run a need-finding interview?
```
```
Give me the EWOR template for an employment contract.
```
```
Explain the VC valuation method.
```

## Contents

```
ewor-skill/
├── SKILL.md        ← entry point: overview tables and navigation
├── reference.md    ← complete file map for all 200+ content files
├── examples.md     ← 20+ worked examples mapping questions to files
└── resources/
    ├── Modules/    ← 10 learning modules (lesson .md files + images)
    └── Resources/  ← 10 resource categories (.pdf guides + .md templates)
```

### Modules

| Module | Key topics |
|--------|-----------|
| A Problem Worth Solving | need-finding, market sizing, competitor analysis, problem statements |
| Been There Done That | founder interviews on leadership, product, sales, fundraising |
| Entrepreneurial Finance | P&L, cash flow, financial models, valuation methods |
| Hiring Talent | job specs, hiring funnel, assessments, onboarding |
| Ideating Solutions | creativity, ideation techniques, idea selection |
| Personal Branding | content engine, distribution, community management |
| Personal Development | mindset, time management, energy management |
| Pretotyping and Prototyping | desirability, viability, feasibility testing |
| Raising (Pre-)Seed Funding | strategy, investor deck, outreach, term sheets |
| Sales and Persuasion | persuasion psychology, sales frameworks, pricing |

### Resources

| Category | What's inside |
|----------|--------------|
| Co-Founders | conversation starter guide, co-founder breakup guide |
| Finance & Accounting | financial analysis guide, VSOP framework |
| Fundraising | investor question prep, term sheet cheat sheet, deck guideline |
| Human Resources | employment/freelance/intern contracts, interview guide, onboarding checklist |
| Introductions & Networking | double opt-in intro templates |
| Legal Templates & Services | NDA templates |
| Management & Leadership | interview guide, onboarding checklist |
| Personal Development | decision style assessment, reflection checklists, productivity guides |
| Sales & Distribution | ICP guide, launch checklists, PR interview guide |

## How it works

When Claude loads this skill, it reads `SKILL.md` for an overview of what's available. For deeper questions, it reads the relevant files from `resources/` on demand — only loading what's needed, keeping context usage efficient.

File types supported:
- `.md` — full text, read directly
- `.pdf` — auto-converted to text by the Read tool
- `.png` / `.jpg` — readable as images
