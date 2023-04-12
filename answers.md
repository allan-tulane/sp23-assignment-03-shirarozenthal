# CMPS 2200 Assignment 3
## Answers

**Name:**___Shira_Rozenthal____


Place all written answers from `assignment-03.md` here for easier grading.


- **b.**

. W(n) = **O(n)** because the function iterates through the whole list element by element.
. S(n) = **O(n)** because the sequential process leaves no opportunity for parallelism. 



- **d.**

The function maps the parens_map function on every element in the list and then implements scan, so

.  W(n) = W(n/2) + n ∈ **O(n)**
.  S(n) = S(n/2) + 1 ∈ **O(log n)**


- **f.**

The merging step takes constant work, so

. W(n) = 2W(n/2) + 1 ∈ **O(n)** 
. S(n) = S(n/2) + 1 ∈ **O(log n)**
