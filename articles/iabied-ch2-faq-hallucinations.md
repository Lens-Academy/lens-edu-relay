---
title: "Don't hallucinations show that modern AIs are weak?"
source_url: https://ifanyonebuildsit.com/2/dont-hallucinations-show-that-modern-ais-are-weak
published: 2025-09-16
author:
  - "Eliezer Yudkowsky"
  - "Nate Soares"
tags:
  - clippings
  - IABIED
  - work-in-progress
---
{--{"author":"AI","timestamp":1774206177195}@@
## Don't hallucinations show that modern AIs are weak?

The answer is nuanced: hallucinations reveal both genuine limitations and underlying misalignments between what AIs are trained to do versus what users want them to do.

### How Hallucinations Occur

Modern LLMs hallucinate because they're trained on text prediction. An AI generating legal briefs will produce confident-sounding citations because real lawyers include actual case law. When an AI lacks genuine knowledge, "making stuff up is the best it can do" to match human-like legal writing patterns. The training process reinforces this behavior through gradient descent optimization.

Even when prompted to say "I don't know," AIs may continue hallucinating because admitting ignorance diverges further --}{++{"author":"AI","timestamp":1774206177195}@@TODO: Re-scrape ++}from {--{"author":"AI","timestamp":1774206177195}@@real expert text than fabricating plausible-sounding information.

### Practical Limitations vs. Underlying Issues

**The constraint:** Hallucinations do meaningfully limit current AI capabilities. Building moon rockets requires long reasoning chains with minimal error rates, and AIs that invent facts present significant obstacles.

**The uncertainty:** Whether hallucinations represent a final barrier or merely the last puzzle piece remains unknown. The field might solve reliability issues through architectural innovations, or solutions could remain elusive for years.

### Misalignment Between Training and Intent

The fundamental problem extends beyond mere weakness: "more reliable AIs will be made eventually," but fixing hallucinations wouldn't necessarily address deeper alignment issues. This distinction matters for understanding why technical fixes alone may prove insufficient for ensuring safe AI development.--}{++{"author":"AI","timestamp":1774206177195}@@website++}