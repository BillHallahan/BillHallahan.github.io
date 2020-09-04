---
permalink: /
title: "William T. Hallahan"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD candidate at Yale University, advised by Ruzica Piskac, and working in .  I am interested in making programmer's lives easier, by allowing apply formal techniques to allow more quickly finding and fixing bugs and more easily writing code.  

Practically, much of my work to achieve this goal has focused on a symbolic execution engine for lazy functional languages (in particular, Haskell.)  Given unannotated Haskell source code, G2 is able to find inputs that lead down all possible paths (up to some recursion depth) in the program.  This can be used to find violations of programmer provided assertions, thus quickly finding bugs.  Or, it can be used to find values that fit a specific constraint, thus allowing Hakell programmers to solve there problems via constraint solving, with the constraints written as ordinary Haskell code.