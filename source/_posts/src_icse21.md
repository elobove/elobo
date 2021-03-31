---
title: Let's not make a fuzz about it (extended abstract)
date: 2021-05-25 10:00:00
tags:
venue: SRC@ICSE
---

> 43rd International Conference on Software Engineering
> (Student Research Competition)

# Abstract

The work of Fuzz has pioneered the use of functional programming languages where types allow to reason about the sensitivity of programs. Fuzz and subsequent work (e.g., DFuzz and Duet) use technical devices like linear types, modal types, and partial evaluation. These features usually require the design of a new programming language from scratch---a major task on its own! While these features are part of the classical toolbox of programming languages, they are often rather obscure for non-programming language experts. In this work, we explore a different direction. We propose the design of a library capable of calculating the sensitivity of programs. The library is built on a novel use of polymorphism to represent (and prove) the sensitivity of functions and the use of type constraints and type-level natural numbers. We show how our approach can be used to reason about the sensitivity of classical examples working over vectors, such as sum, map, and sort -- we leave reasoning about more complex programs for future work. Our library, called DSencity, is implemented with just 360 lines of Haskell code.

[PDF](src_icse21.pdf)
