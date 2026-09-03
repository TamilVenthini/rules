# KSI–Control Analysis

## Purpose

This document analyzes the relationship between FedRAMP Key Security Indicators (KSIs), their associated normalized controls, and the Rev5 Class C baseline.

The analysis identifies shared controls, Class C-relevant shared controls, KSI-to-KSI overlap, and potential implementation/evidence reuse areas.

## Sources

- `fedramp-consolidated-rules.json`
- `schemas/fedramp-consolidated-rules.schema.json`

## 1. KSI Inventory

Total KSI indicators: **46**

### KSI-CED-RAT — Reviewing All Training

**Family:** `CED`

**Statement:** The effectiveness of relevant cybersecurity education and training is persistently reviewed, including at least general training for all employees, role-specific training for employees in high risk roles, training for development and engineering staff on secure software delivery, and training for staff involved with incident response or disaster recovery.

**Controls:** 11

`cp-3`, `ir-2`, `ps-6`, `at-2`, `at-2.2`, `at-2.3`, `at-3.5`, `at-4`, `ir-2.3`, `at-3`, `sr-11.1`

**Controls matching Class C baseline:** 9

### KSI-CMT-LMC — Logging Changes

**Family:** `CMT`

**Statement:** Modifications to the cloud service offering are logged and monitored.

**Controls:** 7

`au-2`, `cm-3`, `cm-3.2`, `cm-4.2`, `cm-6`, `cm-8.3`, `ma-2`

**Controls matching Class C baseline:** 7

### KSI-CMT-RMV — Redeploying vs Modifying

**Family:** `CMT`

**Statement:** Changes to machine-based information resources are executed through the redeployment of version controlled resources rather than direct modification wherever reasonable.

**Controls:** 7

`cm-2`, `cm-3`, `cm-5`, `cm-6`, `cm-7`, `cm-8.1`, `si-3`

**Controls matching Class C baseline:** 7

### KSI-CMT-RVP — Reviewing Change Procedures

**Family:** `CMT`

**Statement:** The effectiveness of documented change management procedures is persistently reviewed.

**Controls:** 6

`cm-3`, `cm-3.2`, `cm-3.4`, `cm-5`, `cm-7.1`, `cm-9`

**Controls matching Class C baseline:** 6

### KSI-CMT-VTD — Validating Throughout Deployment

**Family:** `CMT`

**Statement:** Persistent testing and validation of changes throughout deployment is automated.

**Controls:** 4

`cm-3`, `cm-3.2`, `cm-4.2`, `si-2`

**Controls matching Class C baseline:** 4

### KSI-CNA-DFP — Defining Functionality and Privileges

**Family:** `CNA`

**Statement:** The functionality and privileges for infrastructure and services are strictly defined.

**Controls:** 2

`cm-2`, `si-3`

**Controls matching Class C baseline:** 2

### KSI-CNA-EIS — Enforcing Intended State

**Family:** `CNA`

**Controls:** 2

`ca-2.1`, `ca-7.1`

**Controls matching Class C baseline:** 2

### KSI-CNA-IBP — Implementing Best Practices

**Family:** `CNA`

**Statement:** The use and configuration of third-party machine-based information resources is persistently compared against the original provider's best practices and guidance.

**Controls:** 3

`ac-17.3`, `cm-2`, `pl-10`

**Controls matching Class C baseline:** 3

### KSI-CNA-MAT — Minimizing Attack Surface

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they have a minimal attack surface and that lateral movement is minimized if compromised.

**Controls:** 14

`ac-17.3`, `ac-18.1`, `ac-18.3`, `ac-20.1`, `ca-9`, `sc-7.3`, `sc-7.4`, `sc-7.5`, `sc-7.8`, `sc-8`, `sc-10`, `si-10`, `si-11`, `si-16`

**Controls matching Class C baseline:** 14

### KSI-CNA-OFA — Optimizing for Availability

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they are appropriately optimized for high availability and rapid recovery.

**Controls:** 0



**Controls matching Class C baseline:** 0

### KSI-CNA-RNT — Restricting Network Traffic

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they are appropriately configured to limit inbound and outbound network traffic.

**Controls:** 5

`ac-17.3`, `ca-9`, `cm-7.1`, `sc-7.5`, `si-8`

**Controls matching Class C baseline:** 5

### KSI-CNA-RVP — Reviewing Protections

**Family:** `CNA`

**Statement:** The effectiveness of protection against denial of service attacks and other unwanted activity for machine-based information resources is persistently reviewed.

**Controls:** 3

`sc-5`, `si-8`, `si-8.2`

**Controls matching Class C baseline:** 3

### KSI-CNA-ULN — Using Logical Networking

**Family:** `CNA`

**Statement:** Logical networking and related capabilities are used and persistently reviewed to enforce traffic flow controls.

**Controls:** 8

`ac-12`, `ac-17.3`, `ca-9`, `sc-4`, `sc-7`, `sc-7.7`, `sc-8`, `sc-10`

**Controls matching Class C baseline:** 8

### KSI-IAM-AAM — Automating Account Management

**Family:** `IAM`

**Statement:** The lifecycle and privileges of all accounts, roles, and groups are securely managed using automation.

**Controls:** 9

`ac-2.2`, `ac-2.3`, `ac-2.13`, `ac-6.7`, `ia-4.4`, `ia-12`, `ia-12.2`, `ia-12.3`, `ia-12.5`

**Controls matching Class C baseline:** 9

### KSI-IAM-APM — Adopting Passwordless Methods

**Family:** `IAM`

**Statement:** Secure passwordless methods are used for user authentication and authorization when feasible, otherwise strong passwords with phishing-resistant MFA is used.

**Controls:** 13

`ac-3`, `ia-5.1`, `ia-5.2`, `ia-5.6`, `ia-6`, `ac-2`, `ia-2`, `ia-2.1`, `ia-2.2`, `ia-2.8`, `ia-5`, `ia-8`, `sc-23`

**Controls matching Class C baseline:** 13

### KSI-IAM-ELP — Ensuring Least Privilege

**Family:** `IAM`

**Statement:** Identity and access management measures are used and persistently reviewed to ensure each user or device can only access the resources they need.

**Controls:** 34

`ac-2.5`, `ac-2.6`, `ac-3`, `ac-4`, `ac-6`, `ac-12`, `ac-14`, `ac-17`, `ac-17.1`, `ac-17.2`, `ac-17.3`, `ac-20`, `ac-20.1`, `cm-2.7`, `cm-9`, `ia-2`, `ia-3`, `ia-4`, `ia-4.4`, `ia-5.2`, `ia-5.6`, `ia-11`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `sc-4`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-39`, `si-3`

**Controls matching Class C baseline:** 33

### KSI-IAM-JIT — Authorizing Just-in-Time

**Family:** `IAM`

**Statement:** A least-privileged, role and attribute-based, and just-in-time security authorization model is used and persistently reviewed for all user and non-user accounts and services.

**Controls:** 38

`ac-2`, `ac-2.1`, `ac-2.2`, `ac-2.3`, `ac-2.4`, `ac-2.6`, `ac-3`, `ac-4`, `ac-5`, `ac-6`, `ac-6.1`, `ac-6.2`, `ac-6.5`, `ac-6.7`, `ac-6.9`, `ac-6.10`, `ac-7`, `ac-20.1`, `ac-17`, `au-9.4`, `cm-5`, `cm-7`, `cm-7.2`, `cm-7.5`, `cm-9`, `ia-4`, `ia-4.4`, `ia-7`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `ps-9`, `ra-5.5`, `sc-2`, `sc-23`, `sc-39`

**Controls matching Class C baseline:** 37

### KSI-IAM-SNU — Securing Non-User Authentication

**Family:** `IAM`

**Statement:** Appropriately secure authentication methods are used and persistently reviewed for non-user accounts and services.

**Controls:** 7

`ac-2`, `ac-2.2`, `ac-4`, `ac-6.5`, `ia-3`, `ia-5.2`, `ra-5.5`

**Controls matching Class C baseline:** 7

### KSI-IAM-SUS — Responding to Suspicious Activity

**Family:** `IAM`

**Statement:** Accounts with privileged access are disabled or otherwise secured in response to suspicious activity.

**Controls:** 7

`ac-2`, `ac-2.1`, `ac-2.3`, `ac-2.13`, `ac-7`, `ps-4`, `ps-8`

**Controls matching Class C baseline:** 7

### KSI-INR-AAR — Generating After Action Reports

**Family:** `INR`

**Statement:** Incident after action reports are generated and lessons learned are persistently incorporated.

**Controls:** 4

`ir-3`, `ir-4`, `ir-4.1`, `ir-8`

**Controls matching Class C baseline:** 4

### KSI-INR-RIR — Reviewing Incident Response Procedures

**Family:** `INR`

**Statement:** The effectiveness of documented incident response procedures is persistently reviewed.

**Controls:** 10

`ir-4`, `ir-4.1`, `ir-6`, `ir-6.1`, `ir-6.3`, `ir-7`, `ir-7.1`, `ir-8`, `ir-8.1`, `si-4.5`

**Controls matching Class C baseline:** 9

### KSI-INR-RPI — Reviewing Past Incidents

**Family:** `INR`

**Statement:** Past incidents are persistently reviewed for patterns or vulnerabilities that were not previously apparent or identified.

**Controls:** 5

`ir-3`, `ir-4`, `ir-4.1`, `ir-5`, `ir-8`

**Controls matching Class C baseline:** 5

### KSI-MLA-ALA — Authorizing Log Access

**Family:** `MLA`

**Controls:** 1

`si-11`

**Controls matching Class C baseline:** 1

### KSI-MLA-EVC — Evaluating Configurations

**Family:** `MLA`

**Statement:** The configuration of machine-based information resources, especially infrastructure as code, is persistently evaluated and tested.

**Controls:** 4

`ca-7`, `cm-2`, `cm-6`, `si-7.7`

**Controls matching Class C baseline:** 4

### KSI-MLA-LET — Logging Event Types

**Family:** `MLA`

**Statement:** A list of information resources and event types that will be logged, monitored, and audited is maintained and persistently reviewed to ensure these activities occur.

**Controls:** 10

`ac-2.4`, `ac-6.9`, `ac-17.1`, `ac-20.1`, `au-2`, `au-7.1`, `au-12`, `si-4.4`, `si-4.5`, `si-7.7`

**Controls matching Class C baseline:** 10

### KSI-MLA-OSM — Operating SIEM Capability

**Family:** `MLA`

**Statement:** A Security Information and Event Management (SIEM) or similar system(s) is used and persistently reviewed for centralized, tamper-resistant logging of events, activities, and changes.

**Controls:** 18

`ac-17.1`, `ac-20.1`, `au-2`, `au-3`, `au-3.1`, `au-4`, `au-5`, `au-6.1`, `au-6.3`, `au-7`, `au-7.1`, `au-8`, `au-9`, `au-11`, `ir-4.1`, `si-4.2`, `si-4.4`, `si-7.7`

**Controls matching Class C baseline:** 18

### KSI-MLA-RVL — Reviewing Logs

**Family:** `MLA`

**Statement:** Logs are persistently reviewed and audited.

**Controls:** 7

`ac-2.4`, `ac-6.9`, `au-2`, `au-6`, `au-6.1`, `si-4`, `si-4.4`

**Controls matching Class C baseline:** 7

### KSI-PIY-GIV — Generating Inventories

**Family:** `PIY`

**Statement:** Authoritative sources are used to automatically generate real-time inventories of all information resources when needed.

**Controls:** 7

`cm-2.2`, `cm-7.5`, `cm-8`, `cm-8.1`, `cm-12`, `cm-12.1`, `cp-2.8`

**Controls matching Class C baseline:** 7

### KSI-PIY-RES — Reviewing Executive Support

**Family:** `PIY`

**Statement:** Executive support for achieving the provider's security goals is persistently reviewed and demonstrated.

**Controls:** 0



**Controls matching Class C baseline:** 0

### KSI-PIY-RIS — Reviewing Investments in Security

**Family:** `PIY`

**Statement:** The effectiveness of the provider's investments in achieving security goals is persistently reviewed.

**Controls:** 9

`ac-5`, `ca-2`, `cp-2.1`, `cp-4.1`, `ir-3.2`, `pm-3`, `sa-2`, `sa-3`, `sr-2.1`

**Controls matching Class C baseline:** 8

### KSI-PIY-RSD — Reviewing Security in the SDLC

**Family:** `PIY`

**Statement:** The effectiveness of building security and privacy considerations into the Software Development Lifecycle and aligning with CISA Secure By Design principles is persistently reviewed.

**Controls:** 12

`ac-5`, `au-3.3`, `cm-3.4`, `pl-8`, `pm-7`, `sa-3`, `sa-8`, `sc-4`, `sc-18`, `si-10`, `si-11`, `si-16`

**Controls matching Class C baseline:** 10

### KSI-PIY-RVD — Reviewing Vulnerability Disclosures

**Family:** `PIY`

**Statement:** The effectiveness of the provider's vulnerability disclosure program is persistently reviewed.

**Controls:** 1

`ra-5.11`

**Controls matching Class C baseline:** 1

### KSI-RPL-ABO — Aligning Backups with Objectives

**Family:** `RPL`

**Statement:** The alignment of machine-based information resource backups with defined recovery objectives is persistently reviewed.

**Controls:** 6

`cm-2.3`, `cp-6`, `cp-9`, `cp-10`, `cp-10.2`, `si-12`

**Controls matching Class C baseline:** 6

### KSI-RPL-ARP — Aligning Recovery Plan

**Family:** `RPL`

**Statement:** The alignment of recovery plans with defined recovery objectives is persistently reviewed.

**Controls:** 16

`cp-2`, `cp-2.1`, `cp-2.3`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-6.3`, `cp-7`, `cp-7.1`, `cp-7.2`, `cp-7.3`, `cp-8`, `cp-8.1`, `cp-8.2`, `cp-10`, `cp-10.2`

**Controls matching Class C baseline:** 16

### KSI-RPL-RRO — Reviewing Recovery Objectives

**Family:** `RPL`

**Statement:** The desired Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO) are defined and persistently reviewed for alignment with the provider's business needs and capabilities.

**Controls:** 2

`cp-2.3`, `cp-10`

**Controls matching Class C baseline:** 2

### KSI-RPL-TRC — Testing Recovery Capabilities

**Family:** `RPL`

**Statement:** The capability to recover from incidents and contingencies aligned with defined recovery objectives is persistently tested.

**Controls:** 10

`cp-2.1`, `cp-2.3`, `cp-4`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-9.1`, `cp-10`, `ir-3`, `ir-3.2`

**Controls matching Class C baseline:** 10

### KSI-SCR-MIT — Mitigating Supply Chain Risk

**Family:** `SCR`

**Statement:** Persistently identify, review, and mitigate potential supply chain risks.

**Controls:** 12

`ac-20`, `ra-3.1`, `sa-9`, `sa-10`, `sa-11`, `sa-15.3`, `sa-22`, `si-7.1`, `sr-5`, `sr-6`, `ca-7.4`, `sc-18`

**Controls matching Class C baseline:** 12

### KSI-SCR-MON — Monitoring Supply Chain Risk

**Family:** `SCR`

**Statement:** Third party software information resources are automatically monitored for upstream vulnerabilities using mechanisms that may include contractual notification requirements or active monitoring services.

**Controls:** 10

`ac-20`, `ca-3`, `ir-6.3`, `ps-7`, `ra-5`, `sa-9`, `si-5`, `sr-5`, `sr-6`, `sr-8`

**Controls matching Class C baseline:** 10

### KSI-SVC-ACM — Automating Configuration Management

**Family:** `SVC`

**Statement:** The configuration of machine-based information resources is managed using automation and persistently reviewed for drift.

**Controls:** 11

`ac-2.4`, `cm-2`, `cm-2.2`, `cm-2.3`, `cm-6`, `cm-7.1`, `pl-9`, `pl-10`, `sa-5`, `si-5`, `sr-10`

**Controls matching Class C baseline:** 10

### KSI-SVC-ASM — Automating Secret Management

**Family:** `SVC`

**Statement:** Management, protection, and regular rotation of digital keys, certificates, and other secrets is automated and persistently reviewed.

**Controls:** 5

`ac-17.2`, `ia-5.2`, `ia-5.6`, `sc-12`, `sc-17`

**Controls matching Class C baseline:** 5

### KSI-SVC-EIS — Evaluating and Improving Security

**Family:** `SVC`

**Statement:** Information resources are persistently evaluated for opportunities to improve security and those improvements are persistently made.

**Controls:** 9

`cm-7.1`, `cm-12.1`, `ma-2`, `pl-8`, `sc-7`, `sc-39`, `si-2.2`, `si-4`, `sr-10`

**Controls matching Class C baseline:** 9

### KSI-SVC-PRR — Preventing Residual Risk

**Family:** `SVC`

**Controls:** 1

`sc-4`

**Controls matching Class C baseline:** 1

### KSI-SVC-RUD — Removing Unwanted Data

**Family:** `SVC`

**Controls:** 2

`si-12.3`, `si-18.4`

**Controls matching Class C baseline:** 0

### KSI-SVC-SIN — Securing Information

**Family:** `SVC`

**Statement:** Information is encrypted or otherwise secured from unwanted access or modification.

**Controls:** 12

`ac-1`, `ac-17.2`, `cp-9.8`, `sc-8`, `sc-8.1`, `sc-13`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-28`, `sc-28.1`

**Controls matching Class C baseline:** 12

### KSI-SVC-VCM — Validating Communications

**Family:** `SVC`

**Controls:** 2

`sc-23`, `si-7.1`

**Controls matching Class C baseline:** 2

### KSI-SVC-VRI — Validating Resource Integrity

**Family:** `SVC`

**Statement:** Use cryptographic methods to validate the integrity of machine-based information resources.

**Controls:** 7

`cm-2.2`, `cm-8.3`, `sc-13`, `sc-23`, `si-7`, `si-7.1`, `sr-10`

**Controls matching Class C baseline:** 7

## 2. Rev5 Class C Baseline

Total Class C baseline controls: **322**

- **AC: 43 controls**
- **AT: 6 controls**
- **AU: 16 controls**
- **CA: 13 controls**
- **CM: 27 controls**
- **CP: 23 controls**
- **IA: 27 controls**
- **IR: 17 controls**
- **MA: 10 controls**
- **MP: 7 controls**
- **PE: 19 controls**
- **PL: 7 controls**
- **PS: 10 controls**
- **RA: 11 controls**
- **SA: 21 controls**
- **SC: 29 controls**
- **SI: 24 controls**
- **SR: 12 controls**

## 3. Shared Controls Across KSIs

Total controls referenced by multiple KSIs: **98**

| Control | KSI count | KSIs | Class C |
|---|---:|---|:---:|
| `sc-23` | 6 | KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-SIN, KSI-SVC-VCM, KSI-SVC-VRI | YES |
| `ac-17.3` | 5 | KSI-CNA-IBP, KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN, KSI-IAM-ELP | YES |
| `ac-20.1` | 5 | KSI-CNA-MAT, KSI-IAM-ELP, KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-OSM | YES |
| `cm-2` | 5 | KSI-CMT-RMV, KSI-CNA-DFP, KSI-CNA-IBP, KSI-MLA-EVC, KSI-SVC-ACM | YES |
| `ac-2` | 4 | KSI-IAM-APM, KSI-IAM-JIT, KSI-IAM-SNU, KSI-IAM-SUS | YES |
| `ac-2.4` | 4 | KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL, KSI-SVC-ACM | YES |
| `au-2` | 4 | KSI-CMT-LMC, KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL | YES |
| `cm-3` | 4 | KSI-CMT-LMC, KSI-CMT-RMV, KSI-CMT-RVP, KSI-CMT-VTD | YES |
| `cm-6` | 4 | KSI-CMT-LMC, KSI-CMT-RMV, KSI-MLA-EVC, KSI-SVC-ACM | YES |
| `cm-7.1` | 4 | KSI-CMT-RVP, KSI-CNA-RNT, KSI-SVC-ACM, KSI-SVC-EIS | YES |
| `cp-10` | 4 | KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC | YES |
| `ia-5.2` | 4 | KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-SNU, KSI-SVC-ASM | YES |
| `ir-4.1` | 4 | KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI, KSI-MLA-OSM | YES |
| `sc-4` | 4 | KSI-CNA-ULN, KSI-IAM-ELP, KSI-PIY-RSD, KSI-SVC-PRR | YES |
| `ac-2.2` | 3 | KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SNU | YES |
| `ac-2.3` | 3 | KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SUS | YES |
| `ac-3` | 3 | KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ac-4` | 3 | KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SNU | YES |
| `ac-5` | 3 | KSI-IAM-JIT, KSI-PIY-RIS, KSI-PIY-RSD | YES |
| `ac-6.9` | 3 | KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL | YES |
| `ac-17.1` | 3 | KSI-IAM-ELP, KSI-MLA-LET, KSI-MLA-OSM | YES |
| `ac-17.2` | 3 | KSI-IAM-ELP, KSI-SVC-ASM, KSI-SVC-SIN | YES |
| `ac-20` | 3 | KSI-IAM-ELP, KSI-SCR-MIT, KSI-SCR-MON | YES |
| `ca-9` | 3 | KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN | YES |
| `cm-2.2` | 3 | KSI-PIY-GIV, KSI-SVC-ACM, KSI-SVC-VRI | YES |
| `cm-3.2` | 3 | KSI-CMT-LMC, KSI-CMT-RVP, KSI-CMT-VTD | YES |
| `cm-5` | 3 | KSI-CMT-RMV, KSI-CMT-RVP, KSI-IAM-JIT | YES |
| `cm-9` | 3 | KSI-CMT-RVP, KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `cp-2.1` | 3 | KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC | YES |
| `cp-2.3` | 3 | KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC | YES |
| `cp-4.1` | 3 | KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC | YES |
| `cp-6` | 3 | KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-TRC | YES |
| `ia-4.4` | 3 | KSI-IAM-AAM, KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ia-5.6` | 3 | KSI-IAM-APM, KSI-IAM-ELP, KSI-SVC-ASM | YES |
| `ir-3` | 3 | KSI-INR-AAR, KSI-INR-RPI, KSI-RPL-TRC | YES |
| `ir-4` | 3 | KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI | YES |
| `ir-8` | 3 | KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI | YES |
| `ps-4` | 3 | KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SUS | YES |
| `ps-6` | 3 | KSI-CED-RAT, KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `sc-8` | 3 | KSI-CNA-MAT, KSI-CNA-ULN, KSI-SVC-SIN | YES |
| `sc-39` | 3 | KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-EIS | YES |
| `si-3` | 3 | KSI-CMT-RMV, KSI-CNA-DFP, KSI-IAM-ELP | YES |
| `si-4.4` | 3 | KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL | YES |
| `si-7.1` | 3 | KSI-SCR-MIT, KSI-SVC-VCM, KSI-SVC-VRI | YES |
| `si-7.7` | 3 | KSI-MLA-EVC, KSI-MLA-LET, KSI-MLA-OSM | YES |
| `si-11` | 3 | KSI-CNA-MAT, KSI-MLA-ALA, KSI-PIY-RSD | YES |
| `sr-10` | 3 | KSI-SVC-ACM, KSI-SVC-EIS, KSI-SVC-VRI | YES |
| `ac-2.1` | 2 | KSI-IAM-JIT, KSI-IAM-SUS | YES |
| `ac-2.6` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | NO |
| `ac-2.13` | 2 | KSI-IAM-AAM, KSI-IAM-SUS | YES |
| `ac-6` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ac-6.5` | 2 | KSI-IAM-JIT, KSI-IAM-SNU | YES |
| `ac-6.7` | 2 | KSI-IAM-AAM, KSI-IAM-JIT | YES |
| `ac-7` | 2 | KSI-IAM-JIT, KSI-IAM-SUS | YES |
| `ac-12` | 2 | KSI-CNA-ULN, KSI-IAM-ELP | YES |
| `ac-17` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `au-6.1` | 2 | KSI-MLA-OSM, KSI-MLA-RVL | YES |
| `au-7.1` | 2 | KSI-MLA-LET, KSI-MLA-OSM | YES |
| `cm-2.3` | 2 | KSI-RPL-ABO, KSI-SVC-ACM | YES |
| `cm-3.4` | 2 | KSI-CMT-RVP, KSI-PIY-RSD | YES |
| `cm-4.2` | 2 | KSI-CMT-LMC, KSI-CMT-VTD | YES |
| `cm-7` | 2 | KSI-CMT-RMV, KSI-IAM-JIT | YES |
| `cm-7.5` | 2 | KSI-IAM-JIT, KSI-PIY-GIV | YES |
| `cm-8.1` | 2 | KSI-CMT-RMV, KSI-PIY-GIV | YES |
| `cm-8.3` | 2 | KSI-CMT-LMC, KSI-SVC-VRI | YES |
| `cm-12.1` | 2 | KSI-PIY-GIV, KSI-SVC-EIS | YES |
| `cp-6.1` | 2 | KSI-RPL-ARP, KSI-RPL-TRC | YES |
| `cp-10.2` | 2 | KSI-RPL-ABO, KSI-RPL-ARP | YES |
| `ia-2` | 2 | KSI-IAM-APM, KSI-IAM-ELP | YES |
| `ia-3` | 2 | KSI-IAM-ELP, KSI-IAM-SNU | YES |
| `ia-4` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ir-3.2` | 2 | KSI-PIY-RIS, KSI-RPL-TRC | YES |
| `ir-6.3` | 2 | KSI-INR-RIR, KSI-SCR-MON | YES |
| `ma-2` | 2 | KSI-CMT-LMC, KSI-SVC-EIS | YES |
| `pl-8` | 2 | KSI-PIY-RSD, KSI-SVC-EIS | YES |
| `pl-10` | 2 | KSI-CNA-IBP, KSI-SVC-ACM | YES |
| `ps-2` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ps-3` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ps-5` | 2 | KSI-IAM-ELP, KSI-IAM-JIT | YES |
| `ra-5.5` | 2 | KSI-IAM-JIT, KSI-IAM-SNU | YES |
| `sa-3` | 2 | KSI-PIY-RIS, KSI-PIY-RSD | YES |
| `sa-9` | 2 | KSI-SCR-MIT, KSI-SCR-MON | YES |
| `sc-7` | 2 | KSI-CNA-ULN, KSI-SVC-EIS | YES |
| `sc-7.5` | 2 | KSI-CNA-MAT, KSI-CNA-RNT | YES |
| `sc-10` | 2 | KSI-CNA-MAT, KSI-CNA-ULN | YES |
| `sc-13` | 2 | KSI-SVC-SIN, KSI-SVC-VRI | YES |
| `sc-18` | 2 | KSI-PIY-RSD, KSI-SCR-MIT | YES |
| `sc-20` | 2 | KSI-IAM-ELP, KSI-SVC-SIN | YES |
| `sc-21` | 2 | KSI-IAM-ELP, KSI-SVC-SIN | YES |
| `sc-22` | 2 | KSI-IAM-ELP, KSI-SVC-SIN | YES |
| `si-4` | 2 | KSI-MLA-RVL, KSI-SVC-EIS | YES |
| `si-4.5` | 2 | KSI-INR-RIR, KSI-MLA-LET | YES |
| `si-5` | 2 | KSI-SCR-MON, KSI-SVC-ACM | YES |
| `si-8` | 2 | KSI-CNA-RNT, KSI-CNA-RVP | YES |
| `si-10` | 2 | KSI-CNA-MAT, KSI-PIY-RSD | YES |
| `si-16` | 2 | KSI-CNA-MAT, KSI-PIY-RSD | YES |
| `sr-5` | 2 | KSI-SCR-MIT, KSI-SCR-MON | YES |
| `sr-6` | 2 | KSI-SCR-MIT, KSI-SCR-MON | YES |

## 4. Class C Shared Controls

Total Class C controls shared by multiple KSIs: **97**

### `sc-23` — 6 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-SVC-SIN` — Securing Information
- `KSI-SVC-VCM` — Validating Communications
- `KSI-SVC-VRI` — Validating Resource Integrity

### `ac-17.3` — 5 KSIs

- `KSI-CNA-IBP` — Implementing Best Practices
- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-CNA-RNT` — Restricting Network Traffic
- `KSI-CNA-ULN` — Using Logical Networking
- `KSI-IAM-ELP` — Ensuring Least Privilege

### `ac-20.1` — 5 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability

### `cm-2` — 5 KSIs

- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-CNA-DFP` — Defining Functionality and Privileges
- `KSI-CNA-IBP` — Implementing Best Practices
- `KSI-MLA-EVC` — Evaluating Configurations
- `KSI-SVC-ACM` — Automating Configuration Management

### `ac-2` — 4 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SNU` — Securing Non-User Authentication
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ac-2.4` — 4 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-RVL` — Reviewing Logs
- `KSI-SVC-ACM` — Automating Configuration Management

### `au-2` — 4 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability
- `KSI-MLA-RVL` — Reviewing Logs

### `cm-3` — 4 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-CMT-VTD` — Validating Throughout Deployment

### `cm-6` — 4 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-MLA-EVC` — Evaluating Configurations
- `KSI-SVC-ACM` — Automating Configuration Management

### `cm-7.1` — 4 KSIs

- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-CNA-RNT` — Restricting Network Traffic
- `KSI-SVC-ACM` — Automating Configuration Management
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `cp-10` — 4 KSIs

- `KSI-RPL-ABO` — Aligning Backups with Objectives
- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-RRO` — Reviewing Recovery Objectives
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `ia-5.2` — 4 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-SNU` — Securing Non-User Authentication
- `KSI-SVC-ASM` — Automating Secret Management

### `ir-4.1` — 4 KSIs

- `KSI-INR-AAR` — Generating After Action Reports
- `KSI-INR-RIR` — Reviewing Incident Response Procedures
- `KSI-INR-RPI` — Reviewing Past Incidents
- `KSI-MLA-OSM` — Operating SIEM Capability

### `sc-4` — 4 KSIs

- `KSI-CNA-ULN` — Using Logical Networking
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-PIY-RSD` — Reviewing Security in the SDLC
- `KSI-SVC-PRR` — Preventing Residual Risk

### `ac-2.2` — 3 KSIs

- `KSI-IAM-AAM` — Automating Account Management
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SNU` — Securing Non-User Authentication

### `ac-2.3` — 3 KSIs

- `KSI-IAM-AAM` — Automating Account Management
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ac-3` — 3 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ac-4` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SNU` — Securing Non-User Authentication

### `ac-5` — 3 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-PIY-RIS` — Reviewing Investments in Security
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `ac-6.9` — 3 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-RVL` — Reviewing Logs

### `ac-17.1` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability

### `ac-17.2` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SVC-ASM` — Automating Secret Management
- `KSI-SVC-SIN` — Securing Information

### `ac-20` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SCR-MIT` — Mitigating Supply Chain Risk
- `KSI-SCR-MON` — Monitoring Supply Chain Risk

### `ca-9` — 3 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-CNA-RNT` — Restricting Network Traffic
- `KSI-CNA-ULN` — Using Logical Networking

### `cm-2.2` — 3 KSIs

- `KSI-PIY-GIV` — Generating Inventories
- `KSI-SVC-ACM` — Automating Configuration Management
- `KSI-SVC-VRI` — Validating Resource Integrity

### `cm-3.2` — 3 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-CMT-VTD` — Validating Throughout Deployment

### `cm-5` — 3 KSIs

- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `cm-9` — 3 KSIs

- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `cp-2.1` — 3 KSIs

- `KSI-PIY-RIS` — Reviewing Investments in Security
- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `cp-2.3` — 3 KSIs

- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-RRO` — Reviewing Recovery Objectives
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `cp-4.1` — 3 KSIs

- `KSI-PIY-RIS` — Reviewing Investments in Security
- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `cp-6` — 3 KSIs

- `KSI-RPL-ABO` — Aligning Backups with Objectives
- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `ia-4.4` — 3 KSIs

- `KSI-IAM-AAM` — Automating Account Management
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ia-5.6` — 3 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SVC-ASM` — Automating Secret Management

### `ir-3` — 3 KSIs

- `KSI-INR-AAR` — Generating After Action Reports
- `KSI-INR-RPI` — Reviewing Past Incidents
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `ir-4` — 3 KSIs

- `KSI-INR-AAR` — Generating After Action Reports
- `KSI-INR-RIR` — Reviewing Incident Response Procedures
- `KSI-INR-RPI` — Reviewing Past Incidents

### `ir-8` — 3 KSIs

- `KSI-INR-AAR` — Generating After Action Reports
- `KSI-INR-RIR` — Reviewing Incident Response Procedures
- `KSI-INR-RPI` — Reviewing Past Incidents

### `ps-4` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ps-6` — 3 KSIs

- `KSI-CED-RAT` — Reviewing All Training
- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `sc-8` — 3 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-CNA-ULN` — Using Logical Networking
- `KSI-SVC-SIN` — Securing Information

### `sc-39` — 3 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `si-3` — 3 KSIs

- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-CNA-DFP` — Defining Functionality and Privileges
- `KSI-IAM-ELP` — Ensuring Least Privilege

### `si-4.4` — 3 KSIs

- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability
- `KSI-MLA-RVL` — Reviewing Logs

### `si-7.1` — 3 KSIs

- `KSI-SCR-MIT` — Mitigating Supply Chain Risk
- `KSI-SVC-VCM` — Validating Communications
- `KSI-SVC-VRI` — Validating Resource Integrity

### `si-7.7` — 3 KSIs

- `KSI-MLA-EVC` — Evaluating Configurations
- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability

### `si-11` — 3 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-MLA-ALA` — Authorizing Log Access
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `sr-10` — 3 KSIs

- `KSI-SVC-ACM` — Automating Configuration Management
- `KSI-SVC-EIS` — Evaluating and Improving Security
- `KSI-SVC-VRI` — Validating Resource Integrity

### `ac-2.1` — 2 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ac-2.13` — 2 KSIs

- `KSI-IAM-AAM` — Automating Account Management
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ac-6` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ac-6.5` — 2 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SNU` — Securing Non-User Authentication

### `ac-6.7` — 2 KSIs

- `KSI-IAM-AAM` — Automating Account Management
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ac-7` — 2 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SUS` — Responding to Suspicious Activity

### `ac-12` — 2 KSIs

- `KSI-CNA-ULN` — Using Logical Networking
- `KSI-IAM-ELP` — Ensuring Least Privilege

### `ac-17` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `au-6.1` — 2 KSIs

- `KSI-MLA-OSM` — Operating SIEM Capability
- `KSI-MLA-RVL` — Reviewing Logs

### `au-7.1` — 2 KSIs

- `KSI-MLA-LET` — Logging Event Types
- `KSI-MLA-OSM` — Operating SIEM Capability

### `cm-2.3` — 2 KSIs

- `KSI-RPL-ABO` — Aligning Backups with Objectives
- `KSI-SVC-ACM` — Automating Configuration Management

### `cm-3.4` — 2 KSIs

- `KSI-CMT-RVP` — Reviewing Change Procedures
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `cm-4.2` — 2 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-CMT-VTD` — Validating Throughout Deployment

### `cm-7` — 2 KSIs

- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `cm-7.5` — 2 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-PIY-GIV` — Generating Inventories

### `cm-8.1` — 2 KSIs

- `KSI-CMT-RMV` — Redeploying vs Modifying
- `KSI-PIY-GIV` — Generating Inventories

### `cm-8.3` — 2 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-SVC-VRI` — Validating Resource Integrity

### `cm-12.1` — 2 KSIs

- `KSI-PIY-GIV` — Generating Inventories
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `cp-6.1` — 2 KSIs

- `KSI-RPL-ARP` — Aligning Recovery Plan
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `cp-10.2` — 2 KSIs

- `KSI-RPL-ABO` — Aligning Backups with Objectives
- `KSI-RPL-ARP` — Aligning Recovery Plan

### `ia-2` — 2 KSIs

- `KSI-IAM-APM` — Adopting Passwordless Methods
- `KSI-IAM-ELP` — Ensuring Least Privilege

### `ia-3` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-SNU` — Securing Non-User Authentication

### `ia-4` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ir-3.2` — 2 KSIs

- `KSI-PIY-RIS` — Reviewing Investments in Security
- `KSI-RPL-TRC` — Testing Recovery Capabilities

### `ir-6.3` — 2 KSIs

- `KSI-INR-RIR` — Reviewing Incident Response Procedures
- `KSI-SCR-MON` — Monitoring Supply Chain Risk

### `ma-2` — 2 KSIs

- `KSI-CMT-LMC` — Logging Changes
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `pl-8` — 2 KSIs

- `KSI-PIY-RSD` — Reviewing Security in the SDLC
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `pl-10` — 2 KSIs

- `KSI-CNA-IBP` — Implementing Best Practices
- `KSI-SVC-ACM` — Automating Configuration Management

### `ps-2` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ps-3` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ps-5` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-IAM-JIT` — Authorizing Just-in-Time

### `ra-5.5` — 2 KSIs

- `KSI-IAM-JIT` — Authorizing Just-in-Time
- `KSI-IAM-SNU` — Securing Non-User Authentication

### `sa-3` — 2 KSIs

- `KSI-PIY-RIS` — Reviewing Investments in Security
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `sa-9` — 2 KSIs

- `KSI-SCR-MIT` — Mitigating Supply Chain Risk
- `KSI-SCR-MON` — Monitoring Supply Chain Risk

### `sc-7` — 2 KSIs

- `KSI-CNA-ULN` — Using Logical Networking
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `sc-7.5` — 2 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-CNA-RNT` — Restricting Network Traffic

### `sc-10` — 2 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-CNA-ULN` — Using Logical Networking

### `sc-13` — 2 KSIs

- `KSI-SVC-SIN` — Securing Information
- `KSI-SVC-VRI` — Validating Resource Integrity

### `sc-18` — 2 KSIs

- `KSI-PIY-RSD` — Reviewing Security in the SDLC
- `KSI-SCR-MIT` — Mitigating Supply Chain Risk

### `sc-20` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SVC-SIN` — Securing Information

### `sc-21` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SVC-SIN` — Securing Information

### `sc-22` — 2 KSIs

- `KSI-IAM-ELP` — Ensuring Least Privilege
- `KSI-SVC-SIN` — Securing Information

### `si-4` — 2 KSIs

- `KSI-MLA-RVL` — Reviewing Logs
- `KSI-SVC-EIS` — Evaluating and Improving Security

### `si-4.5` — 2 KSIs

- `KSI-INR-RIR` — Reviewing Incident Response Procedures
- `KSI-MLA-LET` — Logging Event Types

### `si-5` — 2 KSIs

- `KSI-SCR-MON` — Monitoring Supply Chain Risk
- `KSI-SVC-ACM` — Automating Configuration Management

### `si-8` — 2 KSIs

- `KSI-CNA-RNT` — Restricting Network Traffic
- `KSI-CNA-RVP` — Reviewing Protections

### `si-10` — 2 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `si-16` — 2 KSIs

- `KSI-CNA-MAT` — Minimizing Attack Surface
- `KSI-PIY-RSD` — Reviewing Security in the SDLC

### `sr-5` — 2 KSIs

- `KSI-SCR-MIT` — Mitigating Supply Chain Risk
- `KSI-SCR-MON` — Monitoring Supply Chain Risk

### `sr-6` — 2 KSIs

- `KSI-SCR-MIT` — Mitigating Supply Chain Risk
- `KSI-SCR-MON` — Monitoring Supply Chain Risk

## 5. Highest-Impact Class C Controls

These are the Class C baseline controls with the greatest number of KSI references.

- `sc-23` → **6 KSIs**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-SIN, KSI-SVC-VCM, KSI-SVC-VRI
- `ac-17.3` → **5 KSIs**: KSI-CNA-IBP, KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN, KSI-IAM-ELP
- `ac-20.1` → **5 KSIs**: KSI-CNA-MAT, KSI-IAM-ELP, KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-OSM
- `cm-2` → **5 KSIs**: KSI-CMT-RMV, KSI-CNA-DFP, KSI-CNA-IBP, KSI-MLA-EVC, KSI-SVC-ACM
- `ac-2` → **4 KSIs**: KSI-IAM-APM, KSI-IAM-JIT, KSI-IAM-SNU, KSI-IAM-SUS
- `ac-2.4` → **4 KSIs**: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL, KSI-SVC-ACM
- `au-2` → **4 KSIs**: KSI-CMT-LMC, KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- `cm-3` → **4 KSIs**: KSI-CMT-LMC, KSI-CMT-RMV, KSI-CMT-RVP, KSI-CMT-VTD
- `cm-6` → **4 KSIs**: KSI-CMT-LMC, KSI-CMT-RMV, KSI-MLA-EVC, KSI-SVC-ACM
- `cm-7.1` → **4 KSIs**: KSI-CMT-RVP, KSI-CNA-RNT, KSI-SVC-ACM, KSI-SVC-EIS
- `cp-10` → **4 KSIs**: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- `ia-5.2` → **4 KSIs**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-SNU, KSI-SVC-ASM
- `ir-4.1` → **4 KSIs**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI, KSI-MLA-OSM
- `sc-4` → **4 KSIs**: KSI-CNA-ULN, KSI-IAM-ELP, KSI-PIY-RSD, KSI-SVC-PRR
- `ac-2.2` → **3 KSIs**: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SNU
- `ac-2.3` → **3 KSIs**: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SUS
- `ac-3` → **3 KSIs**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT
- `ac-4` → **3 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SNU
- `ac-5` → **3 KSIs**: KSI-IAM-JIT, KSI-PIY-RIS, KSI-PIY-RSD
- `ac-6.9` → **3 KSIs**: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL
- `ac-17.1` → **3 KSIs**: KSI-IAM-ELP, KSI-MLA-LET, KSI-MLA-OSM
- `ac-17.2` → **3 KSIs**: KSI-IAM-ELP, KSI-SVC-ASM, KSI-SVC-SIN
- `ac-20` → **3 KSIs**: KSI-IAM-ELP, KSI-SCR-MIT, KSI-SCR-MON
- `ca-9` → **3 KSIs**: KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN
- `cm-2.2` → **3 KSIs**: KSI-PIY-GIV, KSI-SVC-ACM, KSI-SVC-VRI
- `cm-3.2` → **3 KSIs**: KSI-CMT-LMC, KSI-CMT-RVP, KSI-CMT-VTD
- `cm-5` → **3 KSIs**: KSI-CMT-RMV, KSI-CMT-RVP, KSI-IAM-JIT
- `cm-9` → **3 KSIs**: KSI-CMT-RVP, KSI-IAM-ELP, KSI-IAM-JIT
- `cp-2.1` → **3 KSIs**: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- `cp-2.3` → **3 KSIs**: KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- `cp-4.1` → **3 KSIs**: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- `cp-6` → **3 KSIs**: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-TRC
- `ia-4.4` → **3 KSIs**: KSI-IAM-AAM, KSI-IAM-ELP, KSI-IAM-JIT
- `ia-5.6` → **3 KSIs**: KSI-IAM-APM, KSI-IAM-ELP, KSI-SVC-ASM
- `ir-3` → **3 KSIs**: KSI-INR-AAR, KSI-INR-RPI, KSI-RPL-TRC
- `ir-4` → **3 KSIs**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- `ir-8` → **3 KSIs**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- `ps-4` → **3 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SUS
- `ps-6` → **3 KSIs**: KSI-CED-RAT, KSI-IAM-ELP, KSI-IAM-JIT
- `sc-8` → **3 KSIs**: KSI-CNA-MAT, KSI-CNA-ULN, KSI-SVC-SIN
- `sc-39` → **3 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-EIS
- `si-3` → **3 KSIs**: KSI-CMT-RMV, KSI-CNA-DFP, KSI-IAM-ELP
- `si-4.4` → **3 KSIs**: KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- `si-7.1` → **3 KSIs**: KSI-SCR-MIT, KSI-SVC-VCM, KSI-SVC-VRI
- `si-7.7` → **3 KSIs**: KSI-MLA-EVC, KSI-MLA-LET, KSI-MLA-OSM
- `si-11` → **3 KSIs**: KSI-CNA-MAT, KSI-MLA-ALA, KSI-PIY-RSD
- `sr-10` → **3 KSIs**: KSI-SVC-ACM, KSI-SVC-EIS, KSI-SVC-VRI
- `ac-2.1` → **2 KSIs**: KSI-IAM-JIT, KSI-IAM-SUS
- `ac-2.13` → **2 KSIs**: KSI-IAM-AAM, KSI-IAM-SUS
- `ac-6` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `ac-6.5` → **2 KSIs**: KSI-IAM-JIT, KSI-IAM-SNU
- `ac-6.7` → **2 KSIs**: KSI-IAM-AAM, KSI-IAM-JIT
- `ac-7` → **2 KSIs**: KSI-IAM-JIT, KSI-IAM-SUS
- `ac-12` → **2 KSIs**: KSI-CNA-ULN, KSI-IAM-ELP
- `ac-17` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `au-6.1` → **2 KSIs**: KSI-MLA-OSM, KSI-MLA-RVL
- `au-7.1` → **2 KSIs**: KSI-MLA-LET, KSI-MLA-OSM
- `cm-2.3` → **2 KSIs**: KSI-RPL-ABO, KSI-SVC-ACM
- `cm-3.4` → **2 KSIs**: KSI-CMT-RVP, KSI-PIY-RSD
- `cm-4.2` → **2 KSIs**: KSI-CMT-LMC, KSI-CMT-VTD
- `cm-7` → **2 KSIs**: KSI-CMT-RMV, KSI-IAM-JIT
- `cm-7.5` → **2 KSIs**: KSI-IAM-JIT, KSI-PIY-GIV
- `cm-8.1` → **2 KSIs**: KSI-CMT-RMV, KSI-PIY-GIV
- `cm-8.3` → **2 KSIs**: KSI-CMT-LMC, KSI-SVC-VRI
- `cm-12.1` → **2 KSIs**: KSI-PIY-GIV, KSI-SVC-EIS
- `cp-6.1` → **2 KSIs**: KSI-RPL-ARP, KSI-RPL-TRC
- `cp-10.2` → **2 KSIs**: KSI-RPL-ABO, KSI-RPL-ARP
- `ia-2` → **2 KSIs**: KSI-IAM-APM, KSI-IAM-ELP
- `ia-3` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-SNU
- `ia-4` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `ir-3.2` → **2 KSIs**: KSI-PIY-RIS, KSI-RPL-TRC
- `ir-6.3` → **2 KSIs**: KSI-INR-RIR, KSI-SCR-MON
- `ma-2` → **2 KSIs**: KSI-CMT-LMC, KSI-SVC-EIS
- `pl-8` → **2 KSIs**: KSI-PIY-RSD, KSI-SVC-EIS
- `pl-10` → **2 KSIs**: KSI-CNA-IBP, KSI-SVC-ACM
- `ps-2` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `ps-3` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `ps-5` → **2 KSIs**: KSI-IAM-ELP, KSI-IAM-JIT
- `ra-5.5` → **2 KSIs**: KSI-IAM-JIT, KSI-IAM-SNU
- `sa-3` → **2 KSIs**: KSI-PIY-RIS, KSI-PIY-RSD
- `sa-9` → **2 KSIs**: KSI-SCR-MIT, KSI-SCR-MON
- `sc-7` → **2 KSIs**: KSI-CNA-ULN, KSI-SVC-EIS
- `sc-7.5` → **2 KSIs**: KSI-CNA-MAT, KSI-CNA-RNT
- `sc-10` → **2 KSIs**: KSI-CNA-MAT, KSI-CNA-ULN
- `sc-13` → **2 KSIs**: KSI-SVC-SIN, KSI-SVC-VRI
- `sc-18` → **2 KSIs**: KSI-PIY-RSD, KSI-SCR-MIT
- `sc-20` → **2 KSIs**: KSI-IAM-ELP, KSI-SVC-SIN
- `sc-21` → **2 KSIs**: KSI-IAM-ELP, KSI-SVC-SIN
- `sc-22` → **2 KSIs**: KSI-IAM-ELP, KSI-SVC-SIN
- `si-4` → **2 KSIs**: KSI-MLA-RVL, KSI-SVC-EIS
- `si-4.5` → **2 KSIs**: KSI-INR-RIR, KSI-MLA-LET
- `si-5` → **2 KSIs**: KSI-SCR-MON, KSI-SVC-ACM
- `si-8` → **2 KSIs**: KSI-CNA-RNT, KSI-CNA-RVP
- `si-10` → **2 KSIs**: KSI-CNA-MAT, KSI-PIY-RSD
- `si-16` → **2 KSIs**: KSI-CNA-MAT, KSI-PIY-RSD
- `sr-5` → **2 KSIs**: KSI-SCR-MIT, KSI-SCR-MON
- `sr-6` → **2 KSIs**: KSI-SCR-MIT, KSI-SCR-MON

## 6. KSI-to-KSI Shared Controls

### `KSI-IAM-ELP` ↔ `KSI-IAM-JIT`

Shared controls (16): `ac-2.6`, `ac-3`, `ac-4`, `ac-6`, `ac-17`, `ac-20.1`, `cm-9`, `ia-4`, `ia-4.4`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `sc-23`, `sc-39`

### `KSI-MLA-LET` ↔ `KSI-MLA-OSM`

Shared controls (6): `ac-17.1`, `ac-20.1`, `au-2`, `au-7.1`, `si-4.4`, `si-7.7`

### `KSI-RPL-ARP` ↔ `KSI-RPL-TRC`

Shared controls (6): `cp-2.1`, `cp-2.3`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-10`

### `KSI-IAM-APM` ↔ `KSI-IAM-ELP`

Shared controls (5): `ac-3`, `ia-2`, `ia-5.2`, `ia-5.6`, `sc-23`

### `KSI-IAM-ELP` ↔ `KSI-SVC-SIN`

Shared controls (5): `ac-17.2`, `sc-20`, `sc-21`, `sc-22`, `sc-23`

### `KSI-IAM-JIT` ↔ `KSI-IAM-SNU`

Shared controls (5): `ac-2`, `ac-2.2`, `ac-4`, `ac-6.5`, `ra-5.5`

### `KSI-IAM-JIT` ↔ `KSI-IAM-SUS`

Shared controls (5): `ac-2`, `ac-2.1`, `ac-2.3`, `ac-7`, `ps-4`

### `KSI-CNA-MAT` ↔ `KSI-CNA-ULN`

Shared controls (4): `ac-17.3`, `ca-9`, `sc-8`, `sc-10`

### `KSI-IAM-AAM` ↔ `KSI-IAM-JIT`

Shared controls (4): `ac-2.2`, `ac-2.3`, `ac-6.7`, `ia-4.4`

### `KSI-INR-AAR` ↔ `KSI-INR-RPI`

Shared controls (4): `ir-3`, `ir-4`, `ir-4.1`, `ir-8`

### `KSI-MLA-LET` ↔ `KSI-MLA-RVL`

Shared controls (4): `ac-2.4`, `ac-6.9`, `au-2`, `si-4.4`

### `KSI-SCR-MIT` ↔ `KSI-SCR-MON`

Shared controls (4): `ac-20`, `sa-9`, `sr-5`, `sr-6`

### `KSI-CMT-LMC` ↔ `KSI-CMT-VTD`

Shared controls (3): `cm-3`, `cm-3.2`, `cm-4.2`

### `KSI-CNA-MAT` ↔ `KSI-CNA-RNT`

Shared controls (3): `ac-17.3`, `ca-9`, `sc-7.5`

### `KSI-CNA-MAT` ↔ `KSI-PIY-RSD`

Shared controls (3): `si-10`, `si-11`, `si-16`

### `KSI-CNA-ULN` ↔ `KSI-IAM-ELP`

Shared controls (3): `ac-12`, `ac-17.3`, `sc-4`

### `KSI-IAM-APM` ↔ `KSI-IAM-JIT`

Shared controls (3): `ac-2`, `ac-3`, `sc-23`

### `KSI-IAM-ELP` ↔ `KSI-IAM-SNU`

Shared controls (3): `ac-4`, `ia-3`, `ia-5.2`

### `KSI-IAM-ELP` ↔ `KSI-SVC-ASM`

Shared controls (3): `ac-17.2`, `ia-5.2`, `ia-5.6`

### `KSI-IAM-JIT` ↔ `KSI-MLA-LET`

Shared controls (3): `ac-2.4`, `ac-6.9`, `ac-20.1`

### `KSI-INR-AAR` ↔ `KSI-INR-RIR`

Shared controls (3): `ir-4`, `ir-4.1`, `ir-8`

### `KSI-INR-RIR` ↔ `KSI-INR-RPI`

Shared controls (3): `ir-4`, `ir-4.1`, `ir-8`

### `KSI-MLA-OSM` ↔ `KSI-MLA-RVL`

Shared controls (3): `au-2`, `au-6.1`, `si-4.4`

### `KSI-PIY-RIS` ↔ `KSI-RPL-TRC`

Shared controls (3): `cp-2.1`, `cp-4.1`, `ir-3.2`

### `KSI-RPL-ABO` ↔ `KSI-RPL-ARP`

Shared controls (3): `cp-6`, `cp-10`, `cp-10.2`

### `KSI-CMT-LMC` ↔ `KSI-CMT-RMV`

Shared controls (2): `cm-3`, `cm-6`

### `KSI-CMT-LMC` ↔ `KSI-CMT-RVP`

Shared controls (2): `cm-3`, `cm-3.2`

### `KSI-CMT-RMV` ↔ `KSI-CMT-RVP`

Shared controls (2): `cm-3`, `cm-5`

### `KSI-CMT-RMV` ↔ `KSI-CNA-DFP`

Shared controls (2): `cm-2`, `si-3`

### `KSI-CMT-RMV` ↔ `KSI-IAM-JIT`

Shared controls (2): `cm-5`, `cm-7`

### `KSI-CMT-RMV` ↔ `KSI-MLA-EVC`

Shared controls (2): `cm-2`, `cm-6`

### `KSI-CMT-RMV` ↔ `KSI-SVC-ACM`

Shared controls (2): `cm-2`, `cm-6`

### `KSI-CMT-RVP` ↔ `KSI-CMT-VTD`

Shared controls (2): `cm-3`, `cm-3.2`

### `KSI-CMT-RVP` ↔ `KSI-IAM-JIT`

Shared controls (2): `cm-5`, `cm-9`

### `KSI-CNA-IBP` ↔ `KSI-SVC-ACM`

Shared controls (2): `cm-2`, `pl-10`

### `KSI-CNA-MAT` ↔ `KSI-IAM-ELP`

Shared controls (2): `ac-17.3`, `ac-20.1`

### `KSI-CNA-RNT` ↔ `KSI-CNA-ULN`

Shared controls (2): `ac-17.3`, `ca-9`

### `KSI-IAM-AAM` ↔ `KSI-IAM-SUS`

Shared controls (2): `ac-2.3`, `ac-2.13`

### `KSI-IAM-APM` ↔ `KSI-IAM-SNU`

Shared controls (2): `ac-2`, `ia-5.2`

### `KSI-IAM-APM` ↔ `KSI-SVC-ASM`

Shared controls (2): `ia-5.2`, `ia-5.6`

### `KSI-IAM-ELP` ↔ `KSI-MLA-LET`

Shared controls (2): `ac-17.1`, `ac-20.1`

### `KSI-IAM-ELP` ↔ `KSI-MLA-OSM`

Shared controls (2): `ac-17.1`, `ac-20.1`

### `KSI-IAM-JIT` ↔ `KSI-MLA-RVL`

Shared controls (2): `ac-2.4`, `ac-6.9`

### `KSI-MLA-EVC` ↔ `KSI-SVC-ACM`

Shared controls (2): `cm-2`, `cm-6`

### `KSI-PIY-RIS` ↔ `KSI-PIY-RSD`

Shared controls (2): `ac-5`, `sa-3`

### `KSI-PIY-RIS` ↔ `KSI-RPL-ARP`

Shared controls (2): `cp-2.1`, `cp-4.1`

### `KSI-RPL-ABO` ↔ `KSI-RPL-TRC`

Shared controls (2): `cp-6`, `cp-10`

### `KSI-RPL-ARP` ↔ `KSI-RPL-RRO`

Shared controls (2): `cp-2.3`, `cp-10`

### `KSI-RPL-RRO` ↔ `KSI-RPL-TRC`

Shared controls (2): `cp-2.3`, `cp-10`

### `KSI-SVC-ACM` ↔ `KSI-SVC-EIS`

Shared controls (2): `cm-7.1`, `sr-10`

### `KSI-SVC-ACM` ↔ `KSI-SVC-VRI`

Shared controls (2): `cm-2.2`, `sr-10`

### `KSI-SVC-SIN` ↔ `KSI-SVC-VRI`

Shared controls (2): `sc-13`, `sc-23`

### `KSI-SVC-VCM` ↔ `KSI-SVC-VRI`

Shared controls (2): `sc-23`, `si-7.1`

### `KSI-CED-RAT` ↔ `KSI-IAM-ELP`

Shared controls (1): `ps-6`

### `KSI-CED-RAT` ↔ `KSI-IAM-JIT`

Shared controls (1): `ps-6`

### `KSI-CMT-LMC` ↔ `KSI-MLA-EVC`

Shared controls (1): `cm-6`

### `KSI-CMT-LMC` ↔ `KSI-MLA-LET`

Shared controls (1): `au-2`

### `KSI-CMT-LMC` ↔ `KSI-MLA-OSM`

Shared controls (1): `au-2`

### `KSI-CMT-LMC` ↔ `KSI-MLA-RVL`

Shared controls (1): `au-2`

### `KSI-CMT-LMC` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-6`

### `KSI-CMT-LMC` ↔ `KSI-SVC-EIS`

Shared controls (1): `ma-2`

### `KSI-CMT-LMC` ↔ `KSI-SVC-VRI`

Shared controls (1): `cm-8.3`

### `KSI-CMT-RMV` ↔ `KSI-CMT-VTD`

Shared controls (1): `cm-3`

### `KSI-CMT-RMV` ↔ `KSI-CNA-IBP`

Shared controls (1): `cm-2`

### `KSI-CMT-RMV` ↔ `KSI-IAM-ELP`

Shared controls (1): `si-3`

### `KSI-CMT-RMV` ↔ `KSI-PIY-GIV`

Shared controls (1): `cm-8.1`

### `KSI-CMT-RVP` ↔ `KSI-CNA-RNT`

Shared controls (1): `cm-7.1`

### `KSI-CMT-RVP` ↔ `KSI-IAM-ELP`

Shared controls (1): `cm-9`

### `KSI-CMT-RVP` ↔ `KSI-PIY-RSD`

Shared controls (1): `cm-3.4`

### `KSI-CMT-RVP` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-7.1`

### `KSI-CMT-RVP` ↔ `KSI-SVC-EIS`

Shared controls (1): `cm-7.1`

### `KSI-CNA-DFP` ↔ `KSI-CNA-IBP`

Shared controls (1): `cm-2`

### `KSI-CNA-DFP` ↔ `KSI-IAM-ELP`

Shared controls (1): `si-3`

### `KSI-CNA-DFP` ↔ `KSI-MLA-EVC`

Shared controls (1): `cm-2`

### `KSI-CNA-DFP` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-2`

### `KSI-CNA-IBP` ↔ `KSI-CNA-MAT`

Shared controls (1): `ac-17.3`

### `KSI-CNA-IBP` ↔ `KSI-CNA-RNT`

Shared controls (1): `ac-17.3`

### `KSI-CNA-IBP` ↔ `KSI-CNA-ULN`

Shared controls (1): `ac-17.3`

### `KSI-CNA-IBP` ↔ `KSI-IAM-ELP`

Shared controls (1): `ac-17.3`

### `KSI-CNA-IBP` ↔ `KSI-MLA-EVC`

Shared controls (1): `cm-2`

### `KSI-CNA-MAT` ↔ `KSI-IAM-JIT`

Shared controls (1): `ac-20.1`

### `KSI-CNA-MAT` ↔ `KSI-MLA-ALA`

Shared controls (1): `si-11`

### `KSI-CNA-MAT` ↔ `KSI-MLA-LET`

Shared controls (1): `ac-20.1`

### `KSI-CNA-MAT` ↔ `KSI-MLA-OSM`

Shared controls (1): `ac-20.1`

### `KSI-CNA-MAT` ↔ `KSI-SVC-SIN`

Shared controls (1): `sc-8`

### `KSI-CNA-RNT` ↔ `KSI-CNA-RVP`

Shared controls (1): `si-8`

### `KSI-CNA-RNT` ↔ `KSI-IAM-ELP`

Shared controls (1): `ac-17.3`

### `KSI-CNA-RNT` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-7.1`

### `KSI-CNA-RNT` ↔ `KSI-SVC-EIS`

Shared controls (1): `cm-7.1`

### `KSI-CNA-ULN` ↔ `KSI-PIY-RSD`

Shared controls (1): `sc-4`

### `KSI-CNA-ULN` ↔ `KSI-SVC-EIS`

Shared controls (1): `sc-7`

### `KSI-CNA-ULN` ↔ `KSI-SVC-PRR`

Shared controls (1): `sc-4`

### `KSI-CNA-ULN` ↔ `KSI-SVC-SIN`

Shared controls (1): `sc-8`

### `KSI-IAM-AAM` ↔ `KSI-IAM-ELP`

Shared controls (1): `ia-4.4`

### `KSI-IAM-AAM` ↔ `KSI-IAM-SNU`

Shared controls (1): `ac-2.2`

### `KSI-IAM-APM` ↔ `KSI-IAM-SUS`

Shared controls (1): `ac-2`

### `KSI-IAM-APM` ↔ `KSI-SVC-SIN`

Shared controls (1): `sc-23`

### `KSI-IAM-APM` ↔ `KSI-SVC-VCM`

Shared controls (1): `sc-23`

### `KSI-IAM-APM` ↔ `KSI-SVC-VRI`

Shared controls (1): `sc-23`

### `KSI-IAM-ELP` ↔ `KSI-IAM-SUS`

Shared controls (1): `ps-4`

### `KSI-IAM-ELP` ↔ `KSI-PIY-RSD`

Shared controls (1): `sc-4`

### `KSI-IAM-ELP` ↔ `KSI-SCR-MIT`

Shared controls (1): `ac-20`

### `KSI-IAM-ELP` ↔ `KSI-SCR-MON`

Shared controls (1): `ac-20`

### `KSI-IAM-ELP` ↔ `KSI-SVC-EIS`

Shared controls (1): `sc-39`

### `KSI-IAM-ELP` ↔ `KSI-SVC-PRR`

Shared controls (1): `sc-4`

### `KSI-IAM-ELP` ↔ `KSI-SVC-VCM`

Shared controls (1): `sc-23`

### `KSI-IAM-ELP` ↔ `KSI-SVC-VRI`

Shared controls (1): `sc-23`

### `KSI-IAM-JIT` ↔ `KSI-MLA-OSM`

Shared controls (1): `ac-20.1`

### `KSI-IAM-JIT` ↔ `KSI-PIY-GIV`

Shared controls (1): `cm-7.5`

### `KSI-IAM-JIT` ↔ `KSI-PIY-RIS`

Shared controls (1): `ac-5`

### `KSI-IAM-JIT` ↔ `KSI-PIY-RSD`

Shared controls (1): `ac-5`

### `KSI-IAM-JIT` ↔ `KSI-SVC-ACM`

Shared controls (1): `ac-2.4`

### `KSI-IAM-JIT` ↔ `KSI-SVC-EIS`

Shared controls (1): `sc-39`

### `KSI-IAM-JIT` ↔ `KSI-SVC-SIN`

Shared controls (1): `sc-23`

### `KSI-IAM-JIT` ↔ `KSI-SVC-VCM`

Shared controls (1): `sc-23`

### `KSI-IAM-JIT` ↔ `KSI-SVC-VRI`

Shared controls (1): `sc-23`

### `KSI-IAM-SNU` ↔ `KSI-IAM-SUS`

Shared controls (1): `ac-2`

### `KSI-IAM-SNU` ↔ `KSI-SVC-ASM`

Shared controls (1): `ia-5.2`

### `KSI-INR-AAR` ↔ `KSI-MLA-OSM`

Shared controls (1): `ir-4.1`

### `KSI-INR-AAR` ↔ `KSI-RPL-TRC`

Shared controls (1): `ir-3`

### `KSI-INR-RIR` ↔ `KSI-MLA-LET`

Shared controls (1): `si-4.5`

### `KSI-INR-RIR` ↔ `KSI-MLA-OSM`

Shared controls (1): `ir-4.1`

### `KSI-INR-RIR` ↔ `KSI-SCR-MON`

Shared controls (1): `ir-6.3`

### `KSI-INR-RPI` ↔ `KSI-MLA-OSM`

Shared controls (1): `ir-4.1`

### `KSI-INR-RPI` ↔ `KSI-RPL-TRC`

Shared controls (1): `ir-3`

### `KSI-MLA-ALA` ↔ `KSI-PIY-RSD`

Shared controls (1): `si-11`

### `KSI-MLA-EVC` ↔ `KSI-MLA-LET`

Shared controls (1): `si-7.7`

### `KSI-MLA-EVC` ↔ `KSI-MLA-OSM`

Shared controls (1): `si-7.7`

### `KSI-MLA-LET` ↔ `KSI-SVC-ACM`

Shared controls (1): `ac-2.4`

### `KSI-MLA-RVL` ↔ `KSI-SVC-ACM`

Shared controls (1): `ac-2.4`

### `KSI-MLA-RVL` ↔ `KSI-SVC-EIS`

Shared controls (1): `si-4`

### `KSI-PIY-GIV` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-2.2`

### `KSI-PIY-GIV` ↔ `KSI-SVC-EIS`

Shared controls (1): `cm-12.1`

### `KSI-PIY-GIV` ↔ `KSI-SVC-VRI`

Shared controls (1): `cm-2.2`

### `KSI-PIY-RSD` ↔ `KSI-SCR-MIT`

Shared controls (1): `sc-18`

### `KSI-PIY-RSD` ↔ `KSI-SVC-EIS`

Shared controls (1): `pl-8`

### `KSI-PIY-RSD` ↔ `KSI-SVC-PRR`

Shared controls (1): `sc-4`

### `KSI-RPL-ABO` ↔ `KSI-RPL-RRO`

Shared controls (1): `cp-10`

### `KSI-RPL-ABO` ↔ `KSI-SVC-ACM`

Shared controls (1): `cm-2.3`

### `KSI-SCR-MIT` ↔ `KSI-SVC-VCM`

Shared controls (1): `si-7.1`

### `KSI-SCR-MIT` ↔ `KSI-SVC-VRI`

Shared controls (1): `si-7.1`

### `KSI-SCR-MON` ↔ `KSI-SVC-ACM`

Shared controls (1): `si-5`

### `KSI-SVC-ASM` ↔ `KSI-SVC-SIN`

Shared controls (1): `ac-17.2`

### `KSI-SVC-EIS` ↔ `KSI-SVC-VRI`

Shared controls (1): `sr-10`

### `KSI-SVC-SIN` ↔ `KSI-SVC-VCM`

Shared controls (1): `sc-23`

## 7. Control Identifier Normalization

KSI mappings use normalized lowercase identifiers such as `ac-3`, while Rev5 baseline lists use identifiers such as `AC-03`.

The schema defines these as different identifier formats:

- `control_id` → lowercase form such as `ac-3` or `ac-6.1`
- `rev5_control_id` → Rev5 form such as `AC-03` or `AC-06 (01)`

Therefore literal string comparison is insufficient. This analysis normalizes the identifiers before determining Class C membership.

For example:

`ac-3` → `AC-03`

`ac-6.1` → `AC-06 (01)`

## 8. Implementation and Evidence Implications

A control referenced by multiple KSIs represents a potential high-impact implementation area. A common underlying capability may support several KSI expectations.

However, shared control membership does not automatically mean that one piece of evidence satisfies every KSI. Evidence must still demonstrate the specific KSI statement and applicable requirements.

The Class C shared-control set is therefore useful for prioritizing centralized implementation, continuous validation, and evidence planning.

## 9. Findings

- **46 KSIs** analyzed.
- **98 controls** are shared by multiple KSIs.
- **97 shared controls** are also present in the Rev5 Class C baseline.

- Highest Class C overlap: **`sc-23`**, referenced by **6 KSIs**.
- `ac-3` is treated as the normalized representation of Rev5 `AC-03`.
- Absence of a control from the `CTL` object does not mean that the control is absent from the Class C baseline; baseline membership is represented through `rev5_controls_list`.

## 10. Next Analytical Layer

The natural next layer is to trace each Class C KSI requirement from KSI → normalized control → Rev5 Class C baseline → applicable rule/evidence. This moves the analysis from mapping into implementation and validation.
