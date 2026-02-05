---
title: "Map of Artificial Intelligence"
channel: "Maxime Kawawa-Beaudan"
url: "https://www.youtube.com/watch?v=hDWDtH1jnXg"
---

Artificial intelligence has exploded in popularity since the release of ChatGPT, and for a lot of people, ChatGPT and Midjourney are pretty much the only AI systems they know. But AI as a field is so much broader than that, and like any scientific field, it's broken into a bunch of different subfields with their own experts, problems, and methods. In this video, I'll lay out the major subfields of AI and explain what each of them means.

I'm going to split it into three different categories: fundamental maths, methods, and applications. Let's start with the foundations, the math. There are three major types of math on which all of AI is based. All of AI boils down in one way or another to these three kinds of math. These are like the deep lore or the dark magic of AI.

First among these is linear algebra, which is the study of linear equations—equations in any number of variables where the highest power of any variable is one. You can add, subtract, multiply, and divide and shuffle around these terms however you want, but you can't include powers of variables. So y equals mx plus b, which you might recognize from middle school, that's linear. 4x plus 3y equals 10, that's linear. 4x plus 3y plus 5z equals one, that's linear. But x squared plus 4x plus 3y plus 4z equals one, that's not linear because of the x squared. Y cubed plus x equals one, not linear. Y plus x equals one, linear.

When you stack a bunch of these equations together, you get a system of equations, and you can use computers to really quickly solve these systems of equations to figure out what x, y, and z make all of these equations true at the same time. Now, why do linear equations matter? Well, Gilbert Strang, one of the godfathers of linear algebra, put it really well when he said that linear algebra is the study of flat things, and flat things surprisingly can be used to model all sorts of real-world phenomena, even things that aren't flat. Get flat if you zoom in enough. So you pair that level of versatility with how efficiently computers can deal with linear algebra, and you get a very powerful combination.

Linear algebra also studies all of the geometric interpretations of the math, where we get ideas like vector spaces, which lie at the heart of all of AI. Without getting too into the weeds, vector spaces are basically the mathematical extension of what lies beyond three dimensions. We can all visualize 1D and 2D and 3D pretty well, but when we get beyond that, things start to get tricky. Vector spaces allow us to extend these things we do understand from the math of three dimensions or less to any number of dimensions—thousands, hundreds of thousands, or millions. In a nutshell, if you can find a way to frame a problem in terms of linear algebra, you unlock an entire library of super powerful math that probably already contains the solution somewhere inside of it.

[Music]

Next, we have vector calculus. Calculus is the mathematics of change. Vector calculus is the extension of calculus to multiple dimensions, to the kind of vector spaces that we get from linear algebra. So if regular calculus is the study of how y is changing relative to x, vector calculus extends that to 3D, 4D, and way beyond. If we stick to three dimensions—the x, the y, and the z—then vector calculus answers the questions: how are z and y changing relative to x, but also how is y changing relative to z and z relative to y and x relative to y and z? How are all these variables changing relative to each other, and how does changing x, y, and z change some arbitrary function of x, y, and z?

[Music]

Now, the reason why vector calculus is so important to AI is because generally, x, y, and z are not just random numbers. They're numbers that control the behavior of a computer model. You can think of these like knobs that we're turning to tune a radio. We call numbers that control the behavior of a computer model parameters. We also generally have a function that measures how good each setting of the knobs is, and we call that the loss. If we're trying to get as close as we possibly can to matching some data points that we collected out in the field, the loss might be the difference between our estimate and the actual data points. In other words, we have this function that measures our error.

Vector calculus lets us calculate how changing each knob will change our error. If we know how changing each knob will change the error, we can keep turning the knob in the direction that reduces the error, and if we do that over and over and over again, we can get to the best possible setting of these knobs. And we call that process learning.

[Music]

All right, here we are. The last of the fundamental three maths is probability theory. Probability is the math of uncertainty, and the real world is full of uncertainty. If we're predicting the weather, for example, we can only really tell you what the probability of rain is. We can't ever be sure. So whenever we're building a model of the real world, whenever we're building AI, probability helps us reason about uncertainty.

[Applause]

So those are the three fundamental kinds of math behind AI. All of AI boils down to these three kinds of math, so much so that you'll sometimes hear people in the field refer to AI as applied linear algebra, and they're only half joking.

Let's move on to methods. These are ways that we use the three fundamental maths to build problem-solving approaches that can be applied to a wide array of specific problems.

The first one here could also be considered a fundamental math for AI, but here I'm thinking of it as the group of methods which we call optimization. Optimization is the mathematics of finding the best thing, and if that sounds incredibly vague and broad, that's because it is. Optimization is a super versatile field studying any setting where we're trying to find the best thing out of all things like it. A good example of this is pathfinding, like how Google Maps routes you to your destination. There, the problem is to find the best set of directions out of all possible sets of directions.

Most of the time, optimization is constrained, meaning there are some rules or limitations that it has to obey. In this case, for example, you have to obey the rules of the road. You can't go the wrong way up a one-way road. We also have to define what we mean by "best." We have to define some criterion for choosing between the things that we're choosing between. In this case, that would be the length of the path.

One subfield of optimization is machine learning, which is the science of learning from data. In machine learning, our criterion and our constraints come from the data. Let's imagine that we're trying to build a computer model that tells us whether an image contains a dog or a cat. In this case, the data would be a collection of images, each one with an associated label that says "dog" or "cat." Our computer model, like before, has these knobs or parameters that control its behavior, and our optimization problem is to find the best setting of these knobs that minimizes our error on the data.

Rather than painstakingly writing out a solution that says, you know, for example, if this pixel is white and this pixel is black, then this is a cat, and if this pixel is green but this pixel is gray, then this is a dog, we want instead for the computer to optimize this problem on its own, minimizing its error on the data. And that's machine learning.

That also happens to be supervised learning, a subfield of machine learning that studies learning from data when the data is labeled, meaning when the data includes the right answer for each example. Within supervised learning, you have all sorts of methods like support vector machines and decision trees and random forests.

Unsupervised learning is a subfield of machine learning that studies learning from data when the data doesn't include labels. For an idea of how this might work, you can look at clustering, which uses just similarities between the data points to discover what should be together and what should be apart and where the separations lie. There is also self-supervised and semi-supervised learning, but those are out of scope for this video.

And next we have reinforcement learning, which is the science of learning from action. Let's say you want a robot to open a door. This might sound simple, but it's actually hard for many reasons. First of all, for our dog-cat classifier, there is always a single right answer: "cat" if the image contains a cat and "dog" if the image contains a dog. But there are many possible motor control actions that the robot can take to open a door, and success is only determined after many consecutive decisions. This means that we can't provide labels or right answers that the system can learn from like we can with the dog-cat example.

Second of all, every decision that our system makes changes the environment. The dog-cat classifier doesn't have to worry that answering "cat" to one image might change the next image from a dog to a cat. But if a robot moves its arm forward, it might bump the door and close it, which will change the correct decision to make at the next step. In other words, every decision it makes has a ripple effect that changes the correct decisions it should make in the future. And the science of solving problems like this, of learning from action, is called reinforcement learning.

Finally, we have deep learning, the science of learning with neural networks. Neural networks are just a kind of computer model, but they're really powerful because they're universal function approximators, which means that given the right data and the right algorithm, these models can learn to mimic anything and to replicate any behavior. They can learn all sorts of different relationships, no matter how complicated, and because of that, they're super versatile. So you'll see them used in supervised, unsupervised, semi-supervised, self-supervised, and reinforcement learning.

You'll often find neural networks and deep learning listed as subfields of their own, and I think that's wrong. There's a science and a theory underlying neural networks and a kind of expertise in knowing how to use them right, but at their core, they're just application versions of the three fundamental maths that can be applied to all sorts of different problems. So I'll call them methods.

And now finally, we get to the applications, which you'll find on many online lists ranked right alongside the methods and the fundamental maths we just described, with no differentiation. You might be surprised at how short the rest of this video is. That's because I hope I've spent the time and organized this video so that you can see the hierarchy here, how each layer builds upon the last, so that by the time I get to these applications, I actually don't have to spend that much time getting into the weeds. You can just know that they use everything from the methods, which uses everything from the maths, to solve these specific classes of problems.

So first is computer vision. Computer vision is AI for understanding the visual world—basically AI that sees. And concretely, this means any AI that has to do with photos, videos, or any other kind of digital image. Object detection, facial recognition, image processing for self-driving cars, and automatic analysis of medical images—all of these are computer vision.

[Music]

The next one is natural language processing, which is AI for understanding language. This includes things like speech-to-text, like Siri or Alexa. This also includes chatbots like ChatGPT and other large language models.

[Music]

Then there's robotics, which is AI for interacting with the physical world. Everyone knows what robots are. You can probably recognize Boston Dynamics' Spot or the Roomba you might have in your house. But AI is important to robotics mainly for perception, which is basically how does the robot use its sensors to understand the world and is often highly intertwined with computer vision, and control, which is how does the robot use that information to make decisions, and is frequently intertwined with reinforcement learning.

[Music]

There's also computational biology, which is AI for the life sciences, and includes things like automatic drug discovery or predicting protein structures from DNA sequences, like DeepMind's AlphaFold, which made headlines a couple years ago. This also includes things like molecular simulations and predictions of diseases from genomics.

[Music]

Finally, we have recommender systems, which is AI for predicting what you like. This is what people on YouTube, TikTok, Twitter, and all other sorts of social media call "the algorithm." That's AI, too, trying to figure out what will make you click.

There are, of course, more subfields and many more subfields of subfields. There's expert systems, planning, reasoning, symbolic AI, and many more, but we just don't have the time for that today. So let me know what you think in the comments. Please subscribe if you learned something today, and as always, I'll see you next week.
