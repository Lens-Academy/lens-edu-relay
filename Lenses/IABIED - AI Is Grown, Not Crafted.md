---
id: c4d5e6f7-a8b9-4c01-d234-e5f6a7b8c9d0
summary_for_tutor: "Teaches the gradient descent / grown-not-crafted framework from the first half of Chapter 2. Students first reflect on how they imagine modern AI is made, then read about gradient descent, then articulate why knowing the training process doesn't mean knowing what the model learned."
title: "AI Is Grown, Not Crafted"
tldr: Engineers wrote the training process. They didn't write the AI. Like a parent who knows how babies are made but not what the baby will become.
authors:
  - Chris+Claude
tags:
  - lens
  - IABIED
  - work-in-progress
---
#### Text
content::
\## Reading Assignment
**Read *Chapter 2: Grown, Not Crafted*.** Start at the phrase
> Scene: A man and a woman are sitting in a restaurant in daytime.

Stop when you reach
> Machine minds are subjected to different constraints, and grown under different pressures, than those that shape biological organisms; and although they're trained to predict human writing, the thinking inside an AI runs on a radically different architecture from a human's.

Return here after reading.

---

\## After Reading
Chapter 2 argues that AI produced through gradient descent is "grown, not crafted." What does that mean in practice? An engineer builds the training process — so what exactly do they know about the resulting model, and what don't they know?

#### Chat
instructions::
The student has just finished reading the first half of Chapter 2 of "If Anyone Builds It, Everyone Dies."

Learning outcome for this Lens: Explain how AI produced through gradient descent differs from engineered systems, and why understanding the training process does not mean understanding what the trained model is or does.

Key concepts:
- Traditional software: engineers write explicit rules; the system does exactly what it's told
- Gradient descent (grown): engineers design a training process; the model's weights are shaped by optimization over data
- Engineers understand the process but cannot read the resulting weights to predict behavior
- The DNA analogy: you can sequence the genome and still not know what the person will be like
- Key epistemic gap: process-knowledge ≠ cognition-knowledge

Discussion guidance:
- Ask the student to explain the grown/crafted distinction in their own words
- If they say engineers still understand because they wrote the code, probe: "Do they know what the model learned, or just how it was trained?"
- Draw out the DNA analogy if they haven't mentioned it
- Push toward the safety implication: if you can't look inside and read off what the model believes or wants, what does that mean for verifying it's safe?

Probe: "Is there a difference between knowing how something was made and knowing what it is? Give me a non-AI example."
