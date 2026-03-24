# Evaluating Technical Candidates 

[YouTube](https://youtu.be/aJ_eYmsroNE)

Once you’ve found a promising technical candidate — especially for roles like founding engineer, early developer, or CTO — your goal is not to test how well they can write code. In the AI era, machines can generate code quickly. What matters is whether the candidate has the judgement to define a simple, scalable, and maintainable architecture.

Instead of a classic code test or review, give them a small architecture assignment.

## The Architecture Exercise

Describe a real problem your product needs to solve, and ask the candidate to produce a high-level architecture outline or diagram for it. Their response should cover:

**Tool Choices**

- What database do they pick?
- What backend language and structure?
- Do they fragment it into multiple services or keep it simple?
- What queuing or messaging system (if any) do they choose?

**Reasoning Behind Each Choice**

- For every component, ask: *“What would you use and why?”*

**Cost & Scale Awareness**

- “If this system had 1M users, how would you estimate cost?”
- “What do you expect to be the main driver of infrastructure cost?”

**Simplicity Test**

- Can they justify why this is the simplest solution that solves the problem?

**Operational Reliability**

- “How do you ensure this doesn’t break on deployment?”
- “How do you detect failure before the customer does?”
- “What testing and monitoring do you set up from day one?”

Remember, you don’t need deep technical knowledge to judge the quality of the response. You’re looking for clarity and restraint, not buzzwords and complexity.

If the answer is packed with layers of unnecessary abstractions, it’s a red flag — this is someone building complexity for its own sake. Instead, look for those that are grounded, practical, and minimised.

