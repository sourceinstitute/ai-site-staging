---
title: Practicalities
description: Understand what costs, people and resources are necessary for using different algorithms
class: contribute
toc:
  do-you: "Do you need to build your own AI?"
  costs: "Investment Costs"
  tuning: "Tuning Algorithms"
  more-data: "More Data Or Better Data?"

order: 2
image: 
---
# Do you need to build your own AI?

First, a clarification of the term 'off the shelf'

> "There's virtually no such thing as off the shelf AI. There are plenty of
great APIs which you could call off the shelf, for example. But, very often
you run into the need to adapt and build upon them to make anything more than
an MVP. It's similar to big data - everyone wants to claim they're off the
shelf and that's how it's pitched but in reality it often needs a good amount
of custom work.

>

> -Boyan Benev, Founder of [Gain
IM](https://www.facebook.com/gainisgood/?ref=br_rs)

Andreessen Horowitz [breaks down the overlaps between API, Library, and
SDK](http://aiplaybook.a16z.com/docs/guides/ai-using), but when discussing
"off the shelf" AI, these three concepts are included within that umbrella
term (which is a bit problematic, but that's how people are using it these
days). Also within that term are end-user software products like [Project
Dreamcatcher](https://autodeskresearch.com/projects/dreamcatcher). These
really are products you can pick up and start using without the need to
integrate or customize them for your needs. So, looking broadly at the methods
of using AI that fall within the "off the shelf" umbrella, here are some rules
of thumb:

## 'Off the Shelf' Advantages:

  * The cost is known (and probably less than a custom solution, though not 100% of the time).
  * The capabilities are known.
  * Off the shelf products are becoming more flexible (look to the Google example below)
  * Less development time.

## Off the Shelf Disadvantages:

> "The downside of commercial software is that they are in most cases complete
black boxes to the users and even to the company's engineers. These packages
are developed as single-sell products which address one specific topic or use
and could prove to be unusable if the situation and the environment changes.
Or the company has to pay for an adoption with additional extensions through
add-ons or customization contracts."

>

> -Ralf Montino and Christian Weber, from Integration of Practice-Oriented
Knowledge Technology: Trends and Prospectives

  * There is often a lack of explainability
  * Not very adaptable (yet, but again this is changing)
  * You lose potential opportunities for patenting and licensing your own AI product.

Google is also the elephant in the room when it comes to off the shelf AI
algorithms. As of their 2017 I/O event, they're working on positioning
themselves as leaders in providing the building blocks on which others can
build off the shelf tools:

> "What Google is really talking about is creating the software and the chips
that the entire AI infrastructure then is going to be built on… Google is
trying to create the foundation for that… What also Google is doing is
designing these systems where basically they're giving companies the building
blocks. And then the companies can use those building blocks to create their
own AI products. It's almost the way that right now it's so easy to create a
website, so different than what it was say 15, 20 years ago. So this is what
Google is seeing… creating an AI product will be that simple, but it will all
be tied into the Google system."

>

> -[Anna Szymanski](http://www.slate.com/authors.anna_szymanski.html) on the
[Slate Money
Podcast](http://www.slate.com/articles/podcasts/slate_money/2017/05/the_auto_industry_a_i_assistants_and_apple_s_new_headquarters.html)

But ultimately, whether you're looking to build a custom AI algorithms or use
off-the-shelf options, knowledge of how to evaluate them is critical (and a
major reason for the creation of this course):

> "In the end, the real downside [of off the shelf AI solutions] is… the gap
between the availability of complex AI methods and techniques and the missing
knowledge to judge them for buying as a product."

>

> -Ralf Montino and Christian Weber, from [Integration of Practice-Oriented
Knowledge Technology: Trends and
Prospectives](https://link.springer.com/book/10.1007%2F978-3-642-34471-8)

At this point, [their AI is even beating their own engineers are creating more
AI](https://futurism.com/googles-new-ai-is-better-at-creating-ai-than-the-
companys-engineers/). So, consider the benefits of custom vs off the shelf and
keep an eye on what Google is doing. The next lesson will delve into the cost
side of this question in more detail.



If you'd like to unsubscribe, [click here](http://<unsubscribe>Unsubscribe
here</unsubscribe>). If you have feedback on how we can improve, please reply!
:)


# Investment costs

In the last lesson we mentioned that using off the shelf solutions for AI has
the advantage of giving you fixed costs, capabilities, and development times.
But to understand the importance of those factors, they should be compared to
the costs and risks of developing your own AI. This lesson delves into that
question, though to be clear, these are only a few examples to give you a
broad idea of what costs could be.

Let's look at an increasingly common example: chatbots.

> "Take the simplest option of each of the 3 variables above [What is the
industry vertical, What level of interaction, and What action capabilities?]
and that's going to be around 0K. Now to the other extreme and you're talking
50K and up"

>

> -[Gam Dias](https://www.quora.com/profile/Gam-Dias)

So between the cheapest and most expensive price points is an 830% difference.

[Another software development firm estimates](https://rubygarage.org/blog/how-
much-does-it-cost-to-build-a-chatbot) ,000 to 2,240 for a simpler chatbot
which isn't, say, designed to represent a major brand with the high standards
that come with that.

But what about implementing AI algorithms to analyze data? Krassimir (Casey)
Paskalev suggestion focused on how this can be done quickly and efficiently
with a data scientist:

> "Technically, the fastest cheapest easiest way [to extract conclusions from
data] is that a data scientist has to sign an NDA and run with it for a day or
a week. That will be cheap, that scientist will have lots of interesting
insights and they can capture 90% of the business value that way."

>

> But, "If you can't afford a full-time data scientist or don't think you have
enough work for them, hiring a consultant is another possible route. But as
you might expect, quality varies. As with all consultants, avoid those who may
appear too good to be true."

>

> -Brandon Allgood, CTO at [Numerate](http://www.numerate.com/ "Page 10" )

On Upwork, for example, [freelance data scientists charge between 6 and 00 an
hour](https://www.upwork.com/hiring/for-clients/how-much-hire-data-
scientist/). They cite an average project cost of 00, though that can
obviously vary a lot depending on the complexity of the algorithm and how much
training it needs (you can use our lessons comparing them to get a feel for
this).

Finally, for developing a full blown custom-built AI solution for something
like augmented reality, supply chain optimization, historic performance
analysis, or content categorization, the costs are much higher.
[AI.Works](https://ai.hacker.works/), a custom AI development company, breaks
down its estimates like this:

![](http://sendy.source.institute/uploads/1495623867.png)

Estimates only go so far, as once you get toward the later stages of
development, there are too many extraneous factors to fully predict costs. But
this overview should give you a general idea of what you can expect in terms
of developing chatbots, custom AI solutions, and simple data analysis
algorithms.

The next two lessons will look at gathering and uses data for AI solutions.



If you'd like to unsubscribe, [click here](http://<unsubscribe>Unsubscribe
here</unsubscribe>). If you have feedback on how we can improve, please reply!
:)


# Tuning Algorithms

For [Yavor Stoychev](https://www.linkedin.com/in/ystoychev/?ppe=1), learning
to tune algorithms for eCommerce applications was a trial by fire in the
trenches at Amazon. While he eventually brought those hard-won insights to co-
founding his own eCommerce company, [Perpetto](https://www.perpetto.com/),
getting there required learning that tuning algorithms is a bigger and more
complex job than he realized.

> "All I found out while we were building this predictor at Amazon is that …
it's not really a plug-and-play thing. You don't just develop something and
launch it in the first iteration. It takes a lot of trial and error to figure
out what data is actually important. In a machine learning algorithm, you
provide it with a certain input and it gives you an answer to a question you
have. What happens is you have to figure out what data is relevant. This turns
out to be a fairly difficult problem and it takes a lot of trials to get it
right.

>

> What we found out... is that the type of delivery that the customer chose at
checkout… [is] not really an important determining factor for whether they
will place a second order or not. We had certain assumptions that were false.
For example, one was the shipping method, one was the categories and whether
they purchase from the same category more often than not. We had certain data
that we thought was going to important but it wasn't. And we ended up swapping
it, trying something else, and just going through a lot of iterations of trial
and error to get this right.

>

> You never get it 100% perfect. You get closer and closer and closer and at
one point it just becomes good enough and you're satisfied. Because it's not a
deterministic system [IE, this is or is not a car]. It's a probabilistic
system [IE, how likely is is that a person will buy jeans after they buy
shoes]…"

How did Yavor apply those lessons learned when he left Amazon to co-found
Perpetto?

> "We started building machine learning technology using a framework called
Prediction IO, which was really good for data scientists and for anybody
really who wanted to get something off the ground quickly. Because they had
the infrastructure in place so you could just one click install it. It will
set up all the necessary services for you and then you can download templates
for it on the internet and run them and see how they work. Customize them, run
them again. So it was a really good playground where you could experiment and
customize templates so that it fits your need and then launch them.... It
really helped us get off the ground quickly because we had templates for
collaborative filtering, we had three of them. We just went ahead, we played
with them, we customized them, and we launched them within a month I would
say… That month was full of weekends and weekend nights playing with machine
learning technology. We were just experimenting."

So, understanding that experimentation was going to be necessary, Yavor chose
to work with a more flexible platform the second time around. Building in the
assumption that extensive tuning, tweaking, and testing was going to be
necessary, even for a framework as usable as Prediction IO, allowed Perpetto
to get its AI systems working very quickly.



If you'd like to unsubscribe, [click here](http://<unsubscribe>Unsubscribe
here</unsubscribe>). If you have feedback on how we can improve, please reply!
:)

# More Data or Better Data?

This lesson aims to give you a general framework for thinking about data and
AI by raising a fundamental question about quantity versus quality.

Norman Winarsky, vice president of Ventures at [SRI
International](https://en.wikipedia.org/wiki/SRI_International "SRI
International" ), co-founder and former board member of
[Siri](https://en.wikipedia.org/wiki/Siri_\(software\) "Siri \(software\)" ),
said at an AI conference in April 2017 that:

> "Between a better algorithm and data, choose data. It's the key in the
future. It's the gold rush, like oil in the Middle East."

Or, as Google's Research Director [Peter Norvig](https://www.quora.com/profile
/Peter-Norvig) put it:

> "We don't have better algorithms. We just have more data."

With this in mind, where should your focus be, on getting better data or more
data?

Start with the types of algorithms available and their data requirements. For
a bit more detail, here's a chart from [Scilearn](http://scikit-
learn.org/stable/tutorial/machine_learning_map/index.html).

![](http://sendy.source.institute/uploads/1496757558.png)

So focus on the specifics of your situation, but are there general rules of
thumb when it comes to data?

Let's take the example, mentioned in a previous lesson, of the Support Vector
Machine Algorithm. When applied to regression tasks, it will actually perform
worse with a larger data set. Though this is an exception, comparing it to
this famous [chart from Banko and
Brill](http://ucrel.lancs.ac.uk/acl/P/P01/P01-1005.pdf) on natural language
disambiguation:

![](http://sendy.source.institute/uploads/1495624189.png)

So who's right?

[Xavier Amatriain](https://www.quora.com/profile/Xavier-Amatriain), the
leading Engineer at Quora, made the point that [overgeneralization are
rife](https://www.quora.com/In-machine-learning-is-more-data-always-better-
than-better-algorithms)  when it comes to applying data to AI. Some claim that
more data always beats a better algorithm while others claim that better
quality data will always beat more data. But there are always exceptions.

> "There's a tendency for businesses to rush in and start collecting all of
the data we can. However, it's possible that what you're collecting is the
wrong data (or incomplete data) because you're simply collecting data for
data's sake. Instead, figure out what questions you want AI to answer and work
your way back to identifying what data will prove valuable.

>

> At my firm, in the beginning stages of any project we try to understand what
specific challenges we'll face. Every project is different and comes with
different risks. Based on those risks, we can determine which models we'll
need to build in order to reduce this risk. Then, from the models we've
outlined to build, our team will search existing databases for related data as
well as determine which data we should be collecting/producing throughout the
project to further guide our efforts."

>

> -Brandon Allgood, CTO at [Numerate](http://www.numerate.com/ "Page 10" )

>

>  

The point to pull from this is that you first need to narrow in on what your
specific needs are, find the algorithms you can use, then ask whether more or
better data will make a substantial difference. If you want to know more about
the type of data needed for your algorithm, you can [hire a data
scientist](https://www.upwork.com/hiring/for-clients/how-much-hire-data-
scientist/) to answer your questions.

In the next lesson, we'll add to what was outlined in this lesson by
discussing historical vs real time data.



If you'd like to unsubscribe, [click here](http://<unsubscribe>Unsubscribe
here</unsubscribe>). If you have feedback on how we can improve, please reply!
:)


