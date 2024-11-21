Davao (City in Philippines)
Singapore

# What is Software Architecture
- A sufficiently detailed design plan / blueprint (often expressed in working code / prototype / demo) for an end-to-end software / technology solution to a business problem that contains some ultimate human benefit / impact
- Architecture is not detailed drawing around every requirements, but it requires that we consider if an architecture can theoretically solve a set of related, current, and future requirements.

## Four Roles of the Software Architect
- Design Expert
	- Command of all relevant phases of sys analysis
- Domain Expert
	- Deep understanding of business, market, and users
- Technology Expert
	- Practical experience with relevant platforms & products
- Methodology Expert
	- Best practice knowledge of how to get things done

## What goes into a Software Architecture?
- Business Strategy
- Human Constraints
- IT Strategy
- Quality / Reliability / Scalability Attributes
- Design

### Business Strategy
-   What kind of business are we building / serving?
-   Who are the users we’re serving and why?
-   How are we going to measure this system’s value?
-   What does the resourcing model for this system look like at scale?
-   What are the time constraints in bringing a solution “to market?”
-   What are the alternatives (business & technical)?
-   Are there other business factors/realities that provide a material constraint to IT strategy or or design?
-   What are the potential consequences to a reliability issue with this system in production or at scale?

### Human Constraints
- What’s the change impact of this system? Will it be disruptive to existing people/systems/processes?
- What’s the relationship to change in the corporate culture?
- What is the human cross-section of intended users?
- What personnel are available to build and implement this system? What personnel are available to maintain it?
- Management
	- In a larger company, where is the executive sponsor of this project and what do they care about?
	- In a smaller company, who owns the budget / decision-making for this project/system?

### Quality / Reliability / Scalability
-   What are the presumed / known reliability requirements of this system and why?
-   How maintainable are the architectural elements (given a best-practice small, empowered teams building and maintaining each element(s))?
-   How would growth in the usage of this system affect its topographical map? Where are the potential bottlenecks  
-   What’s the observability strategy for this architecture in a deployed environment?

### Design
- Data Storage
- Data access logic
- Application/business logic
- Presentation logic


# Architectural Patterns
- Discussion of several common models

## Peer-to-peer
- An architecture that distributes control equally to all nodes
	- Decentralized execution and communication
	- Limited atomic redundancy
	- Requires deep consideration of a continuous release as well as observability strategy
**![](https://lh3.googleusercontent.com/zOBsfbihozb33H_lyUN3vNomNgMTkOdqQILoeV81gzhGkzAu6nUe2oGKiQpIVjLu8tB3IWVa7vTSH3hKvdxWnQwOUHSoB-j0BaFY8k-C8JRerlbvefCaV5RzWNsBwFE_raN2HfMlq67KIDVi6gD8tvmZ=s2048)**

## Git
**![](https://lh6.googleusercontent.com/cfDD7Ul_rQ9XJGnCtS2CAYXoUNRAfPVT1dKlbI-Sorx3asc4AFdth2Uk4RPxR6fJjIiHVLhLBlSeOitizpfNSgxwOn574td0TikwmyE29if-2HHqtS4DHjX-ALoxNDydB1pb8kJP2UswzCPIKdu9Y8Yd=s2048)**

## Blockchain
**![](https://lh5.googleusercontent.com/ItO8GRys0RuubvqpOPzCl4WVpmip-7ZNOea8tmbQH91n8GKKYogfWD7fPnPj288ULOjH5YIYRXgpo7fxOvBolcoFl6JbIThmMYNaAeXwpuLalCphZJ_UV2sTmLFPAhH1s8KpI3mUzIQbvAvLjhK2peI8=s2048)**

## Client-server
- **Any architecture that centralizes control in a “single” source
	- +Clarity of data authority
	- +Centralized control and (often) release mgmt.
	- -State / session mgmt. challenges
	- -Scaling / reliability challenges**

## HospitalRun
**![](https://lh6.googleusercontent.com/gC9bLxi_CJGdGM3ke7eAMKbMXXzUpYKvr2xNLu0lz1XH1NjCf3Etu95RXJ3IUm8ZKNJWUZi0YbxdUmPOCCvqrAGvt1swcAraJkQETklk9yb8YRQKyNpm114n2FVqOK8ICXv3ZXHZ6DehtFe5uuCfyLDw=s2048)**

## MVC
- An architecture that separates modeling information (data definition) from UI/UX (data interaction) from business logic (data rules)
	- +Tightly coupled design
	- +Easy-to-adopt
	- +Logical separations for functional mgmt.
	- -Difficult to support multiple, similar views on same model
**![](https://lh3.googleusercontent.com/o7fVcIczDzafiYwHUMhfqk1U4fA0j25yK7RdmJRroVb7mj8_zxASsP65MPoqKYPCrlQBgHh8wMLm7eo7ynSoQ3Cnme8K1BUblu7iMlaitxTtd8D7cTTrucTu0uQX42WIGj_uzBlvrS5-u9Of50fCB5RA=s2048)**

## Rails architecture
**![](https://lh4.googleusercontent.com/puLdtTPO0u23gQ__KskyxJhw_0xX2RkaJEr-ceP3SW1o0tsoLzUJunkXzjgZOrIsY0FGGyBmQWGzy5R9CA6Zdn3Oz7NY4vCDcvyjmG6pAi083O4irj1FNfbj2F70v_YKX9xccM-2sK7_4qjKpErnMGg7=s2048)**

## Layer
- An architecture that relies of sets of independent/loosely-coupled interfaces to service a set of business requirements
	- +Insular architectural components allow more autonomous enhancement
	- +Allows independent technology choices per layer
	- -Requires dependency  mgmt. and advanced observability
**![](https://lh3.googleusercontent.com/kIwKsNPDQEJ7IHQkO9I9usK6KLVDDi9Sr267GAJP81Xqj0Vcvi75rPSTkh_7h-_f_Q6n98GZUlP7_4ffjyy3Gg5G3bhg0cWGHzLpYdpFRkBSDZmpbiYD_7zOeR3PxyTQ4wPzzR3CGjfzjVT2BHuQtZWO=s2048)**

## Network Architecture
**![](https://lh5.googleusercontent.com/keGTKmv3ARlKYLWEbN5Xeqt-q-EXnNssWoi8Vjas4cXF-FSO389p_GB2IVBmC8rlXcP7KtBQB3E_oMiFxWQLBVHOMs-PLwGKYyIKKhGriAWt3tLXww2FUtQ5M9unIbgtRo8Rp8iIerfSgglcmXRboPFI=s2048)**

## GraphQL
**![](https://lh3.googleusercontent.com/mEP5AvMeMhFSBxAl4_DTcOqEiTpDyai-fdCrUinRK77_EAMaolTvPJyOAI3ScmRMJf-Zcl9WnUYJyTBWo4RYX6IHuwzvQ6RFNQSzirtRjLXkPWaEUiOup1UKLrp-FPibuzx8FVyrJe8ol6NwfPO4zjQv=s2048)**

## Broker
- An architectural pattern that decouples services, components, or layers through a communication broker(s)
	- +Makes service distribution transparent to clients
	- +Supports dynamic CRUD of entities, nodes, and objects
	- -May introduce overhead / complexity for smaller projects
**![](https://lh4.googleusercontent.com/bOMbtFqu6_JhPpzCcz8MTBOmEobIdlfe-WmAnasbF_WkHIdERIgS8M63N5NH1mi4v8EnfbWvX8fKgkVybEV-HAbYGJf9vuaz26T-vm7kbWSzf9nUEx4A4lOGfT6-UDAbAVu87hHPP6nYNe2T9cZ2acK_=s2048)**

## Load balancer
**![](https://lh4.googleusercontent.com/7FiZ1s4Yzt-soYDwyXFeiWNr1IzmTdKCgg99NzLE2yNKV-SFicduUyvOdTH1Z2zKQH9oM1WNkqq0XwkKQC22v6H2CJCKeKHcRMwzZHJ95VojEseQijChOlNCbk7jSbeRmXpals8NLykc3iaYwklASr7e=s2048)**

## Broker
**![](https://lh6.googleusercontent.com/dgQ-ABbSfzbLLI_3AKl1d_UU6S89sZIiTluWOEXwntzJfAiXhEyF14C1j4ddaynRejBavGkbokwedAPqygT_pC-VK-D7IRCOAZ7-gA_kwBvAHOSSQjxTetd0ARcSlyFOSYVRvXwkEeHGpBD7_UGcOZaO=s2048)**

## Main-Helper
- An architecture that distributes and manages sets of tasks amongst a set of nodes
	- +Flexible slave implementation and scaling, assuming efficient recombination in the master
	- +/-Limited / no shared state between slaves
	- -Communication latency / instability is a concern
	- -Only viable for problems that can be decomposed
**![](https://lh6.googleusercontent.com/HHYSUiNM3qdBmy59VgrO4gEnZSnE2lA7O_z4w8s1A3MZp7V4DH2DTtu0If9frU4_rCkMHV0XxCrBgjtcbLPKWeq6PHhuDz8yXGLbbH70f7NGQqa2MfOdL5SJ9b12MsY8rffwjgXjdh1zPYZAwj0tnWSz=s2048)**

## CI Tools
**![](https://lh4.googleusercontent.com/Uy49e4pNezJqMjBQVk4Kei5_cSc7Lz7CLF4BzyXNjHfrf0i0XGIwKBHmGef5eFVtaAmdzmV2Y_Zz2u9aopiXBglPLRRVMcmvDvnQwBrWD72HjCZ53VS0sTwjDQQCbhx0m_smEZfRjjGa4Y4hoc3Z4XOr=s2048)**

## Blackboard
- A flexible architecture that leverages brokered communication and large data retention to create more surface area for complex problem spaces
	- +Primarily utilized for large multi-faceted data sets 
	- +Storage of both raw data and calculated solutions
	- +Presumes multi-component architecture and flexibility
	- -Structural mutation to foundational data can introduce complex change mgmt.
**![](https://lh3.googleusercontent.com/MKmjvMdEJ0wSkfxx2Vt8Yr61hrY-Tbq5Z2Vf4bOSYi7sYaigKs9QemDUmXF4D7sExklyd832Qx64Olps8UqbRmsHgkBOYmlEv689hso34FPGUU60iTVkQj6vR3VUuCZTJiLecG7o2TlV0qEpLY-F4sqm=s2048)**

## Microservice
- An architecture that leverages brokered communication to support independent changes and recombination an all layers of the architecture. 
- Note: best applied to well-understood problem spaces.
**![](https://lh3.googleusercontent.com/oPSSoiZ1Z7YS7BLzA0SOTt6XcBCidDJwdObXzZnjlU7HaPykeJorR3JvmTclEeWahKYJJzUogncIlcnvSZfZS9pWUmIBUmQVGjXZU3IQcki_GK_swI9V8Btr0282nImTzCweXLlRyOSbpRFk0BB_6OQH=s2048)**

### Twitter
**![](https://lh4.googleusercontent.com/vev6Opg9sVwyf4u2ZvM_ifH-RI7QhNVOMDLHv7kZEou7qIUEszdGHWPMo4mD1oqKE5clGcYEBIoBdmkDnSzvHhtEWClnqGj926q1W-HXtsuftEVkyHdw0U3O04HK5S9FrfyLB3gool5qAEOKR9zlu8Xq=s2048)**