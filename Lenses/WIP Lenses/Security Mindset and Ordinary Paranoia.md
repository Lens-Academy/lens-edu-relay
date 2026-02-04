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

Ask what they found surprising or new. Check if they can explain  in their own words—it's a key concept.

The user is responding to the question: Imagine you've developed an AI system for automated code writing, and it achieves 99% accuracy on all tests. Instead of celebrating your success, apply a 'security mindset' to this situation. What question should you ask yourself to detect the hidden threat in this 99% success rate? 