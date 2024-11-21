#DatabseConcepts
1. Will create a data model
	1. tables
	2. connections
	3. arrows
	4. many-to-one / one-to-many
2. Will create a relational data model
	1. example: A[A_PK(PK), . . . _B_FK]
	2. CONSTRAINT B_FK
3. SQL
	1. SELECT from *Table_name* Where *Condition* 
	2. INSERT Into *Table_name* (*Column1*, *Column2*, ....) Set (*Value1*, *Value2*, ....)
	3. DELETE From *Table_name* Where *Column* = "*Value*"
	4. UPDATE *Table_name* Set *Column* = "*Value*" Where *Condition*
4. True / False
	1. Given this diagram, there can be many __ rows for __
5. Essays
	1. Positive note: Given 6, chose 3
	2. Think about, what essay could he ask?
		1. What could possibly go wrong with a database
			1. Physical calamity 
			2. User error
		2. What is the difference between data administrator and database administrator
			1. Data admin deals with data in a table
			2. Database admin deals with the design of the database
6. Short answer
	1. Will include normalization, what normal form is this in
		1. Are there any columns that have multiple values
			1. If yes, its not in any normal form
			2. If no, it is at least 1st normal form
		2. If there is 1 key, at least 2nd normal form
		3. Can you determine any field that is not the key by any other field 