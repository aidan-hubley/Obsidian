#EthicalHacking
# Insufficient Identity, Credential, Access and Key Management, Privileged Accounts
- Only the  responsibility of the Customer
- Amazon Data Bucket
	- Every object is a bucket entry
- Search Engines are combing through the buckets
- February 22, 2021 - Bob Diachenko Discovered a bucket with Covid-19 Peroneal Data
- One Bucket named Patient-Images contained 207,524 images of patients' photo ID scans:
	- Driver's Licenses
	- Medical Insurance Cards
	- Passports

# Insecure Interfaces and API's
- API Call 
- An Akami 2021 report documented "in the previous year, Akamai delivered more than 300 trillion API requests - A 53% year-over-year increase"
- Examples
	- unauthenticated endpoints
	- weak authentication
	- excessive permissions
	- standard security controls disabled
	- unpatched systems
	- logical design issues
	- disabled logging or monitoring

### John Deere
- Query for usernames without authentication for rate limiting
- Lookup customer data by a VIN - revealed private own info including name and address

### Peloton
- API allowed leakage of customer info
	- User ID
	- Location
	- Weight
	- Gender
	- Age
- Discovered by Researcher
- Company partially Fixed - But never responded to the researcher
- Researcher went to the press

### Experian
- Bill Demirkapi - Sophomore at RIT
- Shopping for student loans at a 3rd party vendor
- Found a credit score lookup, would credit score when fname lname address where entered
- Vendor made a call to Esperion API with only name, address and birthday
- API could be accessed without authentication

# Security Misconfigurations
- Common misconfigurations
	- Unsecured data storage elements or containers
	- Excessive Permissions
	- Default credentials and configuration settings
	- Standard security controls disabled
	- Unpatched systems
	- Logging or monitoring disabled
	- Unrestricted access to ports and services
	- Unsecured secrets management
	- Poorly configured or lack of configuration validation
- Automated Tools make it easier for these to sneak into the system
- Use automated scanning (or testing)

# Facebook Disappearance
- BGP router misconfiguration
- caused the withdrawal of route that contains the IP address of its DNS nameservers

# Microsoft Pitch Decks
- ~15 companies gave pitch decks to join Microsoft's CRM/ERP Ecosystems
- Azure Data Bucket was misconfigured to make them public
- Loss of Intellectual Property
- Shared responsibility model