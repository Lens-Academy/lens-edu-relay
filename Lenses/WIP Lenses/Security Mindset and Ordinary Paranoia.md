---
id: c549ae1c-9bab-4c11-ae9b-2c8876265a24
---
### Article: Security Mindset and Ordinary Paranoia
source:: [[yudkowsky-security-mindset-and-ordinary-paranoia]]

#### Text
content::
**The next piece focuses on just how hard it is to get systems we build to do the things we want and how those systems break down under adversarial pressure, which is akin to optimization pressure.  
Effective alignment research requires more than mathematical proficiency: it demands a specific cognitive orientation known as the "security mindset." While standard engineering focuses on making a system work under normal conditions, the security mindset focuses on how a system might fail when its environment — or its own internal optimization — pushes it to its limits.**

#### Article-excerpt
to:: "and some fairly mysterious innate talents."

#### Text
content::
Imagine you've developed an AI system for automated code writing, and it achieves 99% accuracy on all tests. Instead of celebrating your success, apply a 'security mindset' to this situation. What question should you ask yourself to detect the hidden threat in this 99% success rate? 
#### Chat: Discussion on X-Risk
instructions::
TLDR of what the user just read:
Summary: Security Mindset and AI Safety

This dialogue distinguishes between **"ordinary paranoia"** and **"security mindset"** - two levels of safety thinking crucial for AI alignment.

**Ordinary paranoia** involves imagining specific attacks and defending against them. An ordinary paranoid encrypts password files and hides encryption keys, essentially playing a cleverness contest against adversaries.

**Security mindset** goes deeper: it designs systems that don't rely on assumptions being correct in the first place. Instead of hiding passwords, hash them so even reading the file doesn't help attackers. The goal is simplifying the _reasoning_ about safety, not adding more defenses.

**AI Safety Application:** The author argues AGI systems should never be designed to "fail safely" only because you assume they lack capabilities. Don't build systems that would hurt you _if_ they gained cosmic powers quickly - that means you've built something fundamentally trying to hurt you. Instead:

- Use **whitelisting over blacklisting**: require operator approval for new capabilities rather than assuming you can react fast enough to dangers
- Don't rely on assumptions about discovery speed or capability limits
- Design systems where the safety story doesn't depend on winning cleverness contests

The core insight: eliminate whole classes of assumptions from your safety reasoning, rather than piling up defenses against imagined scenarios.

Discussion topics to explore:
**1. Classical vs. Grown Systems** How does training neural networks resemble Coral's "intelligent adversaries finding weird states" - except now your own optimization process is the one discovering unexpected capabilities?
**2. The Whitelisting Principle** Why is whitelisting (require approval for new capabilities) versus blacklisting (react to dangerous ones) especially critical for ML systems with emergent capabilities?
**3. Ordinary Paranoia Applied to ML** Why does listing all dangerous capabilities and adding specific safeguards fail for emergent systems? Connect to Coral's "seven encryption keys" criticism.
**4. Assumption Reduction Exercise** Rewrite this in "neutral facts" without goal-laden language: "I believe my ML system won't develop dangerous capabilities during training." What would security mindset replace this with?

Ask what they found surprising or new. Check if they can explain why modern AI systems are grown, rather than built in their own words—it's a key concept.

The user is responding to the question: Imagine you've developed an AI system for automated code writing, and it achieves 99% accuracy on all tests. Instead of celebrating your success, apply a 'security mindset' to this situation. What question should you ask yourself to detect the hidden threat in this 99% success rate? 