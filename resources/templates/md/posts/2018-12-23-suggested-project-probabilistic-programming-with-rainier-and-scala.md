{:title "Suggested Project: Probabilistic Programming With Rainier and Scala"
 :layout :post
 :tags  []
 :toc false}

This is one in a series of posts, where we suggest some personal projects, that you may take on during the course. Preferably, we will do the projects in small teams of 2-3 people.

For an overview of the various projects - please look [here](../../pages-output/projects).


### Background

[Probabilistic programming](https://en.wikipedia.org/wiki/Probabilistic_programming_language) is one of the promising and refreshing approaches to probabilistic modelling and to artificial intelligence nowadays. It will be one of the main themes in this course.

[Rainier](https://github.com/stripe/rainier) is a new probabilistic programming library written by Stripe. It is written in Scala - a language that runs on the JVM, and thus it is conveniently accessible from Clojure.

However, Rainier is based on some ideas which are not so commonly used in Clojure. One of them is the so-called Probability Monad. It would be an interesting question, how to make such ideas accessible in clojure, in a way that woulb be both simple and useful.

### The project

The purpose of this project is to experiment with accessing Rainier from Clojure, and possibly create a certain grammer for doing it comfortably.

#### Suggested tentative plan

1. Read a little bit about Rainier.
2. Learn how to access Scala in Clojure using the [from-scala](https://t6.github.io/from-scala/0.2.1/) library.
3. Translate some small Rainier examples to Clojure.
4. Consider possible ways to make the access more comfortable and idiomatic.
5. Prepare a talk about it.
6. Write a blog post.
7. Discuss with the community.

### Recommended resources

* [A Tour of Rainier's Core](https://github.com/stripe/rainier/blob/develop/docs/tour.md)

* [A recent technical talk by one of the authors, Avi Bryant](https://www.youtube.com/watch?v=I0n0WoAi5B4)

* A couple of [blog](https://darrenjw.wordpress.com/2018/06/10/bayesian-hierarchical-modelling-with-rainier/) [posts](https://darrenjw.wordpress.com/2018/06/01/monadic-probabilistic-programming-in-scala-with-rainier/) by Darren Wilkinson

* An [explanation](https://www.chrisstucchio.com/blog/2016/probability_the_monad.html) of the Probability Monad by Chris Stucchio

* Monads in Clojure
  * Using the [cats library](http://funcool.github.io/cats/latest/#monad)
  * Using the [Fluokitten library](https://fluokitten.uncomplicate.org/articles/functors_applicatives_monads_in_pictures.html) (should be read together with [this](https://web.archive.org/web/20180218211616/http://adit.io/posts/2013-04-17-functors,_applicatives,_and_monads_in_pictures.html) illustrated Haskell-based introduction to category theory notions)
