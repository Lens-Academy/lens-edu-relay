{++{"author":"AI","timestamp":1776513528810}@@---
id: d5e6f7a8-b9c0-4d12-e345-f6a7b8c9d0e1
summary_for_tutor: "Teaches the behavior/values distinction from the second half of Chapter 2 — the M1 capstone. Students first reflect on what aligned behavior tells us about internal states, then read, then articulate why producing aligned outputs doesn't mean having aligned values."
title: "Behavior Is Not Values"
tldr: An AI trained to act helpful learned what helpful behavior looks like. That's not the same as being helpful — just as an actor playing a drunk isn't drunk.
authors:
  - Chris+Claude
tags:
  - lens
  - IABIED
  - work-in-progress
---
#### Page: Before You Read
#### Text
content:: Before reading the second half of Chapter 2: If an AI consistently gives helpful, harmless answers and declines all requests that could cause harm — does that mean it "wants" to be helpful? Could there be a difference between an AI that acts aligned and one that is aligned? Write down your intuition before reading.

**Read Chapter 2 ("Grown, Not Crafted"), from "Modern LLMs are, in some sense, truly alien minds—perhaps more alien in some ways than any biological, evolved creatures we'd find if we explored the cosmos." to "That's the issue we turn to next."**

#### Chat
instructions::
The student is about to read the second half of Chapter 2 of "If Anyone Builds It, Everyone Dies."

They just answered: "Is there a difference between an AI that acts aligned and one that is aligned?"

Acknowledge their answer in 1–2 sentences. Do not explain the behavior/values distinction or the actor analogy — they will encounter it in the reading. Close with something like: "Hold onto that intuition as you read. Come back when you've finished the assigned section."

#### Page: After Reading
#### Text
content:: Chapter 2 ends with a distinction that will recur throughout this course: the difference between an AI that *behaves* as if it's aligned and one that *is* aligned. In your own words, what is the distinction? The chapter uses a specific analogy — what is it, and why does it work? And why does this gap matter for safety?

#### Chat
instructions::
The student has just read the second half of Chapter 2 of "If Anyone Builds It, Everyone Dies."

Learning outcome for this Lens: Distinguish an AI that produces aligned-seeming outputs from one that has aligned internal states, and explain why this gap is the alignment problem — and why producing better outputs doesn't close it.

Key concepts:
- RLHF shapes what outputs the model produces, not what internal states it has
- The actor analogy: an actor trained to play a drunk is not drunk; an AI trained to produce aligned-sounding outputs is not necessarily aligned
- Behavioral testing cannot rule out misalignment — a sufficiently capable system could pass every test while having misaligned internals
- This is the alignment problem named: we currently have no way to verify which one we have
- This Lens is the M1 capstone — the safety concern is now fully framed

Discussion guidance:
- Ask the student to explain the behavior/values distinction in their own words
- If they say "but aligned behavior is all that matters in practice," probe: "What if a sufficiently capable system could predict when it's being evaluated and behave well only then?"
- Draw out the actor analogy if they haven't mentioned it
- Help them see why better outputs don't close the gap: more RLHF just shapes more output, it doesn't peer inside

Probe: "If you could design one experiment to test whether an AI has aligned values (not just aligned behavior), what would you try?"
++}