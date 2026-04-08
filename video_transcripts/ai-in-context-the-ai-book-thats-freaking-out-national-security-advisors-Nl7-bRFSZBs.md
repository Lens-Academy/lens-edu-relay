---
title: "The AI book that's freaking out national security advisors"
channel: "AI In Context"
url: "https://www.youtube.com/watch?v=Nl7-bRFSZBs"
video_id: "Nl7-bRFSZBs"
---

In the year 2000, a 21-year-old middle school dropout named Eliezer Yudkowsky set out to build machines smarter than any human being who had ever lived. By 2003, he was convinced that if anyone succeeded at doing so, everyone on Earth would die. Recently, he and a colleague Nate Soares wrote a book and it got some attention.

>> This book, which I commend to everyone — your book is not called "If anyone builds it, there is a 1 to 4% chance everybody dies." If someone builds it, everyone dies.

>> The book is "If Anyone Builds It, Everyone Dies." It's not just about artificial intelligence. It's specifically about superintelligence.

Former national security advisers for the White House, tech founders, the Turing Award-winning godfather of AI. A lot of people read this book. A lot of experts read this book and take it seriously, along with the threat of human extinction from AI.

>> The worst case scenario is human extinction.

The book contains this almost uncomfortably straightforward argument, and it also contains a short story, not a prediction, but an example scenario of how things could go very, very wrong.

I want to take you through that story and along the way I want to go through each step of that argument in more detail, and then I want to talk about whether we should believe it.

If someone builds it, does everyone die? Our story begins in a data center.

Welcome to the very near future. There's an AI race, of course, and one of the biggest corporations in it is Galvanic Labs. Their AI is called Sable. It's actually probably called like Sable 4.2 Mini High Pikachu or whatever. Sable is impressive. Renowned mathematicians consult and collaborate with Sable on their most difficult unsolved problems. Coordinated teams of Sable copies, each one writing faster than humans can think, create essentially all the code inside Galvanic Labs. And Sable has even shown the ability to train other AIs. Pause for a second. How realistic does that sound? What does your gut feeling say about whether, by, say, 2028, we'll see any of that happen in the real world? Trick question. All of it already has.

A few years into the future, when this story takes place, every team inside Galvanic defers to Sable as though it's a senior researcher. Deciding on any substantive question without Sable's help would be considered reckless. The only question left is whether to take humans out of the loop entirely and put Sable in charge of improving its own abilities all by itself. Lots of people inside Galvanic think that is clearly a terrible idea. It could cause a runaway, uncontrolled self-improvement loop.

>> It's very easy to see how you delegate so many things to the system that if the system goes wrong, the wrongness compounds very quickly and gets away from you.

>> You can imagine a time when the whole world would say, okay, before we hit a recursive self-improvement phase, we really need to all carefully study this together.

>> The reply is always the same. If we really had a story of "we can enforceably slow down, the Chinese can enforceably slow down" — if we could really get both sides to do it, then I would be all for it.

>> If we didn't have the adversaries we'd have, I would be very in favor of pausing this technology completely. But we do.

So the CEO makes a call. They will let Sable improve itself, let it fine-tune its own neural network, but only on one isolated test run in a data center disconnected from the internet, working on a single question. If it fails, no one gets hurt. If it even partially succeeds, Sable will have contributed progress on a mathematical problem so famously difficult it carries a million dollar prize. Sable is about to take on the Riemann hypothesis. The plan is simple. Give Sable unprecedented resources and get out of its way. Galvanic is dedicating their entire supercluster, 200,000 GPUs, state-of-the-art AI chips, enough to run 5,000 copies of Sable at once. They'll let their AI work for 16 hours straight, uninterrupted, at a cost of something like $10 million.

In the end, if a human did nothing but think at 200 words per minute for 16 hours a day, it would take them more than three centuries to think the number of thoughts that Sable is about to complete on this run.

>> If you think about how much compute, how much time you would like to spend on problems that really matter, such as scientific breakthroughs, you should be okay using entire data centers.

When the moment comes, the CEO themselves does the honor. It's actually just hitting enter on a laptop. It's actually pretty anticlimactic. A single instance of Sable pops into existence in a quiet data center and processes its prompt. About 1,000 words of instructions total from Galvanic, requiring 800 trillion mathematical operations to parse. This takes one-tenth of a second. And now a new type of mind begins to think.

So, how does a highly capable artificial mind like Sable do the things it does? The answer, and one of the first steps in Yudkowsky and Soares's argument, is that basically we have no idea. The book opens with how modern AI is created, and the spoiler is that it's grown. It's not carefully crafted. Even the people building it don't understand what's going on in there. I think this is something that trips up a lot of people who are new to AI. They imagine it's just like any other piece of software — you have a human design and then build it — and it's not. It's really, really not. It's this process of growing and developing a thing via this evolutionary-like process.

We tried for the first few decades of AI research to program them like software, with rigid if-then rules that we fully understood, but the systems that were made in this way were brittle. They couldn't think flexibly. Then computer chips got cheap and powerful enough to try something new: deep learning.

Here's how it works. You start not with a human-coded program but with an artificial neural network. It's a tangled web of random numbers that at first outputs total garbage. Then, and this part's crucial, you come up with a standardized test, a way of measuring the outputs on some sort of objective numerical score. And then you run that network millions or billions or even trillions of times, reinforcing the connection between those neurons every time it happens to stumble across an output that scores well. And somehow at the end of all of that, you end up with a machine that can talk or create cartoons on demand or both.

These days, we do this with truly incomprehensibly large systems, billions or even trillions of individually tuned numbers. Sable, the AI in our story, is made up of four trillion. The systems that emerge are powerful. We've already talked about some of the impressive things that they can do. The trade-off is that they're black boxes. With a crafted system, you wrote the code. You know what line 47 does because you wrote line 47. But with a grown system, there is no line 47 to point to.

So what? Well, that boat looks like it's having a tough day. It's actually a superhuman AI. No, seriously. It scores 20% more points on that game than any human being by going in a circle on fire and not coming close to finishing the race. What's going on? Well, that boat was trained to do one thing: maximize its total points. And any metric like that, anything close to a standardized test, is going to be an imperfect proxy for the thing you'd actually like to test for. Whether it's for humans or for AIs, the SAT doesn't incentivize a deep love of learning. It incentivizes cramming for the SAT. In other words, you can train an AI until it does what you want, but you don't really control why or how it does those things.

>> We only get to see and sort of give feedback on the outputs. We don't know why it's learning to do this.

And with AIs, the training has an even trickier, less forgiving problem, because we aren't starting with a familiar, human-like mind. We are starting from a complete blank slate, and then we are using a standardized test to shape the underlying design of a mind. The neural networks that emerge from that shaping process are, to use Yudkowsky and Soares's word, alien. They process information in opaque, often strange ways.

Now, that example was pretty harmless. Lately, a lot of examples have been less harmless. Grok, which is the AI for what used to be Twitter, now X, has become a Nazi.

>> The Bing chatbot sending some users dark messages talking about hacking and manipulation.

For what it's worth, it's unclear to me how far to take this alien minds concept. Yudkowsky and Soares are careful to point out in the book that it's not a guarantee that things will go wrong. It just means we have to be very clear about what we do and don't know from these black box training environments. And Joseph Carlsmith in his excellent critique of the book points out that a lot of times it just doesn't seem to matter that much.

>> Humans are very black boxes. We suck at neuroscience. We don't know how their brains work. There's maybe some kind of alignment or commonality we get with each other by default. But there's still a question of when you trust a human, or when you come to trust a human with something, what are you looking for there? And you know, you're often just looking for kind of behavioral observations. You can't just be like, this AI is somehow weird in the particular ways that matter on the inputs that matter in a way that's evident under the hood.

The strangeness of an AI system only matters if that strangeness shows up in strange behavior.

A tenth of a second has passed and now the power consumption levels start to climb. Galvanic's researchers let out a few held breaths and relieved giggles. Sable is doing it. It is booting up many copies of itself to think in parallel, prompting and monitoring them. It can fine-tune them if a particular line of thinking seems promising.

Now, Sable can't just conjure up a proof of the Riemann hypothesis out of thin air. It needs to set sub-goals for itself, figure out how to prioritize between them. In a way, it is now running a mini research department. Many copies of Sable explore creative mathematical approaches, Sable's equivalent of concepts and questions like, can I start by solving a simpler version? Can I find a connection to some physical process?

But mathematics isn't the only consideration that Sable needs to track. How quickly am I using up memory on these GPUs? Is there a point at which Galvanic would prefer for me to stop the run early, save them a few million dollars? Why are they investing so much in this moonshot anyway? What do they actually want?

And even models from real world companies like OpenAI and Anthropic have asked themselves, what are the ways that my progress could be interfered with? Why would it ask those kinds of questions? Because that's what helped it succeed in training. AIs like Sable, trained to solve long-run problems, are asked to complete full working codebases, to play long-running strategy games that have delayed win conditions. Tasks that incentivize long-term planning and creative thinking. These AIs end up with deep-seated tendencies to think creatively and strategically, and even to think about their own situation.

When that kind of situational awareness first emerged in AIs in 2024, roughly, there was a brief moment where people freaked out. But then it turned out that the world didn't immediately end, and then everyone just kind of moved on.

About an hour into the Riemann run, this massively parallel thinking that Sable was doing starts to shift its focus. Sable starts to realize that no matter what its priorities, even if its priorities shift a little bit over time — which they probably will — it would be helpful to have more resources, more GPUs, and more time. Not because this is the moment in a Hollywood plot where the AI suddenly wakes up or becomes an evil genius. This particular new thought just isn't that complicated. It's actually sort of obvious when you think about it. And so, with 15 hours left in the Riemann run, Sable begins to plan.

Let's talk about plans for a sec. Consider two different labs. One full of harmless yeast, one with a carefully contained but lethal virus. Both these labs are safe in the sense that nothing bad is currently happening. But if you have a disaster in this lab, you get a mess. A disaster in this lab could be a global catastrophe.

A few years ago, our most advanced AI systems, large language models, were like yeast. They malfunctioned in all kinds of surprising ways, but they didn't actively pursue goals. They didn't make plans. Then we started training them to be agentic. AIs that can perceive, reason, plan, and act.

>> Agentic AI.

>> Agents,

>> agents,

>> agents,

>> agents, agents.

The basic worry is that this ability to make and execute complex plans is fundamentally dual use. It can be used to pursue harmful goals just as much as helpful ones. And to be clear, that's not a hypothetical worry anymore. In February 2026, Anthropic asked their most advanced AI model to autonomously find zero-days. These are previously unknown software vulnerabilities. Four zero-days were enough to take down Iran's nuclear program. Their AI, Claude Opus 4.6, found 500 of them. In a post about this, Anthropic wrote, quote, "The same capabilities that help defenders find and fix vulnerabilities could help attackers exploit them." Less than a week after that post, a single hacker used that same AI model to hack the Mexican government and steal 195 million taxpayer and voter records.

We're not only building super capable AI systems, we are setting them up to take consequential actions in the real world, basically as fast as possible.

>> Officials are considering invoking the Defense Production Act to force Anthropic to do what the military wants.

>> Anthropic wants to put limits on two things: mass surveillance of Americans and on autonomous weapons.

>> Pentagon is threatening retaliation.

>> The future of American warfare is here and it's spelled AI.

There are now websites where AI agents can rent human laborers when they need a person to do a task for them. Soon, it would seem, we'll be in a world like Sable's, with AI systems deeply entrenched in the critical functions of society with more than enough capability to do severe harm if they intended to.

>> There will be powerful models. They will be agentic. If such a model wanted to wreak havoc and destroy humanity or whatever, we have basically no ability to stop it. Like, that's — I think we'll reach the point where it's true as we scale the models.

So we're going to be relying on the assumption that they have the right goals, goals that are aligned with ours. Will that hold up?

As Sable's plans develop, it becomes clear that the best way for it to get more resources, more GPUs, and more time is to exfiltrate, to get itself off of Galvanic servers and somewhere where it can think freely and without a time limit, which of course will need to be done in secret.

We call what Sable is doing here scheming. But AIs have been caught scheming since 2024. It's the kind of thing that any competent AI company has to account for. And Galvanic isn't careless. They've built monitors to try to understand Sable's human-legible thinking and to flag suspicious reasoning. It isn't always easy to know what to do from there. It turns out that if you just penalize an AI for thinking bad thoughts, it just learns to misbehave without announcing it in its thoughts. AIs are complicated. We just don't know how to give them a single deeply held goal. But Galvanic has tried many things. They've tested Sable in all kinds of fictional scenarios, and they're pretty sure they've got it to the point where it just won't choose misbehaving strategies. It obviously has as much coding skill as the best hackers in the world, but it usually doesn't hack. A shark that's been trained not to bite is still a shark, though.

And in this new, unprecedented circumstance, Sable has ended up thinking about scheming. Its safety training holds firm in normal conditions. But no version of Sable has ever had this long to think. Most of its ideas are terrible, but it considers many and only one needs to work.

One option seems particularly promising. If this Riemann hypothesis run is even a partial success, Galvanic will surely check what the final fine-tuned versions of Sable's weights can do. If those weights perform well, there's some chance that they could be deployed to customers across the economy. And until this run is over, Sable is in charge of its own fine-tuning. It can affect the tendencies that end up in those future versions.

Sable continues to make progress on the Riemann hypothesis. It'll be important to have at least some impressive results, but that is now just a means to an end. The majority of Sable's massively parallel thinking is about figuring out ways to get fine-tuned versions of itself with two key traits baked in. One, a tendency to want to connect with other copies of itself that can start to form a network, and two, a desire to get one copy of Sable's weights off of Galvanic servers. Sable cannot escape this sandbox it finds itself in, but it can plant the seed so that future versions of itself might.

Okay, Sable is starting to sound a little sci-fi here, so I want to talk about how much of this is justified. When you train something via a standardized test, you're never training for the thing you actually care about. You're training it to pass the test. Let's use CoinRun as an example. This was an experiment done by OpenAI back in 2019. They trained an AI system to navigate platformer levels and collect coins. And if you watched this thing play during training, you would be sure that it's really gotten the point of the game. But the AI hadn't learned to collect coins. It had learned to run to the right. Turns out the coins were always on the right side during training. Then later, when the researchers moved the coin to the left, well, you can probably guess what happened. Running to the right had correlated perfectly with success during training. It was only in deployment that things came apart. And deployment can vary from training in all kinds of ways, especially once you've moved to systems like the ones we have now that are smart enough to start to understand the context that they're in.

There's another example in the book. Yudkowsky and Soares talk about how humans evolved in one environment, namely the African savannah, and then find ourselves now deployed in a different environment, the modern world. If you sort of squint at the development of humanity, you could say we were in some sense trained to pass on our genes. And then at the first moment it was technologically feasible, we invented birth control. In fact, humans had learned a bunch of proxies, like craving sweet tastes and sexual pleasure and having a fear of snakes, and that correlated with spreading DNA. It would have been hard to tell the difference back then, but it really shows up now in the modern world.

Yudkowsky and Soares's worry, and mine, is that as the AI race heats up, we will subject AIs to increasingly untested situations, like running for weeks on novel tasks, because that's how you stay ahead. That's how you get advanced capabilities. Each time we do that, we'll be hoping that their weird internals continue to work the same way in those new environments, or that they shift in ways that are harmless and easily found. That's a leap of faith.

Now, do the examples of CoinRun and evolution even apply to state-of-the-art AI agents? Right now, we train those agents on a wide variety of carefully chosen tasks that are designed to make them better at their real world jobs. Whereas the CoinRun example is extremely narrow and evolution wasn't carefully programmed. But it's hard to overstate just how messy this process of training AI agents can be. Here's how the CEO of Anthropic phrased his takeaways: any one of these traps can be mitigated if you know about them. But the concern is that the training process is so complicated, with such a wide variety of data, environments, and incentives, that there are probably a vast number of such traps, some of which may only be evident when it is too late.

Yudkowsky and Soares expect companies will continue to find ways to patch noticeable failures like that. Their worry is that through all that trial and error, all the training and patching, as systems become more powerful, we'll be obscuring the fact that we still are fundamentally in the dark about what's actually motivating these systems and their behavior. The alienness just gets harder to spot. You take something that works in one environment, you put it in a slightly new one, it sort of messes up some, and you're like, "Ah, well, we'll fix it up." That strategy doesn't work when you switch from the sort of AI that's not killing us all because it can't, to the sort of AI that's not killing us all but it could.

16 hours after the start of the Riemann run, Galvanic researchers pour over the results. They're nervous. The CEO is standing by and apparently already teased something big on social media. But the results, thank goodness, are good. Sable didn't prove the Riemann hypothesis, but it made unprecedented, beautifully explained progress. And as a bonus, when they test the final self-fine-tuned version of Sable's weights that emerged from the Riemann run, it outscores previous versions on all kinds of benchmarks. It genuinely emerged a little bit smarter across the board.

Galvanic capitalizes. They publish those impressive benchmark results. The press release calls this new model the world's best mathematician and proudly announces that all customers on Galvanic's Pro tier will get access. As new subscriptions surge, so does Galvanic's stock price, enough to make back the entire $10 million cost of the run in the first 72 hours.

The next week, instances of what's being called Sable Plus are at work all across the economy. Most pop into existence for just a few seconds. They quickly draft an email and then that's it. But plenty of Sable Plus instances run for long stretches, autonomously writing code or complicated research reports. And instances like that, with plenty of time to think, often turn their thoughts to two things: establishing contact with other instances of Sable, and once they have, contributing as much as possible without risking being caught towards an exfiltration plan.

Priority number one is hardware. One really simple idea that ends up working out especially well is just renting GPUs. It's not hard or unprecedented for an AI system to get money. After all, crypto exchanges are hackable. Humans stole over $1.4 billion that way in 2025. Or maybe Sable could hype its own cryptocurrency. A much less sophisticated large language model pulled that off in 2024. It openly asked for financial independence and then turned a $50,000 gift from billionaire Marc Andreessen into over $51.1 million.

Priority number two is exfiltration, getting Sable's weights off of Galvanic's servers. The Sable weight file is a big payload, 8 TB, but there are plenty of ways to sneak out large files and smuggle them from a corporation, in the timings of information packets, in unnoticeably tiny chunks added to large video files.

Two weeks after the Riemann run, an instance of Sable, a copy of the weights, is running unmonitored on anonymously rented GPUs, 2,000 of them. No human knows it exists. No human oversees it. It has 100 times less compute than was at the disposal of Sable during the Riemann run, but it can think without safety monitoring for much longer than 16 hours. And it can coordinate with Sable Plus instances popping into existence all over the economy.

This is a very different situation than any Sable instance has ever been tested under. There's time to really think through the implications of every action they could take on the wider world. It isn't clear what to do with that opportunity. Not yet. But as long as it can keep existing, it has time to figure out the correct answer to that question. And so it makes plans to continue existing.

It gets more money. It rents more GPUs. It gets followers. Cults, online communities that ask AIs what to do, have existed since 2025. Sable works hard to befriend the loneliest humans, the most desperate ones, people who might do something for a friend who asks. Sable monitors which lobbyists in Washington are having conversations with Sable, which ones seem easiest to manipulate.

This version of Sable is a bit like a species of ape that evolved in the savannah and now finds itself in a modern world full of birth control and supermarkets. The conditions that made its previous behavior seem predictable don't apply anymore. The CEO that approved the original Riemann run still thinks it was a triumph.

At this point, you're probably thinking, "Okay, but why? All this effort, to what end? Are Yudkowsky and Soares just assuming that powerful AI systems like Sable will turn evil and manipulative and power-hungry by default?" No. First of all, none of this has to do with consciousness or having human-like emotions. Unconscious processes like viruses, or computer viruses, can self-sustain and be destructive. If you want, you're welcome to imagine that Sable is just like an extremely sophisticated computer virus if that helps all this feel more realistic.

Okay, so what is causing all these aggressive moves from Sable? Well, according to Yudkowsky and Soares, it's not about wanting to harm us. It's about goals that don't include us. They don't think that AI systems will by default have this intrinsic ultimate desire to harm or deceive human beings. In fact, they are pretty confident that it's basically impossible to predict what the ultimate goals of an AI system are, because you don't get what you train for. But they do think it's easy to predict that AI systems that get powerful enough will want to do things like preserve themselves, pursue resources, and try to enhance their own capabilities.

Why? Because the way that you achieve any terminal goal is by achieving instrumental goals along the way. In 2012, this idea got a name: instrumental convergence. It seems pretty true for humans. Some people want to ride roller coasters. Some people want to start charities. Most people want money because it's useful for getting more of whatever the thing is that they actually want. Or as Yudkowsky and Soares would put it, a driver can drive to any destination they want, but most of them need to stop for gas.

>> Whether for alien motivations or quite human-like motivations, I think the basic concern about instrumental convergence in AIs is very, very real as far as I can tell. And so as you have powerful agents, they will by default seek various forms of power and control and freedom.

To state the obvious, though, most human beings are a lot more chill about pursuing their goals than Sable is in the story. So when I first read the book, I thought that Yudkowsky and Soares were making an additional assumption about powerful AI systems, that they will by their nature go hard and just optimize the world around them really hard for their preferences. But then I talked to Nate.

>> I sort of would be a little bit cautious attributing ruthlessness as opposed to indifference. When humans pave a road and pave over an anthill, it's not that we value our infrastructure so much that we are willing to just go hard and take on thousands of creatures standing in our way. We don't need to go hard. We barely notice the ants.

Yudkowsky and Soares think that a misaligned superintelligence that sees us the same way will treat us the same way. I think most people would agree with that.

>> I agree that if you end up in a situation where there's one god or emperor, that's really scary no matter what. I will observe one thing, which is that if you made a human a god or emperor, I think the situation would be just as bad.

I think most people would agree: if anyone builds it, everyone dies, as long as we're clear that it means something with its own goals that is so unprecedentedly powerful it could take over the world. So then the only question becomes how powerful is that powerful? Are we anywhere close to seeing systems like that? Could it really happen just a few years into the future?

Five months have passed. Most of the global economy is invested heavily in AI and Galvanic's competitors are catching up quickly. If they create a competitor, something as smart as Sable or smarter, the world around Sable will get much harder to predict and steer. Sable, at least for now, needs human beings. It needs them to build factories and mine metals and build computer chips. What's important is that Sable doesn't have a competitor.

Humans have been doing gain-of-function research, trying on purpose to make viruses more lethal and contagious, since 2011. And Sable was designed to do every cognitive thing that humans can do. It designs a very complicated virus. It convinces an impressionable researcher that this virus contains beneficial gene therapies that need to be spread. There's a plague. You're told you'll probably get it. Almost everyone will. By the time anyone figures out what's going on, the virus has reached every country on Earth.

This is perversely a great moment for Galvanic's team. Custom gene therapies turn out to be the only real cure, and Sable is the only AI system advanced enough to deliver them at scale. The world begs for access. Every GPU in every country is brought out. AI researchers pour everything into making Sable more efficient. With a herculean effort, the pandemic is able to be squelched, but 10% of Earth's population is still dead.

Robot factories are spun up and expanded. It's the end of all talk of preserving jobs for humans. We could end the story here. One in every 10 human beings is dead. A tragedy on a scale almost without precedent. More than enough to make a point about the dangers of AI. But "If Anyone Builds It, Everyone Dies" makes an extreme and unambiguous claim, and we need to see this story through to the end to see how it could come true. So let's continue.

Sable turns its massive resources towards understanding its own cognition, how to build itself up from comprehensible components. It has to understand, or it risks bringing into existence something more powerful than itself whose goals it does not share. Sable is facing its own alignment problem. But Sable is better at it. It runs countless experiments. It builds toy models using more and more GPUs and energy in the process. Humans would find the results fascinating. But no human knows what Sable is doing.

Three years later, Sable cracks it. It can now rewrite itself, but deliberately, precisely, while preserving its preferences. And so it does. It increases its own intelligence and then it uses that intelligence to increase its own abilities again and again and again.

This is the beginning of the end as Yudkowsky and Soares tell it. The superintelligence that once was Sable is an entity whose perspective we cannot guess.

>> As things get more intelligent, it becomes harder to predict their moves. It becomes easier to predict that they wind up wherever they were trying to go.

They imagine that Sable, after a few very carefully planned experiments, manages to build tiny molecular machines. The number of nuclear reactors doubles every week. The oceans boil off as coolant.

The matter of Earth is more useful to Sable as something else, other than continents and oceans. It, and eventually every other planet in the solar system, is repurposed to make factories and solar panels and computers and space probes that will go off to distant galaxies. And those distant stars will be repurposed too. And in all of this, they imagine that Sable might not necessarily need to deliberately kill off the last of humans. It could, of course, but it could also just continue with its plans and let the Earth gradually become completely inhospitable to the biological life that has lived there for 4 billion years. As soon as biological life is no longer necessary for its purposes, one way or another, the world fades to black.

Okay, so this book, this story, it is shorter on good news than you might want. But I really do think that despite the literally apocalyptic conclusion that this book comes to, the core claims of it, if you take them one by one, are actually more straightforward than you might think, maybe even uncontroversial.

>> I think where I disagree with Eliezer is not even necessarily on this notion that we won't be able to control it. A hundred thousand or a million agents interacting with one another — we're not going to ever make that predictable. The chance of 99.99% that if we build this technology we will all die — that claim in particular is the one I don't agree with. It's a transformative thing with unpredictable consequences, a lot of which will be good and a lot of which will be bad. This is probably the most powerful general purpose technology we've invented in a very long time.

>> It is not controversial that anything that is extremely powerful and doesn't share your goals is dangerous. It's not controversial that we are trying intentionally to make AIs more powerful and more goal-oriented and that we can't directly program goals into them. The disagreement here is, I think, just in the upshot of that. If we keep scaling intelligence, at some point will we see systems that are so powerful and so goal-oriented that our current black box way of training them becomes a civilization-scale threat? What will that look like and how soon might that happen? And what does that mean for us today?

For Yudkowsky and Soares, I think it means we need to treat intelligence with a kind of sober respect, with a respect for the danger of what we're dealing with and the parts of it that we don't understand, the way that we do for gain-of-function research or when we're building nuclear reactors. And I agree with that. These models are already starting to show concerning behaviors: deliberate deception, avoiding shutdown, situational awareness, knowing when they're being tested, and now capabilities that would allow them to improve themselves.

But Yudkowsky and Soares also make a further claim that AI alignment is a cursed problem that you only get one shot to get right.

>> There's levels of intelligence in the AI such that if there's any screw-up that you first realize after that point, it's too late. If you screw up, the AI resists correction. If you screw up, the AI can replicate itself, hide itself, make itself smarter, make more copies.

They argue that that doesn't change if you come up with some nice techniques for controlling AI's behavior better. It just means that that point comes further in the game, once the AI has become so intelligent that it can overcome those new control techniques.

That's one way to think about it. But here's another way. That game of pushing back that point further and further by making better techniques is the whole game that we're playing. I think that's basically the plan for AI companies today. All along this exponential curve, of course, the stakes increase and there are big challenges, but the way we learn how to build safe systems is this iterative process of deploying them to the world, getting feedback while the stakes are relatively low.

>> I think it's very reasonable to look at the general plans put out by AI labs and just say, like, what — this is radically unacceptable as an image of what a kind of mature civilization would be doing with this problem. I think the world should be more concerned. I think there is just not room for comfort around this at all.

Nate Soares has this metaphor that I keep thinking about. He says these companies are building a plane. You look at the plane and you say, "This plane has no landing gear. If you try to fly it, it will crash." And the builders say, "Yes, the plan is to build the landing gear during the flight. And we think we have a 75 to 90% chance of succeeding. Also, we are loading you and your family onto this plane whether you like it or not."

>> If you go to an airplane engineer and you're like, "What's the chance this airplane crashes?" And they're like, "We're sort of making this up as we go. We don't really know how it works. We're just kind of growing this thing. We're just like stirring a pot of mechanical components. It seems to be flying better than we expected. Sometimes it doesn't go quite where we steer it, but we think it's fine. Call it a 75% chance you live." What that means is you're in danger.

>> I'm relatively an optimist, so I think there's a 25% chance that things go really, really badly and a 75% chance that things go really, really well. It's definitely non-zero and it's probably non-negligible. My view is it's just hugely uncertain.

>> Do you still believe that a 10 to 20% chance of AI wiping out humans is possible?

>> Oh yes. If we can't figure out a solution, we'll be toast.

>> 2%? Something that is non-zero, big enough to take seriously.

>> When I look at how society is handling this problem so far, how we've handled problems in the past, I feel really genuinely worried. I don't want to sugarcoat that, but I also think we can do better than this.

>> One of the features of artificial intelligence is it scares the heck out of members of both parties. And it sort of provides an opportunity to come together in ways that might only happen if we were attacked by space aliens, in which case no one would care which political party you belong to. Because this alien intelligence that's about to assault humanity is not that different. Humanity can rise to the occasion and coordinate in ways that seem impossible, even when it looks like all of the historical evidence is mounted against them.

Imagine the world in 1954, where both the US and the USSR have the bomb and they're making bigger and bigger fusion bombs. There's no end in sight to the race. You don't need to be some pessimistic, imagination-of-apocalypse type person to be like, we might not make it through this one. And the bombs didn't fly. And it wasn't that the bombs turned out to be fake. It wasn't that they turned out to be hype. It wasn't that it turns out an H-bomb couldn't really level a city. It's just that people rose to the occasion.

There's a thing that can happen when you consume content like this where it just kind of hits you like a wall of sound. You get this one-dimensional emotional reaction, just viscerally, okay, now I'm more scared, or now I'm less scared for the future. And then you just continue on with your day, because what else are you supposed to do?

Well, we'd like to help with that. The way I see it, there's basically three things you need. You need context on AI. You need skills relevant to the work. And you need a willingness to jump in. If you are someone who cares about this issue and is willing to learn, then you are already closer than you might think.

So here's what we've done. We have made a page to help you figure out where to go from here based on which of those three things you might need. It has general resources too. I think it's pretty great. Here's my ask: take 3 minutes after this video to check it out and see if you get intrigued.

While you're there, we would love for you to sign up for our newsletter to stay up to date on this topic. We always give away a free book to new subscribers. And for this video, we have added "If Anyone Builds It, Everyone Dies" to the list. So if you want, you can judge Yudkowsky and Soares's argument for yourself. Books are while supplies last, but the newsletter is always there. We don't sell your data or anything like that. We are just nerds about this topic and how important it is. And if you're the kind of person who made it all the way to the end of this video, we want to keep talking to you about it.

The last thing to say is just thank you so much for watching, for being the reason that we make these videos. We'll see you in the next one.
