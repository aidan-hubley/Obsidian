#EthicalHacking
-- Hacking Someone Else's Computer --

# AWS - Kick off

# Why Cloud Computing
- Pay for what you need
- Better availability
- They do the stuff you don't want to do
	- Patch
	- Backup
	- Redundancy
	- Physical
	- Firewall


# Virtual Machine vs. Computer
- VMs have a hypervisor to oversee OSs 
- Containers have container engine and 1 OS

# Linux Container (LXC) versus Docker
- Docker is a containerized environment to run a simple application
- Linux Container is an environment to run an OS

## Key Differences
- LXC
	- filesystem neutral
	- containers are like VMs with a fully functional OS
	- Data can be saved in a counter or outside
	- Build loosely coupled . . .


# Kubernetes
- Tool to manage large number of containers
- Docker is for the deployment of applications in standalone containers
- Kubernetes is for the running og those containers
- Kubernetes and Docker Work Together


# OWASP Top 10 For Cloud
1. Cloud, Computer, and Orchestration Not Secure
	- Publicly Open Cloud Storage Buckets
	- Improper permissions set on cloud storage buckets
	- Container runs as root
	- Container shares resources with the host (Network interface, etc.)
	- Insecure Infrastructure-as-Code (IaC) configuration
2. Injection Flaws
	- SQL Inject Commands
	- OS Command Injection
	- Serverless Event Data Injection
3. Cloud, Container, and Orchestration Not Secure
	- Unauthenticated API access on a microservice
	- Over-permissive cloud IAM role
	- Lack of orchestrator node trust rules (e.g. unauthorized hosts joining the cluster)
	- Unauthenticated orchestrator console access
4. CI/CD Pipeline & Supply Chain Access
	- Insufficient Authentication on CI/CD Pipeline Systems
	- Use of untrusted images
	- Use of stale images
	- Insecure communication channels to registries
	- Overly-permissive registry access
5. 