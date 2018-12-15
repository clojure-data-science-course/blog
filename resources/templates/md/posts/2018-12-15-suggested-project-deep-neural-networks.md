{:title "Suggested Project: Deep Neural Networks"
 :layout :post
 :tags  []
 :toc false}

This is one in a series of posts, where we suggest some personal projects, that you may take on during the course. Preferably, we will do the projects in small teams of 2-3 people.

For an overview of the various projects - please look [here](../../pages-output/projects).


### Background

[Deep Neural Networks](https://en.wikipedia.org/wiki/Deep_learning#Deep_neural_networks) is one of those fields where scientists and engineers try to create Artificial Intelligence by building something that is loosely analogous to living organisms.

Due to some recent advances -- both in computing power and in the underlying numerical and statistical methods -- it has been proved useful for a large variety of [applications](https://en.wikipedia.org/wiki/Deep_learning#Applications). It has become one of the popular paradigms among Machine Learning scientists, at least in those cases where one has a huge amount of data. 

In Clojure, there has been several libraries for Deep Neural Networks. Some of them are wrappers for external libraries (like [jutsu.ai](https://github.com/hswick/jutsu.ai) wrapping [DeepLearning4J](https://deeplearning4j.org/) and [Clojure-MXNet](https://github.com/gigasquid/clojure-mxnet) wrapping [Apache MXNet](https://mxnet.apache.org/)). Others are written from scratch (like [Cortex](https://github.com/originrose/cortex)).

### The project

On this project, you will study one of these libraries, extend its documentation by solving a problem, and possibly help improving it.

#### Suggested tentative plan


1. Choose one of the above mentioned libraries.
  - We recommend **Clojure-MXNet**, which is having some community momentum and is under active development.
  - Study the library: read the documentation, look into its code structure, read some examples, play with them, read some conversations of the community around it.
  
2. Choose some problem which is suitable for Deep Learning. 
  - It can be about NLP, Computer Vision, or many other areas. 
  - If you are new to this field, we suggest to choose something which is not too difficult -- possibly some textbook example, or a problem similar to other problems which have already been studied and documented.

3. Work on your problem, discuss it with the community.

4. Have you run across any special prolems during your work? If so, discusss them with the community, and try to help improving the situation.

5. Document your work, preferably in some form of literate programming (Gorilla-REPL / Jupyter / org-mode / ...).

6. Prepare a talk about your work.

7. Write a blog post about your experience and conclusions.

### Recommended resources

#### Reading

- The [blog](http://gigasquidsoftware.com/) of [Carin Meier](https://twitter.com/gigasquid) -- the main author of Clojure-MXNet.

#### Community

- The #mxnet channel in [The Clojurians Slack](https://clojurians.slack.com) is rather active.
