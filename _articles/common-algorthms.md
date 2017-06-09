---
title: Common Algorithms
description: Know what's possible with different algorithms 
class: contribute
toc:
  categories: "The Major Categories"

order: 2
image: 
---

# Categories
This is a basic outline of the algorithms we'll be covering in the next three
lessons. They aim at tackling the problem outlined by Montino and Weber above:
helping you better compare the capabilities of these AI algorithms.

## Classification (tell me what category this fits into)

Examples of classification tasks would be giving an algorithm medical data and
asking it whether the patient has cancer or not. Or, giving an algorithm data
about your customers and asking it to divide them into categories it will
create.

  * Naive Bayes
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors
  * Random Forest
  * Decision Trees
  * Artificial Neural Networks
  * Logistic Regression

## Regression (help me predict something based on what I know)

Examples of regression tasks would be, say, giving an algorithm historical
data on traffic patterns and asking it to predict what will happen if you
close a specific road for repairs. Or, entering economic data to ask an
algorithm what the effect of a 20% decline in the price of oil on other
commodities will be.

  * Linear Regression
  * Support Vector Machine (SVM)
  * K-Nearest Neighbors
  * Apriori Algorithm
  * Random Forest
  * Decision Trees
  * Artificial Neural Networks

## Clustering (tell me what things are alike)

Clustering algorithms are best when you don't just want to know what
categories data fits into, but how alike or similar they are to everything
else in that category. For example, you could give a clustering algorithm
stock data and ask it to create categories of stocks based on their
performance. Then, based on what clusters they fit into and where they end up
within those clusters, you could chose where you'd like to invest.

  * K Means Clustering
  * Hierarchical Clustering


# Classification 
This lesson breaks down the 6 main AI algorithms which can do this and
discusses their advantages and disadvantages.

> "A good first rule for choosing a method is choose one that you understand
very well.  
>

> It's a theoretical fact that none of these methods are universally any
better than the other, but I'd argue that perhaps more surprisingly there
isn't even often a practical difference that is more significant than who is
using the tool.  
>

> Barring a deep understanding of any of the methods, trees and their various
ensembles (random forests, rotation forests, bagging) are a good place to
start because... they have few free parameters and they're pretty robust to
common real-world data pathologies like irrelevant features, missing data,
features of different scales, certain kinds of outliers, and they can handle
categorical/numerical data side by side."

>

> -[Rick Barber](https://www.quora.com/profile/Rick-Barber-1)



## Naive Bayes Algorithm

You give the algorithm a series of categories, it takes new data and places it
into one of those categories. However, you do need to tell it when it's
correct and when it isn't. The best examples of this are spam filters. Also,
just like with spam filters, this isn't a perfect system and errors will
occur.

Supervised or Unsupervised? | Supervised  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Generative  
  
Used for: document classification and sentiment analysis

Specific Use Cases: spam filters, disease prediction, document classification,
sentiment analysis.

Requirements: A medium to large data set, less than 100,000 samples generally,
several attributes to analyze, conditionally independent attributes, a
balanced data set.



## Support Vector Machine (SVM)

This algorithm classifies data by drawing a line between them, maximizing the
distance between the data and the line. It tends to be very good at not
overfitting (when an algorithm gets really good at its test data and bad at
predicting other thigns, check out our [Jargon file](https://medium.com
/source-institute/ai-jargon-explained-b43fcedb247d) for more on that). So,
it's great at accurately classifying new data based on its training set. The
flip side of this is that it doesn't perform well with huge data sets or if
the classes you're separating your data into overlap. An example might be
trying to analyze news stories and determine whether they are positive or
negative based on the words used.

Supervised or Unsupervised? | Supervised  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: Efficiently classifying data and not overfitting based on the
training data.

Specific Use Cases: Data science libraries, facial expression classification,
text categorization, speech recognition.

Requirements: As mentioned, you don't want your data set too large. For
documents, one example showed performance [slowly began to
decrease](https://stats.stackexchange.com/questions/47090/increasing-the-
sample-size-does-not-help-the-classification-performance) once it analyzed
more than 1,000 documents. You also shouldn't have overlapping classes. It's
better with binary classification overall. You also can't attribute meaning to
its decisions because they are unexplainable.



## K-Nearest Neighbors

[Considered the simplest classification
algorithm](https://www.analyticsvidhya.com/blog/2014/10/introduction-k
-neighbours-algorithm-clustering/), it classifies data points based on the
classification of nearby data points. Because of its simplicity, it's very
fast and the data is very easy to interpret, though its predictive power is
more average. But [be careful and scale your
data](https://mathbabe.org/2013/04/04/k-nearest-neighbors-dangerously-simple/)
(so you don't, for example, have some data on a 1-5 scale while other data is
on a 0-100 scale, they should all be on the same scale), otherwise this
algorithm can really lead you astray.

Supervised or Unsupervised? | Supervised  
---|---  
Explainable or unexplainable? |
[Explainable](https://books.google.bg/books?id=EKNoKQ1L4CoC&pg=PA548&lpg=PA548&dq=is+Na%C3%AFve+Bayes+Classifier+Algorithm+explainable?&source=bl&ots=hJAd1VBrdp&sig=NA0sggSWCgZOJZYsSUU9DXcsyXo&hl=en&sa=X&ved=0ahUKEwj8_Nj_yvnTAhUFQJoKHYCtBMoQ6AEIRjAG#v=onepage&q=is%20Na%C3%AFve%20Bayes%20Classifier%20Algorithm%20explainable%3F&f=false)  
Generative or Discriminative? | Generative  
  
Used for: simple classification tasks

Specific Use Cases: Gene expression, understanding protein structures and
interactions, basic classification of items like, say flowers, based on their
characteristics.

Requirements: Can be done with &lt;100,000 samples, data should be able to be
represented on a plane, your data is scalable.



## Decision Trees

This algorithm is designed to help you handle uncertainty in classifying
things. More specifically, they help you better understand how any one change
affects other factors in classifying things, kind of a big picture
perspective. [It's also good if your data is
incomplete](https://www.dezyre.com/article/top-10-machine-learning-
algorithms/202).

Supervised or Unsupervised? | [Supervised](https://www.quora.com/What-are-the-
typical-use-cases-for-different-machine-learning-algorithms)  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: weighing complex situations with multiple decision-making steps,
each of which affects what future options are available

Specific Use Cases: option pricing, classifying loan applicants,

Requirements: Should be relatively small, the larger it gets the less accurate
and usable it gets. Relies on your expectations, which could be wrong. In this
way, these are very human and fallible versions of AI.



## Random Forest

Creates a series of decision trees with small random variations and calculates
each one. Then, it polls the results to come up with an overall prediction. So
it has all the same requirements as a regular decision tree algorithm because
it begins with the same type of data. The big difference is that it helps to
prevent overfitting, which can be a problem with a single decision tree.

Supervised or Unsupervised? | [Supervised](https://www.quora.com/What-are-the-
typical-use-cases-for-different-machine-learning-algorithms)  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: weighing complex situations with multiple decision-making steps,
each of which affects what future options are available where you want to
prevent overfitting

Specific Use Cases: classifying loan applications, predicting mechanical
failures, predict the onset of chronic disease.

Requirements: Super easy to use, lots of open source options,  overfitting
isn't really an issue here. Other than that, it has all the same advantages of
a regular decision tree.



## Artificial Neural Networks (ANNs)

(Sometimes called Neural Networks, though this technically refers to a broader
category including things like deep belief networks.) This is probably the
most famous type of classification algorithm. It broadly mimics the structure
of the human brain by layering artificial neurons. Each layer chooses a factor
it determines to be important and uses it to make choices to give better
outputs. This structure makes ANNs very flexible.

Supervised or Unsupervised? | Can be either  
---|---  
Explainable or unexplainable? | Unexplainable  
Generative or Discriminative? | Can be either  
  
Used for: When you need a system to figure out how to classify things and
don't care how the system does it.

Specific Use Cases: Character recognition, image compression, stock market
prediction, application decisions (universities, bank loans, etc.), and many
more.

Requirements: Difficult to set up, needs thousands of cycles to train itself,
difficult to troubleshoot when issues arise, but extremely powerful when it
works ([extremetech has some excellent examples of what it can
do](https://www.extremetech.com/extreme/215170-artificial-neural-networks-are-
changing-the-world-what-are-they)).



## Logistic Regression

Don't be fooled by the name, this may be "logistic regression" but it's a
classification algorithm, not a regression one. It just happens to use
regression techniques to do its classification. It looks at a bunch of
variables and predicts the probability of a data point falling into a specific
category based on them.

Supervised or Unsupervised? |
[Supervised](https://chemicalstatistician.wordpress.com/2014/01/05/machine-
learning-lesson-of-the-day-classification-and-regression/)  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: Answering whether a set of predictors can accurately categorize
data.

Specific Use Cases: Image Segmentation and Categorization, Geographic Image
Processing, Handwriting recognition, Healthcare predictions.

Requirements: You shouldn't have outliers, also your variables shouldn't be
highly correlated with each other.


# Regression


Now we're going to break down all the algorithms you can use for regression
and the characteristics of each. Regression itself is all about predicting
future data based on past data.

> "A good first rule for choosing a method is choose one that you understand
very well.  
>

> It's a theoretical fact that none of these methods are universally any
better than the other, but I'd argue that perhaps more surprisingly there
isn't even often a practical difference that is more significant than who is
using the tool.  
>

> Barring a deep understanding of any of the methods, trees and their various
ensembles (random forests, rotation forests, bagging) are a good place to
start because... they have few free parameters and they're pretty robust to
common real-world data pathologies like irrelevant features, missing data,
features of different scales, certain kinds of outliers, and they can handle
categorical/numerical data side by side."

>

> -[Rick Barber](https://www.quora.com/profile/Rick-Barber-1)

## Linear Regression

This algorithm shows the relationship between two variables and how changes in
one affect the other. But this is not based on individual cases, it's based on
an overall conclusions the algorithm draws from the data.

Supervised or Unsupervised? | Unsupervised  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? |
[Discriminative](https://en.wikipedia.org/wiki/Discriminative_model)  
  
Used for: Showing how a change in one variable will affect another variable

Specific Use Cases: Sales estimations, risk assessment, traffic prediction

Requirements: Not many, famously easy to use and explain. It's also very fast.
There are risks of test error and bias affecting your results.



## Support Vector Machine Algorithm (SVMs)

This algorithm classifies data by drawing a hyperplane (a line or plane)
between them. It maximizes the distance between the data and the
hyperplane(s), which means that it tends to be very good at not overfitting.
It usually does this to classify the data, but when used for regression the
trajectory of the hyperplane itself is the regression. As a result, it's great
at accurately classifying new data based on its training set. The flip side of
this is that it doesn't perform well with huge data sets or if the classes
you're separating your data into overlap

Supervised or Unsupervised? | Supervised  
---|---  
Explainable or unexplainable? |
[Unexplainable](https://books.google.bg/books?id=GdQoS1igTtgC&pg=PA203&lpg=PA203&dq=is+Na%C3%AFve+Bayes+Classifier+Algorithm+explainable?&source=bl&ots
=Tq5NM-pkb6&sig=Hb9q8yf8sRfw-
F5NLEEP56yKu10&hl=en&sa=X&ved=0ahUKEwj8_Nj_yvnTAhUFQJoKHYCtBMoQ6AEIUDAI#v=onepage&q=is%20Na%C3%AFve%20Bayes%20Classifier%20Algorithm%20explainable%3F&f=false)  
Generative or Discriminative? | Discriminative  
  
Used for: Efficiently classifying data and not overfitting based on the
training data.

Specific Use Cases:  [Stock market and other financial
forecasting](http://www.svms.org/regression/TrIn00.pdf) (comparing relative
performance of stocks relative to others in the same sector), [time series
forecasting](http://www.svms.org/regression/Cao02.pdf), [automatic currency
control](http://www.svms.org/regression/SBSW.pdf).

Requirements: As mentioned, you don't want your data set too large. For
documents, one example showed the ability to generalize decreasing after 1,000
documents [slowly began to
decrease](https://stats.stackexchange.com/questions/47090/increasing-the-
sample-size-does-not-help-the-classification-performance). You also shouldn't
have overlapping classes.



## K-Nearest Neighbors

When it's regression, it estimates the value of a point based on the value of
nearby points instead of its classification based on nearby points. It's
[considered the simplest classification
algorithm](https://www.analyticsvidhya.com/blog/2014/10/introduction-k
-neighbours-algorithm-clustering/). Because of its simplicity, it's very fast
and the data is very easy to interpret, though its predictive power is more
average. But [be careful and scale your
data](https://mathbabe.org/2013/04/04/k-nearest-neighbors-dangerously-simple/)
so it's directly comparable, otherwise this algorithm can really lead you
astray.

Supervised or Unsupervised? | Supervised  
---|---  
Explainable or unexplainable? |
[Explainable](https://books.google.bg/books?id=EKNoKQ1L4CoC&pg=PA548&lpg=PA548&dq=is+Na%C3%AFve+Bayes+Classifier+Algorithm+explainable?&source=bl&ots=hJAd1VBrdp&sig=NA0sggSWCgZOJZYsSUU9DXcsyXo&hl=en&sa=X&ved=0ahUKEwj8_Nj_yvnTAhUFQJoKHYCtBMoQ6AEIRjAG#v=onepage&q=is%20Na%C3%AFve%20Bayes%20Classifier%20Algorithm%20explainable%3F&f=false)  
Generative or Discriminative? | Generative  
  
Used for: Estimating continuous variables by distance from each other.

Specific Use Cases: Predicting housing prices, loan amounts, and other
financial indicators.

Requirements: Can be done with &lt;100,000 samples, none of your independent
variables should have a lot of variance or interact with each other (they
should be relatively standard and distinct).



## Decision Trees

When the variable you're trying to predict is continuous (meaning it has an
infinite number of possible values, and not just, say, 1-100), a decision tree
regression works well. [It's also good if your data is
incomplete](https://www.dezyre.com/article/top-10-machine-learning-
algorithms/202), fast, and accurate.

Supervised or Unsupervised? | [Supervised](https://www.quora.com/What-are-the-
typical-use-cases-for-different-machine-learning-algorithms)  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: Quickly and accurately predicting values.

Specific Use Cases: Predicting the price of a consumer good

Requirements: Should be relatively small, the larger it gets the less accurate
and usable it gets. Relies on your expectations, which could be wrong. In this
way, these are very human and fallible versions of AI.



## Random Forests

Creates a series of decision trees with small random variations and calculates
each one. Then, it polls the results to come up with an overall prediction. So
it has all the same requirements as a regular decision tree algorithm because
it begins with the same type of data.

Supervised or Unsupervised? | [Supervised](https://www.quora.com/What-are-the-
typical-use-cases-for-different-machine-learning-algorithms)  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: weighing a number of variables to make predictions.

Specific Use Cases: Predicting income, crop yields, test scores, or home
prices.

Requirements: Super easy to use, lots of open source options,  overfitting
isn't really an issue here. Other than that, it has all the same advantages of
a regular decision tree



## Artificial Neural Networks

This is probably the most famous type of classification algorithm. It broadly
mimics the structure of the human brain by layering artificial neurons. Each
layer chooses a factor it determines to be important and uses it to make
choices to give better outputs. This structure makes ANNs very flexible.

Supervised or Unsupervised? | Can be either  
---|---  
Explainable or unexplainable? | Unexplainable  
Generative or Discriminative? | Can be either  
  
Used for: When you need a system to figure out how to estimate things and
don't care how the system does it.

Specific Use Cases: Predicting prices, crop yields, weather, test scores, and
much more.

Requirements: Considerable skill is required to build this type of network, it
needs thousands of cycles to train itself, it's difficult to troubleshoot when
issues arise. However, it is extremely powerful when it works.



# Clustering


Finally, this lesson will break down the two main clustering algorithms.

Remember, clustering algorithms are best when you don't just want to know what
categories data fits into, but how alike or similar they are to everything
else in that category. For example, you could give a clustering algorithm
stock data and ask it to create categories of stocks based on their
performance. Then, based on what clusters they fit into and where they end up
within those clusters, you could chose where you'd like to invest. This is
different from classification, which will only put a label on the data and
won't tell you anything about how different the data within a single category
is.

## K Means Clustering

[Better when you already know what clusters you want to divide your data into.
It's a very simple algorithm to classify numerical data into
clusters.](https://www.google.bg/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwiykqePivzTAhUO1mMKHauxBI4QFggrMAA&url=http%3A%2F%2Fplg.uwaterloo.ca%2F~holt%2Fpapers%2Ficsm05-wu.pdf&usg
=AFQjCNH9HDVrr3baaAJy2nALW-vPEhSlew&sig2=SBNgGZMkZZ6Ps3FAGkOn0Q)

Supervised or Unsupervised? | Unsupervised  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: Dividing data into clusters (where their spacial relationships are
important) instead of just classes (in which case you would use a classifier
algorithm).

Specific Use Cases: Some financial analysis, astronomy, agriculture,
[microprocessor design](https://www.quora.com/What-are-the-problems-for-
which-K-means-algorithm-can-be-a-solution), and geostatistics.

Requirements: You have to know how many clusters you want. The data has to be
numerical.



## Hierarchical Clustering

This clustering algorithm creates a hierarchical structure of clusters and
does not require you to pre-specify the number of clusters you want. It's
deterministic, meaning if the input remains the same, the output will always
remain the same. It's also slower to run than K-Means.

Supervised or Unsupervised? | Unsupervised  
---|---  
Explainable or unexplainable? | Explainable  
Generative or Discriminative? | Discriminative  
  
Used for: Creating ranked clusters.

Specific Use Cases: Search engine queries, image classification (but only part
of the process), and document classification

Requirements: Your data has to be numerical.

