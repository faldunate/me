---
layout: post
title: Problems of coexistence between jade and angular
date:   2015-05-22 12:00:00
categories: posts
---

A while ago I was working on a project made on Flask with Jade, and this worked great!, 
but after a while I integrated Angular Js, that's where all the trouble started, because Jade and Angular Js we use
double curly braces for variables, you can imagine the problem...

here, one of many solutions:

<pre>
  <code data-language="coffeescript">
    app = angular.module 'todayApp', [], ($interpolateProvider) ->
      $interpolateProvider.startSymbol '[['
      $interpolateProvider.endSymbol ']]'
  </code>
</pre>
