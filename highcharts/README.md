# cljsjs/highcharts

[](dependency)
```clojure
[cljsjs/highcharts "4.2.6-1"] ;; latest release
```
[](/dependency)

Note that this no longer includes a dependency on jQuery.

This jar comes with `deps.cljs` as used by the [Foreign Libs][flibs] feature
of the Clojurescript compiler. After adding the above dependency to your project
you can require the packaged library like so:

```clojure
(ns application.core
  (:require cljsjs.highcharts))
```

[flibs]: https://github.com/clojure/clojurescript/wiki/Packaging-Foreign-Dependencies
