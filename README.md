# Attempt to use wasm with cljs

## Intro

This will be a small example on how to use web assembly with Clojurescript. I'll be using [game-of-life-3d](https://www.npmjs.com/package/game-of-life-3d) as example as I created it, and already used it with Typescript and Elm.

It was created following the steps on [ClojureScript with Webpack](https://clojurescript.org/guides/webpack). With some differences, and after validating the react dependency was working.

## Current state

Trying to start up the REPL with 

```clj -m cljs.main -co build.edn -v -c -r```

gives an error:

```No such namespace: game-of-life-3d, could not locate game_of_life_3d.cljs, game_of_life_3d.cljc, or JavaScript source providing "game-of-life-3d" (Please check that namespaces with dashes use underscores in the ClojureScript file name)```