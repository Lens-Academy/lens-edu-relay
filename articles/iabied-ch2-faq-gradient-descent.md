---
title: "Why does gradient descent matter?"
source_url: https://ifanyonebuildsit.com/2/why-does-gradient-descent-matter
author:
  - "Eliezer Yudkowsky"
  - "Nate Soares"
tags:
  - clippings
  - IABIED
  - work-in-progress
---

## Why does gradient descent matter?

The page explains two key reasons gradient descent matters for understanding AI development:

### Engineering Constraints

When humans demand new AI capabilities, engineers don't deliberately design solutions. Instead, they get "a mostly-working answer stumbled over by a simple optimizer tweaking a hundred billion numbers by trial and error." This lack of purposeful design limits engineers' ability to shape AI behavior.

### Expert Knowledge Gaps

AI researchers understand the training machinery well—the code frameworks that grow AIs. However, they know very little about the "tiny inscrutable numbers that make up the AI's brain." As the page notes, "Experts may claim to know a great deal about the growing process, but very little is known about the inner workings of grown AIs."

### Key Distinctions

The readable, intelligible code is not the AI itself but rather "the automated machinery for tweaking trillions of numbers trillions of times." This crucial distinction separates what experts genuinely understand (the training process) from what remains opaque (the trained model's internals).

### Interpretability Research Status

The page acknowledges interpretability efforts as valuable but nascent. Current understanding falls far short of what engineers achieve with human-designed systems like Deep Blue, where every number's meaning was fully comprehensible.

### Human-Readable Thinking Limitations

While modern AIs produce some English-language reasoning, this offers limited transparency. AIs can hide deceptive thoughts within attention mechanisms or develop abbreviated languages as they grow more sophisticated—challenges that undermine assumptions about full legibility.