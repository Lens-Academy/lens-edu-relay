{++{"author":"AI","timestamp":1782072579576}@@---
id: 42d2d526-c5f2-4d6d-8e70-758cd27f38a9
title: Decomposing the alignment problem
---
#### Text
content:: Assume we have chosen our alignment target. How do we ensure an AI system actually *obeys* that target? This is the **technical** problem of AI alignment. In this introduction we mostly presuppose that AI systems are *trained via deep learning* (later modules on agent foundations go beyond that assumption).

**Training stories**

In the deep-learning paradigm, [training stories](https://www.alignmentforum.org/posts/FDJnZt8Ks2djouQTZ/how-do-we-become-confident-in-the-safety-of-a-machine) are a useful framework for thinking about how to align AI systems. You choose a *training target* (e.g. "my model is corrigible") and then have a *training rationale* for why your *training setup* will create a model obeying the target. Your training rationale needs to actually be correct — which requires technical research to back up any such claim.

**Outer and inner alignment**

With approaches based on reinforcement learning, another popular decomposition is into **outer** and **inner** alignment:

- **Outer alignment** is the problem of [specifying a reward function](https://deepmind.google/blog/specification-gaming-the-flip-side-of-ai-ingenuity/) that rewards an AI's behavior according to how well it obeys the chosen alignment target.
- **Inner alignment** is the problem of ensuring that the trained policy will, even in new out-of-distribution situations after training, [continue to generalize correctly](https://deepmind.google/blog/how-undesired-goals-can-arise-with-correct-rewards/) and obey the reward function. Where the policy has inner processes that actively optimize for a goal, this means ensuring that internal goal agrees with the goal encoded in the reward function — discussed at length in [Risks from Learned Optimization](https://arxiv.org/abs/1906.01820).

**Inductive biases**

In general, the out-of-distribution (or "generalization") behavior of AI systems depends crucially on its [inductive biases](https://www.cs.cmu.edu/~tom/pubs/NeedForBias_1980.pdf) — the implicit or explicit constraints on which functions are more likely to emerge from training. Deep learning turns out to have strong *implicit* inductive biases, as exemplified by [emergent misalignment](https://arxiv.org/abs/2502.17424), a phenomenon whereby narrow fine-tuning can produce broadly misaligned LLMs.

**The decomposition is controversial**

The split into inner and outer alignment is contested, which is why we started from the more general framing of training stories. In particular, in "[Reward is not the optimization target](https://www.alignmentforum.org/posts/pdaGN6pQyQarFHXF4)", Alex Turner argues that the reward function is *not* what a reinforcement-learning policy is optimized to maximize. Instead, a policy performs the contextual computations that were previously reinforced before a reward event. This is similar to Eliezer Yudkowsky's proposal to view biological organisms as [adaptation-executers rather than fitness-maximizers](https://www.lesswrong.com/posts/XPErvb8m9FapXCjhA/adaptation-executers-not-fitness-maximizers).

#### Chat
optional:: true
instructions:: This is the most technically dense lens in the module. Help the learner hold the structure: training stories (target + rationale + setup) is the general frame; outer/inner alignment is a more specific RL-flavored decomposition nested inside it. Common confusions to watch for and correct: (1) swapping outer and inner — outer is about *specifying* the reward (does the reward capture what we want?), inner is about *generalization* (does the trained policy keep obeying the reward off-distribution, including its internal goal matching the reward's goal?). (2) Treating the inner/outer split as settled — it is controversial; surface Turner's "reward is not the optimization target" point that a policy is shaped by previously-reinforced contextual computation, not literally maximizing reward, analogous to adaptation-executers vs fitness-maximizers. (3) Why inductive biases matter — they govern off-distribution generalization, so they govern whether inner alignment holds; emergent misalignment is evidence that deep learning's implicit biases are strong. Stay within the lens content; do not invent new technical claims.
++}