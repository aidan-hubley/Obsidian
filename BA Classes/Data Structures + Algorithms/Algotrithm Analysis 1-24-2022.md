#DataStructAlgorithms
## Program to find GCD) Greatest Common Divisor)
1. Given two positive integers m and n, find their greatest common divisor, that is, the largest positive integer that evenly divides both m and n.
2. 1220 % __
3. Operation: **mod**
## Euclid's Algorithm
E1. [FInd remainder] Divide m by n and let r be the remainder
E2. [Is it Zero?] If r = 0, the algorithm terminates; n is the answer
E3. [Reduce] Set m <- n, n <- r, and go back to step E1

Example: Let m = 119, and n = 544
1. E1. r = m % n     r = 119
3. E2. Is r == 0, No
4. E3. m = 554, n = 119

Need an E0. [Ensure m >= n] If m < n, exchange m <-> n

## Guessing Game
1. How different algorithms for the same problem can have wildly different efficiencies
2. The computer is going to randomly select an integer from 1 to 15. You'// keep guessing numbers until you find the computer's number, and the computer will tell you each time if your guess was too high or too low:
3. 1 2 3 4 5 6 7 8 9 10 11 12 13 14 15
4. Once you've found the number, reflect on what techniques you use when deciding what number to guess next.
### Binary Search
1. Breaks down the total array/section into halves
2. For Number 1 - 15: Need no more than 4 guesses
3. For Number 1 - 300: Need no more than 9 guesses
4. Formula:
	1. Log\\/2 n
5. Example:
	1. Log\\/2 15 = 3.9068905961
## Problem Size
1. Define size of the problem
2. For a search algorithm, the size of the problem is the size of the search pool
3. For a sorting algorithm, the size of the program is the number of elements to be sorted
## Growth Functions
1. We must also decide what we are trying to efficiently optimize
2. CPU time is generally the focus
3. A growth function shows the relationship between the size of the problem (n) and the value optimized (time)
## Asymptotic Complexity
## BIG-OH Notation
1. The coefficients and the lower order terms become increasingly less relevant as time goes on
## Comparing Growth Functions
1. You might think that faster processors would make efficient algorithms less important
2. A faster CPU helps, but not relative to the dominant term
## Analyzing Loop Execution
1. First determine the order of the body of the loop, then multiply that by the number of times the loop will execute
2. 