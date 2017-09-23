# clojure-goes-fast.com

This repository contains sources from
which [clojure-goes-fast.com](http://clojure-goes-fast.com/) website is created.
It is a static site generated by [Perun](https://github.com/hashobject/perun).

## Build

You need [Boot](boot-clj.com) to be installed. Then:

    boot live

will build the site and serve it on [localhost:3000](http://localhost:3000), and
will automatically regenerate it if any content changes.

To build the final version of the site do:

    boot build
