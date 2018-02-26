---
layout: post
title: An Interesting new Project
---

# Background
I was digging through my robotics closet a few weeks ago, and I found this box. In it, there was a small white robot and a very long USB cable. I did some digging, and it turns out that this little robot is called a [Finch](https://www.finchrobot.com/), and it's specifically designed for computer science education. Now then, I thought, this would be a *great* way for people to learn how to program the *actual* competition robot. So now, my latest project is converting the standard Finch library into a simulation of the [RoboRIO](http://www.ni.com/en-us/support/model.roborio.html), and more specifically WPILib, used by FRC teams.

# How to do it?
WPILib is a massive, complex library that includes tools and support for sensors far outside of the Finch's capacity, so first I need to specify exactly which sensors and motor control systems I'm going to support. That should be easy, as all I have to do is compare the Finch's sensor suite with the WPILib supported suite. Once that is done, I will need to look at how WPILib controls the sensors I want to control, as I want to have this new library get as close as possible to the real thing.

# GitHub Link
As always, here is the GitHub link to the repository I have set up to hold all the source files.

[https://github.com/Dev-Osmium/FinchLib](https://github.com/Dev-Osmium/FinchLib)
