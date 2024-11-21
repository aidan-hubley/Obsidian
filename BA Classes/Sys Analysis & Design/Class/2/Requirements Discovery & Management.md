Netherlands
# Process Modeling (Notations)
A structure for organizing information that defines the scope of the architecture and how the areas of the architecture relate to each other .

There are several great starting points
1.  IDEF0
2.  Data Flow Diagrams
3.  Flowchart (Microsoft defacto standard)
4.  Event Driven Process Chain
5.  UML (Activity, Sequence, Use Case)
6.  BPMN
7.  (really there is no shortage)

## IDEFO
Highly intuitive Grid where the intersections form around the Ontological Questions (Who, What, When, Where, Why & How) and the Level of detail.
Cons - Unclear on how to connect the 36 different attributes (could become very disjointed)
**![](https://lh5.googleusercontent.com/LPNdM0Nw4rP2HbioD7b8yBTdmVznYHKrU-xUyY1Col8_icByOPAXYCmhT17riKsJktaPzh1G_SeXd0RXUUZirrXMbL1P9FfAiU54MGdM0PqxgWiwYTMYvZh9YV-1BdIN5YVa0ShjYZ7WurgA4EJdo9nkFKyUBs3WKKnWMRhEBBXgIHtOh2LAB21Ty4mlGI0=s2048)**
**![](https://lh3.googleusercontent.com/iCIlvrzEtriqTkK4yC02QXEct-z-HRK0gtg5IKaDSFWISdgqWdno-58lgEFgpDz579fo39vMdvxStEfso2A1GTOF2iIKpAj5Qxyub7ZloEDIiaiiSPCRxy5O__DnEGtVPNZlzRIWTcEbACDHTXU3A0j-G4zADd0Sohx0TqaewV2naoqAgJRjYciNf8ozFUA=s2048)**

## Data Flow Diagram (DFD)
- Process
	- a Number /ID
	-   Name (Verb-Noun) + Description
	-   Description
	-   Input and Output
-   Data Flow
	-   Name (noun) + Description
-   Data Store
	-   ID
	-   Name (noun) + Description
	-   Incoming or outgoing flow
-   External Entity
	-   Name + Description
**![](https://lh4.googleusercontent.com/Yp7k0x8-FeM7ReYVNdvbHZWkZpPRbixg5g7c_tpFF3ooAok9LlasBOHCfqQ9PpK09VPcUOUeZRbJGXlq3Msk_zo0R_zd3w2NA4B1h8CpV8HaClNaxKwsRCfb03uRdUA4CxHybNWVqJasSxP3FBbRfE2FpKPEvq7vNOZXHciBYfblRxMPWq2gbEuure2yrsA=s2048)**

## Defacto 
-   Process (Box)
	-   Different types (Manual vs Predefined)
-   Line
	-   Name (noun) + Description
-   Diamond
	-   Decisions
-   Document
	-   Name + Description
-   Data Store
	-   System or Database
**![](https://lh3.googleusercontent.com/i1bE9lNiYFYqPK8iE0M-m3eJpNZXplJHJ8sKUQdy1OwLrqU0L_ggOZdVL_mf1j8GHr16WJnxlPs_sL171-gkgudsmJGlpNhiHSj-u7Z82WnHF4mzSfMHFuKBkbrF5O_RtIA5SiWeugVzj4InkR-zArBt0rV-QVUcJBkKBU1PuMJRARXZu_Y9p4NQCZB9Gos=s2048)**

## Event-Process Chains
-   Event (Hexagon)
	-   Noun-Verb
-   Process (Box)
	-   Verb-Noun
-   Line
	-   Sequence or Influence
-   Diamond
	-   Branch / Merge
-   Others
	-   Document 
	-   System or Module
	-   Organization
**![](https://lh6.googleusercontent.com/ta9i3TwdzF6aXf2YwOdaECk0By02DEW1F4zNDyPhTc_waXYlY61EF6P3jY2w9U-fszE0bPTqB3sKx9josd3OzrHWFDybNojuii5Oyw8MI0GbHm6dXOp_wQ9OZiv2QyMaHPUZwo_23P33BoW8Ah6EWlYNkaPakHaj_lav9Hj4_QIJkQ7xNVLMZraIFLYoClw=s2048)**
ENFORCED ROUTING RULES (and, or, xor)

Heavily used in SAP or ERP implementations where system is reliant on triggering events.

# Unified Modeling Language
### Activity
Very similar to the Event-Chain Diagram but can handle multiple scenarios
**![](https://lh3.googleusercontent.com/dVfhb9QSDMEOGZxTHkkOPiu2w26O0dKHOPCI7DJ1ZsMWmHJ2hUecKwj_V93P2qqPfqgcpO5p3fu6iPs95wpJ3Ksidp6UaoSccXiCdIvOIbn3RMcsirMudXIkheV-3257QKwlh4WOjjj3GOgT1y941CgM3L-FHrzlHyw7pgMl6ukax1XW6znJpuHT6u_fVSo=s2048)**
### Sequence
Very helpful when describing tiers in an application logic (I use these for system integration or API interactions)
**![](https://lh3.googleusercontent.com/Zz-TvLS5G_0wO-ml7zD5WN1a4pLkf6Z3XYy_rQnRMCErb2yL81mElXNWjpP18RaN_FFVPr5UuesfMOEcjiT8kaJEwoGBAv31Pow9YrtBnff-5gOKHkCPCvMouurQW0DDylLiL1OPNPseeLpbU31ojkc_OzdyrKNkDsUOoKqfCY-jIGG_DjzSMQk9WNbdw8M=s2048)**
### Use Case
Very simple depiction of who can perform which function and relationships between functions... notice how they extend use cases to denote an alternative processes
![[Pasted image 20230124085240.png]]


Model-driven architectures
Consistent Meta-model for System Engineering for 13 Visualizations


## Business Process Modeling Notation
- Events
- Activates
- Gateways
- Swimlanes
**![](https://lh3.googleusercontent.com/wa_l-uYma3TvgK00H-tBi58VljGcRP-bsIU1suf487eRxrwYuqo4vRoUNYz7KSITXYI9k94oBh0xTSknoXraBPGVZta6FVb25RLb7KqmY6--S1Z8xOuKFVIssLzWwFAzj5mqxcCi-mVSEckjOMCSH1HAHkIr83SecJst4AHsEqwGZh3jJYyzNKjfJsoVGjE=s2048)**

My personal favorite - BPMN.  I think that it does a great job blending model integrity (clear requirements) with something that an end-user or stakeholder can relate to.  

I highly recommend looking at some of the work by Michael zurMulen on BPMN Primatives.  It helps to remove ambiguity in documentation.

## Context: Value Chain
**![](https://lh6.googleusercontent.com/xphNZG7LgI3Y1IFEPlFZEIWyFket9wkG-TLfCnAOMOelFZoZoF8sJ5FwyLKwW2wHjWpY-YJ-H7SVOivSxGkQtgZFMSN6o4tywO-5LZY59KMioy5LNVuRRsCvbjcuPOv114f0BDdCt85KMQRsJOE5tnPQxMNB5QsZkZY2i5BsVEWTSebj7gvTTQ6Wgxfn-qs=s2048)****![](https://lh5.googleusercontent.com/UVy5k_LiYFb5nlpC3QNVgA6GPnG55r4MNpQeARIo5WSbeFc59IG0b0Q543IfqU-uY2_hboIZlvSA-5cSoxjDAa9LQ9JfK_K3TsA8gF6dOlDu36IHAc0N9pljCW29x3E-HXO91w5cngDkP262fnd8aOqjSE9CKoiehE_5AC--lf5atO7V15L-VE65hWccXTg=s2048)
After discussing the simple context of Program Data, and it’s role in sending their grandmother a letter to request funds, we will invite them

# Current Process
![[Pasted image 20230124085950.png]]
# Backup 2: Review Process
![[Pasted image 20230124090620.png]]


# Use Cases
How do use a use case?
very simple sentence: as a user role, I want to perform X task, so that I can achieve Y outcome

**![](https://lh5.googleusercontent.com/WOktZnexEOyE8e9qmw0uDUbnVk6efTzF0Mj7oUdG1k2YDwq-HRzukW4lsEX9CG8_wTJ8PyNAhVpdwtPLzanWPRTWaLbhyr6zGTJjRRpTeJfRl7LKLAtKrDm-KUBuRFTqCU47kdiJP25kaUd-BAhC958p-gfCuFOEGC5uyrj8gBSvnkxHIcrqR-zKgRHRfdM=s2048)**

# Prototype Screens & Validation
**![](https://lh6.googleusercontent.com/CAy7NVtaXiNPZF6KJ5lqVqCgsamTd_8T-IHf3bfoKacVlRhUMPX5TjoSp5ymh-dLnTnVMuWF_4PLVRGFSqvNWZceHEXLeDGvQQ2C1SgIi5ltZto2X7sXyV_knYgoE2L_Q53xtS5yiw4EEyCff1ZJRJdd9fSm3_k-K2F2wzdhjdFqwDdDZ3CuS5LQIO90Lqo=s2048)**



The best description of requirements **is working code.**

Then why document use cases?
**Communication**


# Reminder of Project Planning Benchmarks
Typical Business Apps Phases
- Planning 15%
- Analysis 20%
- Design%
- Implementation 30%
What is missing?
- Deployment
- Monitoring and Support


# Waterfall Project Planning
1. Outline a Work Breakdown Structure (WBS)
2. Assign Task Dependencies
	1. Predecessors
	2. Lag (e.g. Finish to Start + 3d)
3. Confirm Task Constraints/Characteristics
	1. Fix duration vs. Fixed work
	2. Fixed start or Fixed end vs. As soon as possible
4. Build your resource table (who, Role and $ $ $)
5. Assign Resources (Person * % of time)
6. Balance your plan (Review Resource Utilization)



# Types of Requirements
- **Business** - The business objective that the system needs to satisfy
- **User** - The actions that a user takes within the system
- **Functional** - The functions should the system perform
- **Non-functional** - The characteristics that the system should have
- **System** - Specifications about how the system should be built

## Samples
note: using no wiggle room words such as "must" is vital
Business
- B.1 The system **must** limit orders based on staff capacity, so that the delivery Service Level Agreement of within 10 of promised delivery is not placed in jeopardy. (Pointy Hair Boss)
User
- U.1 The user **must** associate their account with payment method (e.g., Falcon Dollars or Credit Card) (Hungry Student 1).
Functional
- F.1 The system **must** present an anticipated delivery time prior to allowing the user to confirm the order (Hangry Student 2).
Non-Functional
- N.1 The system **must** render pages in less than 10 seconds after any user action or application event. (UX Expert Lady) 
System
- S.1 The system **must** use Messiah College Single Sign On (SSO) solution for any accounts with a messiah.edu domain. (Policy IT01.02)

# Requirement Format
Must haves
- Unique identifiers
- Original source
- Shall, Must, Will vs. Should, May

Goal is clear communication, what works best?
- Context Diagram / Images
- Table
- Paragraphs or simple sentences