#DatabseSecurity [[Exploitation and Defense]]
- SQL Injection
	- Method used by intruders to break into databases
	- Intruders use bits of SQL code and SQL queries to gain database access
	- Creates vulnerabilities and can allow intruder to obtain full administrator privileges
- Three common strategies for SQL injections
	- Single channel
	- Multichannel
	- Observational
- Single Channel Attack
	- Intruder uses one channel to execute SQL injections and obtain the returned results
	- Example: entering SQL injections into a Web application
- Multichannel Attack
	- Intruder uses one avenue to initiate the injection 
		- Uses a different channel to obtain results
- Inferential injections
		- Intruder does not intend to receive data
			- Observes and learns from returned behavior

# Injections and the Network Environment
- Most SQL injections performed through a Web application
	- Application interfaces with back-end database
- Web applications are common today
	- Examples: e-mail access, auctions, shopping, banking, blogging, online gaming
	- Primary target for intruders
- General steps for retrieving and manipulating data using Web applications
	- User accesses the site
	- ....
- Dynamic SQL statement
	- SQL statement generated on the fly by an application using a string of characters from user input
	- Developers build applications that handle most of the SQL code in real time
- Static SQL statement
	- Statement built by the user in which full text is known at compilation

# Identifying Vulnerabilities 
- Primary step toward securing data
- Security actions fruitless without knowledge of system weaknesses
- Play the role of intruder to find vulnerabilities
- Several different types of attacks 
- Different areas of network can be attacked
- Different methods of deploying injections

# Inferential Testing for Locating SQL Injections
- Look for clues in behaviors returned from the database in response to a controlled attack
- Administrator must input parameters from the client side of the database environment
	- Observe database behaviors
	- Document abnormal responses
- Administrator must be familiar with application and Web browser behavior during normal data retrieval

# Using HTTP
- All network communication based on same basic principles
	- Client send request to obtain resource
	- Request is received and processed
	- Client's privilege is checked to determine allowable permissions
	- Once approved, requested resource packaged and sent from server to client
- Each step handled using standards or protocols
- Examples of protocols
	- TCP defines rules to ensure reliable virtual connection
	- HTTP defines formatting method for hypertext requests and responses
- When request made from Web application to database server:
	- HTTP initiates TCP connection as transfer agent 
	- ....
- ....