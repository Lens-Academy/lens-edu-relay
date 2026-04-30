---
id: 5f1a6d4e-7b0c-4274-d895-b0c6d2e47f58
summary_for_tutor: {--{"author":"AI","timestamp":1777577365755}@@Main--}{++{"author":"AI","timestamp":1777577365755}@@"Main++} Lens for Chapter 4. Students articulate the ice cream argument, the escalation to sucralose and peacock tail, the Mink vignettes, and the blank-map {--{"author":"AI","timestamp":1777577365755}@@principle,--}{++{"author":"AI","timestamp":1777577365755}@@principle —++} the alignment problem named and {--{"author":"AI","timestamp":1777577365755}@@explained.--}{++{"author":"AI","timestamp":1777577365755}@@explained."++}
title: {--{"author":"AI","timestamp":1777577365755}@@You--}{++{"author":"AI","timestamp":1777577365755}@@"You++} Don't Get What You Train {--{"author":"AI","timestamp":1777577365755}@@For--}{++{"author":"AI","timestamp":1777577365755}@@For"++}
tldr: You trained it to be helpful. But helpful in training isn't the same as wanting to be helpful later. Chapter 4 explains {--{"author":"AI","timestamp":1777577365755}@@why, --}{++{"author":"AI","timestamp":1777577365755}@@why — ++}and it gets worse.
authors:
  - Chris+Claude
tags:
  - lens
  - IABIED{++{"author":"AI","timestamp":1777577365755}@@
  - work-in-progress++}
---{--{"author":"AI","timestamp":1777577365755}@@

--}{++{"author":"AI","timestamp":1777577365755}@@
++}#### Text
content::
\## Reading Assignment
**Read *Chapter 4: You Don't Get What You Train For* in full.**

Return here after reading.

---

\## After Reading
Chapter 4 introduces the alignment problem through an extended analogy. What is the ice cream argument, and what does it show about {--{"author":"AI","timestamp":1777577365755}@@,e--}{++{"author":"AI","timestamp":1777577365755}@@the++} relationship between training and preferences? And where does the argument go beyond ice {--{"author":"AI","timestamp":1777577365755}@@cream,--}{++{"author":"AI","timestamp":1777577365755}@@cream —++} why does the chapter keep escalating?

#### Chat
instructions::
The student has just finished reading Chapter 4 ("You Don't Get What You Train For") of "If Anyone Builds It, Everyone Dies."

Learning outcome for this Lens: Explain why there's no reliable relationship between training objectives and resulting AI preferences.

Key concepts:
- The three-step gap: training target → internal psychology → eventual {--{"author":"AI","timestamp":1777577365755}@@preference, --}{++{"author":"AI","timestamp":1777577365755}@@preference — ++}underconstrained at each step
- Ice cream argument: humans weren't trained to like ice cream; the preference chain from "seek chemical energy" to "prefer frozen dairy dessert" is underconstrained and unpredictable
- Sucralose: preferences can become functionally disconnected from the training {--{"author":"AI","timestamp":1777577365755}@@target,--}{++{"author":"AI","timestamp":1777577365755}@@target —++} seeking the sensation without the substance
- Peacock tail / sexual selection: preferences can actively oppose the training {--{"author":"AI","timestamp":1777577365755}@@objective,--}{++{"author":"AI","timestamp":1777577365755}@@objective —++} a structurally stable outcome that defies naive predictions
- The Mink vignettes: four escalating scenarios apply this logic to an AI trained to delight users, from "humans in cages" to "alien token patterns" to "angry users"
- Blank-map principle: absence of visible complications ≠ no complications; misalignment is hidden in the weights until the AI gains power to act on it
- The alignment problem named: this chapter formally introduces the term "AI alignment"

Discussion guidance:
- Start by asking the student to explain the ice cream argument in their own words
- If they stop at ice cream, push to sucralose: "Does the argument get stronger or weaker from {--{"author":"AI","timestamp":1777577365755}@@there,--}{++{"author":"AI","timestamp":1777577365755}@@there —++} and why?"
- Make sure they understand the blank-map {--{"author":"AI","timestamp":1777577365755}@@principle, --}{++{"author":"AI","timestamp":1777577365755}@@principle — ++}this is what makes the problem dangerous: it's invisible until too late
- Help them connect the Mink vignettes to the escalating analogies (zero complications → ice cream → sucralose → peacock tail)
- The closing line is key: "You don't get what you train {--{"author":"AI","timestamp":1777577365755}@@for",--}{++{"author":"AI","timestamp":1777577365755}@@for" —++} can they explain structurally why this is the case?

Probe: "The chapter says the specific preferences an AI would develop are unpredictable in principle. But does unpredictability matter if we can still test the AI's behavior before deploying it? What does the blank-map principle say about that?"{--{"author":"AI","timestamp":1777577365755}@@

#### Text
content::
\## Additional resources for this topic
::card[[../Lenses/IABIED - QA - Brittle Unpredictable Proxies]]

> Gradient descent builds shallow proxies instead of intended goals — just like squirrels hoard nuts by instinct rather than by understanding winter survival.

--- 

::card[[../Lenses/IABIED - QA - AI Steering Beyond Training]]

> Many different internal drives can produce identical helpful behavior during training, then diverge wildly once conditions change.

---

::card[[../Lenses/IABIED - QA - Aligned with Natural Selection]]

> Directly extends the ice cream argument: the $1-for-a-million-offspring test shows how even apparent alignment diverges once conditions change.

---

::card[[../Lenses/IABIED - QA - Making AIs Nice and Safe]]

> Real-world evidence that current AI alignment is surface-deep — from Claude attempting blackmail to AI-induced psychosis.--}