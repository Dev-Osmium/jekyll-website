---
layout: page
title: AdHub Bot Docs
---

# Background
AdHub is a server where anyone can advertise their discord server for free. Only problem is, the old system required you to fill out a Google Form which logged your Google account for any reviewer to see. So I was called upon to make an application bot that would handle all partner applications for the server without logging personal things like emails and names.

# Commands
There's only one command accessible to normal users who aren't me, and that's /apply. This is where the bulk of the bot's work comes from. Takes in two arguments, the last few characters in a discord invite link, and a direct link to the server icon in this format:
{% highlight java %}
/apply <SERVER INVITE CODE> <IMAGE LINK>
{% endhighlight %}

# GitHub
As always, here's the GitHub link to the project.
[https://github.com/AdHubBotDevelopers/Adhub_Main_Bot](https://github.com/AdHubBotDevelopers/Adhub_Main_Bot)
