# Recursion
1. **Recursion** is a programming technique in which a method can call itself to fulfill its purpose
2. A recursive definition is one which uses the word or concept being defined in the definition itself
3. In some situation a recursive definition can be an appropriate way to express a concept
4. Before applying recursion to programming, ti si best practice to thinking recursively
## Definitions
1. Consider the following list of numbers:
	1. 24, 88, 40, 37
2. Such list can be defined recursively
	1. A list is a :
		1. Number
	2. Or a :
		1. number comma LIST
	3. That is, a LIST can be a number, or a number followed by a comma followed by a LIST
	4. The concept of a LIST is used to define itself
## Infinite Recursion
1. All recursive definitions **Must have a non-recursive part**
	1. If they don't, there is no way to terminate the recursive path
2. A definition without a non-recursive part causes **infinite recursion**
	1. This problem is similar to an infinite loop - with the definition itself causing the infinite loop
## Recursion in Math
1. Mathematical formulas are often expressed recursively
2. N!, for any positive integer N, is defined to be the product of all integers between 1 and N inclusive
## Recursive Programming
1. A method in Java can invoke itself; if set up that way, it is called a recursive method
2. The code of a recursive method must handle both the base case and the recursive case
3. **Each call sets up a new execution environment, with new parameters and new local variables**
4. As always, when the method completes, control returns to the method that invoked it (which may be another instance of itself)
5. Consider the problem of computing the sum of all the integers between 1 and N, inclusive
	6. If N is 5, the sum is 
		1. 1 + 2 + 3 + 4 + 5
	7. The problem can be expressed recursively:
		1. The sum of 1 to N is N plus the sum of 1 to N - 1
		2. N + Sum of 1 to N - 1 (Ex: 5 + (1 + 2 + 3 + 4)) or (5 + (5 - 1) + 5 + (5 - 2) ...)
## Direct vs. Indirect Recursion
1. A method invoking itself is considered to be direct recursion
2. A method could invoke another method, which invokes another, etc ... until eventually the original method is invoked again
3. For example, method m1 could invoke m2, which invokes m3, which invokes m1 again
4. This is called indirect recursion