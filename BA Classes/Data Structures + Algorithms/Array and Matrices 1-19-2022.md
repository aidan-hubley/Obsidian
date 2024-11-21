# Array
1. One Dimensional
2. Two-Dimensional
3. N-Dimensional
4. General form of a one-dimensional array declaration
## Specify the type and number of elements
1. int intArray[]; - declaring array
2. intArray = new int[20]; - allocating memory to array
OR
4. int[] intArray = new int[20] - combining both statements in one
## Matrix representation
Arr[0][0] Arr[0][1] Arr[0][2]
Arr[1][0]  Arr[1][1] Arr[1][2]
Arr[2][0] Arr[2][1] Arr[2][2]
## Diagonal Matrices
1. Diagonal matrices are those with 0 elements everywhere but along the diagonal
## Upper Triangle Matrices
1. Just a diagonal matrices, but includes everything 'above' the diagonal
2. Put differently, any value below the diagonal is 0
	1. To check, find any place where i > j (i being the rows, and j the columns)
## Convert Upper Triangular Matrices to 1D Array
1. Two Options:
	1. Row-wise:
		1. Read left to right, row to row.	
	2. Column-wise:
		1. Read top down, column to column
## Strict Upper Triangular Matrices
1. Same as normal Upper Triangular Matrices
2. Does not include the diagonal