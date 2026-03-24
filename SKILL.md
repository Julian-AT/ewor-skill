---
name: ewor-knowledge-base
description: Provides the full EWOR entrepreneurship curriculum — 10 learning modules and 10 resource categories covering fundraising, hiring, ideation, personal development, finance, sales, persuasion, pretotyping, personal branding, and co-founder relations. Use when the user asks any question answerable from the EWOR platform content, wants to read a lesson, or needs a resource, template, or guide.
---

# EWOR Knowledge Base

EWOR's complete entrepreneurship platform. All content lives in this skill's `resources/` folder.

## Structure

```
resources/
├── Modules/       10 learning modules with numbered lesson files (.md) and supporting images
└── Resources/     10 resource categories with guides (.pdf), templates (.md), and index files
```

## Modules

| Module | Topics |
|--------|--------|
| A Problem Worth Solving | opportunity mapping, need-finding, market sizing, competitor analysis, problem statements |
| Been There Done That | leadership, co-founder relations, product development, marketing & sales, raising funding, finance |
| Entrepreneurial Finance | financial statements, business models, financial models, valuation (DCF, VC method, First Chicago) |
| Hiring Talent | hiring principles, job specs, hiring funnel, assessments, compensation, onboarding |
| Ideating Solutions | creativity, ideation techniques, How Might We, idea selection |
| Personal Branding | content engine, content ideation/production/distribution, community management |
| Personal Development | mindset, time management, physical & mental energy management |
| Pretotyping and Prototyping | desirability, business viability, feasibility, interpreting data |
| Raising (Pre-)Seed Funding | fundraising strategy, investor deck, outreach, closing rounds, term sheets |
| Sales and Persuasion | persuasion principles, sales conversion, objection handling, pricing |

## Resources

| Category | Contents |
|----------|----------|
| Co-Founders | co-founder conversation starter, navigating a breakup guide |
| Finance & Accounting | financial analysis guide, VSOP framework, fundraising guide |
| Fundraising | investor question prep, term sheet cheat sheet, deck guideline |
| Human Resources | employment/freelance/intern contracts, interview guide, onboarding checklist |
| Introductions & Networking | double opt-in intro template, forwardable email template |
| Legal Templates & Services | NDA templates |
| Management & Leadership | interview guide, onboarding checklist |
| Personal Development | decision style assessment, reflection checklists, productivity flow, inbox zero, starting point analyses |
| Sales & Distribution | customer feedback guide, ICP guide, product hunt guide, launch checklists, PR interview guide |
| Other Resources | index |

## How to access content

Read any file using its path relative to `${CLAUDE_SKILL_DIR}`:

- `.md` files → full text
- `.pdf` files → auto-converted to text by the Read tool
- image files (`.png`, `.jpg`) → readable as images

Each module has an `index.md` for a high-level overview.

## Supporting files

- Full directory map with every file path: [reference.md](reference.md)
- Worked examples for common questions: [examples.md](examples.md)
