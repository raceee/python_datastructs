### Chapter Summary
* Know the complexity of storing or retrieving a value from a list or the memory of the computer
* know how memory is like a post office
* know how memory is NOT like a post office
* know how ot use the datetime module to get information about the time it takes to complete an operation in a program
* Know hoe to write an XML file that can be used by the polotting program to plot information about the performance of an algorithm or piece of code
* Understand the definition of big-Oh notation an how it establishes an upper bound on the performance of a piece of code
* understand why the list + operation is not as efficient as the append operation
* understand the differeence between $O(n)$ , $O(n^{2})$, and other computation complexities an why those differences are important to us as computer programmers
* Understand Theta notation an what an asymptotically tight bound says about an algorithm
* Understand Amortized complexity and how to apply it in some simple situations

### Review Questions
* How is a list like a bunch of post office boxes?
* How is accessing an element of a list NOT like retrieving the contents of a post office box?
* How can you compuite the amount of time it takes to ocmplete an operation in a comupter using Python?
* In terms of computational complexity, which is better, an algorithm that is $O(n^2)$ or an algorithm that is $O(2^n)$?
* Describe, in English, what it means for an algorithm to be $O(n^2)$.
* When doing a proof by induction, what twto parts are there to the proof?
* If you had an algorithm with a loop that executed $n$ steps the first time through then $n-2$ the second time, $n-4$ the next time, and kept repeating until the last time through the loop it executed 2 steps, what would be the complexity measure of this loop? Justify your answer with what you learned in this chapter.
* Assume you had a data set of size $n$ and two algorithms that processed that data set in the same way. Algorithm A toop 10 steps to process each item in the data set. Algorithm B processed each item in 100 steps. What would the complexity be of these two algorithms?
* Explain why the $append$ operation on a list is more efficient than the + operator.
* Deescribe an algorithm for finding a particular value in a list. Then give the computational complexity of this algorithm. You may make any assumptions you want, but you should state your assumptions along with your algorithm.