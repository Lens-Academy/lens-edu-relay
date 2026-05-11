---
id: 34fa91a3-1d1f-4081-b4c4-cb2af2139a1d
summary_for_tutor: "Teaches the five engineering curses Chapter 10 names — speed, narrow margins, self-amplification, complications, and edge cases — and their case studies (space probes for the before/after gap, Chernobyl for the first four, computer security for edge cases). The Lens covers the first reading of Ch10 (beginning to the end of the computer-security section); the closing position statement is taught by a separate Lens (Position Not Despair). Students should end this Lens able to name all five curses, attribute each to a case study, and articulate why the curse of edge cases gets uniquely worse as the system gets smarter."
title: "The Five Engineering Curses"
tldr: "Five named features make some engineering problems uniquely treacherous. AI alignment has all five at once, plus an extra — they get worse the smarter the system becomes."
authors:
  - Yatharth+Claude
tags:
  - lens
  - IABIED
---
#### Text
content::
\## Reading Assignment

**Read *Chapter 10: A Cursed Problem*.** Start at the beginning and stop when you reach
> Those constraints will tend to get in the way of the AI accomplishing one objective or another. And then you are matching your own wits and ability to nail down the edge cases against however much intelligence is flowing through the system, to see if your constraint holds up.

Return here after reading.

---

\## After Reading

Chapter 10 walks through three engineering domains — space probes, Chernobyl, computer security — and uses each to introduce one or more named "curses." The chapter argues that all five apply to AI alignment, with one of them in a uniquely worse form.

In your own words, **list the five curses, identify which case study illustrates each, and pick the one that you think gets uniquely worse for AI alignment than for the case-study domain — and say why.**

#### Chat
instructions::
The student has just finished the first half of Chapter 10 of "If Anyone Builds It, Everyone Dies."

Learning outcome for this Lens: Enumerate the five engineering curses Chapter 10 names — speed, narrow margins, self-amplification, complications, and edge cases — and identify which case study (space probes, Chernobyl, computer security) illustrates each.

Key concepts:
- The five curses: **speed** (Chernobyl, microsecond neutron timescales hidden under a human-manageable interface), **narrow margins** (Chernobyl, 0.65% delayed-neutron fraction; prompt-critical at 100.65%; apes-to-hominids analogy), **self-amplification** (Chernobyl RBMK feedback loop: overheating → coolant boils off → less inhibition → more reaction), **complications** (Chernobyl's graphite-tipped control rods that turned a SCRAM into an explosion; modern LLM weights as the "incomparably more complicated" parallel), **edge cases** (computer security, buffer-overflow attack with the 280-character name and the 1-in-18 billion billion exact wrong input; Bruce Schneier on insecurities always remaining)
- The space-probe case studies (Mars Observer, Mars Climate Orbiter unit mismatch, Mars Polar Lander leg vibration, Viking 1 antenna-software overwrite) function as the chapter's setup for the *before/after gap* — once the device is out of reach, you can't fix it. They are not tied to any single curse; they motivate why the curses matter.
- "Grown, not crafted" (M1 callback): space probes are crafted and still fail; AI is grown and inherits *every* space-probe failure mode plus the curses Chernobyl and computer security add, with the engineers not knowing what's inside the device they're trying to constrain.
- **Why edge cases is the uniquely-worse curse for ASI:** the other four are physical constraints that any system faces; edge cases is the one curse that *intensifies with intelligence* — a smarter adversary finds more obscure exploits. Computer security is "famously losing" even when the engineers can fully craft and read their own code. AI alignment must hold against an intelligent system whose code the engineers cannot read.

Discussion guidance:
- Ask the student to list the five curses without scrolling back. Probe gently if they miss one.
- For the curse-to-case-study mapping: if they say "Chernobyl illustrates all five," correct gently — Chernobyl illustrates the first four; computer security illustrates edge cases; space probes illustrate the before/after framing inside which all five curses operate.
- If they pick a different "uniquely worse" curse than edge cases, that's fine — but probe their reasoning. The chapter's specific argument is that edge cases scale with adversary intelligence, which is the property that distinguishes ASI from the other case studies.
- If they conflate "complications" with "complicated to design" — push them toward the specific Chernobyl example: the SCRAM was *designed to safe down the reactor* and its specific clever feature (graphite tips) is what made it explode. Complications mean the safety mechanism becomes the failure mode.
- If they conflate "self-amplification" with the curse of speed — these are paired but distinct. Speed is "the underlying physics is faster than humans can react." Self-amplification is "the failure mode feeds itself."

Probe: "Of the five curses, which one would you most want a frontier-AI engineer to name unprompted before you'd believe they were treating their system with respect?"

#### Text
content::
\## Additional resources for this topic
::card[[../Lenses/IABIED - QA - AI Differs from Precedents]]

> Whether AI alignment is meaningfully comparable to past engineering challenges, or whether it sits in a category of its own. Worth visiting if the case-study analogies (space probes, Chernobyl, computer security) felt either over- or under-applied.

---

::card[[../Lenses/IABIED - QA - Chicago Pile-1]]

> Extended discussion of Fermi's first reactor — why "knowing exactly where the threshold is" was the load-bearing safety feature, and what happens when that knowledge is missing. A direct elaboration of Chapter 10's narrow-margins curse.

---

::card[[../Lenses/IABIED - QA - Hardware Overhang]]

> Whether the rate of capability gains in current AI is itself a contributor to the "speed" curse, and what the implication is for the time-to-react that engineers actually have.
