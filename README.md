# CYBER-SECURITY-AUDIT-1
This is my first audit related my cyber security course.

## Botium Toys: Scope, goals, and risk assessment report

#### Scope and goals of the audit

#### Scope: The scope is defined as the entire security program at Botium Toys. This means all assets need to be assessed alongside internal processes and procedures related to the implementation of controls and compliance best practices.

#### Goals: Assess existing assets and complete the controls and compliance checklist to determine which controls and compliance best practices need to be implemented to  improve Botium Toys’ security posture.

### Current assets:

#### Assets managed by the IT Department include: 

- On-premises equipment for in-office business needs  
- Employee equipment: end-user devices (desktops/laptops, smartphones), remote workstations, headsets, cables, keyboards, mice, docking stations, surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the company’s adjoining warehouse
- Management of systems, software, and services: accounting, telecommunication, database, security, ecommerce, and inventory management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human monitoring 

### Risk assessment

#### Risk description

- Currently, there is inadequate management of assets. Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and international regulations and standards. 

#### Control best practices

- The first of the five functions of the NIST CSF is Identify. Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them. Additionally, they will need to classify existing assets and determine the impact of the loss of existing assets, including systems, on business continuity.

#### Risk score

- On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of controls and adherence to compliance best practices.

#### Additional comments

The potential impact from the loss of an asset is rated as medium, because the IT department does not know which assets would be at risk. The risk to assets or fines from governing bodies is high because Botium Toys does not have all of the necessary controls in place and is not fully adhering to best practices related to compliance regulations that keep critical data private/secure. Review the following bullet points for specific details:

- Currently, all Botium Toys employees have access to internally stored data and may be able to access cardholder data and customers’ PII/SPII.
Encryption is not currently used to ensure confidentiality of customers’ credit card information that is accepted, processed, transmitted, and stored locally in the company’s internal database. 
- Access controls pertaining to least privilege and separation of duties have not been implemented.
- The IT department has ensured availability and integrated controls to ensure data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department. 
- The IT department has not installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does not have backups of critical data. 
- The IT department has established a plan to notify E.U. customers within 72 hours if there is a security breach. Additionally, privacy policies, procedures, and processes have been developed and are enforced among IT department members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and not in line with current minimum password complexity requirements (e.g., at least eight characters, a combination of letters and at least one number; special characters). 
- There is no centralized password management system that enforces the password policy’s minimum requirements, which sometimes affects productivity when employees/vendors submit a ticket to the IT department to recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store front, and warehouse of products, has sufficient locks, up-to-date closed-circuit television (CCTV) surveillance, as well as functioning fire detection and prevention systems.

Audit Focus: Entire security program including assets, controls, and compliance with regulatory frameworks.

# CONTROLS ASSESSMENT:

| Control                                  | In Place? | Notes                                                                          |
| ---------------------------------------- | --------- | ------------------------------------------------------------------------------ |
| **Least Privilege**                      |  No      | All employees have access to internally stored data, including cardholder/PII. |
| **Disaster Recovery Plans**              |  No      | No DR plans or critical data backups exist.                                    |
| **Password Policies**                    |  No      | Exists, but not aligned with modern standards (weak complexity requirements).  |
| **Separation of Duties**                 |  No      | Not implemented.                                                               |
| **Firewall**                             |  Yes     | Installed and rule-based filtering in place.                                   |
| **Intrusion Detection System (IDS)**     |  No      | Not installed.                                                                 |
| **Backups**                              |  No      | No backup systems in place.                                                    |
| **Antivirus Software**                   |  Yes     | Regularly monitored.                                                           |
| **Manual Monitoring for Legacy Systems** |  Yes     | Performed, but no schedule or clear intervention plan.                         |
| **Encryption**                           |  No      | No encryption for customer credit card data.                                   |
| **Password Management System**           |  No      | Not centralized; causes productivity issues.                                   |
| **Locks (Physical Security)**            |  Yes     | Sufficient locks in all locations.                                             |
| **CCTV Surveillance**                    |  Yes     | Operational and up to date.                                                    |
| **Fire Detection/Prevention**            |  Yes     | Systems in place and functioning.                                              |

# COMPLIANCE CHECKLIST:

### PCI DSS

| Best Practice                                 | In Place? | Notes                                     |
| --------------------------------------------- | --------- | ----------------------------------------- |
| Only authorized users access credit card data | No      | All employees currently have access.      |
| Secure environment for card data              | No      | Not securely stored or transmitted.       |
| Data encryption                               | No      | Not implemented.                          |
| Secure password management                    | No      | Inadequate policy; no enforcement system. |


### GDPR

| Best Practice                       | In Place? | Notes                   |
| ----------------------------------- | --------- | ----------------------- |
| Private/Secured EU customer data    | Yes     | Some controls in place. |
| Breach notification within 72 hours | Yes     | Plan exists.            |
| Data classification and inventory   | No      | Not yet implemented.    |
| Privacy policies/procedures         | Yes     | Developed and enforced. |


### SOC 1 & SOC 2

| Best Practice                         | In Place? | Notes                            |
| ------------------------------------- | --------- | -------------------------------- |
| User access policies                  | No      | No access controls in place.     |
| Sensitive data kept private           | No      | Not effectively controlled.      |
| Data integrity                        | Yes     | Controls ensure integrity.       |
| Data availability to authorized users | Yes     | Availability ensured by IT team. |


# RISK ASSESSMENT:

| Category                 | Score/Status                                               |
| ------------------------ | ---------------------------------------------------------- |
| **Overall Risk Score**   | 8/10 (High)                                                |
| **Biggest Risk Factors** | Lack of access controls, encryption, backups, and DR plan. |
| **Impact of Loss**       | Medium to High                                             |
| **Regulatory Risk**      | High (noncompliance with PCI DSS and SOC standards)        |


### RECOMMENDATIONS TO IT MANAGER

Implement Least Privilege & Role-Based Access Control.
Deploy Encryption for Cardholder and Sensitive Data.
Establish and Test a Disaster Recovery & Backup Strategy.
Adopt a Centralized Password Management System with Strong Policy Enforcement.
Install Intrusion Detection System (IDS).
Develop a Formal Access Control Policy & User Lifecycle Management.
Classify and Inventory All Data Assets.
Upgrade Password Policy (min 8 chars, complexity, rotation).
Ensure PCI DSS and SOC framework controls are addressed and documented.
