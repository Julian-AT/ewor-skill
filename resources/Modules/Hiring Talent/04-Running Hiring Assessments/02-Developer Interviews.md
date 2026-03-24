# Developer Interviews

[YouTube](https://youtu.be/EtbgiuM4Jdw)

The way we build software has changed. With AI able to generate huge amounts of code, the question is no longer “Can they write code?” — it's “Do they understand what they’re building and can they keep it simple, reliable, and maintainable?”

This shift completely changes what you should look for when hiring your first developer, founding engineer, or CTO.

## The New Developer Standard

AI can write code, but it cannot reason about architecture, scale, or simplicity. That means your early technical hire must bring foundational thinking, not just coding speed.

Look for developers who:

- Understand how software actually runs on the machine — data types, parallelisation, system limits, Linux fundamentals.
- Can break down a problem into components, choose the simplest tool to get the job done, and avoid over-engineering.
- Think like an engineer, not a framework-operator.

This is especially important in early-stage startups where technical decisions become long-term constraints.

## What to Look for During the Interview

**Tool Choice**

When interviewing, present a real problem from your product and ask: *“How would you approach this and what tools would you use?”*

Listen closely to tool choice — database, backend language, architecture. Most early-stage products don’t need Kubernetes clusters and microservices. They might fit on a single €39 machine. A great engineer knows this instinctively and favours clarity over complexity.

> **Tip:** If you’re non-technical, copy their answer into an LLM and ask: *“Is this the simplest solution for this scale?”* It’s a surprisingly effective filter.

**Language Choice**

Your candidate’s language choice speaks volumes about their thinking quality. Explore this by asking, *“What language would you use for the backend?”* The goal is not to see whether they can write code, but whether they can **c**hoose the right tool for long-term stability.

You’re looking for:

- **Deliberate tool selection.** A candidate who chooses based on maintainability and system health, not personal comfort.
- **Signals of good judgement.** Answers like *“Golang”* or *“Rust”* indicate a mindset geared toward reliability, type safety, and performance.
- **Awareness that AI can write code, but humans must define constraints.** The value lies in picking a language that leads to clean, maintainable infrastructure.

**Operational Discipline**

Beyond architecture thinking, ask operational questions:

- *“How do you deploy safely?”*
- *“How do you know if production breaks before the customer calls us?”*
- *“What monitoring or checks would you put in place?”*

You want someone who cares about keeping the system alive, not just shipping features. Early engineers without operational discipline cost more in weekends ruined than their salary.
