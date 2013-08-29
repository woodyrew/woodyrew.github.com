---
published: true
layout: post
category: info
tagline: Starting out with node.js
tags: 
  - JavaScript
  - node.js
---

{% include JB/setup %}

I've been starting to get into [node.js](http://nodejs.org/) recently, I love the idea of using JavaScript throughout the stack - Frontend and backend.

Here are the resources I found useful to get going:

- [Teach yourself node.Js in 10 steps](http://blog.ponyfoo.com/2013/07/12/teach-yourself-nodejs-in-10-steps)
- [Test Driven Development with node.js (and Grunt)](http://markdalgleish.com/2012/09/test-driven-node-js-development-with-grunt/)


Making a command line utility for git
-------------------------------------

We use git with the git-flow principle but git-flow doesn't fully fit our process so we have a wiki for running common tasks like creating a hotfix when there's already a hotfix in progress.

I wanted to write a git-flow-esq utility that would be easy for the rest of the team to amend etc.
I used [Writing a command Line utility with node.js (and Grunt)](http://flippinawesome.org/2013/07/29/writing-a-command-line-utility-using-node/) as a starting point for this.