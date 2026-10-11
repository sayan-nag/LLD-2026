# Start here: your hands-on agentic engineering course

Build **SupportOps**, a Python order-support agent, then extend the project through AI system-design exercises.

**For:** a senior software engineer new to agentic development.  
**Pace:** 4–6 hours per week, approximately 12–13 weeks.  
**Structure:** 24 labs, usually two per week. Allow an extra session when a completion check needs more work.

This folder contains the current plan incorporating all three supplied transcript submissions and the two screenshots. These are learning documents; the application has not been implemented.

## Step 1 — Open the full course

Read the project contract, fictional refund rules, and stack before beginning Lab 1. The dated revision notes explain the additional topics but do not require separate study sessions.

[Open the full course](/Users/apple/Documents/Codex/2026-09-28/ge/outputs/Agentic-Engineering-Course/01-Full-Course.md)

## Step 2 — Follow the labs in order

Each pair below is a weekly module, not a fixed calendar deadline. Start whenever you are ready.

| Week | Labs | Focus |
|---|---|---|
| 1 | 1–2 | Domain foundation and first model call |
| 2 | 3–4 | Agent loop, evaluations, and tracing |
| 3 | 5–6 | State, memory, and policy retrieval |
| 4 | 7–8 | Approved actions and failure recovery |
| 5 | 9–10 | Orchestration and trust boundaries |
| 6 | 11–12 | Model routing and foundation checkpoint |
| 7 | 13–14 | Inference, KV caching, serving, and batching |
| 8 | 15–16 | Latency, cost, and retrieval comparisons |
| 9 | 17–18 | Index freshness and conversational search |
| 10 | 19–20 | Durable jobs, clocks, and recovery across workers |
| 11 | 21–22 | Recommendation candidates and learned ranking |
| 12 | 23–24 | Coding agent and final design review |

Use a thirteenth week for spillover, targeted scaling drills, and final review if needed. The rate-limiting, GPU-capacity, partitioning, clock-failure, and model-change exercises are included in the relevant labs.

## Step 3 — Complete one learning cycle per lab

1. Read the lab's short concept and predict the expected behavior.
2. Implement the smallest working increment yourself.
3. Run its deliberate failure exercise.
4. Check the actual outcome against the completion criteria.
5. Save a test result, trace, or measurement table.
6. Write what failed, why it failed, and what you changed.
7. Bring that evidence for review before starting a dependent lab.

Aim for 10–15 minutes of explanation, 60–90 minutes of implementation, 20–30 minutes of failure testing, and 10–15 minutes of review. Advanced drills can take longer.

## Step 4 — Do your first 90-minute session

No model API key or GPU is needed for this session.

1. **Minutes 0–15:** write the supported requests, fictional refund rules, and trusted customer-identity boundary in your project's README.
2. **Minutes 15–35:** create the six synthetic orders listed in the full course and a fixed test clock.
3. **Minutes 35–65:** implement `get_order()` and a pure `evaluate_refund()` function.
4. **Minutes 65–85:** check all six orders, the exact 30-day boundary, and access to another customer's order.
5. **Minutes 85–90:** write five sentences explaining which decisions the future model will make and which the application must enforce.

Your first review submission is those two functions, their checks, and that explanation.

## Step 5 — Track completion using evidence

[Open the progress checklist](/Users/apple/Documents/Codex/2026-09-28/ge/outputs/Agentic-Engineering-Course/02-Progress-Checklist.md)

Check a lab only after its completion criteria are met. Record failures and unresolved questions instead of treating a working demo as completion. A measured lack of improvement is still a useful result when a lab compares alternatives.

## Step 6 — Use the two review milestones

- **After Lab 12:** demonstrate the support agent, its approvals, recovery, evaluations, and traces.
- **After Lab 24:** demonstrate the expanded system and present your serving/retrieval measurements, recovery evidence, recommendation results, coding-agent checks, and six system-design cards.

Keep real measurements, synthetic-data experiments, and scheduler simulations labelled separately.

## Step 7 — Resume coaching from your current lab

Use this message when returning to the course:

> I am working on Lab [number] of the SupportOps course. Give me a short explanation and one implementation task at a time. Review my attempt before showing a complete solution. Here is my code, test or trace output, and what I think is happening: ...

Keep your implementation and experiment notes alongside the course or in your preferred project directory. The full course contains the detailed exercises and acceptance criteria.
