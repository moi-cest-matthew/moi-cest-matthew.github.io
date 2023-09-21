---
layout: essay
type: essay
title: "Coding For Matt: Standard Languages are Here, They Sneer, and We're Used to It"
date: 2023-09-20
published: true
labels:
  - Coding Standards
  - ESLint
  - Package formats
---

*The following text is licensed under a CC-BY-SA 4.0 Global License. You may share it freely, even for economical purposes, so long as you provide me credit and a link to the license.*

On March 27, 1977, a Dutch plane attempted taking off in Tenerife while and American one was still on the runway. The resulting collision, which killed 583 people (everyone except 61 survivors on the U.S. plane), is the deadliest in aviation history. One of the factors that lead to the tragedy was a series of failures in communication: the usage of ambiguous phrases such as "at takeoff" and "OK" (which may or may not mean actually having clearance to take off) and nobody bothering to clarify anything after the Dutch and American crews sending simultaneous radio messages caused interference. Nowadays, there is a list of standard phrases crews must use, all of which are in English.

My "Hello, World!" program should follow suit, whether I like it or not.

Obviously, it is extremely unlikely that you will kill hundreds of people all because of a curly brace having its own line or indenting an extra space, but it can still cause its own sets of problems. For instance, should unused variables be considered an error? On the one hand, they do not cause any contradiction in your code that can cause it to fail mid-execution. Having them flagged as errors can also be annoying when you just need to test some code that comes before the variable is used. On the other hand, this can absolutely save you from typos that would have taken an eternity to find, such as `bâ` being written as `b^a`.

With that said, I have spent more time trying to make my IDE and connection to GitHub work at all than being able to use ESLint, but from what little I have been able to get out of it, it seems very useful. There is already a button that can fix most errors for me, which saves me much time that is already too easy to lose. Frankly, having to choose the coding standard myself is a waste of time in and of itself; I could have spent that time pushing my code to GitHub or writing code. So, I am perfectly okay with using this thing in the future. It seems like it will provide me with some stability in my life.