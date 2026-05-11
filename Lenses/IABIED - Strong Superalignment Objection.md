---
id: 8f349745-2ea7-4f34-8146-6aff150a5e8d
summary_for_tutor: "Teaches the strong-superalignment objection from the second half of Chapter 11: using a smarter-than-human AI to solve alignment fails because the AI capable of doing so would itself be untrustworthy and dangerous, and a 'special-purpose alignment AI' rebuttal fails on no-training-examples + dangerous-skill-set + verification grounds. Students should end this Lens able to articulate the capability-paradox argument and explain why it doesn't reduce to ordinary engineering difficulty."
title: "Strong Superalignment Objection"
tldr: "OpenAI's flagship plan was 'use AI to solve alignment.' The plan contains a paradox that Chapter 11 walks through carefully — and the workaround doesn't work either."
authors:
  - Yatharth+Claude
tags:
  - lens
  - IABIED
---
#### Text
content::
\## Reading Assignment

**Read *Chapter 11: An Alchemy, Not a Science*.** Start at the phrase
> Some AI companies do try to look less cavalier than that, about ASI alignment, and put forth plans more detailed than those.

Read to the end of the chapter.

Return here after reading.

---

\## After Reading

Chapter 11 closes by examining the most-developed plan AI labs have proposed for alignment: "superalignment," which OpenAI made flagship in 2023. The chapter splits this into a weak version (use AI to automate interpretability research) and a strong version (use a smarter-than-human AI to solve the alignment problem itself). The chapter argues both fail, with the strong version failing in a particularly structural way.

In your own words: **what is the strong-superalignment plan, and what specifically does Chapter 11 say is wrong with it? If your friend said "OK, but we'll just train a special-purpose AI that only does alignment research and isn't generally dangerous" — what would Chapter 11's response be?**

#### Chat
instructions::
The student has just finished the second half of Chapter 11 of "If Anyone Builds It, Everyone Dies."

Learning outcome for this Lens: Describe the strong version of superalignment as Chapter 11 presents it — using a smarter-than-human AI to solve the alignment problem — and state the chapter's two-step objection: (1) the AI capable of doing this would itself be too dangerous and untrustworthy, and (2) a "special-purpose" alignment AI has no training examples of solved alignment and requires the precise dangerous skill set that makes an unaligned AI catastrophic.

Key concepts:
- **Weak superalignment** = use AI to automate the tedious parts of interpretability research. The chapter's objection: reading some of an AI's mind is not a plan for aligning it. "Learning what's going on inside atoms is not a plan for making a nuclear reactor that doesn't melt down." Diagnosis is not treatment; the ability to *see* a problem is not the ability to *fix* it.
- **Strong superalignment** = use a smarter-than-human AI to solve the alignment problem on humanity's behalf. The chapter's objection has two steps:
  - **Step 1 — Capability paradox:** to solve alignment you'd need an AI that exceeds humanity's geniuses. You shouldn't build an AI like that, and can't trust an AI like that, *before* alignment is solved. The plan requires having already done the thing it claims it will do.
  - **Step 2 — The "special-purpose" rebuttal fails:** "we'll just train a narrow alignment AI that isn't generally dangerous" runs into three obstacles. (a) No training examples of solved alignment exist, so the AI has to *generalize* from related skills. (b) The skills required — programming, growing AIs, AI preferences in detail, human psychology — *are* the dangerous skill set. (c) An AI handing you an alignment proposal cannot be verified; you'd have to either trust the AI or be persuaded by its arguments, both of which are the failure mode you were trying to avoid.
- **The biomedical-AI counterexample:** the chapter offers a contrast. A biology-specialized AI is "at least not thinking explicitly about how to make better AIs." If it outputs a cancer cure, you can run separate narrower tools (protein-interaction checkers) to verify the output without trusting the bio-AI's word. Strong superalignment doesn't have that out — there's no narrower checker for "is this alignment plan secretly going to fail."
- **The pattern:** the chapter is identifying a *structural* problem with strong superalignment, not a *practical* one. It's not that the plan is hard to execute; it's that the plan contains a self-undermining dependency. You cannot use the dangerous thing to align the dangerous thing before you've aligned it.

Discussion guidance:
- The most common confusion is reading the objection as "AI is too dumb to solve alignment yet." That's not the chapter's claim. The chapter's claim is that *the AI capable of solving it would itself be too dangerous* — the obstacle is on the trust/safety side, not the capability side.
- If the student reduces the objection to "we don't have an AI smart enough yet" — push them: "What if next year's model is smart enough? Does the objection go away?" The answer is no, because the objection is about what kind of AI it would have to be to actually solve the problem.
- If the student reaches for "but we could check the AI's work" — walk through the verification gap. Checking an alignment proposal requires either understanding the proposal (in which case you didn't need the AI) or trusting the AI (in which case you've trusted the unaligned thing).
- If the student offers the biomedical-AI counterexample on their own — confirm and probe: "What's the load-bearing difference? Why does the bio-AI have a verification path that the alignment-AI doesn't?"
- If the student suggests "OK, then just use a dumber AI that helps interpretability" — note that this is the weak superalignment proposal, and that the chapter's objection there is different: it's not that the proposal is paradoxical, it's that *interpretability is not alignment.* Reading is not treating.

Probe: "What kind of AI capability would you need before strong superalignment becomes safe to attempt — and what would you have to know about that AI before you could trust it to be working on your side?"

#### Text
content::
\## Additional resources for this topic
::card[[../Lenses/IABIED - QA - Can Interpretability Solve This]]

> The natural follow-up: even if interpretability worked perfectly, why doesn't it close the gap to alignment? An expansion of the weak-superalignment objection.

---

::card[[../Lenses/IABIED - QA - AIs Debate Compete Oversee]]

> Discusses the family of "use AIs to monitor AIs" proposals that share structural features with strong superalignment. Useful if the student wants to apply the capability-paradox reasoning to neighboring plans.

---

::card[[../Lenses/IABIED - QA - Various Other Alignment Plans]]

> A broader sweep of the field's currently-floated plans, with the chapter's reasoning about which ones reduce to the same structural problems and which ones don't.

---

::card[[../Lenses/IABIED - QA - Race for Alignment Research]]

> Engages the question of whether the field could outrun the capability-paradox by getting alignment ahead of capability — and what conditions would have to hold for that race to be winnable.
