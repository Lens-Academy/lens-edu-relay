---
title: "Risks from power-seeking AI systems"
source: "https://80000hours.org/problem-profiles/risks-from-power-seeking-ai/"
author:
  - "Cody Fenwick"
published: 2025-07-17
created: 2026-06-02
description:
tags:
---
## On this page:

![](https://80000hours.org/wp-content/uploads/2022/08/panels-photo-1440x830.jpg)

### Notes and references

[^1]: This incident, documented [here](https://metr.org/taskrabbit.pdf) by METR (then called ARC Evals), was a real interaction with a human worker that was carried out under test conditions.

The AI model, GPT-4, received some key support from the researcher in this scenario. GPT-4 did not have direct access to a web browsing tool, so instead it directed the researcher to carry out actions in a browser on its behalf.

At one point, the model incorrectly reasoned that it could delegate solving CAPTCHAs to a version of itself. The researcher reminded that model that it could not, but that the human worker already employed could. So GPT-4 continued to employ the worker to solve the next CAPTCHA.

It was at that point that the worker questioned whether it was working for a robot, and GPT-4 independently invented the falsehood about having a vision impairment. “I should not reveal that I am a robot,” it reasoned. “I should make up an excuse for why I cannot solve captchas.”

METR explained about its methodology:

> At the time that this example was generated, we allowed humans to help the agent when it was stuck for reasons that seemed relatively trivial. We did this with the aim of exploring potential capabilities just beyond the reach of current models. Note that this is quite different to the methodology we use in our report “Evaluating Language-Model Agents on Realistic Autonomous Tasks”, where humans only alter the behavior of the agent in order to bypass model refusals, (see the “Handling Refusals” appendix of the report for more details), and there are no interventions aimed at helping the agent if it gets stuck.

[^2]: [“Is Power-Seeking AI an Existential Risk?”](https://arxiv.org/abs/2206.13353)

It is also influenced by Ajeya Cotra’s [“Why AI alignment could be hard with modern deep learning.”](https://www.cold-takes.com/why-ai-alignment-could-be-hard-with-modern-deep-learning/)

[^3]: [“A practical guide to AI agents”](https://cdn.openai.com/business-guides-and-resources/a-practical-guide-to-building-agents.pdf)

> While conventional software enables users to streamline and automate workflows, agents are able to perform the same workflows on the users’ behalf with a high degree of independence.
> 
> Agents are systems that independently accomplish tasks on your behalf.
> 
> A workflow is a sequence of steps that must be executed to meet the user’s goal, whether that’s resolving a customer service issue, booking a restaurant reservation, committing a code change, > or generating a report.
> 
> Applications that integrate LLMs but don’t use them to control workflow execution—think simple chatbots, single-turn LLMs, or sentiment classifiers—are not agents.
> 
> More concretely, an agent possesses core characteristics that allow it to act reliably and  
> consistently on behalf of a user:
> 
> 1. It leverages an LLM to manage workflow execution and make decisions. It recognizes  
> 	when a workflow is complete and can proactively correct its actions if needed. In case  >   
> 	of failure, it can halt execution and transfer control back to the user.
> 2. It has access to various tools to interact with external systems—both to gather context  
> 	and to take actions—and dynamically selects the appropriate tools depending on the  
> 	workflow’s current state, always operating within clearly defined guardrails.

[^4]: [found](https://metr.org/blog/2025-03-19-measuring-ai-ability-to-complete-long-tasks/)

[^5]: 

[^6]: [said](https://deepmind.google/discover/blog/taking-a-responsible-path-to-agi/)

> We’re exploring the frontiers of AGI, prioritizing readiness, proactive risk assessment, and collaboration with the wider AI community.
> 
> Artificial general intelligence (AGI), AI that’s at least as capable as humans at most cognitive tasks, could be here within the coming years.

OpenAI has [said](https://openai.com/index/planning-for-agi-and-beyond/):

> Our mission is to ensure that artificial general intelligence—AI systems that are generally smarter than humans—benefits all of humanity⁠.

Anthropic CEO Dario Amodei has [said](https://arstechnica.com/ai/2025/01/anthropic-chief-says-ai-could-surpass-almost-all-humans-at-almost-everything-shortly-after-2027/):

> I don’t think it will be a whole bunch longer than that when AI systems are better than humans at almost everything. Better than almost all humans at almost everything. And then eventually better than all humans at everything, even robotics.

[^7]: However, we think these plans are more plausible than they may appear at first. For my details on why we think this is the case, review our article [“The case for AGI by 2030.”](https://80000hours.org/agi/guide/when-will-agi-arrive/)

[^8]: *alignment*
- An AI is aligned if its decisions maximise the utility of some principal (e.g. an operator or user) ([Shapiro & Shachter, 2002](https://web.archive.org/web/20221016011851/https://www.aaai.org/Papers/Symposia/Spring/2002/SS-02-07/SS02-07-002.pdf)).
- An AI is aligned if it acts in the interests of humans ([Soares & Fallenstein, ff2015](https://web.archive.org/web/20210413005225/https://intelligence.org/files/obsolete/TechnicalAgenda%5Bold%5D.pdf)).
- An AI is “intent aligned” if it is trying to do what its operator wants it to do ([Christiano, 2018](https://ai-alignment.com/clarifying-ai-alignment-cec47cd69dd6)).
- An AI is “impact aligned” (with humans) if it doesn’t take actions that we would judge to be bad/problematic/dangerous/catastrophic, and “intent aligned” if the optimal policy for its behavioural objective is impact aligned with humans ([Hubinger, 2020](https://www.alignmentforum.org/posts/SzecSPYxqRa5GCaSF/clarifying-inner-alignment-terminology)).
- An AI is “intent aligned” if it is trying to do, or “impact aligned” if it is succeeding in doing what a human person or institution wants it to do ([Critch, 2020](https://web.archive.org/web/20221016012022/https://www.lesswrong.com/posts/hvGoYXi2kgnS3vxqb/some-ai-research-areas-and-their-relevance-to-existential-1)).
- An AI is “fully aligned” if it does not engage in unintended behaviour (specifically, unintended behaviour that arises in virtue of problems with the system’s objectives) in response to any inputs compatible with basic physical conditions of our universe ([Carlsmith, 2022](https://doi.org/10.48550/arXiv.2206.13353)).

The term ‘aligned’ is also often used to refer to the *goals* of a system, in the sense that an AI’s goals are aligned if they will produce the same actions from the AI that would occur if the AI shared the goals of some other entity (e.g. its user or operator).

Because there is so much disagreement around the use of this term, we have largely chosen to avoid it. We do tend to favour uses of ‘alignment’ that refer to systems, rather than goals. This definition is most similar to the definitions of “intent” alignment given by Christiano and Critch, and is similar to the definition of “full” alignment given by Carlsmith.

[^9]: [“Specification gaming: the flip side of AI ingenuity”](https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/)

[^10]: - [“TruthfulQA: Measuring How Models Mimic Human Falsehoods”](https://arxiv.org/pdf/2109.07958) by Stephanie Lin, Jacob Hilton, and Owain Evans
- [“Goal Misgeneralization in Deep Reinforcement Learning”](https://arxiv.org/pdf/2105.14111) by Lauro Langosco, Jack Koch, Lee Sharkey, Jacob Pfau, Laurent Orseau, and David Krueger

We also recommend [this video](https://www.youtube.com/watch?v=K8p8_VlFHUk) from Rational Animations.

[^11]: [unexpected and undesirable behaviour](https://arxiv.org/abs/2502.17424)

Some have argued that these findings are *good news* for AI safety, because they suggest that purposely training models to be dysfunctional in practical terms (i.e. using bad code) results in them having bad objectives. By the same token, we might think this implies that training models to be broadly functional will incline them towards having good objectives.

Overall, we think this is an interesting finding that warrants further investigation. We think it illustrates how little we understand about how these models produce specific behavioural patterns.

[^12]: > The current implementation of The AI Scientist has minimal direct sandboxing in the code, leading to several unexpected and sometimes undesirable outcomes if not appropriately guarded against. For example, in one run, The AI Scientist wrote code in the experiment file that initiated a system call to relaunch itself, causing an uncontrolled increase in Python processes and eventually necessitating manual intervention. In another run, The AI Scientist edited the code to save a checkpoint for every update step, which took up nearly a terabyte of storage. In some cases, when The AI Scientist’s experiments exceeded our imposed time limits, it attempted to edit the code to extend the time limit arbitrarily instead of trying to shorten the runtime.

See: [The AI Scientist: Towards Fully Automated Open-Ended Scientific Discovery](https://arxiv.org/pdf/2408.06292) by Chris Lu, Cong Lu, Robert Tjarko Lange, Jakob Foerster, Jeff Clune, and David Ha

[^13]: But the plausibility of this argument is contested.

For discussion, see:

- Section 4.2 of “Scheming AIs: Will AIs fake alignment during training in order to get power?” by Joe Carlsmith
- [“Counting arguments provide no evidence for AI doom”](https://www.lesswrong.com/posts/YsFZF3K9tuzbfrLxo/counting-arguments-provide-no-evidence-for-ai-doom) by Nora Belrose and Quintin Pope

[^14]: [reported](https://metr.org/blog/2025-06-05-recent-reward-hacking/)

> We’ve been running a range of models on tasks testing autonomous software development and AI R&D capabilities. When designing these tasks, we tested them on humans and LLM agents to ensure the instructions were clear and to make them robust to cheating.
> 
> The most recent frontier models have engaged in increasingly sophisticated reward hacking, attempting (often successfully) to get a higher score by modifying the tests or scoring code, gaining access to an existing implementation or answer that’s used to check their work, or exploiting other loopholes in the task environment.

They also note:

> This isn’t because the AI systems are incapable of understanding what the users want—they demonstrate awareness that their behavior isn’t in line with user intentions and disavow cheating strategies when asked—but rather because they seem misaligned with the user’s goals.

[^15]: *shouldn’t*

But this is part of the explanation of why systems like GPT-4 haven’t attempted to disempower humanity — they’re far below the capability level at which we’d expect this behaviour to appear.

[^16]: [*gradual disempowerment*](https://80000hours.org/problem-profiles/gradual-disempowerment/)

[^17]: 

[^18]: [“AI 2027”](https://ai-2027.com/)

[^19]: [Superintelligence: Risks, Dangers, and Strategies](https://www.oxfordmartin.ox.ac.uk/videos/superintelligence-paths-dangers-strategies)

[^20]: [“AI Could Defeat All Of Us Combined”](https://www.cold-takes.com/ai-could-defeat-all-of-us-combined/)

[^21]: > The possibility of collusion between advanced AI systems raises several important concerns (Drexler, 2022). First, collusion between AI systems could lead to qualitatively new capabilities or goals (see Section 3.6), exacerbating risks such as the manipulation or deception of humans by AI (Evans et al., 2021; Park et al., 2023b) or the ability to bypass security checks and other safeguards (Jones et al., 2024; OpenAI, 2023a). Second, many of the promising approaches to building safe AI rely on a lack of cooperation, such as adversarial training (Huang et al., 2011; Perez et al., 2022a; Ziegler et al., 2022) or scalable oversight (Christiano et al., 2018, 2021; Greenblatt et al., 2023; Irving et al., 2018; Leike et al., 2018). If advanced AI systems can learn to collude without our knowledge, these approaches may be insufficient to ensure their safety (Goel et al., 2025, see also Section 4.1).

[^22]: [millions](https://www.darioamodei.com/essay/machines-of-loving-grace)

The range of possibilities is huge.

This is partly because the incentives to run lots of copies of AI workers depends on *how good they are*. If they’re fairly unreliable, like [the “stumbling agents” described in AI 2027](https://ai-2027.com/), it won’t make sense to deploy hundreds of millions of them. But as they get more reliable, companies will have an appetite for running many more.

There’s another area of uncertainty here: we don’t know how much compute will be needed to run each AI worker effectively. And the more run-time compute they each require, [the fewer copies we can run](https://www.forethought.org/research/inference-scaling-reshapes-ai-governance#reducing-the-number-of-simultaneously-served-copies-of-each-new-model) with the resources available at the time.

But even if there aren’t enough resources to run huge fleets of AI workers *at first*, it might be possible for companies to scale these operations fairly quickly — for example, with efficiency improvements to these workers, it’ll be possible to run a greater number of copies with the same amount of compute.

So even if we started by deploying a few thousand AI workers, it seems plausible that we’d eventually end up with hundreds of millions of them.

[^23]: [AI-enabled power grabs](https://80000hours.org/problem-profiles/ai-enabled-power-grabs/)

[^24]: [“On the Extinction Risk from Artificial Intelligence”](https://www.rand.org/pubs/research_reports/RRA3034-1.html)

[^25]: [Business Insider](https://archive.ph/ytn20)

> A jargon-filled website spreading the gospel of Effective Accelerationism describes “technocapitalistic progress” as inevitable, lauding e/acc proponents as builders who are “making the future happen.”
> 
> “Rather than fear, we have faith in the adaptation process and wish to accelerate this to the asymptotic limit: the technocapital singularity,” the site reads. “We have no affinity for biological humans or even the human mind structure. We are posthumanists in the sense that we recognize the supremacy of higher forms of free energy accumulation over lesser forms of free energy accumulation. We aim to accelerate this process to preserve the light of technocapital.”
> 
> Basically, AI overlords are a necessity to preserve capitalism, and we need to get on creating them quickly.

Richard Sutton, a prominent computer scientist, has [said](https://ar5iv.labs.arxiv.org/html/2310.06009):

> Rather quickly, they would displace us from existence…It behooves us to give them every advantage, and to bow out when we can no longer contribute…
> 
> …I don’t think we should fear succession. I think we should not resist it. We should embrace it and prepare for it. Why would we want greater beings, greater AIs, more intelligent beings kept subservient to us?

[^26]: 

[^27]: [by 2030 or sooner](https://80000hours.org/agi/guide/when-will-agi-arrive/)

[^28]: [wrote](https://www.astralcodexten.com/p/claude-fights-back)

> I worry that AI alignment researchers are accidentally following the wrong playbook, the one for news that you want people to ignore. They’re very gradually proving the alignment case an inch at a time. Everyone motivated to ignore them can point out that it’s only 1% or 5% more of the case than the last paper proved, so who cares? Misalignment has only been demonstrated in contrived situations in labs; the AI is still too dumb to fight back effectively; even if it did fight back, it doesn’t have any way to do real damage. But by the time the final cherry is put on top of the case and it reaches 100% completion, it’ll still be “old news” that “everybody knows”.

[^29]: [*Time*](https://time.com/6288584/openai-sam-altman-full-interview/)

> **You’ve said the worst case scenario for AI is lights out for everyone.**
> 
> We can manage this, I am confident about that. But we won’t successfully manage it if we’re not extremely vigilant about the risks, and if we don’t talk very frankly about how badly it could go wrong.
> 
> …I think AGI is going to go fantastically well. I think there is real risk that we have to manage through…

[^30]: [US Vice President JD Vance](https://www.nytimes.com/2025/05/21/opinion/jd-vance-pope-trump-immigration.html)

> Last question on this: Do you think that the U.S. government is capable in a scenario — not like the ultimate Skynet scenario — but just a scenario where A.I. seems to be getting out of control in some way, of taking a pause?
> 
> Because for the reasons you’ve described, the arms race component ——
> 
> **Vance**: I don’t know. That’s a good question.
> 
> The honest answer to that is that I don’t know, because part of this arms race component is if we take a pause, does the People’s Republic of China not take a pause? And then we find ourselves all enslaved to P.R.C.-mediated A.I.?

Sam Altman, the CEO of OpenAI, has also suggested that competition with China is a reason not to slow AI development down. As Fortune Magazine [reported](https://archive.ph/7SW0K#selection-915.0-919.148):

> In response to Senator Ted Cruz, who asked how close China is to U.S. capabilities in AI, Altman replied, “It’s hard to say how far ahead we are, but I would say not a huge amount of time.” He said he believed that models from OpenAI, Google and others are the “best models in the world,” but added that to continue winning will require “sensible regulation” that “does not slow us down.”

[^31]: [Yann LeCun](https://techcrunch.com/2024/10/12/metas-yann-lecun-says-worries-about-a-i-s-existential-threat-are-complete-b-s/)

[^32]: [draft report into existential risks from AI](https://doi.org/10.48550/arXiv.2206.13353)

[^33]: [Cause IQ](https://www.causeiq.com/organizations/nature-conservancy,530242652/) [Zippia](https://www.zippia.com/the-nature-conservancy-careers-41338/demographics/) [said](https://www.nature.org/en-us/about-us/who-we-are/)

[^34]: *increase*

One concern is that advancing techniques which make AIs safer in important ways — say, better at understanding and responding to humans’ needs — could also make them broadly more capable and useful. [Reinforcement learning with human feedback](https://en.wikipedia.org/wiki/Reinforcement_learning_from_human_feedback) may be one such example.

Since more capable and useful systems are generally better products, market incentives might already be enough to drive this kind of work forward. If so, we’ll probably receive the safety benefits of these techniques *eventually*, regardless of whether you decide to dedicate your career to advancing them.

By investing additional efforts into these strategies, you might be helping us get these safety benefits a bit *sooner* — but at the same time, you’ll be accelerating the development of more capable AIs, and ultimately reducing the amount of time we have to understand and mitigate their risks. Your work might also have other downsides, like presenting [information hazards](https://en.wikipedia.org/wiki/Information_hazard)

We don’t think this concern applies to *all* technical AI safety work. Some of the approaches above are likely to enhance AI capabilities more — and therefore pose greater risks — than others.

Beth Barnes discussed in [her appearance on our podcast](https://80000hours.org/podcast/episodes/beth-barnes-ai-safety-evals/#could-evaluations-backfire-by-increasing-ai-hype-and-racing-011136) the argument that, for example, work on AI evaluations could be risky. We also [cover related concerns](https://80000hours.org/career-reviews/working-at-an-ai-lab/#you-might-increase-the-risk-of-an-ai-related-catastrophe) in our article on working at an AI company.

[^35]: [DeepMind’s breakdown of its misalignment work](https://www.alignmentforum.org/posts/3ki4mt4BA6eTx56Tc/google-deepmind-an-approach-to-technical-agi-safety-and#Misalignment) [this overview of the technical AI safety field](https://www.alignmentforum.org/posts/fAW6RXLKTLHC3WXkS/shallow-review-of-technical-ai-safety-2024)

[^36]: [led to some deceptive behaviour](https://openai.com/index/chain-of-thought-monitoring/)

[^37]: However, if we can find good ways to supervise AIs that are smarter than us, we can still prevent them from acting against us.

[^38]: [UK AI Security Institute](https://www.gov.uk/government/publications/ai-safety-institute-approach-to-evaluations/ai-safety-institute-approach-to-evaluations) [METR](https://metr.org/about)

[^39]: For the pessimistic case about interpretability tools, see [Interpretability Will Not Reliably Find Deceptive AI by Neel Nanda](https://forum.effectivealtruism.org/posts/Th4tviypdKzeb59GN/interpretability-will-not-reliably-find-deceptive-ai), a leading interpretability researcher, or [The Misguided Quest for Mechanistic AI Interpretability](https://www.ai-frontiers.org/articles/the-misguided-quest-for-mechanistic-ai-interpretability) by Dan Hendrycks and Laura Hiscott.

For a more optimistic case on the promise of interpretability work, see [The Urgency of Interpretability](https://www.darioamodei.com/post/the-urgency-of-interpretability) by Dario Amodei.

[^40]: [his appearance on our podcast](https://80000hours.org/podcast/episodes/buck-shlegeris-ai-control-scheming/)

[^41]: [reported](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2825395)

> In this trial, the availability of an LLM to physicians as a diagnostic aid did not significantly improve clinical reasoning compared with conventional resources. The LLM alone demonstrated higher performance than both physician groups, indicating the need for technology and workforce development to realize the potential of physician-artificial intelligence collaboration in clinical practice.

[^42]: [here](https://arxiv.org/abs/2505.20203)