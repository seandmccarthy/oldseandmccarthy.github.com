---
layout: post
title: "Simplicity Matters: Railsconf Keynote by Rich Hickey"
date: 2012-06-12 20:03
comments: true
categories: [railsconf thoughtleader fp bookmarks]
---

Rich Hickey is the creator of [Clojure](http://clojure.org/).

I watched and really liked his keynote from Railsconf 2012 ([Video](http://www.confreaks.com/videos/860-railsconf2012-keynote-simplicity-matters), [PDF of Slides](https://raw.github.com/richhickey/slides/master/simplicitymatters.pdf)).

The key points to remember:

* Simple: meaning lack of interleaving
* Make challenges easy by _simplifying_ them (e.g. break down to known/understood concepts, reduce interleaving)
* We can be creating the exact same programs out of significantly simpler components

He used this table to show "simple" alternatives to complexity.

<table>
<tr><th>Complexity</th><th>Simplicity</th></tr>
<tr><td>State, Objects</td><td>Values</td></tr>
<tr><td>Methods</td><td>Functions, Namespaces</td></tr>
<tr><td>variables</td><td>Managed refs</td></tr>
<tr><td>Inheritance, switch, matching</td><td>Polymorphism a la carte</td></tr>
<tr><td>Syntax</td><td>Data</td></tr>
<tr><td>Imperative loops, fold</td><td>Set functions</td></tr>
<tr><td>Actors</td><td>Queues</td></tr>
<tr><td>ORM</td><td>Declarative data manipulation</td></tr>
<tr><td>Conditionals</td><td>Rules</td></tr>
<tr><td>Inconsistency</td><td>Consistency</td></tr>
</table>
  
  
Most of the concepts are covered in some way on the Clojure website. It's interesting to consider how concepts from functional programming might be integrated into imperative programming.

Note to self: If you haven't committed at least a small Clojure project to GitHub in the next 6 months, I'll be very disappointed.
