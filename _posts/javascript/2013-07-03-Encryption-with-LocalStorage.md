---
published: true
layout: post
category: info
tagline: Client side encryption with JavaScript and LocalStorage offline
tags: 
  - JavaScript
  - localStorage
  - encryption
  - security
  - offline
  - appCache
---

{% include JB/setup %}

I've been looking for an offline solution for an application that will hold sensitive data.  AppCache will provide the offlineability aspect, localStorage to hold the data that is to be stored locally, but how to ensure the data is safe (as it can be)?

I came across [this post on stackoverflow](http://stackoverflow.com/questions/10830934/html5-offline-mode-localstorage-and-security-are-on-a-boat "JavaScript Encryption solution").  Using the password as the key to encrypt/decrypt the data is a really simple and elegant solution.

I'll be checking out [SJCL](http://crypto.stanford.edu/sjcl/ "Stanford Javascript Crypto Library") for this.
