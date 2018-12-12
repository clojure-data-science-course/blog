{:title "Software"
 :layout :page
 :page-index 3
 :navbar? true}

Here are some suggestions for the software tools that you may use in the course.

If you have any difficulty with the installation or usage -- then let us talk. It is better to solve this kind of problems at early stages.

## The minimum
You will at least need Git, Java (JDK version 8 or above) and Leiningen. You may use [the guide](https://practicalli.github.io/clojure/development-tools/) of Practical.li for installing them.

### Gorilla REPL
During the first talks, we will use [Gorilla REPL](http://gorilla-repl.org/), a notebook-like example originally written by [Jony Hudson](http://j-star.org/). It has its own visualization library and very interesting ideas regarding the creation of composable visual reports. It is rather common among Clojure data scientists.

We will also use it to share our work online.

You may use Gorilla through [lein-gorilla](https://clojars.org/org.clojars.benfb/lein-gorilla), which requires Leiningen. Just add `[org.clojars.benfb/lein-gorilla "0.5.3"]` under your `:plugins` section at your `project.clj` file.

Another option is [gorilla-repl-docker](https://github.com/lcir/gorilla-repl-docker), which requires Docker.

See some more details under the [gorilla-repl stream](https://clojurians.zulipchat.com/#narrow/stream/173759-gorilla-repl) at Zulip.

## Editors
At about the 4th meeting, when we start writing larger pieces of code, it will become important to use a proper code editor.

Practical.li has nice [installation guides](https://practicalli.github.io/clojure/development-tools/install-guides/) for several editors.

At our talks we will use Atom Editor.

### Other options

If you like the wonderful Emacs, then you can also use the [installation guide](https://www.braveclojure.com/basic-emacs/) at Higginbotham's book.

If you like Spacemacs, then you can also use the more [detailed guide](https://practicalli.github.io/spacemacs/) by Practical.li.

Another option is [Nightcode](https://sekao.net/nightcode/) - a minimalistic editor, dedicated to Clojure, which is rather easy to install.

## Trying Clojure online.

 For your practice, you may also use Clojure online.
 - [repl.it](https://repl.it/languages/clojure) - here you can try the language online.

