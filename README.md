## _react-native_ demo

[![Circle CI](https://circleci.com/gh/damienstanton/movies.svg?style=shield)](https://circleci.com/gh/damienstanton/movies)

This repository contains the completed source code for [the official React Native tutorial](https://facebook.github.io/react-native/docs/tutorial.html).

It's a toy movie-listing app that doesn't do anything other than fetch the top movies from Rotten Tomatoes.

#### Usage

Make sure Node and Xcode are reasonably up to date.

You should probably also be familiar with developing in ReactJS or one of its variants before playing with this.

In your terminal:

```shell
git clone https://github.com/damienstanton/movies && cd movies
npm install
open ireact.xcodeproj
```
Then, in Xcode:

`⌘R`

Observe that making changes to _index.ios.js_ and hitting `⌘R` results in live updating in the iOS simulator.

If you write in another language (something awesome, like [ClojureScript](https://github.com/clojure/clojurescript)) simply target your compiler at _index.ios.js_.

Shared under the `MIT LICENSE`
