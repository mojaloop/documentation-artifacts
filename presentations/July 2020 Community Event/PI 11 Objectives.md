# PI 11 Objectives (draft)

## Performance/POC
* Decide if Event-sourcing benefits are worth it
* Provide a plan to implement this in production, along with required  migration and boostrapping tooling
* Provide a visibility and monitoring tools (or their design)

## Settlement
* Settlement V2 Complete

## ISO 20022
* POC to investigate what it would take and impact to scheme (cross network & native support)
* Which standard of ISO 20022 to adopt
* Heart of Mojaloop whitepaper
* Do we need to recommend additional messages for discovery and agreement stage (/party /quote) to the ISO 20022 RA (PTPG) ?

## Streamline Testing & QA
* Documentation in the form of sequence diagrams correlate with tests/assertions for the core services
* Improvements in running regression tests (4 collections run up from 1); Streamline collections (API, Contract, etc)
* Improve test coverage (include new features) - 1.5k to 3k tests

## Portals for Onboarding
* Functional PoC to demo Technology Framework
* Approved Guidance on how to add config specific pages
* Approved Guidance on security and Auditing

## PISP
* End to end transfers flow at the switch
* Account linking flow at switch
* Scheme Adapter + Mojaloop Simulator implementation for E2E Transfers 
* Working MojaPay PISP Demo App** (thanks to interns)
* Fully implemented Auth service

## Fraud Management
* To drive the delivery of a fraud risk management solution to complement a Mojaloop platform implementation

## Extend Bulk Transfer
* Design a PoC for advanced Bulk Payment Use Cases such as Bulk Lookup, Bulk Quote & Transfers for multiple Payee FSPs and present to the CCB

## Le
rship & Community Management
* Restructure community governance committees: Community Leadership Comittee (CLC), Design Authority (DA), Change Control Board (CCB)
* Develop a new community membership model
* Review effectiveness of existing community workflows and revise where needed
ngage entrepreneurs and Fintech companies to identify their needs and develop measures to respond to them

## Onboarding
* Deploy and test new Dev Hub 

## PDP
1.	PI Objective #1: Support wider adoption of the testing toolkit by implementers. [Have two of the implementation teams use the toolkit by the end of the PI for Hub testing & Onboarding FSPs.]
2.	PI Objective #2: Implement a hosted version of Testing Toolkit that can be securely hosted by Schemes easily. [Can be deployed using helm charts, and is well-documented]

Measuring criteria:
1.	[An FSP can login securely to a hosted testing toolkit solution and use it to test its Mojaloop implementation.]
2.	[Secure means implementation of JWS, TLS and OAuth;]
3.	[Well-documented means Deployment / usage instructions are made available]
Stretch Objective #1.1: Implement a distributed architecture for the testing toolkit to support scalability
3.	Stretch Objective #1.2: Include a Reference OAuth Server in Helm Chart

