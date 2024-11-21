# Authentication vs. Authorization
- Two main steps in controlling access to data
	- Authentication Definition
		- Process of confirming the identity of individuals requesting access to a secure environment
		- Done by verifying the login and credentials match those created within the environment 
	- Authorization
- What is the difference between Authentication and Authorization?
	- Authentication - I am proving who I am  
		- Verifies who the user is
		- Works through passwords, one-time pins, biometric information, and other information provided or entered by the user
		- Is the first step of a good identify and access management process
		- Is visible to and partially changeable
	- Authorization - After I have proved who I am, you allow me to do something
		- Determines what resources the user can access
		- Works through settings that are implemented and maintained by the organization
		- Always takes place after authentication
		- Isn't visible to or changeable by the user

# Authentication
## Login
- Login
	- Object mapped to a user account within a database
	- Associated to a user by the security identifier (SID)
	- Required for authentication into the environment
	- Different from user account, which controls activities in the environment
- Default logins are created during database installation
	- Must be managed correctly

## Credentials
- Credential
	- Piece of information used to verify identity
- Examples of credentials
	- Person's username and password
	- Application's secure ID
	- Host's network name and address
- Types of credentials used to verify identity:
	- Depend on the authentication processes of a particular system or environment 

## Verification
- Authentication can be verified a few times and at different levels during a single logon attempt
- Third-party applications can add security to authentication process
	- They may use password encryption to keep network environment secure
- Three levels of authentication in a database environment
	- OS level, database level, third-party support

## Operating System
- Credentials authenticated primarily through the OS
	- Account must reside on operating system

## Database Authentication
- User must have a local database account to check credentials and gain access
- User may be required to access several systems before reaching the database
- Challenges
	- Users must keep different credentials for different systems
	- Difficulty often leads to weak passwords and poos password practices
	- Administration is more difficult with separate accounts

## Network or Third-Party
- Can be used for remote and physical environments
- Users not required to have an account on OS or database
	- Must have a network account recognized by the third-party application
- Types of external authentication
	- Smart card uses PIN for authentication
	- Kerberos uses symmetric-key cryptology
	- Public key infrastructure (PK)
	- Digital certificate
- Third-party or external authentication not recommended for use alone
	- Can be combined with OS and server authentication

## SQL Server 
- SQL Server authentication modes
	- Windows Authentication (default)
		- Users logging in to the database must have a windows login to access
	- Mixed Mode Authentication 
		- Allows both windows authentication....

## MySQL
- MySQL authentication information
	- Three pieces of information used for verify user's identity
		- Host name
		- MySQL username
		- Password

## Oracle
- Oracle authentication information
	- Oracle supports many authentication options
	- Database servers, database links, and environment passwords can all be used as credentials
	- Additional security applications are available
- Advanced Security
	- Comprehensive security application
	- Encrypts transmitted and stored information
	- Provides....

## Middleware
- Middleware applications
	- Designed to monitor external requests for database access
-  Database linking
	- Feature that enhances authentication support
	- Link between two databases resulting in one logical storage unit
	- Enables applying common policies

## Password Policies
- Most intrusions originate from a cracked or stolen password
- Password policy implementation
	- Organization's first defense against compromised passwords
	- Can be enforced within database server application
	- More effective than written policy
- Both written and server-defined policies should be used for maximum effectiveness

## Database-Enforced Password Policies
- Password policy options are often vendor specific
	- Most server applications share similar configuration settings
- Four password attributes can be enforced in almost every database server
	- Complexity...

## Written Password Policies
- Included in equipment usage agreement between and organization and its employees
	- Usage agreements must be flexible enough to be consistently enforced
	- Any strict enough to ensure users abide by the policy
- Common standards likely to be included in an equipment usage agreement
	- Password discretion / sharing

## SQL Server
- Available password policy methods
	- Password complexity, expiration, policy
	- Requirements

## MySQL
- Password policy
	- Admins must rely on operating system and third-party applications
	- Stored in 45-bit encryption in user table
	- Easiest to break in

## Oracle
- Password policy
	- Stored and encrypted...


# Authorization
- Process of applying permissions to a user
	- Ensures users requesting access have permissions to do so
- Determined prior to a user obtaining authentication credentials
- Choosing the most appropriate privileges for each user helps maintain a healthy and secure database

## User Account Management 
- User management tasks
	- Add, remove, and assign privileges to users
- Administrator must understand:
	- Default user accounts and privileges created during installation of database management system

## Default User Accounts
- Default user accounts are created with predefined user access
	- True for virtually every type of database
- Most default users are the system or admin accounts
- Default passwords, usernames, rights and privileges can easily be found online
- Need to secure the default accounts to protect data

### SQL Server - MySQL - Oracle
- On Canvas

## Adding and Removing Users
- Always change default password of a new user
	- Or force password change prior to server entry
- Save user password in an encrypted file
- Enforce strong password policies
- Use different logins and passwords for different applications
- Ensure users read and agree to database usage policies
- Before removing user, perform inventory of user's created objects
- Recommended to disable a user account instead of deleting it
	- Always document removals of database user accounts
- Documentation
	- Most important component of adding or deleting accounts

## User Privileges
- Privilege
	- Smallest unit of authorization
	- Ability to access a specific resource to perform a specific action
- Examples of privileges
	- Deleting a row
	- Creating a table
	- Executing a procedure 
- Privileges should be planned out in early stages of database planning
- Principle of least privilege
	- Security standard 
	- Each user given minimum set of privileges needed to conduct legitimate business within the system
- Managing user privileges
	- Granting a privilege
	- Denying a privilege
	- Revoking a privilege
- Two ways to grant a privilege
	- Fixed and single statement

### SQL Server - MySQL - Oracle
- On Canvas

## Roles
- Related privileges can be combined to create a role 
	- Used to centrally manage group of objects or users
- Roles can be created for users, objects, and applications
	- Single role can be assigned to many users
	- Single user can be assigned many roles
- Advantages of using roles
	- Saves time and resources
	- Provides a central location for administration

### SQL Server
- Roles defined at either server or database level
- Server roles
	- Grant rights to manipulate the server environment
	- Rights granted to login accounts
- Database roles
	- Grant access to database objects
	- Rights granted to user accounts
- Five types of available roles
	- Fixed server
		- Provide server-level privileges
		- Cannot be changed or deleted
		- Users can be added to them
	- Fixed database
		- Fixed database roles
		- Provides privileges specific to the database
		- Cannot be altered, yet users can be added
	- User-defined
		- Built to control access of objects within the database
	- Application
		- Created to support security requirements of applications
	- Public
		- Special role in which every database user is a member
		- Members cannot be removed
		- Provides a way to assign privilege for all user
- Version 5.7
	- Roles are not included in MySQL Server alone (v.5.7)
	- Roles may be created using scripting and third-party application
- Version 8.0
	- A named collection of privileges
	- Can be granted and revoked 
	- Mandatory Roles - granted to all users

### Oracle
- Defining roles in Oracle 
	- Several roles are built-in
	- Roles provide privileges at system and object levels
	- Roles can be granted to other roles
	- 33 roles exist for the Oracle database alone


# Threat
## Inference
- Method for **unauthorized** users to obtain sensitive information
	- Making assumptions based on database's reactions or query responses
- Unauthorized users can draw conclusions about the database
	- Enables knowledge or understanding of the data
	- Users may be internal or external
- Inference is a great security threat
	- Difficult to predict, detect, and eliminate

### Examples
- Two primary means of inference
	- Using logic
	- Using statistics
- Logic, relationship, and constraint interference
	- Well organized, logical tables are vulnerable to inference
- Example of logical
	- Hotel database table includes customer ID, last name, first name, and profile level  
	- Customer ID is primary key
	- Security rule or constraint ensures only hotel managers can view information about high profile guests’ rooms 
	- Desk clerk cannot see room 4001 in the table
	- Desk clerk tries to book but cannot  
	- Can infer room 4001 is occupied by a high profile guest
- Statistical inference
	- Statistical queries analyze the data but do not return actual data 
	- Can be easily manipulated to retrieve sensitive information
- Example of statistical inference
	- Database user queries average of her salary and a co-worker’s
	- Uses basic arithmetic to determine co-worker’s salary

## Minimizing Inference
- Techniques to limit a person's ability to infer
	- Polyinstantiation
	- Low, monitor, and alter of events
	- Limit user capability
	- Limit query responses

### Polyinstantiation
- Disruptive to database environment
- Strategy that allows database to contain multiple instances of a record
- Creates "fake" records
- Downside: confusing false records with real ones

### Other Methods
-   Log, monitor, and alert of events  
	- Monitor activities  
	- Set baseline and threshold alert for unusual user activity
	- Capture and analyze database activity logs  
- Limit user capability
	- Limit user’s query size 
	- Allow only aggregate operators  
- Limit query responses  
	- Return classes and ranges instead of exact numbers