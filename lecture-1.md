# Lecture 1

http://www-bcf.usc.edu/~adamchik/570/


adjacency list/matrix



1. statement
2. present the solution
3. prove correctness
4. perform complexity analysis

---
### E.g. stable matching
Problem: _n_ men and _n_ women. they can stay happily married ever after.

**Step1**
M = { ... }
W = { ... }

**perfect matching**
men rank women 1-n
women rank men 1-n

preference list

**complete step1**
intput
output: no instability

**step2**
_Gale Shapley algorithm_

**step3**
1. from the woman's perspective. she states single, and once she gets engaged she can only get into better engagements
2. from men get engaged, and might be dropped. only to setle for a women with lower ranking.
3. does stop after n^2 iterations
4. perfect matching