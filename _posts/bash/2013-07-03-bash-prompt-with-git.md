---
published: false
layout: post
category: bash
tagline: Bash prompt with git info
tags: 
  - bash
  - git
---

{% include JB/setup %}

I was initally interested in just changing the colour of my prompt so I could highlight the machine I was logged into as I ssh into various machines.

I found a [Bash shell prompt configuration](http://www.cyberciti.biz/tips/howto-linux-unix-bash-shell-setup-prompt.html) how to and [Bash Prompt Colours](http://www.cyberciti.biz/faq/bash-shell-change-the-color-of-my-shell-prompt-under-linux-or-unix/) listings which let me work out the following:

	export PS1="\u@\[\e[37m\]\h\[\e[0m\]:\w\$ "
which gave me:
<span style="red">{username}</span>@{machineName}:{currentWorkingDirectory}$ 
