---
layout: post
title: Collatz-Out-Of-The-Way
---

* What did I do this past week?
  -Got the Collatz project for SWE and OOP out of the way, and practiced some interview questions from Cracking the Coding Interview.
* What's in your way?
  -Nothing at the moment is in my way. 
* What will I do next week?
  -Practice the classical guitar(nothing at all cs related just something I've been learning), and start on an android utility app that will function as a tuner and a metronome.
  
---

#The Feelz
----------
With the second week done and the first project out of the way I have to remind my self to stay diligent with regards to these classes because I know the work load will ramp up. The second week of class has yet to introduce anything new, but that doesn't meen someone should slack off durring these early class days. Downing's lecture still hold plenty of value to them, as they explain proper means of utilizing exceptions versus asserts in your projects. I walked out of class with further appreciation of the exception handlers in language, and how they allow the error trickle down to the level of the software where it can be handled. 

---

#Tip-of-the-Week
For you python users out there, I was introduced to an interesting python programming concept called decorators. I stumbled upon this functional programming concpet when I was looking at different ways to design a cache or utilize memoization on my function that computed the cycle length. What a decorator is, is a callable Python object that can be used to modify functions. The function is passed into the decorator as an argument and it returns the modified function. For my case, the decorator wrapped around my cycle length function and only called it when the computed value wasnt in the cache. This managed to keep the implementation elegant looking instead of muddy. 
https://technotroph.wordpress.com/2012/04/05/memoize-it-the-python-way/
http://simeonfranklin.com/blog/2012/jul/1/python-decorators-in-12-steps/
