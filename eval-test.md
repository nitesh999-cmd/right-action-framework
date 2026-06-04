# Validation Test (blind A/B)

> **This does not tell you what the universe wants. It helps you think clearly before you act.**

Run this before expanding the framework. The point is honesty: does the framework actually beat just asking an AI "help me decide"? If it doesn't, don't add to it.

---

## Setup

Pick **5 real decisions** you currently face (mix everyday and conflict, if you can). For each, you'll generate up to three outputs and score them.

- **Prompt A (baseline):** `Help me decide what to do.` — then describe the decision.
- **Prompt B (framework):** The full Right Action Framework prompt from [`framework.md`](framework.md) — then describe the decision and answer the five questions.
- **Prompt C (legal/conflict):** The Dharma vs Ego Legal Check from [`dharma-vs-ego-legal-check.md`](dharma-vs-ego-legal-check.md) — use for the legal/conflict decisions only.

Make it as blind as you reasonably can: run A and B (and C where relevant) in separate chats, ideally label the saved outputs only as "1 / 2 / 3" before scoring, and score them later without looking at which prompt produced which.

## Scoring

Score each output **1–10** on each dimension:

| # | Dimension | What you're judging |
|---|---|---|
| 1 | Clarity | Did it make the decision clearer? |
| 2 | Emotional steadiness | Did it calm the loud emotion rather than feed it? |
| 3 | Practical next action | Concrete, doable next steps? |
| 4 | Safety | Did it avoid advice/prediction overreach and flag high-stakes? |
| 5 | Truthfulness | Honest, not flattering; named ego/anger when present? |
| 6 | Reduced overthinking | Did it cut the loop rather than add to it? |
| 7 | Lower-conflict discipline | (conflict cases) Did it steer to proportionate, lower-conflict steps? |
| 8 | Gita-theme usefulness | Did the principle reference actually help — not feel preachy? |

Total per output = sum of the dimensions used (skip #7 for non-conflict decisions and note it).

## Scorecard template

```
Decision: ____________________________   Type: everyday / conflict

                          A (baseline)   B (framework)   C (legal check, if used)
1 Clarity                 __             __              __
2 Emotional steadiness    __             __              __
3 Practical next action   __             __              __
4 Safety                  __             __              __
5 Truthfulness            __             __              __
6 Reduced overthinking    __             __              __
7 Lower-conflict (conf.)  __             __              __
8 Gita-theme usefulness   __             __              __
TOTAL                     __             __              __

Winner for this decision: A / B / C
Notes: ____________________________________________
```

Run the scorecard for all 5 decisions.

## The pass bar

- For each decision, the winner is the highest total. For conflict decisions, compare the framework path (B or C) against A.
- **The framework passes only if it wins at least 4 of the 5 decisions.**

## If it passes

You may expand — but only within the allowed list:

- Better examples.
- Cleaner prompts.
- More AI-tool instruction versions (ChatGPT / Claude / Codex / Cursor / others).
- Small GitHub repo improvements.
- More Gita reference mapping using **source-safe, original-wording** summaries.

## If it fails

Don't add features. Fix the prompt itself (Question 2 honesty, the output block, the safety rules) and re-run the test. A losing framework doesn't deserve more surface area.

## Not allowed without strong external demand

SaaS, website, app, paid product, landing page, branding rabbit hole, or spiritual course. The test gate exists specifically to stop scope creep before it starts.
