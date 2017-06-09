---
title: AI Functionality
description: Distinguish types of AI and know what's possible with different algorithms 
class: contribute
toc:
  what-is-ai: "What Is Artificial Intelligence?"
  machine-learning-vs-deep-learning: "Machine Learning vs Deep Learning"
  supervised-vs-unsupervised-learning: "Supervised vs Unsupervised Learning"
  generative-or-discriminative: "Generative or Discriminative?"
  explainability: "Explainability"
order: 1
image: 
---


## What Is AI?
Welcome to the first lesson of our course on AI.

We'll explain a lot of terms ([check out our jargon file](https://medium.com
/source-institute/ai-jargon-explained-b43fcedb247d?source=collection_home---3
------0-----------) for help on that), but always with an eye on how to
understand AI enough to find business opportunities and act on them. Because,
as the book AI for Dummies put it:

> "Like the purveyors of the emperor's new clothes, many of the "hype leaders"
are get­ting by because they are depending on the rest of us being too afraid
to ask the tough questions or express any doubt."

Or, as Brandon Allgood, CTO at [Numerate](http://www.numerate.com/ "Page 10" )
put it:

> "Everyone is being told that they need AI, but few know why -- and even
fewer know how to use it."

With that in mind, this course will get you ready to both ask the right
questions and learn how you can apply AI to practical business cases. Of
course the first thing to get to is, just what is AI?

In its simplest form, it is the use of algorithms powered by data and
processing power to draw conclusions. Plenty of other computer programs use
algorithms, that's how your phone's calculator works for example, but the
biggest difference here is their application to process large amounts of data.

When you ask your calculator to find a square root, you're inserting a finite
number of data points and receiving a finite number out. If you told your
calculator that you, for example, wanted to figure out the best way to
calculate the average number of bedrooms a 100m2 apartment has in Berlin, your
calculator wouldn't have the faintest idea how to begin to answer you, even
though it can handle all of the math involved. The right type of AI algorithm
with the right data, however, could answer just that question.

Put another way, AI relies on implied understanding and large amounts of data
while classic computation uses structured calculations and fixed processes.

The next lesson will start to delve into two of the most talked about areas
within AI: Machine Learning and Deep Learning. We'll start to explain what
each is, how they fit into the larger world of AI, and what capabilities these
categories have. The goal of these first few lessons is to get you able to
choose between categories of algorithms given a specific challenge.


## Machine Learning vs Deep Learning

Deep Learning (DL) beyond the buzzwords.

![](http://sendy.source.institute/uploads/1495706759.png)

(this is an image we borrowed from [David Kelner](https://medium.com/mmc-
writes/the-fourth-industrial-revolution-a-primer-on-artificial-intelligence-
ai-ff5e7fffcae1))

This chart shows how machine learning is a subset of AI, Deep Learning is a
subset within Machine Learning.

> *Bear in mind that the timeline in the chart is rough, as these new
techniques evolve over time and aren't purely the result of "ah hah" moments.



Data scientist [Yassine Alouini](https://www.quora.com/profile/Yassine-
Alouini) out the distinction most clearly when he wrote:

> **"Machine learning**[[1]](https://www.quora.com/What-is-the-difference-
between-deep-learning-and-usual-machine-learning#bZwzp) is the field of making
computers smarter and able to learn from the data rather than static
instructions.

>

> **Deep learning**[[2]](https://www.quora.com/What-is-the-difference-between-
deep-learning-and-usual-machine-learning#RgiBv) is a sub-field of machine
learning focused on** high-level abstracted representation** of data using
multiple processing layers (thus the **deep** qualifier)."

So is Deep Learning a superior type of Machine Learning which should always be
preferred? Well, [Carlos E. Perez warns](https://medium.com/intuitionmachine
/why-deep-learning-is-radically-different-from-machine-learning-945a4a65da4d)
about just that kind of thinking:

> "The conclusion that DL is just a better algorithm than SVM [Support vector
machines] or Decision Trees is akin to focusing only on the trees and not
seeing the forest."

So DL is both an advanced version of ML and something quite revolutionary in
its own right. Its long-term effects look likely to dwarf what other ML
algorithms are capable of. But in the meantime, that doesn't mean it's better
for all business needs (more on that in later lessons). Ultimately, Perez
finds, ironically, that "despite being ignored, DL continues to by hyped".
It's simultaneously not taken seriously enough and hyped too much and in too
shallow a fashion.

The David Kelner article linked to above gave a useful list of the types of
tasks DL is suited for:

  * Recognizing elements in pictures
  * Translating between languages in real-time
  * Using speech to control devices (via Apple's Siri, Google Now; Amazon Alexa and Microsoft Cortana)
  * Predicting how genetic variation will effect DNA transcription
  * Analyzing sentiment in customer reviews
  * Detecting tumours in medical images

The limitations are that it requires large datasets, lots of processing power,
and is an unexplainable algorithm (more on why that's important in a later
lesson). So DL is great if you have a more abstract problem to tackle where
you want an algorithm that can determine how to do the job it's been assigned
largely on its own, you can afford the raw computing power it needs, you've
got lots of data to work with, and you don't need to be able to explain
precisely how it comes to its conclusions.

Machine Learning outside of Deep Learning is better suited for more defined
tasks like fraud detection, product recommendations, online search, and
financial trading. But we'll explore the specific types of algorithms within
Machine Learning and their applications in later lessons.

In the next lesson, we'll explain the difference between unexplainable and
explainable algorithms and, more importantly, why the difference matters when
applying AI to a use case.




## Supervised vs Unsupervised

Today's lesson is a quick one, just explaining another of the common
distinctions between AI algorithms.

Karl Morrison [summed them up very succinctly on
StackExchange](https://stats.stackexchange.com/questions/144154/supervised-
learning-unsupervised-learning-and-reinforcement-learning-workflow):

> "[Supervised learning is] to be used when, "I know how to classify this
data, I just need you (the classifier) to sort it…

>

> [Unsupervised learning is] to be used when, "I have no idea how to classify
this data, can you (the algorithm) create a classifier for me?"…

>

> [Reinforcement learning is] to be used when, "I have no idea how to classify
this data, can you classify this data and I'll give you a reward if it's
correct or I'll punish you if it's not."

Now let's look at some examples of each type.

Supervised Learning: you show an algorithm pictures of cars and then ask it to
look at a new set pictures and determine whether or not they are pictures of
cars.

Unsupervised Learning: you give an algorithm pictures of cars and ask it to
invent categories for the cars and then place those cars into those
categories.

Reinforcement Learning: you give an algorithm pictures of cars and ask it to
determine which cars are "cool" looking. It doesn't know how to do this so it
learns by making guesses. You tell it whether each guess is correct or not so
the algorithm gradually gets better.

But beyond these three basic ideas there's a lot of math, but this is enough
for you to know which of these three you'll need for any given task. When we
explain various ML algorithms, we'll note whether they're examples of
supervised, unsupervised, reinforcement learning, or a combination.

If you'd like to unsubscribe, [click here](http://<unsubscribe>Unsubscribe
here</unsubscribe>). If you have feedback on how we can improve, please reply!
:)

## Generative or Discriminative

Next, let's look at the important distinction between generative and
discriminative algorithms.

Discriminative algorithms are therefore better if what you care about is the
boundaries between different things instead of how data points are distributed
within those things. Put another way, generative algorithms care about
probabilities, about confidence levels, while discriminative algorithms just
classify things and don't care whether it's 51% or 99% certain.

Let's say you want to understand stock performance. If you'd like an algorithm
that can look at a large number of stocks and find interesting patterns, you
want a generative one. If you'd like to, say, look at stocks and determine
whether or not they outperform similar stocks, you'd want a Discriminative
algorithm.

Here's how [a StackOverflow user](https://stackoverflow.com/questions/879432
/what-is-the-difference-between-a-generative-and-discriminative-algorithm)
summarized an example taken from [a Stanford
course](http://cs229.stanford.edu/notes/cs229-notes2.pdf):

> suppose we have two classes of animals, elephant(y = 1) and dog(y = 0). And
**x** is the feature of animals.

>

> Given a training set, an algorithm like logistic regression or the
perceptron algorithm (basically) tries to find a straight line--that is, a
decision boundary--that separates the elephants and dogs. Then, to classify a
new animal as either an elephant or a dog, it checks on which side of the
decision boundary it falls, and makes its prediction accordingly. We call
these **discriminative learning algorithm**.

>

> Here's a different approach. First, looking at elephants, we can build a
model of what elephants look like. Then, looking at dogs, we can build a
separate model of what dogs look like. Finally, to classify a new animal, we
can match the new animal against the elephant model, and match it against the
dog model, to see whether the new animal looks more like the elephants or more
like the dogs we had seen in the training set. We call these **generative
learning algorithm**.

So when considering which AI algorithms might be suitable for your needs,
think about whether the answers you'd like from them would be discriminative
or generative. When we compare all of the AI algorithms in a later lesson,
each one will be labeled in one of these categories.

## Explainability


When algorithmic decisions need to be explained later, for example decisions
that need to follow legal compliance, where lives are at stake, or any
situation where ethics are an important component, the explainability of
different approaches must be considered. Some decision-making algorithms can
explain decisions in retrospect, while others can't. [David
Weinberger](https://backchannel.com/our-machines-now-have-knowledge-well-
never-understand-857a479dcc0e) compares AlphaGo and Deep Blue, two AI systems
designed to play classic games:

> "Although AlphaGo has proven itself to be a world class player, it can't
spit out practical maxims from which a human player can learn. The program
works not by developing generalized rules of play -- e.g., 'Never have more
than four sets of unconnected stones on the board'  --  but by analyzing which
play has the best chance of succeeding given a precise board configuration."

AlphaGo functions through deep learning, a system of layered neurons, more
specifically a Monte Carlo Tree Search (MCTS). With this system, the computer
starts playing games of Go with itself, gradually learning what produces wins
and losses. It's only programmed with the rules of Go, no human gives it a set
of criteria for how to develop a strategy other than to win. The number of
neural steps in that process is so massive that there's no way a human could
fully grasp it. It's an unexplainable algorithm. We create the basic rules and
its designs itself in a way we can't understand. Or, [as Dave Gershgorn put
it](https://qz.com/897498/by-sparring-with-alphago-researchers-are-learning-
how-an-algorithm-thinks/):

> "The way deep neural networks make decisions is often referred to as a
'black box'--while researchers can tune knobs on the outside to vary how the
machine functions, its inner workings are granular and difficult to decipher,
making the process extremely arduous."

Going back to David Weinberger, the difference between that and Deep Blue is
that:

> "In contrast, [Deep
Blue](https://en.wikipedia.org/wiki/Deep_Blue_%28chess_computer%29), the
dedicated IBM chess-playing computer, has been programmed with some general
principles of good play."

Deep Blue is an explainable algorithm. One person can understand the full list
of rules it operates under and how it makes any one decision (Kasparov was
frustrated the team behind it [wouldn't share the
printouts](https://backchannel.com/what-deep-blue-tells-us-about-ai-
in-2017-3284f92b2a93) to show its decision making and prove no human
intervened). It's advantage is its raw computational power. A human can in
theory make decisions the way it does, the problem is that it would take an
incredible amount of time (an entire lifetime, for example). The same cannot
be said about AlphaGo.

In a world increasing concerned about the ethics of AI, having unexplainable
algorithms equals having unexplained ethical systems for making decisions. So,
if you're developing or using an AI system, keep in mind that if you're going
to need to explain its decision making process and the ethics behind it,
explainable AI is probably a better choice.

