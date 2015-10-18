
# Om TodoMVC Example

> Om is a ClojureScript UI component library over React.

> _[Om - github.com/swannodette/om](http://github.com/swannodette/om)_


Run dev

~~~
lein repl
~~~

Step 0 - Starting dev on localhost:8081 using internal component

~~~
(require '[todomvc.core])
(todomvc.core/dev-start)
~~~

Step 1 - build cljs

![Step 1](https://raw.githubusercontent.com/griffio/griffio.github.io/master/public/clojure-build.png)

Step 2 - connect to browser repl

~~~
cljs.user=> (js/alert "Hello browser")
~~~

![Step 2](https://raw.githubusercontent.com/griffio/griffio.github.io/master/public/clojure-brepl.png)
