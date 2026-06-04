# Right Action Framework

A practical AI decision framework for choosing clearly when fear, anger, ego, guilt, desire, confusion, or attachment are loud.

> **This does not tell you what the universe wants. It helps you think clearly before you act.**

> **Use this to prepare your thinking, not to decide high-stakes matters.**

---

## Use this when / Do not use this as

**Use this when:**

- You are emotionally stirred and need clearer thinking.
- You are deciding how to respond, pause, act, or wait.
- You want to separate fear, anger, ego, guilt, desire, attachment, and avoidance from a grounded next step.
- You want to prepare your thinking before speaking to a professional.

**Do not use this as:**

- Legal advice
- Medical advice
- Financial advice
- Mental-health advice
- Spiritual authority
- A prediction tool
- A replacement for qualified professional advice
- A final decision-maker for high-stakes matters

---

## 1. What this is

The Right Action Framework is a plain-English, reusable prompt system for making decisions when your emotions are loud and your thinking is cloudy. You paste it into ChatGPT, Claude, Codex, Cursor, or any capable AI assistant, answer a short set of questions, and get a grounded breakdown: a candidate next action to consider, why, what to watch in yourself, what you control, what you don't, and the next few concrete steps.

It is inspired by selected, practical decision themes found in the Bhagavad Gita — duty, right action, detachment from outcome, self-mastery, clarity, courage, and steadiness — translated into modern, secular, everyday language.

It is a thinking tool. Nothing more, nothing less.

## 2. Who it is for

- Anyone facing a decision where emotion is interfering with judgment.
- People facing low-stakes everyday, work, relationship, and conflict decisions; for legal, medical, mental-health, financial, safety, or child-welfare stakes, use only as preparation for qualified professional advice.
- People in conflict situations who want to separate principled action from ego-driven escalation (see the Dharma vs Ego Legal Check).
- Builders who want a clean, source-safe decision prompt they can drop into their own AI tools.

## 3. What it is not

- It is **not** legal, medical, financial, psychological, or spiritual advice.
- It is **not** a religious or spiritual authority.
- It does **not** teach the Bhagavad Gita, claim to represent it fully, or speak for any tradition.
- It does **not** predict outcomes or tell you what any person, court, regulator, or institution will do.
- It is **not** a product, course, app, or movement. It is a free set of markdown files.

## 4. Why it references the Bhagavad Gita

The Gita is, among other things, a very old text about how to act well under pressure — when you are afraid, conflicted, attached to a result, or unsure what your duty is. Those are exactly the moments modern people make bad decisions.

This framework borrows a handful of those *decision themes* and nothing else. It does not quote the text, does not reproduce any modern translation or commentary, and does not present any spiritual claim as fact. Chapter references are given as **themes only**, so you know where an idea is loosely inspired from — not as scripture being taught.

See [`gita-reference-map.md`](gita-reference-map.md) and [`sources.md`](sources.md).

## 5. How the Gita themes map to modern decision-making

| Gita theme (inspiration) | Modern decision use |
|---|---|
| Dharma — right responsibility, duty | "What is actually my responsibility here?" |
| Karma Yoga — right action without obsessing over results | Act well on the part you control; stop white-knuckling the outcome |
| Detachment from outcome | Reduce anxiety-driven and revenge-driven choices |
| Self-mastery | Notice when fear, anger, ego, guilt, or desire is steering |
| Clarity over confusion | Decide from a clear head, not impulse |
| Courage | Do the uncomfortable right thing instead of avoiding |
| Equanimity | Stay steady through success, failure, praise, blame, gain, loss |

Full mapping in [`gita-reference-map.md`](gita-reference-map.md).

## 6. How to use it in ChatGPT

1. Open [`chatgpt-instructions.md`](chatgpt-instructions.md).
2. Paste the framework prompt into a new chat (or save it for reuse — see the optional reuse note in the ChatGPT instructions).
3. Describe your decision. Answer the 5 questions.
4. Read the structured output. Take the next 3 steps.

## 7. How to use it in Claude

1. Open [`claude-instructions.md`](claude-instructions.md).
2. Paste the framework as a Project instruction or at the top of a conversation.
3. Describe your decision and answer the questions.

## 8. How to use it in Codex/Cursor

1. Open [`codex-cursor-rules.md`](codex-cursor-rules.md).
2. Add it as a rules file / system prompt so the assistant runs the framework when you ask for a decision.

## 9. The core 5-step framework

1. **What is the real decision?**
2. **What is loud right now?** (fear, anger, ego, guilt, desire, attachment, avoidance, pride, revenge, impatience, comfort-seeking — or genuine clarity)
3. **What is my right responsibility?**
4. **What is the clearest next action to consider?**
5. **What result am I attached to — what can I influence, and what can I not control?**

Then the AI returns a practical output block. Full prompt in [`framework.md`](framework.md).

## 10. The Dharma vs Ego Legal Check

For legal and conflict decisions, a second prompt helps you separate principled action (protecting a real issue you should document or discuss with a qualified professional — child welfare, safety, fairness, finances, truth) from ego-driven escalation (wanting to punish, expose, embarrass, or win). It is a motive/evidence/proportionality preparation check only — it does not assess whether a legal right exists. It pushes you toward evidence, proportionality, lower-conflict first steps, and the exact question to ask a professional.

Full prompt in [`dharma-vs-ego-legal-check.md`](dharma-vs-ego-legal-check.md).

## 11. The safety boundary

This framework helps you *think*. It does not advise, predict, or decide for you. It will not tell you what a judge, lawyer, doctor, regulator, employer, or partner will do. It will not encourage revenge, threats, harassment, or avoiding professional help. For anything high-stakes — legal, medical, financial, safety, or mental health — get proper professional advice.

Full rules in [`safety.md`](safety.md).

## 12. The source/copyright boundary

The Bhagavad Gita is ancient and not itself under copyright, but **modern translations and commentaries usually are**. This repo uses only original plain-English wording and theme/chapter references. It does not copy or closely paraphrase any modern translation or commentary. Public-domain translations (e.g. Kashinath Trimbak Telang, 1882; Edwin Arnold's *The Song Celestial*, 1885) are mentioned only as reference points, without long quotation.

Full notes in [`sources.md`](sources.md).

## 13. The validation test before expanding

Before adding anything, run the blind A/B test in [`eval-test.md`](eval-test.md): compare a plain "help me decide" prompt against this framework on 5 real decisions. Only expand the framework if it wins at least **4 out of 5**. Allowed expansion is limited (better examples, cleaner prompts, more AI-tool instructions, small repo improvements, more source-safe Gita mapping). No SaaS, app, website, paid product, landing page, branding expansion, or course.

---

## Files

| File | Purpose |
|---|---|
| [`framework.md`](framework.md) | The full Right Action Framework prompt |
| [`gita-reference-map.md`](gita-reference-map.md) | Source-safe theme/chapter inspiration map |
| [`dharma-vs-ego-legal-check.md`](dharma-vs-ego-legal-check.md) | Legal/conflict motive-check prompt |
| [`chatgpt-instructions.md`](chatgpt-instructions.md) | ChatGPT setup |
| [`claude-instructions.md`](claude-instructions.md) | Claude setup |
| [`codex-cursor-rules.md`](codex-cursor-rules.md) | Codex/Cursor rules |
| [`examples.md`](examples.md) | 8 worked everyday examples |
| [`legal-conflict-examples.md`](legal-conflict-examples.md) | 5 worked legal/conflict examples |
| [`safety.md`](safety.md) | Safety boundaries |
| [`sources.md`](sources.md) | Copyright and source notes |
| [`eval-test.md`](eval-test.md) | Blind A/B validation test |
| [`LICENSE`](LICENSE) | MIT License |

## License

MIT — see [`LICENSE`](LICENSE).
