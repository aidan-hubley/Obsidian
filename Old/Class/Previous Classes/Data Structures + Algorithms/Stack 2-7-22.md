# Stack
1. A stack is a classic collection used to help solve many types of problems
2. A stack is a linear collection whose elements are added in a last in, first out (LIFO) manner
3. That is, the last element to be put on a stack is the fist one to be removed
4. Think of a stack of books, where you add and remove from the top, but can't reach into the middle
## Stack Operations
1. Some collections use particular terms for their operations
2. These are the classic stack operations
	1. **Push**
		1. Adds an element to the top of the stack
	2. **Pop**
		1. Removes an element from the top of the stack
	3. **Peek**
		1. Examines the element at the top of the stack
	4. **isEmpty**
		1. Determines if the stack is empty
	5. **Size**
		1. Determines the number of elements on the stack
## Postfix Expression
1. Let's see how a stack can be used to help us solve the problem of evaluating postfix expressions
2. A postfix expression is written with the operator following the two operands instead of between them:
	1. 15 8 - 
3. Is equivalent to the traditional (infix) expression
	1. 15 - 8
4. Postfix expressions eliminate the need for parentheses to specify the order of operations
5. The infix expression:
	1. (3 * 4 - (2 + 5)) * 4 / 2
6. Is equivalent to the postfix expression:
	1. 3 4 * 2 5 + - 4 * 2 /
