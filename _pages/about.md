---
permalink: /
title: "William T. Hallahan"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a PhD student at Yale University, advised by Ruzica Piskac.  I currently work on a symbolic execution engine for lazy functional languages (in particular, Haskell.)  Given unannotated Haskell source code, we aim to determine either inputs that lead down all possible paths in the program, or input that will produce output satisfying a given predicate.  This requires generation of constraints, expressed in first order logic, on the Haskell program's output, which can be solved by an SMT solver.
