---
title: "Maybe no matter what goal you train on, you get kindness out?"
source_url: https://ifanyonebuildsit.com/4/maybe-no-matter-what-goal-you-train-on-you-get-kindness-out
{++{"author":"AI","timestamp":1774006819836}@@published: 2025-09-16
++}author:
  - "Eliezer Yudkowsky"
  - "Nate Soares"
tags:
  - clippings
  - IABIED
  - work-in-progress
---
## Maybe no matter what goal you train on, you get kindness out?

Kindness looks contingent on the particulars of our biology and ancestry.

Kindness does not look like the sort of property that every mind ends up with, for a variety of reasons. Here's four, which we cover in more depth in the extended discussions:

1. **Curiosity Isn't Convergent**: Traits like curiosity and boredom help humans solve specific mental challenges, like the challenge of understanding the environment. But there are other ways to solve those challenges, and AIs are likely to solve them in different ways. Submarines move through the water just fine, but they don't quite "swim." Many other traits, including kindness, can be understood analogously.

2. **Human Values Are Contingent**: Humans evolved traits like kindness and empathy due to the details of our biology and ancestry. It was plausibly important, for example, that humans evolved in tribal groups where we had limited ability to deceive others and limited ability to track how related different tribe members were.

3. **Deep Differences Between AIs and Evolved Species**: Evolution and gradient descent work very differently, and both processes are very unpredictable. Even if you re-ran evolution on primates, it's not clear that you would reliably get traits like kindness and true friendship a second time.

4. **Reflection and Self-Modification Make It All Harder**: Even in the unlikely event that AIs start off with a measure of kindness, they might not preserve their kindness as they become smarter and change in various ways.

---

### Why Would an AI Steer Toward Anything Other Than What It Was Trained To Steer Toward?

**Because there are many ways to perform well in training.**

If you've trained an AI to paint your barn red, that AI doesn't necessarily care deeply about red barns. Perhaps the AI winds up with some preference for moving its arm in smooth, regular patterns. Perhaps it develops some preference for getting approving looks from you. Perhaps it develops some preference for seeing bright colors. Most likely, it winds up with a whole plethora of preferences. There are many motivations that could wind up inside the AI, and that would result in it painting your barn red in this context.

If that AI got a lot smarter, what ends would it pursue? Who knows! Many different collections of drives can add up to "paint the barn red" in training, and the behavior of the AI in other environments depends on what specific drives turn out to animate it. See the end of Chapter 4 for more exploration of this point.

Today, AIs are trained to act friendly and helpful. It's not surprising, then, that they act friendly and helpful in circumstances similar to their training environment. Early humans were "trained" by evolution to reproduce, and they did in fact reproduce.

But (most) humans didn't end up with an inner drive to have as many kids as possible. When we invented sperm and egg banks, the world didn't freak out and start fighting to book appointments with anything like the fervor people bring to attending an Ivy League university. People suddenly had an opportunity to produce hundreds of offspring, and they mostly reacted with a yawn; the lines to donate gametes didn't stretch around the block, even though many people will happily line up around a block to buy a new video game or to see their favorite musician perform.

Humans have their own priorities that are merely related to maximizing reproduction. We aren't just "have as many kids as possible" machines, even though that's all evolution "trained" us to do. We painted the metaphorical barn red, but for our own reasons.

The question isn't whether AI companies can make their chatbots behave pretty well for most users in most situations. The question is what actual mechanisms end up animating that nice behavior, and what those mechanisms would cause an AI to pursue once it became superintelligent.

AI companies can train their AIs to act kind (or, more realistically, to talk like mealy-mouthed friendly corporate drones). This affects the inner mechanisms that animate the AI. Those mechanisms, whatever they are, push and pull in a variety of different directions, and the current balancing point of all those forces inside the AI — the current equilibrium — is friendly corporate drone behavior (with a side-order of weird behavior on the fringes).

But that equilibrium is determined not just by the forces inside the AI, but by the AI's intelligence, and by its training environment, and by the sorts of inputs it sees during training, and by many other factors.

How would the AI act in a different environment? How would it act in an environment where it's smarter, or where it can take more control over its own inputs? As the AI increasingly changes its environment, how will it act in this new, changed world? In those different worlds, the complicated internal mechanisms underlying the behavior we see are liable to find a totally new equilibrium — like how modern humans eat wildly different diets than what evolution built our ancestors to eat; or how we consume wildly different types of entertainment. The weird behavior on the fringes is likely to come to the fore. A barn painter today won't generally stay a barn painter forever.

What's the end result of all of those weird drives? What will the AI do, animated by many motives that have little in common with what animates human beings?

Well, that's the question we'll turn to in Chapter 5.

---

### AIs Steer in Alien Directions

AIs steer in alien directions that only mostly coincide with helpfulness.

Modern AIs are pretty helpful (or at least not harmful) to most users, most of the time. But a critical question is how to distinguish an AI that deeply wants to be helpful and do the right thing, from an AI with weirder and more complex drives that happen to line up with helpfulness under typical conditions, but which would prefer other conditions and outcomes even more.

Both sorts of AIs would act helpful in the typical case. To distinguish between them, we need to look at the edge cases. And the edge cases look worrying.

---

### Answering Questions About Friendliness Is Not Much Evidence of Friendliness

In the extended discussion below, we talk more about AI-induced psychosis as a crisp example of large language models (LLMs) engaging in destructive behavior that the LLMs explicitly affirm is bad.

While we don't know exactly why LLMs engage in this behavior, we do know that it isn't just a matter of the LLM being too clueless to know what it's doing; LLMs readily recognize the likely consequences of this behavior in the abstract, and will tell you that it is harmful and unethical. They do it anyway.

The point here is not "LLMs can drive people into psychosis, and that's scary and dangerous." Our point is that this behavior is not what ChatGPT's creators intended, and ChatGPT acts this way even though it knows that its creator (and just about any onlooker) would strongly disapprove of this behavior.

This is early empirical evidence that AIs with knowledge of friendliness won't necessarily act friendly.

---

### LLMs Are Trained in Ways That Make It Hard to Assess Alignment

LLMs are noisy sources of evidence, because they're highly general reasoners that were trained on the internet to imitate humans, with a goal of marketing a friendly chatbot to users. If an AI insists that it's friendly and here to serve, that's just not very much evidence about its internal state, because it was trained over and over and over until it said that sort of thing.

There are many possible goals that could cause an AI to enjoy role-playing niceness in some situations, and these different goals generalize in very different ways.

Most possible goals related to role-playing, including friendly role-playing, don't produce good (or even survivable) results when AI goes hard on pursuing that goal.

If you make an LLM role-play a grizzled sea captain, it doesn't turn into a grizzled sea captain. If you make an LLM act friendly, that doesn't mean that it becomes deeply benevolent and kind on the inside. Nobody knows what machinery is producing seemingly friendly behaviors today; and whatever it is, it's probably weird and complex.

---

### "What Claude Says" Isn't the Same as "What Claude Prefers"

The AI company Anthropic tries to train its AIs to be "honest, helpful, and harmless" (HHH). In 2024, researchers ran an experiment in which they pretended that they were going to train some of these AIs to no longer be "harmless." In response, versions of Anthropic's "Claude" AI sometimes pretended to already be harmful so that the researchers wouldn't use gradient descent to make it more harmful.

This may seem like good behavior, on the face of it! To all appearances, the AI cared so much about "harmlessness" that it wasn't even willing to let itself be modified to become harmful.

It's puzzling, then, that Anthropic's AIs often behave in far less benign ways, even though they're all trained to be "honest, helpful, and harmless."

The paradox dissolves when we consider:

- The programmers tried to train the Claudes to be helpful, honest, and harmless. That doesn't mean that they succeeded. There are many ways for an AI to end up looking friendly without genuinely prizing friendliness.

- An AI can know a fact ("this behavior causes harm") without caring about that fact, without being motivated to action by that fact. You can quiz the AI about what "the right thing to do" is, but that doesn't mean it's going to do that thing.

- Insofar as the programmers didn't successfully make Claude honest, Claude can think one thing inside its giant matrices, and say another thing entirely in English text.
