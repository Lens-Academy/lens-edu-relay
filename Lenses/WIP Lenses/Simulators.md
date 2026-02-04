---
id: c88cfac7-1fe2-4a14-b20b-7903a28daa8d
---
### Article: Simulators
source:: [[janus-simulators]]

#### Text
content::
When discussing AI impact and risks, people often speak of AI as agents, oracles, or other forms of AI actively influencing the world and human understanding. How do these ideas align with what we see in LLMs? Simulator theory shows how, in certain circumstances, an LLM might behave like an agent, oracle, or tool because it can simulate instances of these kinds of systems. The following material provides a brief overview of the "simulators" concept. 

#### Article-excerpt
to:: "influences, including innate structure and reinforcement."

#### Text
content::
How can LLMs exhibit the properties of oracles, agents, or tools while remaining statistical predictors?
#### Chat: Discussion on X-Risk
instructions::
Author's own TLDR of what the user just read:
```
**TL;DR**: Self-supervised learning may create AGI or its foundation. What would that look like?

Unlike the limit of RL, the limit of self-supervised learning has received surprisingly little conceptual attention, and recent progress has made deconfusion in this domain more pressing.

Existing AI taxonomies either fail to capture important properties of self-supervised models or lead to confusing propositions. For instance, GPT policies do not seem globally agentic, yet can be conditioned to behave in goal-directed ways. This post describes a frame that enables more natural reasoning about properties like agency: GPT, insofar as it is inner-aligned, is a **simulator** which can simulate agentic and non-agentic **simulacra**.

The purpose of this post is to capture these objects in words ~~so GPT can reference them~~ and provide a better foundation for understanding them.

I use the generic term “simulator” to refer to models trained with predictive loss on a self-supervised dataset, invariant to architecture or data type (natural language, code, pixels, game states, etc). The outer objective of self-supervised learning is Bayes-optimal conditional inference over the prior of the training distribution, which I call the **simulation objective**, because a conditional model can be used to simulate rollouts which probabilistically obey its learned distribution by iteratively sampling from its posterior (predictions) and updating the condition (prompt). Analogously, a predictive model of physics can be used to compute rollouts of phenomena in simulation. A goal-directed agent which evolves according to physics can be simulated by the physics rule parameterized by an initial state, but the same rule could also propagate agents with different values, or non-agentic phenomena like rocks. This ontological distinction between simulator (rule) and simulacra (phenomena) applies directly to generative models like GPT.
```

Discussion topics to explore:{>>Examples:
- What is "instrumental convergence"? Why would any smart AI seek self-preservation and resources?
- What is the "Gorilla Problem" (Stuart Russell's analogy)?
- How do "Monkey's Paw" or "King Midas" effects apply to goal specification?
- What do skeptics like Yann LeCun argue, and what are the counter-arguments?
- Why might "kill switches" fail against superintelligence?<<}
- `<Discussion point 1>`
- `<Discussion point 2>`
- `<Discussion point 3>`
- `<Discussion point 4>`

Ask what they found surprising or new. Check if they can explain `<key concept>` in their own words—it's a key concept.

The user just answered the question: "How can LLMs exhibit the properties of oracles, agents, or tools while remaining statistical predictors?"