---
title: "FDA vs FNA"
date: 2021-03-25T06:00:20+06:00
menu:
  sidebar:
    name: FDA vs FNA
    identifier: fdafna
    parent: school
    weight: 10
---
### FDA or FNA?
We can ask ourselves:
#### What is the difference between a FDA and a FNA?

From the class notes, we can see that the power of an automaton is mesured in the hability of accepting a language.

### In fact:
For every FNA N, we can construct a FDA that accepts the same language, i.e:

## L(N) = L(M)


### But why do both AFD and AFN exist if we can represent the acceptance of a language in both ways? 

1. Well, one of the main reasons is that a FNA is more easy to construct and to understand, but the problem that this type of finite automata can't be implemented in real 

2. Converting an FNA N with k states to an FDA M requires in some instances exponential growth (2 ^ k) in the number of states.

But knowing the existence of these type of automata is very important to really understand how a computer model works