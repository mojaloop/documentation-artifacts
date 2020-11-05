
# PI 12 Objectives

## Performance (Miguel/Pedro)
•	Production ready MVP, consisting of happy path plus a limited set of non-happy path use cases that are fully QA'd (resilient & consistent)

•	Phase 5 plan to have the complete production ready central-ledger

##	ISO 20020  (Warren)
•	How to settle in an ISO world

•	POC

•	Draft ISO Business justification

•	Contributing member of ISO RTP group

##	Implement Cascading Timeouts (Sam)
•	Scheme specified cascaded timeouts [using durations, headers] are  implemented

•	Draft proposals for changes to the ML APIs made to CCB/SIGs

•	Design changes needed to support cascaded timeouts natively without affecting JWS / end-to-end encryption [Stretch]

##	Business Operations Framework (Steve H)
•	Define business objectives

•	Develop v1 UX for Business

•	Define APIs required

##	Accelerate Engagement with the value proposition  (was Training and onboarding for SI’s) (Lesley-Ann)
•	We have an articulated value proposition for the chosen personas

•	Use the uncdf tanzania opportunity to understand what happens when there is SI traction

•	Stretch:  we need to understand GSMA perspective (as an influencer)

##	PISP (Lewis/JJ)
•	Finish linking design and implementation

•	Packaging and consolidation of code and docs

•	Facilitate input on 3p use cases.
 
##	PDP/Testing toolkit: (Vijay)
•	Reach parity with Postman end-to-end test coverage for validating Switch, FSP implementations (for TTK), so Schemes can be confident of adoption; Measuring criteria:Hub test suites provide testUcoverage as much as the PM MojaSim test collection. Separate FSP test suites for validating FSP implementations

•	Support Schemes’ adoption of TTK; Measuring criteria: Support Mowali Scheme [or one scheme]

•	Providing enhancements for TechOps teams of Schemes; sage / UI enhancements based on community feedback;Sequence diagrams for default tests (based on event framework)

•	Automate steps for onboarding any new API [Stretch]

## Core: (Sam)
•	Will include "Implement Cascading Timeouts " for Switch [Objectives will be same as the work-stream]

•	Maintenance: Provide design, PR reviews, critical fixes, Helm releases and general technical oversight for contributions to core services

##	Versioning: (Lewis/Sam) 
•	Implement auto-releases for all core repositories in CI/CD [Measurability criteria: Improved release notes, Consolidate CI/CD Config across relevant repos]

•	Enhance ml-operator (v1.1) to apply image patching upon confirmation by Hub Operators with configurability options for automation [using a user interface - stretch goal] [Measurability criteria: Apply image patches upon confirmation]

•	Streamline Data migrations + Upgrades based on inputs from current implementers and leveraging the zero-down-time PoC {stretch goal]

##	Code quality/security: (Godfrey)
•	Enhance security in new functionality additions

•	Support major implementations

•	Design a secure cryptographic processing module

•	Improve data protection measures and controls

•	Baselining of Mojaloop against industry standards

•	Maintain and enhance secure DevOps/CI CD practices

•	Improve communication and community engagement

•	Improve access control measures

## LPS Adaptor: (Renjith/Adrian)
•	Get some implementation experience from Umoja and TIPS (at least open a dialogue about requirements and understand how the adaptor would suit theirs)

•	Add support for 3rd party APIs (i.e. initiate ATM and POS via the 3rd party APIs)

•	Update TTK integration to use the 3rd party APIs

## Web Payments (Don/Adrian)

•	Find a adopter/home for all testing/demo tools including our Web-based wallet and ATM and POS simulators

##	Settlement V2/Cross-Currency: (Michael)
•	Determine a pilot for potential implementation and feedback

##	Fraud Management: (Justus)
•	TBD

##	Leadership and Community mgmt.: (Simeon)

•	Governance: Conduct elections for Design Authority and Community Council and reconstitute Community Governance Committees

•	Metrics: Define and operationalize Growth and Engagement Indexes

•	Community Strategy: Establish OSS Contribution Cycle Tracker
 
