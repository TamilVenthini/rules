# FedRAMP 2026 Class C Deep Dive

> Generated directly from `fedramp-consolidated-rules.json` and its schema. No external assumptions added.

## 1. Executive Facts

- KSI indicators: **46**
- Class C baseline controls: **322** normalized IDs
- Controls referenced by multiple KSIs: **98**
- Shared controls intersecting Class C baseline: **97**
- KSI families represented: **10**

## 2. Class C Baseline — All Families

### AC — 43 controls

AC-01, AC-02, AC-02 (01), AC-02 (02), AC-02 (03), AC-02 (04), AC-02 (05), AC-02 (07), AC-02 (09), AC-02 (12), AC-02 (13), AC-03, AC-04, AC-04 (21), AC-05, AC-06, AC-06 (01), AC-06 (02), AC-06 (05), AC-06 (07), AC-06 (09), AC-06 (10), AC-07, AC-08, AC-11, AC-11 (01), AC-12, AC-14, AC-17, AC-17 (01), AC-17 (02), AC-17 (03), AC-17 (04), AC-18, AC-18 (01), AC-18 (03), AC-19, AC-19 (05), AC-20, AC-20 (01), AC-20 (02), AC-21, AC-22

### AT — 6 controls

AT-01, AT-02, AT-02 (02), AT-02 (03), AT-03, AT-04

### AU — 16 controls

AU-01, AU-02, AU-03, AU-03 (01), AU-04, AU-05, AU-06, AU-06 (01), AU-06 (03), AU-07, AU-07 (01), AU-08, AU-09, AU-09 (04), AU-11, AU-12

### CA — 13 controls

CA-01, CA-02, CA-02 (01), CA-02 (03), CA-03, CA-06, CA-07, CA-07 (01), CA-07 (04), CA-08, CA-08 (01), CA-08 (02), CA-09

### CM — 27 controls

CM-01, CM-02, CM-02 (02), CM-02 (03), CM-02 (07), CM-03, CM-03 (02), CM-03 (04), CM-04, CM-04 (02), CM-05, CM-05 (01), CM-05 (05), CM-06, CM-06 (01), CM-07, CM-07 (01), CM-07 (02), CM-07 (05), CM-08, CM-08 (01), CM-08 (03), CM-09, CM-10, CM-11, CM-12, CM-12 (01)

### CP — 23 controls

CP-01, CP-02, CP-02 (01), CP-02 (03), CP-02 (08), CP-03, CP-04, CP-04 (01), CP-06, CP-06 (01), CP-06 (03), CP-07, CP-07 (01), CP-07 (02), CP-07 (03), CP-08, CP-08 (01), CP-08 (02), CP-09, CP-09 (01), CP-09 (08), CP-10, CP-10 (02)

### IA — 27 controls

IA-01, IA-02, IA-02 (01), IA-02 (02), IA-02 (05), IA-02 (06), IA-02 (08), IA-02 (12), IA-03, IA-04, IA-04 (04), IA-05, IA-05 (01), IA-05 (02), IA-05 (06), IA-05 (07), IA-06, IA-07, IA-08, IA-08 (01), IA-08 (02), IA-08 (04), IA-11, IA-12, IA-12 (02), IA-12 (03), IA-12 (05)

### IR — 17 controls

IR-01, IR-02, IR-03, IR-03 (02), IR-04, IR-04 (01), IR-05, IR-06, IR-06 (01), IR-06 (03), IR-07, IR-07 (01), IR-08, IR-09, IR-09 (02), IR-09 (03), IR-09 (04)

### MA — 10 controls

MA-01, MA-02, MA-03, MA-03 (01), MA-03 (02), MA-03 (03), MA-04, MA-05, MA-05 (01), MA-06

### MP — 7 controls

MP-01, MP-02, MP-03, MP-04, MP-05, MP-06, MP-07

### PE — 19 controls

PE-01, PE-02, PE-03, PE-04, PE-05, PE-06, PE-06 (01), PE-08, PE-09, PE-10, PE-11, PE-12, PE-13, PE-13 (01), PE-13 (02), PE-14, PE-15, PE-16, PE-17

### PL — 7 controls

PL-01, PL-02, PL-04, PL-04 (01), PL-08, PL-10, PL-11

### PS — 10 controls

PS-01, PS-02, PS-03, PS-03 (03), PS-04, PS-05, PS-06, PS-07, PS-08, PS-09

### RA — 11 controls

RA-01, RA-02, RA-03, RA-03 (01), RA-05, RA-05 (02), RA-05 (03), RA-05 (05), RA-05 (11), RA-07, RA-09

### SA — 21 controls

SA-01, SA-02, SA-03, SA-04, SA-04 (01), SA-04 (02), SA-04 (09), SA-04 (10), SA-05, SA-08, SA-09, SA-09 (01), SA-09 (02), SA-09 (05), SA-10, SA-11, SA-11 (01), SA-11 (02), SA-15, SA-15 (03), SA-22

### SC — 29 controls

SC-01, SC-02, SC-04, SC-05, SC-07, SC-07 (03), SC-07 (04), SC-07 (05), SC-07 (07), SC-07 (08), SC-07 (12), SC-07 (18), SC-08, SC-08 (01), SC-10, SC-12, SC-13, SC-15, SC-17, SC-18, SC-20, SC-21, SC-22, SC-23, SC-28, SC-28 (01), SC-39, SC-45, SC-45 (01)

### SI — 24 controls

SI-01, SI-02, SI-02 (02), SI-02 (03), SI-03, SI-04, SI-04 (01), SI-04 (02), SI-04 (04), SI-04 (05), SI-04 (16), SI-04 (18), SI-04 (23), SI-05, SI-06, SI-07, SI-07 (01), SI-07 (07), SI-08, SI-08 (02), SI-10, SI-11, SI-12, SI-16

### SR — 12 controls

SR-01, SR-02, SR-02 (01), SR-03, SR-05, SR-06, SR-08, SR-10, SR-11, SR-11 (01), SR-11 (02), SR-12

## 3. Every KSI

### KSI-CED-RAT — Reviewing All Training

**Family:** `CED`

**Statement:** The effectiveness of relevant cybersecurity education and training is persistently reviewed, including at least general training for all employees, role-specific training for employees in high risk roles, training for development and engineering staff on secure software delivery, and training for staff involved with incident response or disaster recovery.

**Terms:** Incident, Persistently, Vulnerability Response

**Controls:** 11

`cp-3`, `ir-2`, `ps-6`, `at-2`, `at-2.2`, `at-2.3`, `at-3.5`, `at-4`, `ir-2.3`, `at-3`, `sr-11.1`

**Controls matching Class C baseline:** 9

`cp-3`, `ir-2`, `ps-6`, `at-2`, `at-2.2`, `at-2.3`, `at-4`, `at-3`, `sr-11.1`

### KSI-CMT-LMC — Logging Changes

**Family:** `CMT`

**Statement:** Modifications to the cloud service offering are logged and monitored.

**Terms:** Cloud Service Offering

**Controls:** 7

`au-2`, `cm-3`, `cm-3.2`, `cm-4.2`, `cm-6`, `cm-8.3`, `ma-2`

**Controls matching Class C baseline:** 7

`au-2`, `cm-3`, `cm-3.2`, `cm-4.2`, `cm-6`, `cm-8.3`, `ma-2`

### KSI-CMT-RMV — Redeploying vs Modifying

**Family:** `CMT`

**Statement:** Changes to machine-based information resources are executed through the redeployment of version controlled resources rather than direct modification wherever reasonable.

**Terms:** Information Resource, Machine-Based (Information Resources)

**Controls:** 7

`cm-2`, `cm-3`, `cm-5`, `cm-6`, `cm-7`, `cm-8.1`, `si-3`

**Controls matching Class C baseline:** 7

`cm-2`, `cm-3`, `cm-5`, `cm-6`, `cm-7`, `cm-8.1`, `si-3`

### KSI-CMT-RVP — Reviewing Change Procedures

**Family:** `CMT`

**Statement:** The effectiveness of documented change management procedures is persistently reviewed.

**Terms:** Persistently

**Controls:** 6

`cm-3`, `cm-3.2`, `cm-3.4`, `cm-5`, `cm-7.1`, `cm-9`

**Controls matching Class C baseline:** 6

`cm-3`, `cm-3.2`, `cm-3.4`, `cm-5`, `cm-7.1`, `cm-9`

### KSI-CMT-VTD — Validating Throughout Deployment

**Family:** `CMT`

**Statement:** Persistent testing and validation of changes throughout deployment is automated.

**Terms:** Persistently, Validation

**Controls:** 4

`cm-3`, `cm-3.2`, `cm-4.2`, `si-2`

**Controls matching Class C baseline:** 4

`cm-3`, `cm-3.2`, `cm-4.2`, `si-2`

### KSI-CNA-DFP — Defining Functionality and Privileges

**Family:** `CNA`

**Statement:** The functionality and privileges for infrastructure and services are strictly defined.

**Controls:** 2

`cm-2`, `si-3`

**Controls matching Class C baseline:** 2

`cm-2`, `si-3`

### KSI-CNA-EIS — Enforcing Intended State

**Family:** `CNA`

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 2

`ca-2.1`, `ca-7.1`

**Controls matching Class C baseline:** 2

`ca-2.1`, `ca-7.1`

### KSI-CNA-IBP — Implementing Best Practices

**Family:** `CNA`

**Statement:** The use and configuration of third-party machine-based information resources is persistently compared against the original provider's best practices and guidance.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently, Provider

**Controls:** 3

`ac-17.3`, `cm-2`, `pl-10`

**Controls matching Class C baseline:** 3

`ac-17.3`, `cm-2`, `pl-10`

### KSI-CNA-MAT — Minimizing Attack Surface

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they have a minimal attack surface and that lateral movement is minimized if compromised.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 14

`ac-17.3`, `ac-18.1`, `ac-18.3`, `ac-20.1`, `ca-9`, `sc-7.3`, `sc-7.4`, `sc-7.5`, `sc-7.8`, `sc-8`, `sc-10`, `si-10`, `si-11`, `si-16`

**Controls matching Class C baseline:** 14

`ac-17.3`, `ac-18.1`, `ac-18.3`, `ac-20.1`, `ca-9`, `sc-7.3`, `sc-7.4`, `sc-7.5`, `sc-7.8`, `sc-8`, `sc-10`, `si-10`, `si-11`, `si-16`

### KSI-CNA-OFA — Optimizing for Availability

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they are appropriately optimized for high availability and rapid recovery.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 0

``

**Controls matching Class C baseline:** 0

### KSI-CNA-RNT — Restricting Network Traffic

**Family:** `CNA`

**Statement:** Machine-based information resources are persistently reviewed to ensure they are appropriately configured to limit inbound and outbound network traffic.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 5

`ac-17.3`, `ca-9`, `cm-7.1`, `sc-7.5`, `si-8`

**Controls matching Class C baseline:** 5

`ac-17.3`, `ca-9`, `cm-7.1`, `sc-7.5`, `si-8`

### KSI-CNA-RVP — Reviewing Protections

**Family:** `CNA`

**Statement:** The effectiveness of protection against denial of service attacks and other unwanted activity for machine-based information resources is persistently reviewed.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 3

`sc-5`, `si-8`, `si-8.2`

**Controls matching Class C baseline:** 3

`sc-5`, `si-8`, `si-8.2`

### KSI-CNA-ULN — Using Logical Networking

**Family:** `CNA`

**Statement:** Logical networking and related capabilities are used and persistently reviewed to enforce traffic flow controls.

**Terms:** Persistently

**Controls:** 8

`ac-12`, `ac-17.3`, `ca-9`, `sc-4`, `sc-7`, `sc-7.7`, `sc-8`, `sc-10`

**Controls matching Class C baseline:** 8

`ac-12`, `ac-17.3`, `ca-9`, `sc-4`, `sc-7`, `sc-7.7`, `sc-8`, `sc-10`

### KSI-IAM-AAM — Automating Account Management

**Family:** `IAM`

**Statement:** The lifecycle and privileges of all accounts, roles, and groups are securely managed using automation.

**Controls:** 9

`ac-2.2`, `ac-2.3`, `ac-2.13`, `ac-6.7`, `ia-4.4`, `ia-12`, `ia-12.2`, `ia-12.3`, `ia-12.5`

**Controls matching Class C baseline:** 9

`ac-2.2`, `ac-2.3`, `ac-2.13`, `ac-6.7`, `ia-4.4`, `ia-12`, `ia-12.2`, `ia-12.3`, `ia-12.5`

### KSI-IAM-APM — Adopting Passwordless Methods

**Family:** `IAM`

**Statement:** Secure passwordless methods are used for user authentication and authorization when feasible, otherwise strong passwords with phishing-resistant MFA is used.

**Controls:** 13

`ac-3`, `ia-5.1`, `ia-5.2`, `ia-5.6`, `ia-6`, `ac-2`, `ia-2`, `ia-2.1`, `ia-2.2`, `ia-2.8`, `ia-5`, `ia-8`, `sc-23`

**Controls matching Class C baseline:** 13

`ac-3`, `ia-5.1`, `ia-5.2`, `ia-5.6`, `ia-6`, `ac-2`, `ia-2`, `ia-2.1`, `ia-2.2`, `ia-2.8`, `ia-5`, `ia-8`, `sc-23`

### KSI-IAM-ELP — Ensuring Least Privilege

**Family:** `IAM`

**Statement:** Identity and access management measures are used and persistently reviewed to ensure each user or device can only access the resources they need.

**Terms:** Persistently

**Controls:** 34

`ac-2.5`, `ac-2.6`, `ac-3`, `ac-4`, `ac-6`, `ac-12`, `ac-14`, `ac-17`, `ac-17.1`, `ac-17.2`, `ac-17.3`, `ac-20`, `ac-20.1`, `cm-2.7`, `cm-9`, `ia-2`, `ia-3`, `ia-4`, `ia-4.4`, `ia-5.2`, `ia-5.6`, `ia-11`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `sc-4`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-39`, `si-3`

**Controls matching Class C baseline:** 33

`ac-2.5`, `ac-3`, `ac-4`, `ac-6`, `ac-12`, `ac-14`, `ac-17`, `ac-17.1`, `ac-17.2`, `ac-17.3`, `ac-20`, `ac-20.1`, `cm-2.7`, `cm-9`, `ia-2`, `ia-3`, `ia-4`, `ia-4.4`, `ia-5.2`, `ia-5.6`, `ia-11`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `sc-4`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-39`, `si-3`

### KSI-IAM-JIT — Authorizing Just-in-Time

**Family:** `IAM`

**Statement:** A least-privileged, role and attribute-based, and just-in-time security authorization model is used and persistently reviewed for all user and non-user accounts and services.

**Terms:** Persistently

**Controls:** 38

`ac-2`, `ac-2.1`, `ac-2.2`, `ac-2.3`, `ac-2.4`, `ac-2.6`, `ac-3`, `ac-4`, `ac-5`, `ac-6`, `ac-6.1`, `ac-6.2`, `ac-6.5`, `ac-6.7`, `ac-6.9`, `ac-6.10`, `ac-7`, `ac-20.1`, `ac-17`, `au-9.4`, `cm-5`, `cm-7`, `cm-7.2`, `cm-7.5`, `cm-9`, `ia-4`, `ia-4.4`, `ia-7`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `ps-9`, `ra-5.5`, `sc-2`, `sc-23`, `sc-39`

**Controls matching Class C baseline:** 37

`ac-2`, `ac-2.1`, `ac-2.2`, `ac-2.3`, `ac-2.4`, `ac-3`, `ac-4`, `ac-5`, `ac-6`, `ac-6.1`, `ac-6.2`, `ac-6.5`, `ac-6.7`, `ac-6.9`, `ac-6.10`, `ac-7`, `ac-20.1`, `ac-17`, `au-9.4`, `cm-5`, `cm-7`, `cm-7.2`, `cm-7.5`, `cm-9`, `ia-4`, `ia-4.4`, `ia-7`, `ps-2`, `ps-3`, `ps-4`, `ps-5`, `ps-6`, `ps-9`, `ra-5.5`, `sc-2`, `sc-23`, `sc-39`

### KSI-IAM-SNU — Securing Non-User Authentication

**Family:** `IAM`

**Statement:** Appropriately secure authentication methods are used and persistently reviewed for non-user accounts and services.

**Terms:** Persistently

**Controls:** 7

`ac-2`, `ac-2.2`, `ac-4`, `ac-6.5`, `ia-3`, `ia-5.2`, `ra-5.5`

**Controls matching Class C baseline:** 7

`ac-2`, `ac-2.2`, `ac-4`, `ac-6.5`, `ia-3`, `ia-5.2`, `ra-5.5`

### KSI-IAM-SUS — Responding to Suspicious Activity

**Family:** `IAM`

**Statement:** Accounts with privileged access are disabled or otherwise secured in response to suspicious activity.

**Terms:** Vulnerability Response

**Controls:** 7

`ac-2`, `ac-2.1`, `ac-2.3`, `ac-2.13`, `ac-7`, `ps-4`, `ps-8`

**Controls matching Class C baseline:** 7

`ac-2`, `ac-2.1`, `ac-2.3`, `ac-2.13`, `ac-7`, `ps-4`, `ps-8`

### KSI-INR-AAR — Generating After Action Reports

**Family:** `INR`

**Statement:** Incident after action reports are generated and lessons learned are persistently incorporated.

**Terms:** Incident, Persistently

**Controls:** 4

`ir-3`, `ir-4`, `ir-4.1`, `ir-8`

**Controls matching Class C baseline:** 4

`ir-3`, `ir-4`, `ir-4.1`, `ir-8`

### KSI-INR-RIR — Reviewing Incident Response Procedures

**Family:** `INR`

**Statement:** The effectiveness of documented incident response procedures is persistently reviewed.

**Terms:** Incident, Persistently, Vulnerability Response

**Controls:** 10

`ir-4`, `ir-4.1`, `ir-6`, `ir-6.1`, `ir-6.3`, `ir-7`, `ir-7.1`, `ir-8`, `ir-8.1`, `si-4.5`

**Controls matching Class C baseline:** 9

`ir-4`, `ir-4.1`, `ir-6`, `ir-6.1`, `ir-6.3`, `ir-7`, `ir-7.1`, `ir-8`, `si-4.5`

### KSI-INR-RPI — Reviewing Past Incidents

**Family:** `INR`

**Statement:** Past incidents are persistently reviewed for patterns or vulnerabilities that were not previously apparent or identified.

**Terms:** Incident, Persistently, Vulnerability

**Controls:** 5

`ir-3`, `ir-4`, `ir-4.1`, `ir-5`, `ir-8`

**Controls matching Class C baseline:** 5

`ir-3`, `ir-4`, `ir-4.1`, `ir-5`, `ir-8`

### KSI-MLA-ALA — Authorizing Log Access

**Family:** `MLA`

**Terms:** Persistently

**Controls:** 1

`si-11`

**Controls matching Class C baseline:** 1

`si-11`

### KSI-MLA-EVC — Evaluating Configurations

**Family:** `MLA`

**Statement:** The configuration of machine-based information resources, especially infrastructure as code, is persistently evaluated and tested.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 4

`ca-7`, `cm-2`, `cm-6`, `si-7.7`

**Controls matching Class C baseline:** 4

`ca-7`, `cm-2`, `cm-6`, `si-7.7`

### KSI-MLA-LET — Logging Event Types

**Family:** `MLA`

**Statement:** A list of information resources and event types that will be logged, monitored, and audited is maintained and persistently reviewed to ensure these activities occur.

**Terms:** Information Resource, Persistently

**Controls:** 10

`ac-2.4`, `ac-6.9`, `ac-17.1`, `ac-20.1`, `au-2`, `au-7.1`, `au-12`, `si-4.4`, `si-4.5`, `si-7.7`

**Controls matching Class C baseline:** 10

`ac-2.4`, `ac-6.9`, `ac-17.1`, `ac-20.1`, `au-2`, `au-7.1`, `au-12`, `si-4.4`, `si-4.5`, `si-7.7`

### KSI-MLA-OSM — Operating SIEM Capability

**Family:** `MLA`

**Statement:** A Security Information and Event Management (SIEM) or similar system(s) is used and persistently reviewed for centralized, tamper-resistant logging of events, activities, and changes.

**Terms:** Persistently

**Controls:** 18

`ac-17.1`, `ac-20.1`, `au-2`, `au-3`, `au-3.1`, `au-4`, `au-5`, `au-6.1`, `au-6.3`, `au-7`, `au-7.1`, `au-8`, `au-9`, `au-11`, `ir-4.1`, `si-4.2`, `si-4.4`, `si-7.7`

**Controls matching Class C baseline:** 18

`ac-17.1`, `ac-20.1`, `au-2`, `au-3`, `au-3.1`, `au-4`, `au-5`, `au-6.1`, `au-6.3`, `au-7`, `au-7.1`, `au-8`, `au-9`, `au-11`, `ir-4.1`, `si-4.2`, `si-4.4`, `si-7.7`

### KSI-MLA-RVL — Reviewing Logs

**Family:** `MLA`

**Statement:** Logs are persistently reviewed and audited.

**Terms:** Persistently

**Controls:** 7

`ac-2.4`, `ac-6.9`, `au-2`, `au-6`, `au-6.1`, `si-4`, `si-4.4`

**Controls matching Class C baseline:** 7

`ac-2.4`, `ac-6.9`, `au-2`, `au-6`, `au-6.1`, `si-4`, `si-4.4`

### KSI-PIY-GIV — Generating Inventories

**Family:** `PIY`

**Statement:** Authoritative sources are used to automatically generate real-time inventories of all information resources when needed.

**Terms:** Information Resource

**Controls:** 7

`cm-2.2`, `cm-7.5`, `cm-8`, `cm-8.1`, `cm-12`, `cm-12.1`, `cp-2.8`

**Controls matching Class C baseline:** 7

`cm-2.2`, `cm-7.5`, `cm-8`, `cm-8.1`, `cm-12`, `cm-12.1`, `cp-2.8`

### KSI-PIY-RES — Reviewing Executive Support

**Family:** `PIY`

**Statement:** Executive support for achieving the provider's security goals is persistently reviewed and demonstrated.

**Terms:** Persistently, Provider

**Controls:** 0

``

**Controls matching Class C baseline:** 0

### KSI-PIY-RIS — Reviewing Investments in Security

**Family:** `PIY`

**Statement:** The effectiveness of the provider's investments in achieving security goals is persistently reviewed.

**Terms:** Persistently, Provider

**Controls:** 9

`ac-5`, `ca-2`, `cp-2.1`, `cp-4.1`, `ir-3.2`, `pm-3`, `sa-2`, `sa-3`, `sr-2.1`

**Controls matching Class C baseline:** 8

`ac-5`, `ca-2`, `cp-2.1`, `cp-4.1`, `ir-3.2`, `sa-2`, `sa-3`, `sr-2.1`

### KSI-PIY-RSD — Reviewing Security in the SDLC

**Family:** `PIY`

**Statement:** The effectiveness of building security and privacy considerations into the Software Development Lifecycle and aligning with CISA Secure By Design principles is persistently reviewed.

**Terms:** Persistently

**Controls:** 12

`ac-5`, `au-3.3`, `cm-3.4`, `pl-8`, `pm-7`, `sa-3`, `sa-8`, `sc-4`, `sc-18`, `si-10`, `si-11`, `si-16`

**Controls matching Class C baseline:** 10

`ac-5`, `cm-3.4`, `pl-8`, `sa-3`, `sa-8`, `sc-4`, `sc-18`, `si-10`, `si-11`, `si-16`

### KSI-PIY-RVD — Reviewing Vulnerability Disclosures

**Family:** `PIY`

**Statement:** The effectiveness of the provider's vulnerability disclosure program is persistently reviewed.

**Terms:** Persistently, Provider, Vulnerability

**Controls:** 1

`ra-5.11`

**Controls matching Class C baseline:** 1

`ra-5.11`

### KSI-RPL-ABO — Aligning Backups with Objectives

**Family:** `RPL`

**Statement:** The alignment of machine-based information resource backups with defined recovery objectives is persistently reviewed.

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 6

`cm-2.3`, `cp-6`, `cp-9`, `cp-10`, `cp-10.2`, `si-12`

**Controls matching Class C baseline:** 6

`cm-2.3`, `cp-6`, `cp-9`, `cp-10`, `cp-10.2`, `si-12`

### KSI-RPL-ARP — Aligning Recovery Plan

**Family:** `RPL`

**Statement:** The alignment of recovery plans with defined recovery objectives is persistently reviewed.

**Terms:** Persistently

**Controls:** 16

`cp-2`, `cp-2.1`, `cp-2.3`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-6.3`, `cp-7`, `cp-7.1`, `cp-7.2`, `cp-7.3`, `cp-8`, `cp-8.1`, `cp-8.2`, `cp-10`, `cp-10.2`

**Controls matching Class C baseline:** 16

`cp-2`, `cp-2.1`, `cp-2.3`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-6.3`, `cp-7`, `cp-7.1`, `cp-7.2`, `cp-7.3`, `cp-8`, `cp-8.1`, `cp-8.2`, `cp-10`, `cp-10.2`

### KSI-RPL-RRO — Reviewing Recovery Objectives

**Family:** `RPL`

**Statement:** The desired Recovery Time Objectives (RTO) and Recovery Point Objectives (RPO) are defined and persistently reviewed for alignment with the provider's business needs and capabilities.

**Terms:** Persistently, Provider

**Controls:** 2

`cp-2.3`, `cp-10`

**Controls matching Class C baseline:** 2

`cp-2.3`, `cp-10`

### KSI-RPL-TRC — Testing Recovery Capabilities

**Family:** `RPL`

**Statement:** The capability to recover from incidents and contingencies aligned with defined recovery objectives is persistently tested.

**Terms:** Incident, Persistently

**Controls:** 10

`cp-2.1`, `cp-2.3`, `cp-4`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-9.1`, `cp-10`, `ir-3`, `ir-3.2`

**Controls matching Class C baseline:** 10

`cp-2.1`, `cp-2.3`, `cp-4`, `cp-4.1`, `cp-6`, `cp-6.1`, `cp-9.1`, `cp-10`, `ir-3`, `ir-3.2`

### KSI-SCR-MIT — Mitigating Supply Chain Risk

**Family:** `SCR`

**Statement:** Persistently identify, review, and mitigate potential supply chain risks.

**Terms:** Persistently

**Controls:** 12

`ac-20`, `ra-3.1`, `sa-9`, `sa-10`, `sa-11`, `sa-15.3`, `sa-22`, `si-7.1`, `sr-5`, `sr-6`, `ca-7.4`, `sc-18`

**Controls matching Class C baseline:** 12

`ac-20`, `ra-3.1`, `sa-9`, `sa-10`, `sa-11`, `sa-15.3`, `sa-22`, `si-7.1`, `sr-5`, `sr-6`, `ca-7.4`, `sc-18`

### KSI-SCR-MON — Monitoring Supply Chain Risk

**Family:** `SCR`

**Statement:** Third party software information resources are automatically monitored for upstream vulnerabilities using mechanisms that may include contractual notification requirements or active monitoring services.

**Terms:** Information Resource, Vulnerability

**Controls:** 10

`ac-20`, `ca-3`, `ir-6.3`, `ps-7`, `ra-5`, `sa-9`, `si-5`, `sr-5`, `sr-6`, `sr-8`

**Controls matching Class C baseline:** 10

`ac-20`, `ca-3`, `ir-6.3`, `ps-7`, `ra-5`, `sa-9`, `si-5`, `sr-5`, `sr-6`, `sr-8`

### KSI-SVC-ACM — Automating Configuration Management

**Family:** `SVC`

**Statement:** The configuration of machine-based information resources is managed using automation and persistently reviewed for drift.

**Terms:** Drift, Information Resource, Machine-Based (Information Resources), Persistently

**Controls:** 11

`ac-2.4`, `cm-2`, `cm-2.2`, `cm-2.3`, `cm-6`, `cm-7.1`, `pl-9`, `pl-10`, `sa-5`, `si-5`, `sr-10`

**Controls matching Class C baseline:** 10

`ac-2.4`, `cm-2`, `cm-2.2`, `cm-2.3`, `cm-6`, `cm-7.1`, `pl-10`, `sa-5`, `si-5`, `sr-10`

### KSI-SVC-ASM — Automating Secret Management

**Family:** `SVC`

**Statement:** Management, protection, and regular rotation of digital keys, certificates, and other secrets is automated and persistently reviewed.

**Terms:** Persistently, Regularly

**Controls:** 5

`ac-17.2`, `ia-5.2`, `ia-5.6`, `sc-12`, `sc-17`

**Controls matching Class C baseline:** 5

`ac-17.2`, `ia-5.2`, `ia-5.6`, `sc-12`, `sc-17`

### KSI-SVC-EIS — Evaluating and Improving Security

**Family:** `SVC`

**Statement:** Information resources are persistently evaluated for opportunities to improve security and those improvements are persistently made.

**Terms:** Information Resource, Persistently

**Controls:** 9

`cm-7.1`, `cm-12.1`, `ma-2`, `pl-8`, `sc-7`, `sc-39`, `si-2.2`, `si-4`, `sr-10`

**Controls matching Class C baseline:** 9

`cm-7.1`, `cm-12.1`, `ma-2`, `pl-8`, `sc-7`, `sc-39`, `si-2.2`, `si-4`, `sr-10`

### KSI-SVC-PRR — Preventing Residual Risk

**Family:** `SVC`

**Terms:** Federal Customer Data, Information Resource, Likely, Persistently

**Controls:** 1

`sc-4`

**Controls matching Class C baseline:** 1

`sc-4`

### KSI-SVC-RUD — Removing Unwanted Data

**Family:** `SVC`

**Terms:** Agency, Federal Customer Data, Promptly

**Controls:** 2

`si-12.3`, `si-18.4`

**Controls matching Class C baseline:** 0

### KSI-SVC-SIN — Securing Information

**Family:** `SVC`

**Statement:** Information is encrypted or otherwise secured from unwanted access or modification.

**Controls:** 12

`ac-1`, `ac-17.2`, `cp-9.8`, `sc-8`, `sc-8.1`, `sc-13`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-28`, `sc-28.1`

**Controls matching Class C baseline:** 12

`ac-1`, `ac-17.2`, `cp-9.8`, `sc-8`, `sc-8.1`, `sc-13`, `sc-20`, `sc-21`, `sc-22`, `sc-23`, `sc-28`, `sc-28.1`

### KSI-SVC-VCM — Validating Communications

**Family:** `SVC`

**Terms:** Information Resource, Machine-Based (Information Resources), Persistently, Validation

**Controls:** 2

`sc-23`, `si-7.1`

**Controls matching Class C baseline:** 2

`sc-23`, `si-7.1`

### KSI-SVC-VRI — Validating Resource Integrity

**Family:** `SVC`

**Statement:** Use cryptographic methods to validate the integrity of machine-based information resources.

**Terms:** Information Resource, Machine-Based (Information Resources), Validation

**Controls:** 7

`cm-2.2`, `cm-8.3`, `sc-13`, `sc-23`, `si-7`, `si-7.1`, `sr-10`

**Controls matching Class C baseline:** 7

`cm-2.2`, `cm-8.3`, `sc-13`, `sc-23`, `si-7`, `si-7.1`, `sr-10`

## 4. Highest-Overlap Controls

- **sc-23** — 6 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-SIN, KSI-SVC-VCM, KSI-SVC-VRI
- **ac-17.3** — 5 KSIs **[CLASS C]**: KSI-CNA-IBP, KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN, KSI-IAM-ELP
- **ac-20.1** — 5 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-IAM-ELP, KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-OSM
- **cm-2** — 5 KSIs **[CLASS C]**: KSI-CMT-RMV, KSI-CNA-DFP, KSI-CNA-IBP, KSI-MLA-EVC, KSI-SVC-ACM
- **ac-2** — 4 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-JIT, KSI-IAM-SNU, KSI-IAM-SUS
- **ac-2.4** — 4 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL, KSI-SVC-ACM
- **au-2** — 4 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- **cm-3** — 4 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-CMT-RMV, KSI-CMT-RVP, KSI-CMT-VTD
- **cm-6** — 4 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-CMT-RMV, KSI-MLA-EVC, KSI-SVC-ACM
- **cm-7.1** — 4 KSIs **[CLASS C]**: KSI-CMT-RVP, KSI-CNA-RNT, KSI-SVC-ACM, KSI-SVC-EIS
- **cp-10** — 4 KSIs **[CLASS C]**: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- **ia-5.2** — 4 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-SNU, KSI-SVC-ASM
- **ir-4.1** — 4 KSIs **[CLASS C]**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI, KSI-MLA-OSM
- **sc-4** — 4 KSIs **[CLASS C]**: KSI-CNA-ULN, KSI-IAM-ELP, KSI-PIY-RSD, KSI-SVC-PRR
- **ac-17.1** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-MLA-LET, KSI-MLA-OSM
- **ac-17.2** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-SVC-ASM, KSI-SVC-SIN
- **ac-2.2** — 3 KSIs **[CLASS C]**: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SNU
- **ac-2.3** — 3 KSIs **[CLASS C]**: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SUS
- **ac-20** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-SCR-MIT, KSI-SCR-MON
- **ac-3** — 3 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT
- **ac-4** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SNU
- **ac-5** — 3 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-PIY-RIS, KSI-PIY-RSD
- **ac-6.9** — 3 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL
- **ca-9** — 3 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN
- **cm-2.2** — 3 KSIs **[CLASS C]**: KSI-PIY-GIV, KSI-SVC-ACM, KSI-SVC-VRI
- **cm-3.2** — 3 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-CMT-RVP, KSI-CMT-VTD
- **cm-5** — 3 KSIs **[CLASS C]**: KSI-CMT-RMV, KSI-CMT-RVP, KSI-IAM-JIT
- **cm-9** — 3 KSIs **[CLASS C]**: KSI-CMT-RVP, KSI-IAM-ELP, KSI-IAM-JIT
- **cp-2.1** — 3 KSIs **[CLASS C]**: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- **cp-2.3** — 3 KSIs **[CLASS C]**: KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- **cp-4.1** — 3 KSIs **[CLASS C]**: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- **cp-6** — 3 KSIs **[CLASS C]**: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-TRC
- **ia-4.4** — 3 KSIs **[CLASS C]**: KSI-IAM-AAM, KSI-IAM-ELP, KSI-IAM-JIT
- **ia-5.6** — 3 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-ELP, KSI-SVC-ASM
- **ir-3** — 3 KSIs **[CLASS C]**: KSI-INR-AAR, KSI-INR-RPI, KSI-RPL-TRC
- **ir-4** — 3 KSIs **[CLASS C]**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- **ir-8** — 3 KSIs **[CLASS C]**: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- **ps-4** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SUS
- **ps-6** — 3 KSIs **[CLASS C]**: KSI-CED-RAT, KSI-IAM-ELP, KSI-IAM-JIT
- **sc-39** — 3 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-EIS
- **sc-8** — 3 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-CNA-ULN, KSI-SVC-SIN
- **si-11** — 3 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-MLA-ALA, KSI-PIY-RSD
- **si-3** — 3 KSIs **[CLASS C]**: KSI-CMT-RMV, KSI-CNA-DFP, KSI-IAM-ELP
- **si-4.4** — 3 KSIs **[CLASS C]**: KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- **si-7.1** — 3 KSIs **[CLASS C]**: KSI-SCR-MIT, KSI-SVC-VCM, KSI-SVC-VRI
- **si-7.7** — 3 KSIs **[CLASS C]**: KSI-MLA-EVC, KSI-MLA-LET, KSI-MLA-OSM
- **sr-10** — 3 KSIs **[CLASS C]**: KSI-SVC-ACM, KSI-SVC-EIS, KSI-SVC-VRI
- **ac-12** — 2 KSIs **[CLASS C]**: KSI-CNA-ULN, KSI-IAM-ELP
- **ac-17** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ac-2.1** — 2 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-IAM-SUS
- **ac-2.13** — 2 KSIs **[CLASS C]**: KSI-IAM-AAM, KSI-IAM-SUS
- **ac-2.6** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ac-6** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ac-6.5** — 2 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-IAM-SNU
- **ac-6.7** — 2 KSIs **[CLASS C]**: KSI-IAM-AAM, KSI-IAM-JIT
- **ac-7** — 2 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-IAM-SUS
- **au-6.1** — 2 KSIs **[CLASS C]**: KSI-MLA-OSM, KSI-MLA-RVL
- **au-7.1** — 2 KSIs **[CLASS C]**: KSI-MLA-LET, KSI-MLA-OSM
- **cm-12.1** — 2 KSIs **[CLASS C]**: KSI-PIY-GIV, KSI-SVC-EIS
- **cm-2.3** — 2 KSIs **[CLASS C]**: KSI-RPL-ABO, KSI-SVC-ACM
- **cm-3.4** — 2 KSIs **[CLASS C]**: KSI-CMT-RVP, KSI-PIY-RSD
- **cm-4.2** — 2 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-CMT-VTD
- **cm-7** — 2 KSIs **[CLASS C]**: KSI-CMT-RMV, KSI-IAM-JIT
- **cm-7.5** — 2 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-PIY-GIV
- **cm-8.1** — 2 KSIs **[CLASS C]**: KSI-CMT-RMV, KSI-PIY-GIV
- **cm-8.3** — 2 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-SVC-VRI
- **cp-10.2** — 2 KSIs **[CLASS C]**: KSI-RPL-ABO, KSI-RPL-ARP
- **cp-6.1** — 2 KSIs **[CLASS C]**: KSI-RPL-ARP, KSI-RPL-TRC
- **ia-2** — 2 KSIs **[CLASS C]**: KSI-IAM-APM, KSI-IAM-ELP
- **ia-3** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-SNU
- **ia-4** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ir-3.2** — 2 KSIs **[CLASS C]**: KSI-PIY-RIS, KSI-RPL-TRC
- **ir-6.3** — 2 KSIs **[CLASS C]**: KSI-INR-RIR, KSI-SCR-MON
- **ma-2** — 2 KSIs **[CLASS C]**: KSI-CMT-LMC, KSI-SVC-EIS
- **pl-10** — 2 KSIs **[CLASS C]**: KSI-CNA-IBP, KSI-SVC-ACM
- **pl-8** — 2 KSIs **[CLASS C]**: KSI-PIY-RSD, KSI-SVC-EIS
- **ps-2** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ps-3** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ps-5** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-IAM-JIT
- **ra-5.5** — 2 KSIs **[CLASS C]**: KSI-IAM-JIT, KSI-IAM-SNU
- **sa-3** — 2 KSIs **[CLASS C]**: KSI-PIY-RIS, KSI-PIY-RSD
- **sa-9** — 2 KSIs **[CLASS C]**: KSI-SCR-MIT, KSI-SCR-MON
- **sc-10** — 2 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-CNA-ULN
- **sc-13** — 2 KSIs **[CLASS C]**: KSI-SVC-SIN, KSI-SVC-VRI
- **sc-18** — 2 KSIs **[CLASS C]**: KSI-PIY-RSD, KSI-SCR-MIT
- **sc-20** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-21** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-22** — 2 KSIs **[CLASS C]**: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-7** — 2 KSIs **[CLASS C]**: KSI-CNA-ULN, KSI-SVC-EIS
- **sc-7.5** — 2 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-CNA-RNT
- **si-10** — 2 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-PIY-RSD
- **si-16** — 2 KSIs **[CLASS C]**: KSI-CNA-MAT, KSI-PIY-RSD
- **si-4** — 2 KSIs **[CLASS C]**: KSI-MLA-RVL, KSI-SVC-EIS
- **si-4.5** — 2 KSIs **[CLASS C]**: KSI-INR-RIR, KSI-MLA-LET
- **si-5** — 2 KSIs **[CLASS C]**: KSI-SCR-MON, KSI-SVC-ACM
- **si-8** — 2 KSIs **[CLASS C]**: KSI-CNA-RNT, KSI-CNA-RVP
- **sr-5** — 2 KSIs **[CLASS C]**: KSI-SCR-MIT, KSI-SCR-MON
- **sr-6** — 2 KSIs **[CLASS C]**: KSI-SCR-MIT, KSI-SCR-MON

## 5. Class C Shared-Control Hotspots

- **sc-23** — 6 KSIs: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-SIN, KSI-SVC-VCM, KSI-SVC-VRI
- **ac-17.3** — 5 KSIs: KSI-CNA-IBP, KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN, KSI-IAM-ELP
- **ac-20.1** — 5 KSIs: KSI-CNA-MAT, KSI-IAM-ELP, KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-OSM
- **cm-2** — 5 KSIs: KSI-CMT-RMV, KSI-CNA-DFP, KSI-CNA-IBP, KSI-MLA-EVC, KSI-SVC-ACM
- **ac-2** — 4 KSIs: KSI-IAM-APM, KSI-IAM-JIT, KSI-IAM-SNU, KSI-IAM-SUS
- **ac-2.4** — 4 KSIs: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL, KSI-SVC-ACM
- **au-2** — 4 KSIs: KSI-CMT-LMC, KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- **cm-3** — 4 KSIs: KSI-CMT-LMC, KSI-CMT-RMV, KSI-CMT-RVP, KSI-CMT-VTD
- **cm-6** — 4 KSIs: KSI-CMT-LMC, KSI-CMT-RMV, KSI-MLA-EVC, KSI-SVC-ACM
- **cm-7.1** — 4 KSIs: KSI-CMT-RVP, KSI-CNA-RNT, KSI-SVC-ACM, KSI-SVC-EIS
- **cp-10** — 4 KSIs: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- **ia-5.2** — 4 KSIs: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-SNU, KSI-SVC-ASM
- **ir-4.1** — 4 KSIs: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI, KSI-MLA-OSM
- **sc-4** — 4 KSIs: KSI-CNA-ULN, KSI-IAM-ELP, KSI-PIY-RSD, KSI-SVC-PRR
- **ac-17.1** — 3 KSIs: KSI-IAM-ELP, KSI-MLA-LET, KSI-MLA-OSM
- **ac-17.2** — 3 KSIs: KSI-IAM-ELP, KSI-SVC-ASM, KSI-SVC-SIN
- **ac-2.2** — 3 KSIs: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SNU
- **ac-2.3** — 3 KSIs: KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SUS
- **ac-20** — 3 KSIs: KSI-IAM-ELP, KSI-SCR-MIT, KSI-SCR-MON
- **ac-3** — 3 KSIs: KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT
- **ac-4** — 3 KSIs: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SNU
- **ac-5** — 3 KSIs: KSI-IAM-JIT, KSI-PIY-RIS, KSI-PIY-RSD
- **ac-6.9** — 3 KSIs: KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL
- **ca-9** — 3 KSIs: KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN
- **cm-2.2** — 3 KSIs: KSI-PIY-GIV, KSI-SVC-ACM, KSI-SVC-VRI
- **cm-3.2** — 3 KSIs: KSI-CMT-LMC, KSI-CMT-RVP, KSI-CMT-VTD
- **cm-5** — 3 KSIs: KSI-CMT-RMV, KSI-CMT-RVP, KSI-IAM-JIT
- **cm-9** — 3 KSIs: KSI-CMT-RVP, KSI-IAM-ELP, KSI-IAM-JIT
- **cp-2.1** — 3 KSIs: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- **cp-2.3** — 3 KSIs: KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- **cp-4.1** — 3 KSIs: KSI-PIY-RIS, KSI-RPL-ARP, KSI-RPL-TRC
- **cp-6** — 3 KSIs: KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-TRC
- **ia-4.4** — 3 KSIs: KSI-IAM-AAM, KSI-IAM-ELP, KSI-IAM-JIT
- **ia-5.6** — 3 KSIs: KSI-IAM-APM, KSI-IAM-ELP, KSI-SVC-ASM
- **ir-3** — 3 KSIs: KSI-INR-AAR, KSI-INR-RPI, KSI-RPL-TRC
- **ir-4** — 3 KSIs: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- **ir-8** — 3 KSIs: KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI
- **ps-4** — 3 KSIs: KSI-IAM-ELP, KSI-IAM-JIT, KSI-IAM-SUS
- **ps-6** — 3 KSIs: KSI-CED-RAT, KSI-IAM-ELP, KSI-IAM-JIT
- **sc-39** — 3 KSIs: KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-EIS
- **sc-8** — 3 KSIs: KSI-CNA-MAT, KSI-CNA-ULN, KSI-SVC-SIN
- **si-11** — 3 KSIs: KSI-CNA-MAT, KSI-MLA-ALA, KSI-PIY-RSD
- **si-3** — 3 KSIs: KSI-CMT-RMV, KSI-CNA-DFP, KSI-IAM-ELP
- **si-4.4** — 3 KSIs: KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- **si-7.1** — 3 KSIs: KSI-SCR-MIT, KSI-SVC-VCM, KSI-SVC-VRI
- **si-7.7** — 3 KSIs: KSI-MLA-EVC, KSI-MLA-LET, KSI-MLA-OSM
- **sr-10** — 3 KSIs: KSI-SVC-ACM, KSI-SVC-EIS, KSI-SVC-VRI
- **ac-12** — 2 KSIs: KSI-CNA-ULN, KSI-IAM-ELP
- **ac-17** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ac-2.1** — 2 KSIs: KSI-IAM-JIT, KSI-IAM-SUS
- **ac-2.13** — 2 KSIs: KSI-IAM-AAM, KSI-IAM-SUS
- **ac-6** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ac-6.5** — 2 KSIs: KSI-IAM-JIT, KSI-IAM-SNU
- **ac-6.7** — 2 KSIs: KSI-IAM-AAM, KSI-IAM-JIT
- **ac-7** — 2 KSIs: KSI-IAM-JIT, KSI-IAM-SUS
- **au-6.1** — 2 KSIs: KSI-MLA-OSM, KSI-MLA-RVL
- **au-7.1** — 2 KSIs: KSI-MLA-LET, KSI-MLA-OSM
- **cm-12.1** — 2 KSIs: KSI-PIY-GIV, KSI-SVC-EIS
- **cm-2.3** — 2 KSIs: KSI-RPL-ABO, KSI-SVC-ACM
- **cm-3.4** — 2 KSIs: KSI-CMT-RVP, KSI-PIY-RSD
- **cm-4.2** — 2 KSIs: KSI-CMT-LMC, KSI-CMT-VTD
- **cm-7** — 2 KSIs: KSI-CMT-RMV, KSI-IAM-JIT
- **cm-7.5** — 2 KSIs: KSI-IAM-JIT, KSI-PIY-GIV
- **cm-8.1** — 2 KSIs: KSI-CMT-RMV, KSI-PIY-GIV
- **cm-8.3** — 2 KSIs: KSI-CMT-LMC, KSI-SVC-VRI
- **cp-10.2** — 2 KSIs: KSI-RPL-ABO, KSI-RPL-ARP
- **cp-6.1** — 2 KSIs: KSI-RPL-ARP, KSI-RPL-TRC
- **ia-2** — 2 KSIs: KSI-IAM-APM, KSI-IAM-ELP
- **ia-3** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-SNU
- **ia-4** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ir-3.2** — 2 KSIs: KSI-PIY-RIS, KSI-RPL-TRC
- **ir-6.3** — 2 KSIs: KSI-INR-RIR, KSI-SCR-MON
- **ma-2** — 2 KSIs: KSI-CMT-LMC, KSI-SVC-EIS
- **pl-10** — 2 KSIs: KSI-CNA-IBP, KSI-SVC-ACM
- **pl-8** — 2 KSIs: KSI-PIY-RSD, KSI-SVC-EIS
- **ps-2** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ps-3** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ps-5** — 2 KSIs: KSI-IAM-ELP, KSI-IAM-JIT
- **ra-5.5** — 2 KSIs: KSI-IAM-JIT, KSI-IAM-SNU
- **sa-3** — 2 KSIs: KSI-PIY-RIS, KSI-PIY-RSD
- **sa-9** — 2 KSIs: KSI-SCR-MIT, KSI-SCR-MON
- **sc-10** — 2 KSIs: KSI-CNA-MAT, KSI-CNA-ULN
- **sc-13** — 2 KSIs: KSI-SVC-SIN, KSI-SVC-VRI
- **sc-18** — 2 KSIs: KSI-PIY-RSD, KSI-SCR-MIT
- **sc-20** — 2 KSIs: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-21** — 2 KSIs: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-22** — 2 KSIs: KSI-IAM-ELP, KSI-SVC-SIN
- **sc-7** — 2 KSIs: KSI-CNA-ULN, KSI-SVC-EIS
- **sc-7.5** — 2 KSIs: KSI-CNA-MAT, KSI-CNA-RNT
- **si-10** — 2 KSIs: KSI-CNA-MAT, KSI-PIY-RSD
- **si-16** — 2 KSIs: KSI-CNA-MAT, KSI-PIY-RSD
- **si-4** — 2 KSIs: KSI-MLA-RVL, KSI-SVC-EIS
- **si-4.5** — 2 KSIs: KSI-INR-RIR, KSI-MLA-LET
- **si-5** — 2 KSIs: KSI-SCR-MON, KSI-SVC-ACM
- **si-8** — 2 KSIs: KSI-CNA-RNT, KSI-CNA-RVP
- **sr-5** — 2 KSIs: KSI-SCR-MIT, KSI-SCR-MON
- **sr-6** — 2 KSIs: KSI-SCR-MIT, KSI-SCR-MON

## 6. KSI-to-KSI Overlap

- **KSI-IAM-ELP ↔ KSI-IAM-JIT** — 16 shared controls: ps-6, cm-9, ac-20.1, ia-4.4, ac-3, sc-23, ac-2.6, ac-4, ac-6, ac-17, ia-4, ps-2, ps-3, ps-4, ps-5, sc-39
- **KSI-MLA-LET ↔ KSI-MLA-OSM** — 6 shared controls: au-2, ac-20.1, ac-17.1, si-7.7, au-7.1, si-4.4
- **KSI-RPL-ARP ↔ KSI-RPL-TRC** — 6 shared controls: cp-2.1, cp-4.1, cp-6, cp-10, cp-2.3, cp-6.1
- **KSI-IAM-APM ↔ KSI-IAM-ELP** — 5 shared controls: ac-3, ia-5.2, ia-5.6, ia-2, sc-23
- **KSI-IAM-ELP ↔ KSI-SVC-SIN** — 5 shared controls: sc-23, ac-17.2, sc-20, sc-21, sc-22
- **KSI-IAM-JIT ↔ KSI-IAM-SNU** — 5 shared controls: ac-2.2, ac-2, ac-4, ac-6.5, ra-5.5
- **KSI-IAM-JIT ↔ KSI-IAM-SUS** — 5 shared controls: ac-2.3, ac-2, ps-4, ac-2.1, ac-7
- **KSI-CNA-MAT ↔ KSI-CNA-ULN** — 4 shared controls: ac-17.3, ca-9, sc-8, sc-10
- **KSI-IAM-AAM ↔ KSI-IAM-JIT** — 4 shared controls: ac-2.2, ac-2.3, ac-6.7, ia-4.4
- **KSI-INR-AAR ↔ KSI-INR-RPI** — 4 shared controls: ir-3, ir-4, ir-4.1, ir-8
- **KSI-MLA-LET ↔ KSI-MLA-RVL** — 4 shared controls: au-2, ac-2.4, ac-6.9, si-4.4
- **KSI-SCR-MIT ↔ KSI-SCR-MON** — 4 shared controls: ac-20, sa-9, sr-5, sr-6
- **KSI-CMT-LMC ↔ KSI-CMT-VTD** — 3 shared controls: cm-3, cm-3.2, cm-4.2
- **KSI-CNA-MAT ↔ KSI-CNA-RNT** — 3 shared controls: ac-17.3, ca-9, sc-7.5
- **KSI-CNA-MAT ↔ KSI-PIY-RSD** — 3 shared controls: si-10, si-11, si-16
- **KSI-CNA-ULN ↔ KSI-IAM-ELP** — 3 shared controls: ac-17.3, ac-12, sc-4
- **KSI-IAM-APM ↔ KSI-IAM-JIT** — 3 shared controls: ac-3, ac-2, sc-23
- **KSI-IAM-ELP ↔ KSI-IAM-SNU** — 3 shared controls: ia-5.2, ac-4, ia-3
- **KSI-IAM-ELP ↔ KSI-SVC-ASM** — 3 shared controls: ia-5.2, ia-5.6, ac-17.2
- **KSI-IAM-JIT ↔ KSI-MLA-LET** — 3 shared controls: ac-20.1, ac-2.4, ac-6.9
- **KSI-INR-AAR ↔ KSI-INR-RIR** — 3 shared controls: ir-4, ir-4.1, ir-8
- **KSI-INR-RIR ↔ KSI-INR-RPI** — 3 shared controls: ir-4, ir-4.1, ir-8
- **KSI-MLA-OSM ↔ KSI-MLA-RVL** — 3 shared controls: au-2, si-4.4, au-6.1
- **KSI-PIY-RIS ↔ KSI-RPL-TRC** — 3 shared controls: cp-2.1, cp-4.1, ir-3.2
- **KSI-RPL-ABO ↔ KSI-RPL-ARP** — 3 shared controls: cp-6, cp-10, cp-10.2
- **KSI-CMT-LMC ↔ KSI-CMT-RMV** — 2 shared controls: cm-3, cm-6
- **KSI-CMT-LMC ↔ KSI-CMT-RVP** — 2 shared controls: cm-3, cm-3.2
- **KSI-CMT-RMV ↔ KSI-CMT-RVP** — 2 shared controls: cm-3, cm-5
- **KSI-CMT-RMV ↔ KSI-CNA-DFP** — 2 shared controls: cm-2, si-3
- **KSI-CMT-RMV ↔ KSI-IAM-JIT** — 2 shared controls: cm-5, cm-7
- **KSI-CMT-RMV ↔ KSI-MLA-EVC** — 2 shared controls: cm-6, cm-2
- **KSI-CMT-RMV ↔ KSI-SVC-ACM** — 2 shared controls: cm-6, cm-2
- **KSI-CMT-RVP ↔ KSI-CMT-VTD** — 2 shared controls: cm-3, cm-3.2
- **KSI-CMT-RVP ↔ KSI-IAM-JIT** — 2 shared controls: cm-5, cm-9
- **KSI-CNA-IBP ↔ KSI-SVC-ACM** — 2 shared controls: cm-2, pl-10
- **KSI-CNA-MAT ↔ KSI-IAM-ELP** — 2 shared controls: ac-17.3, ac-20.1
- **KSI-CNA-RNT ↔ KSI-CNA-ULN** — 2 shared controls: ac-17.3, ca-9
- **KSI-IAM-AAM ↔ KSI-IAM-SUS** — 2 shared controls: ac-2.3, ac-2.13
- **KSI-IAM-APM ↔ KSI-IAM-SNU** — 2 shared controls: ia-5.2, ac-2
- **KSI-IAM-APM ↔ KSI-SVC-ASM** — 2 shared controls: ia-5.2, ia-5.6
- **KSI-IAM-ELP ↔ KSI-MLA-LET** — 2 shared controls: ac-20.1, ac-17.1
- **KSI-IAM-ELP ↔ KSI-MLA-OSM** — 2 shared controls: ac-20.1, ac-17.1
- **KSI-IAM-JIT ↔ KSI-MLA-RVL** — 2 shared controls: ac-2.4, ac-6.9
- **KSI-MLA-EVC ↔ KSI-SVC-ACM** — 2 shared controls: cm-6, cm-2
- **KSI-PIY-RIS ↔ KSI-PIY-RSD** — 2 shared controls: ac-5, sa-3
- **KSI-PIY-RIS ↔ KSI-RPL-ARP** — 2 shared controls: cp-2.1, cp-4.1
- **KSI-RPL-ABO ↔ KSI-RPL-TRC** — 2 shared controls: cp-6, cp-10
- **KSI-RPL-ARP ↔ KSI-RPL-RRO** — 2 shared controls: cp-10, cp-2.3
- **KSI-RPL-RRO ↔ KSI-RPL-TRC** — 2 shared controls: cp-10, cp-2.3
- **KSI-SVC-ACM ↔ KSI-SVC-EIS** — 2 shared controls: cm-7.1, sr-10
- **KSI-SVC-ACM ↔ KSI-SVC-VRI** — 2 shared controls: cm-2.2, sr-10
- **KSI-SVC-SIN ↔ KSI-SVC-VRI** — 2 shared controls: sc-23, sc-13
- **KSI-SVC-VCM ↔ KSI-SVC-VRI** — 2 shared controls: sc-23, si-7.1
- **KSI-CED-RAT ↔ KSI-IAM-ELP** — 1 shared controls: ps-6
- **KSI-CED-RAT ↔ KSI-IAM-JIT** — 1 shared controls: ps-6
- **KSI-CMT-LMC ↔ KSI-MLA-EVC** — 1 shared controls: cm-6
- **KSI-CMT-LMC ↔ KSI-MLA-LET** — 1 shared controls: au-2
- **KSI-CMT-LMC ↔ KSI-MLA-OSM** — 1 shared controls: au-2
- **KSI-CMT-LMC ↔ KSI-MLA-RVL** — 1 shared controls: au-2
- **KSI-CMT-LMC ↔ KSI-SVC-ACM** — 1 shared controls: cm-6
- **KSI-CMT-LMC ↔ KSI-SVC-EIS** — 1 shared controls: ma-2
- **KSI-CMT-LMC ↔ KSI-SVC-VRI** — 1 shared controls: cm-8.3
- **KSI-CMT-RMV ↔ KSI-CMT-VTD** — 1 shared controls: cm-3
- **KSI-CMT-RMV ↔ KSI-CNA-IBP** — 1 shared controls: cm-2
- **KSI-CMT-RMV ↔ KSI-IAM-ELP** — 1 shared controls: si-3
- **KSI-CMT-RMV ↔ KSI-PIY-GIV** — 1 shared controls: cm-8.1
- **KSI-CMT-RVP ↔ KSI-CNA-RNT** — 1 shared controls: cm-7.1
- **KSI-CMT-RVP ↔ KSI-IAM-ELP** — 1 shared controls: cm-9
- **KSI-CMT-RVP ↔ KSI-PIY-RSD** — 1 shared controls: cm-3.4
- **KSI-CMT-RVP ↔ KSI-SVC-ACM** — 1 shared controls: cm-7.1
- **KSI-CMT-RVP ↔ KSI-SVC-EIS** — 1 shared controls: cm-7.1
- **KSI-CNA-DFP ↔ KSI-CNA-IBP** — 1 shared controls: cm-2
- **KSI-CNA-DFP ↔ KSI-IAM-ELP** — 1 shared controls: si-3
- **KSI-CNA-DFP ↔ KSI-MLA-EVC** — 1 shared controls: cm-2
- **KSI-CNA-DFP ↔ KSI-SVC-ACM** — 1 shared controls: cm-2
- **KSI-CNA-IBP ↔ KSI-CNA-MAT** — 1 shared controls: ac-17.3
- **KSI-CNA-IBP ↔ KSI-CNA-RNT** — 1 shared controls: ac-17.3
- **KSI-CNA-IBP ↔ KSI-CNA-ULN** — 1 shared controls: ac-17.3
- **KSI-CNA-IBP ↔ KSI-IAM-ELP** — 1 shared controls: ac-17.3
- **KSI-CNA-IBP ↔ KSI-MLA-EVC** — 1 shared controls: cm-2
- **KSI-CNA-MAT ↔ KSI-IAM-JIT** — 1 shared controls: ac-20.1
- **KSI-CNA-MAT ↔ KSI-MLA-ALA** — 1 shared controls: si-11
- **KSI-CNA-MAT ↔ KSI-MLA-LET** — 1 shared controls: ac-20.1
- **KSI-CNA-MAT ↔ KSI-MLA-OSM** — 1 shared controls: ac-20.1
- **KSI-CNA-MAT ↔ KSI-SVC-SIN** — 1 shared controls: sc-8
- **KSI-CNA-RNT ↔ KSI-CNA-RVP** — 1 shared controls: si-8
- **KSI-CNA-RNT ↔ KSI-IAM-ELP** — 1 shared controls: ac-17.3
- **KSI-CNA-RNT ↔ KSI-SVC-ACM** — 1 shared controls: cm-7.1
- **KSI-CNA-RNT ↔ KSI-SVC-EIS** — 1 shared controls: cm-7.1
- **KSI-CNA-ULN ↔ KSI-PIY-RSD** — 1 shared controls: sc-4
- **KSI-CNA-ULN ↔ KSI-SVC-EIS** — 1 shared controls: sc-7
- **KSI-CNA-ULN ↔ KSI-SVC-PRR** — 1 shared controls: sc-4
- **KSI-CNA-ULN ↔ KSI-SVC-SIN** — 1 shared controls: sc-8
- **KSI-IAM-AAM ↔ KSI-IAM-ELP** — 1 shared controls: ia-4.4
- **KSI-IAM-AAM ↔ KSI-IAM-SNU** — 1 shared controls: ac-2.2
- **KSI-IAM-APM ↔ KSI-IAM-SUS** — 1 shared controls: ac-2
- **KSI-IAM-APM ↔ KSI-SVC-SIN** — 1 shared controls: sc-23
- **KSI-IAM-APM ↔ KSI-SVC-VCM** — 1 shared controls: sc-23
- **KSI-IAM-APM ↔ KSI-SVC-VRI** — 1 shared controls: sc-23
- **KSI-IAM-ELP ↔ KSI-IAM-SUS** — 1 shared controls: ps-4
- **KSI-IAM-ELP ↔ KSI-PIY-RSD** — 1 shared controls: sc-4
- **KSI-IAM-ELP ↔ KSI-SCR-MIT** — 1 shared controls: ac-20
- **KSI-IAM-ELP ↔ KSI-SCR-MON** — 1 shared controls: ac-20
- **KSI-IAM-ELP ↔ KSI-SVC-EIS** — 1 shared controls: sc-39
- **KSI-IAM-ELP ↔ KSI-SVC-PRR** — 1 shared controls: sc-4
- **KSI-IAM-ELP ↔ KSI-SVC-VCM** — 1 shared controls: sc-23
- **KSI-IAM-ELP ↔ KSI-SVC-VRI** — 1 shared controls: sc-23
- **KSI-IAM-JIT ↔ KSI-MLA-OSM** — 1 shared controls: ac-20.1
- **KSI-IAM-JIT ↔ KSI-PIY-GIV** — 1 shared controls: cm-7.5
- **KSI-IAM-JIT ↔ KSI-PIY-RIS** — 1 shared controls: ac-5
- **KSI-IAM-JIT ↔ KSI-PIY-RSD** — 1 shared controls: ac-5
- **KSI-IAM-JIT ↔ KSI-SVC-ACM** — 1 shared controls: ac-2.4
- **KSI-IAM-JIT ↔ KSI-SVC-EIS** — 1 shared controls: sc-39
- **KSI-IAM-JIT ↔ KSI-SVC-SIN** — 1 shared controls: sc-23
- **KSI-IAM-JIT ↔ KSI-SVC-VCM** — 1 shared controls: sc-23
- **KSI-IAM-JIT ↔ KSI-SVC-VRI** — 1 shared controls: sc-23
- **KSI-IAM-SNU ↔ KSI-IAM-SUS** — 1 shared controls: ac-2
- **KSI-IAM-SNU ↔ KSI-SVC-ASM** — 1 shared controls: ia-5.2
- **KSI-INR-AAR ↔ KSI-MLA-OSM** — 1 shared controls: ir-4.1
- **KSI-INR-AAR ↔ KSI-RPL-TRC** — 1 shared controls: ir-3
- **KSI-INR-RIR ↔ KSI-MLA-LET** — 1 shared controls: si-4.5
- **KSI-INR-RIR ↔ KSI-MLA-OSM** — 1 shared controls: ir-4.1
- **KSI-INR-RIR ↔ KSI-SCR-MON** — 1 shared controls: ir-6.3
- **KSI-INR-RPI ↔ KSI-MLA-OSM** — 1 shared controls: ir-4.1
- **KSI-INR-RPI ↔ KSI-RPL-TRC** — 1 shared controls: ir-3
- **KSI-MLA-ALA ↔ KSI-PIY-RSD** — 1 shared controls: si-11
- **KSI-MLA-EVC ↔ KSI-MLA-LET** — 1 shared controls: si-7.7
- **KSI-MLA-EVC ↔ KSI-MLA-OSM** — 1 shared controls: si-7.7
- **KSI-MLA-LET ↔ KSI-SVC-ACM** — 1 shared controls: ac-2.4
- **KSI-MLA-RVL ↔ KSI-SVC-ACM** — 1 shared controls: ac-2.4
- **KSI-MLA-RVL ↔ KSI-SVC-EIS** — 1 shared controls: si-4
- **KSI-PIY-GIV ↔ KSI-SVC-ACM** — 1 shared controls: cm-2.2
- **KSI-PIY-GIV ↔ KSI-SVC-EIS** — 1 shared controls: cm-12.1
- **KSI-PIY-GIV ↔ KSI-SVC-VRI** — 1 shared controls: cm-2.2
- **KSI-PIY-RSD ↔ KSI-SCR-MIT** — 1 shared controls: sc-18
- **KSI-PIY-RSD ↔ KSI-SVC-EIS** — 1 shared controls: pl-8
- **KSI-PIY-RSD ↔ KSI-SVC-PRR** — 1 shared controls: sc-4
- **KSI-RPL-ABO ↔ KSI-RPL-RRO** — 1 shared controls: cp-10
- **KSI-RPL-ABO ↔ KSI-SVC-ACM** — 1 shared controls: cm-2.3
- **KSI-SCR-MIT ↔ KSI-SVC-VCM** — 1 shared controls: si-7.1
- **KSI-SCR-MIT ↔ KSI-SVC-VRI** — 1 shared controls: si-7.1
- **KSI-SCR-MON ↔ KSI-SVC-ACM** — 1 shared controls: si-5
- **KSI-SVC-ASM ↔ KSI-SVC-SIN** — 1 shared controls: ac-17.2
- **KSI-SVC-EIS ↔ KSI-SVC-VRI** — 1 shared controls: sr-10
- **KSI-SVC-SIN ↔ KSI-SVC-VCM** — 1 shared controls: sc-23

## 7. KSI Family Distribution

- **CED:** 1 KSIs
- **CMT:** 4 KSIs
- **CNA:** 8 KSIs
- **IAM:** 6 KSIs
- **INR:** 3 KSIs
- **MLA:** 5 KSIs
- **PIY:** 5 KSIs
- **RPL:** 4 KSIs
- **SCR:** 2 KSIs
- **SVC:** 8 KSIs

## 8. Class C FRR Rule Statements

### `/CCM/data/all/QTR/CCM-QTR-MTG/varies_by_class/c`

Providers with Class C Certifications MUST host a synchronous Quarterly Review every 3 months, open to all necessary parties, to review aspects of the most recent Ongoing Certification Reports that the provider determines are of the most relevance to agencies.

**force:** `MUST`

**timeframe_type:** `months`

**timeframe_num:** `3`

**artifacts:** `{'all': ['selected ordinal recurrence for the Ongoing Certification Report cycle.']}`

### `/CDS/data/all/CSO/CDS-CSO-AVR/varies_by_class/c`

Providers with Class C Certifications MUST maintain a web service, available to all necessary parties, that indicates current and historical availability of core services within the cloud service offering over at least the past 30 days, including availability incidents, in both human-readable and machine-readable formats; this service MUST be available even if the primary cloud service offering is unavailable.

**note:** `This service may be separate from the trust center.`

**force:** `MUST`

### `/CDS/data/all/CSO/CDS-CSO-PSM/varies_by_class/c`

Providers with Class C Certifications MAY supply per-service FedRAMP Certification materials.

**force:** `MAY`

**artifacts:** `{'all': ['Explanation of the supplied materials, including how to access and use them.']}`

### `/CMU/data/all/CSO/CMU-CSO-UVM/varies_by_class/c`

Providers with Class C Certifications SHOULD use cryptographic modules or update streams of cryptographic modules with active validations under the NIST Cryptographic Module Validation Program when using cryptographic services to protect federal customer data.

**force:** `SHOULD`

**artifacts:** `{'all': ['List of cryptographic modules including whether these modules are validated under the NIST Cryptographic Module Validation Program or are update streams of such modules.']}`

### `/CPO/data/all/CSO/CPO-CSO-OSA/varies_by_class/c`

Providers seeking Class C Certification MUST also include the overall summary of their FedRAMP independent assessment, supplied by the assessor per IVV-IAS-OSA (Overall Summary of Assessment), in their Certification Package Overview.

**force:** `MUST`

### `/CPO/data/20x/CSX/CPO-CSX-CPM/varies_by_class/c`

Providers with 20x Class C Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every 2 weeks.

**force:** `MUST`

**timeframe_type:** `weeks`

**timeframe_num:** `2`

### `/CPO/data/rev5/CSF/CPO-CSF-CPM/varies_by_class/c`

Providers with Rev5 Class C Certifications MUST persistently maintain their FedRAMP Certification Package to ensure it is up to date and complete at least once every year.

**force:** `MUST`

**timeframe_type:** `years`

**timeframe_num:** `1`

### `/FRC/data/all/APP/FRC-APP-FIA/varies_by_class/c`

Providers seeking Class C Certification MUST supply a fresh initial FedRAMP independent assessment that was completed by a FedRAMP Recognized independent assessment service within the previous 3 months.

**force:** `MUST`

**timeframe_type:** `months`

**timeframe_num:** `3`

### `/FRC/data/20x/CSX/FRC-CSX-VVK/varies_by_class/c`

Providers seeking 20x Class C Certification MUST implement automated methods to persistently verify and validate the accuracy and completeness of Key Security Indicators with at least 2 automated methods for each Key Security Indicator.

**force:** `MUST`

### `/FRC/data/20x/CSX/FRC-CSX-MOT/varies_by_class/c`

Providers seeking 20x Class C Certification MUST supply historical metrics including status from persistent validation over at least the past 6 months for all Key Security Indicators.

**force:** `MUST`

### `/FRC/data/20x/CSX/FRC-CSX-VVR/varies_by_class/c`

Providers seeking 20x Class C Certification SHOULD implement automated methods to persistently verify and validate the accuracy and completeness of the Security Decision Record for FedRAMP rules when applicable.

**force:** `SHOULD`

### `/FRC/data/rev5/CSF/FRC-CSF-BSL/varies_by_class/c`

Providers seeking FedRAMP Rev5 Class C Certification MUST include at least the following NIST SP 800-53 Rev. 5 controls in their Security Decision Record:

**force:** `MUST`

### `/IEC/data/all/CSO/IEC-CSO-IIR/varies_by_class/c`

Providers with Class C Certifications MUST responsibly notify all affected parties after identifying FedRAMP Reportable Incidents by providing an Initial Incident Report with as much of the following information that is available at the time of reporting and/or the current relevant status for each item:

**following_information:** `['Contact information for the federal incident response coordinator.', "Provider's internally assigned tracking identifier", 'Description of the incident', 'Timeline of the incident, including start time, time and source of detection, time of completed FedRAMP Reportable Incident evaluation, and other major incident milestones determined by the provider', 'Historically and currently estimated Potential Agency Impact N-rating (PAIN) of the incident, including an explanation of the evaluation following the requirements in IEC-CSO-EFI (Estimate Federal Impact) (if applicable)', 'Functional impact to federal agency customers (include impact to confidentiality and/or integrity and the impacted federal customer data types)', 'Estimated recovery plan, milestones, and timelines', 'List of likely affected customer agencies']`

**force:** `MUST`

**artifacts:** `{'all': ['An Initial Incident Report for one or more incidents. The report can be from real incidents, simulated incidents, or a combination of sources.']}`

### `/IEC/data/all/CSO/IEC-CSO-OIR/varies_by_class/c`

Providers with Class C Certifications MUST responsibly notify all affected parties of ongoing activity as new information becomes available during incident response for FedRAMP Reportable Incidents, including updates (or lack of updates) to all previously reported information and as much of the the following additional information that is available and/or the current relevant status for each item:

**following_information:** `['Observed incident activity', 'Indicators of compromise', 'Related Common Vulnerabilities and Exposures (CVE) identifier, if applicable', 'Root cause', 'Response and recovery activities']`

**force:** `MUST`

**artifacts:** `{'all': ['An Ongoing Incident Report for one or more incidents. The report can be from real incidents, simulated incidents, or a combination of sources.']}`

### `/IEC/data/all/CSO/IEC-CSO-FIR/varies_by_class/c`

Providers with Class C Certifications MUST responsibly notify all affected parties by providing a Final Incident Report once the incident has been resolved and recovery is complete, including final updates to all previously reported information.

**force:** `MUST`

**artifacts:** `{'all': ['An Final Incident Report for one or more incidents. The report can be from real incidents, simulated incidents, or a combination of sources.']}`

### `/IVV/data/all/CSO/IVV-CSO-FIA/varies_by_class/c`

Providers with Class C Certifications MUST persistently complete an independent verification and validation assessment of all applicable FedRAMP rules with a FedRAMP Recognized independent assessment service OR FedRAMP at least once per year; this is a FedRAMP independent assessment.

**force:** `MUST`

**timeframe_type:** `years`

**timeframe_num:** `1`

### `/IVV/data/20x/CSX/IVV-CSX-AIA/varies_by_class/c`

Providers with 20x Class C Certifications MUST include all Key Security Indicators in a FedRAMP independent assessment at least once per year.

**force:** `MUST`

**timeframe_type:** `years`

**timeframe_num:** `1`

### `/IVV/data/rev5/CSF/IVV-CSF-AIA/varies_by_class/c`

Providers with Rev5 Class C Certifications MUST include the following Rev5 Controls in a FedRAMP independent assessment at least once per year:

**force:** `MUST`

**timeframe_type:** `years`

**timeframe_num:** `1`

### `/SDR/data/20x/CSX/SDR-CSX-KMT/varies_by_class/c`

Providers with 20x Class C Certifications MUST also include historical metrics in their Security Decision Record, supplying at least the following information for each applicable Key Security Indicator:

**following_information:** `['Summary of each metric over the past 30 days', 'Summary of metric up to the past year (where available)', 'All daily metric data up to the past year (where available)']`

**force:** `MUST`

### `/VDR/data/all/TFR/VDR-TFR-PDD/varies_by_class/c`

Providers with Class C Certifications SHOULD persistently perform vulnerability detection on all information resources that are likely to drift, at least once every 14 days.

**force:** `SHOULD`

**timeframe_type:** `days`

**timeframe_num:** `14`

### `/VDR/data/all/TFR/VDR-TFR-PCD/varies_by_class/c`

Providers with Class C Certifications SHOULD persistently perform vulnerability detection on all information resources that are NOT likely to drift, at least once every month.

**force:** `SHOULD`

**timeframe_type:** `months`

**timeframe_num:** `1`

### `/VDR/data/all/TFR/VDR-TFR-PVR/varies_by_class/c`

Providers with Class C Certifications SHOULD partially mitigate vulnerabilities, fully mitigate vulnerabilities, or remediate vulnerabilities to a lower Potential Agency Impact N-rating within the timeframes from evaluation shown below, factoring for the current Potential Agency Impact N-rating as defined in VER-EVA-EPA (Estimate Potential Agency Impact), internet reachability, and likely exploitability:

**force:** `SHOULD`

### `/VDR/data/all/TFR/VDR-TFR-PSD/varies_by_class/c`

Providers with Class C Certifications SHOULD persistently perform vulnerability detection on representative samples of similar machine-based information resources, at least once every 3 days.

**force:** `SHOULD`

**timeframe_type:** `days`

**timeframe_num:** `3`

### `/VDR/data/20x/TFR/VDR-TFR-MVX/varies_by_class/c`

Providers of FedRAMP 20x Class C offerings MUST verify and validate the status of machine-based information resources at least once every 3 days.

**force:** `MUST`

**timeframe_type:** `days`

**timeframe_num:** `3`

### `/VDR/data/rev5/TFR/VDR-TFR-MVF/varies_by_class/c`

Providers of FedRAMP Rev5 Class C offerings MUST verify and validate the status of machine-based information resources at least once every month.

**force:** `MUST`

**timeframe_type:** `months`

**timeframe_num:** `1`

### `/VER/data/all/TFR/VER-TFR-MRH/varies_by_class/c`

Providers with Class C Certifications SHOULD make all recent historical vulnerability detection and response activity available in JSON format for automated retrieval by all necessary parties (e.g. using an API service or similar); this information SHOULD be updated persistently, at least once every 14 days.

**force:** `SHOULD`

**timeframe_type:** `days`

**timeframe_num:** `14`

**artifacts:** `{'all': ['URL and access instructions for historical vulnerability detection and response activity in machine readable format', 'or an explanation of why machine readable content is not being provided']}`

### `/VER/data/all/TFR/VER-TFR-EVU/varies_by_class/c`

Providers with Class C Certifications SHOULD evaluate ALL vulnerabilities as required by VER-EVA (Evaluation) within 5 days of detection.

**force:** `SHOULD`

**timeframe_type:** `days`

**timeframe_num:** `5`

### `/VER/data/all/TFR/VER-TFR-IRI/varies_by_class/c`

Providers with Class C Certifications SHOULD treat internet-reachable likely exploitable vulnerabilities where Potential Agency Impact N-rating > 3 as a FedRAMP Reportable Incident until they are partially mitigated vulnerabilities at N3 or below.

**force:** `SHOULD`

### `/VER/data/all/TFR/VER-TFR-NRI/varies_by_class/c`

Providers with Class C Certifications MAY treat likely exploitable vulnerabilities that are NOT internet-reachable where Potential Agency Impact N-rating = 5 as a FedRAMP Reportable Incident until they are partially mitigated vulnerabilities at N4 or below.

**force:** `MAY`

## 9. Schema Definitions Relevant to This Analysis

### `control_id`

```json
{
  "type": "string",
  "pattern": "^[a-z]{2}-\\d+(?:\\.\\d+)?$"
}
```

### `rev5_control_id`

```json
{
  "type": "string",
  "pattern": "^[A-Z]{2}-\\d{2}(?: \\(\\d{2}\\))?$"
}
```

### `rev5_controls_list`

```json
{
  "type": "object",
  "minProperties": 1,
  "propertyNames": {
    "pattern": "^[A-Z]{2}$"
  },
  "additionalProperties": {
    "type": "array",
    "items": {
      "$ref": "#/$defs/rev5_control_id"
    },
    "minItems": 1,
    "uniqueItems": true
  }
}
```

### `ksi_indicator_level`

```json
{
  "type": "object",
  "required": [
    "statement"
  ],
  "properties": {
    "statement": {
      "type": "string"
    },
    "artifacts": {
      "$ref": "#/$defs/artifacts"
    }
  },
  "additionalProperties": false
}
```

## 10. Implementation / Evidence Reuse Signals

The mapping shows where one control can participate in evidence or implementation work for multiple KSIs. The strongest reuse candidates are the controls with the largest KSI overlap, especially where they also belong to the Class C baseline.

- **sc-23** → 6 KSIs → KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT, KSI-SVC-SIN, KSI-SVC-VCM, KSI-SVC-VRI
- **ac-17.3** → 5 KSIs → KSI-CNA-IBP, KSI-CNA-MAT, KSI-CNA-RNT, KSI-CNA-ULN, KSI-IAM-ELP
- **ac-20.1** → 5 KSIs → KSI-CNA-MAT, KSI-IAM-ELP, KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-OSM
- **cm-2** → 5 KSIs → KSI-CMT-RMV, KSI-CNA-DFP, KSI-CNA-IBP, KSI-MLA-EVC, KSI-SVC-ACM
- **ac-2** → 4 KSIs → KSI-IAM-APM, KSI-IAM-JIT, KSI-IAM-SNU, KSI-IAM-SUS
- **ac-2.4** → 4 KSIs → KSI-IAM-JIT, KSI-MLA-LET, KSI-MLA-RVL, KSI-SVC-ACM
- **au-2** → 4 KSIs → KSI-CMT-LMC, KSI-MLA-LET, KSI-MLA-OSM, KSI-MLA-RVL
- **cm-3** → 4 KSIs → KSI-CMT-LMC, KSI-CMT-RMV, KSI-CMT-RVP, KSI-CMT-VTD
- **cm-6** → 4 KSIs → KSI-CMT-LMC, KSI-CMT-RMV, KSI-MLA-EVC, KSI-SVC-ACM
- **cm-7.1** → 4 KSIs → KSI-CMT-RVP, KSI-CNA-RNT, KSI-SVC-ACM, KSI-SVC-EIS
- **cp-10** → 4 KSIs → KSI-RPL-ABO, KSI-RPL-ARP, KSI-RPL-RRO, KSI-RPL-TRC
- **ia-5.2** → 4 KSIs → KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-SNU, KSI-SVC-ASM
- **ir-4.1** → 4 KSIs → KSI-INR-AAR, KSI-INR-RIR, KSI-INR-RPI, KSI-MLA-OSM
- **sc-4** → 4 KSIs → KSI-CNA-ULN, KSI-IAM-ELP, KSI-PIY-RSD, KSI-SVC-PRR
- **ac-17.1** → 3 KSIs → KSI-IAM-ELP, KSI-MLA-LET, KSI-MLA-OSM
- **ac-17.2** → 3 KSIs → KSI-IAM-ELP, KSI-SVC-ASM, KSI-SVC-SIN
- **ac-2.2** → 3 KSIs → KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SNU
- **ac-2.3** → 3 KSIs → KSI-IAM-AAM, KSI-IAM-JIT, KSI-IAM-SUS
- **ac-20** → 3 KSIs → KSI-IAM-ELP, KSI-SCR-MIT, KSI-SCR-MON
- **ac-3** → 3 KSIs → KSI-IAM-APM, KSI-IAM-ELP, KSI-IAM-JIT

## 11. Important Interpretation

- A KSI's `controls` list identifies controls associated with that indicator; it does not by itself prove that satisfying one control automatically satisfies the entire KSI.
- Class C baseline membership is determined here by normalized Rev5 control-family/number matching.
- Shared-control analysis identifies potential reuse and dependency hotspots; actual compliance/evidence sufficiency still depends on the applicable rule, control requirements, parameters, and implementation evidence.

