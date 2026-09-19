# Third-Party AI Vendor Risk Assessment


## Scorecard

| Domain                           | Weight %                |   Score % |   Weighted Contribution |
|:---------------------------------|:------------------------|----------:|------------------------:|
| Security                         | 25                      |        85 |                   21.25 |
| Privacy & Data Protection        | 15                      |        72 |                   10.8  |
| AI Governance                    | 20                      |        61 |                   12.2  |
| Compliance & Legal               | 10                      |        80 |                    8    |
| Resilience & Business Continuity | 10                      |        90 |                    9    |
| Model & AI Assurance             | 10                      |        68 |                    6.8  |
| Third-Party & Supply Chain       | 5                       |        80 |                    4    |
| Contractual & Exit Controls      | 5                       |        60 |                    3    |
| TOTAL                            | 100                     |           |                   75.05 |
| Decision                         | APPROVE WITH CONDITIONS |           |                         |



## Questionnaire

| ID     | Domain                           | Question                                                                                          | Score (0-5)   | Evidence   | Notes   | Remediation   |
|:-------|:---------------------------------|:--------------------------------------------------------------------------------------------------|:--------------|:-----------|:--------|:--------------|
| SEC-01 | Security                         | Does the vendor maintain a documented information security programme approved by management?      |               |            |         |               |
| SEC-02 | Security                         | Does the vendor maintain current ISO/IEC 27001 certification or equivalent independent assurance? |               |            |         |               |
| SEC-03 | Security                         | Does the vendor maintain a current SOC 2 Type II report covering the service?                     |               |            |         |               |
| SEC-04 | Security                         | Is MFA mandatory for privileged administrative access?                                            |               |            |         |               |
| SEC-05 | Security                         | Is MFA mandatory for customer administrator access?                                               |               |            |         |               |
| SEC-06 | Security                         | Are least-privilege and role-based access controls implemented?                                   |               |            |         |               |
| SEC-07 | Security                         | Are privileged access rights reviewed periodically?                                               |               |            |         |               |
| SEC-08 | Security                         | Is customer data encrypted in transit?                                                            |               |            |         |               |
| SEC-09 | Security                         | Is customer data encrypted at rest?                                                               |               |            |         |               |
| SEC-10 | Security                         | Are cryptographic keys centrally managed and rotated?                                             |               |            |         |               |
| SEC-11 | Security                         | Are production systems scanned for vulnerabilities on a defined schedule?                         |               |            |         |               |
| SEC-12 | Security                         | Does the vendor conduct independent penetration testing?                                          |               |            |         |               |
| SEC-13 | Security                         | Are critical vulnerabilities subject to defined remediation SLAs?                                 |               |            |         |               |
| SEC-14 | Security                         | Does the vendor operate a secure software development lifecycle?                                  |               |            |         |               |
| SEC-15 | Security                         | Are third-party dependencies inventoried and vulnerability-managed?                               |               |            |         |               |
| SEC-16 | Security                         | Are secrets and API keys protected from source-code exposure?                                     |               |            |         |               |
| SEC-17 | Security                         | Are privileged and security-relevant actions logged?                                              |               |            |         |               |
| SEC-18 | Security                         | Does the vendor maintain continuous or near-real-time security monitoring?                        |               |            |         |               |
| SEC-19 | Security                         | Does the vendor maintain and exercise an incident-response plan?                                  |               |            |         |               |
| SEC-20 | Security                         | Can the vendor provide independent security assurance evidence relevant to the service?           |               |            |         |               |
| PRI-01 | Privacy & Data Protection        | Does the vendor maintain an inventory of personal data processed by the AI service?               |               |            |         |               |
| PRI-02 | Privacy & Data Protection        | Are processing purposes documented and limited to defined business purposes?                      |               |            |         |               |
| PRI-03 | Privacy & Data Protection        | Does the vendor apply data minimisation?                                                          |               |            |         |               |
| PRI-04 | Privacy & Data Protection        | Are retention periods defined for candidate and employee data?                                    |               |            |         |               |
| PRI-05 | Privacy & Data Protection        | Can the customer require deletion of its data?                                                    |               |            |         |               |
| PRI-06 | Privacy & Data Protection        | Does the vendor test end-to-end deletion across production and backup environments?               |               |            |         |               |
| PRI-07 | Privacy & Data Protection        | Is customer data prohibited from shared-model training without explicit authorisation?            |               |            |         |               |
| PRI-08 | Privacy & Data Protection        | Can the customer opt out of secondary uses of its data?                                           |               |            |         |               |
| PRI-09 | Privacy & Data Protection        | Are data residency and processing locations documented?                                           |               |            |         |               |
| PRI-10 | Privacy & Data Protection        | Does the vendor maintain a current subprocessor list?                                             |               |            |         |               |
| PRI-11 | Privacy & Data Protection        | Are appropriate safeguards used for international data transfers?                                 |               |            |         |               |
| PRI-12 | Privacy & Data Protection        | Does the vendor provide timely privacy-incident notification?                                     |               |            |         |               |
| AIG-01 | AI Governance                    | Does the vendor maintain a formal AI governance policy?                                           |               |            |         |               |
| AIG-02 | AI Governance                    | Does the vendor operate an AI risk management framework?                                          |               |            |         |               |
| AIG-03 | AI Governance                    | Does the vendor maintain an inventory of AI systems and material AI components?                   |               |            |         |               |
| AIG-04 | AI Governance                    | Is there a named accountable owner for the AI service?                                            |               |            |         |               |
| AIG-05 | AI Governance                    | Are AI systems classified according to risk and impact?                                           |               |            |         |               |
| AIG-06 | AI Governance                    | Does the vendor conduct AI impact assessments for high-impact use cases?                          |               |            |         |               |
| AIG-07 | AI Governance                    | Are human-oversight responsibilities defined for recruitment decisions?                           |               |            |         |               |
| AIG-08 | AI Governance                    | Is there a documented process for approving material AI-system changes?                           |               |            |         |               |
| AIG-09 | AI Governance                    | Does the vendor notify customers of material model changes?                                       |               |            |         |               |
| AIG-10 | AI Governance                    | Does the vendor maintain an AI incident taxonomy and escalation process?                          |               |            |         |               |
| AIG-11 | AI Governance                    | Are AI systems tested before production deployment?                                               |               |            |         |               |
| AIG-12 | AI Governance                    | Is ongoing model monitoring performed?                                                            |               |            |         |               |
| AIG-13 | AI Governance                    | Does the vendor conduct bias and fairness testing relevant to recruitment?                        |               |            |         |               |
| AIG-14 | AI Governance                    | Are known model limitations and intended-use boundaries documented?                               |               |            |         |               |
| AIG-15 | AI Governance                    | Does the vendor provide meaningful AI functionality and limitation information?                   |               |            |         |               |
| AIG-16 | AI Governance                    | Is AI governance independently reviewed on a defined basis?                                       |               |            |         |               |
| COM-01 | Compliance & Legal               | Does the vendor maintain a documented regulatory and legal compliance programme?                  |               |            |         |               |
| COM-02 | Compliance & Legal               | Does the vendor assess AI regulatory requirements across relevant jurisdictions?                  |               |            |         |               |
| COM-03 | Compliance & Legal               | Are records maintained for AI systems subject to regulatory obligations?                          |               |            |         |               |
| COM-04 | Compliance & Legal               | Can the vendor contractually support the customer’s regulatory obligations?                       |               |            |         |               |
| COM-05 | Compliance & Legal               | Can the vendor provide evidence needed for customer or regulator audits?                          |               |            |         |               |
| COM-06 | Compliance & Legal               | Does the vendor monitor relevant AI, privacy, employment and cybersecurity regulatory changes?    |               |            |         |               |
| COM-07 | Compliance & Legal               | Does the vendor support legal holds where applicable?                                             |               |            |         |               |
| COM-08 | Compliance & Legal               | Are intellectual-property rights and responsibilities clearly defined?                            |               |            |         |               |
| RES-01 | Resilience & Business Continuity | Does the vendor maintain a documented business continuity programme?                              |               |            |         |               |
| RES-02 | Resilience & Business Continuity | Does the vendor maintain and test disaster recovery plans?                                        |               |            |         |               |
| RES-03 | Resilience & Business Continuity | Are RTO and RPO defined?                                                                          |               |            |         |               |
| RES-04 | Resilience & Business Continuity | Does the service use resilient/high-availability architecture?                                    |               |            |         |               |
| RES-05 | Resilience & Business Continuity | Are service availability commitments documented in an SLA?                                        |               |            |         |               |
| RES-06 | Resilience & Business Continuity | Are backups tested for restoration effectiveness?                                                 |               |            |         |               |
| RES-07 | Resilience & Business Continuity | Does the vendor assess concentration risk from critical cloud/model dependencies?                 |               |            |         |               |
| RES-08 | Resilience & Business Continuity | Does the vendor maintain a documented service-exit strategy?                                      |               |            |         |               |
| MOD-01 | Model & AI Assurance             | Does the vendor document model architecture or material model components?                         |               |            |         |               |
| MOD-02 | Model & AI Assurance             | Does the vendor maintain documented training-data governance practices?                           |               |            |         |               |
| MOD-03 | Model & AI Assurance             | Does the vendor assess training-data quality, provenance and suitability?                         |               |            |         |               |
| MOD-04 | Model & AI Assurance             | Does the vendor perform benchmark and performance evaluation before release?                      |               |            |         |               |
| MOD-05 | Model & AI Assurance             | Does the vendor conduct fairness evaluation relevant to employment outcomes?                      |               |            |         |               |
| MOD-06 | Model & AI Assurance             | Does the vendor provide meaningful explainability information for high-impact outputs?            |               |            |         |               |
| MOD-07 | Model & AI Assurance             | Does the vendor monitor model performance and drift?                                              |               |            |         |               |
| MOD-08 | Model & AI Assurance             | Does the vendor maintain a model card, system card or equivalent assurance document?              |               |            |         |               |
| SUP-01 | Third-Party & Supply Chain       | Does the vendor operate a formal third-party risk-management programme?                           |               |            |         |               |
| SUP-02 | Third-Party & Supply Chain       | Are critical subprocessors assessed before supporting the service?                                |               |            |         |               |
| SUP-03 | Third-Party & Supply Chain       | Does the vendor maintain an inventory of material AI, cloud, model and technology dependencies?   |               |            |         |               |
| SUP-04 | Third-Party & Supply Chain       | Are critical suppliers included in supply-chain incident response and recovery planning?          |               |            |         |               |
| CTR-01 | Contractual & Exit Controls      | Does the contract prohibit unauthorised secondary use of customer data?                           |               |            |         |               |
| CTR-02 | Contractual & Exit Controls      | Does the contract require notification of material AI, security and privacy incidents?            |               |            |         |               |
| CTR-03 | Contractual & Exit Controls      | Does the contract provide risk-based audit or independent-assurance rights?                       |               |            |         |               |
| CTR-04 | Contractual & Exit Controls      | Does the contract require secure termination, data return and verifiable deletion?                |               |            |         |               |



## Risk Register

| Risk ID   | Risk                                        | Domain                   |   Likelihood |   Impact |   Score | Rating   | Treatment   | Required Action                                                                                             |
|:----------|:--------------------------------------------|:-------------------------|-------------:|---------:|--------:|:---------|:------------|:------------------------------------------------------------------------------------------------------------|
| VR-001    | Inadequate AI governance documentation      | AI Governance            |            4 |        5 |      20 | Critical | Mitigate    | Complete AI governance framework, inventory, impact assessment and accountable ownership before production. |
| VR-002    | Recruitment bias or discriminatory outcomes | AI / Model Assurance     |            3 |        5 |      15 | High     | Mitigate    | Require fairness testing, thresholds, remediation and human review.                                         |
| VR-003    | Uncontrolled material model changes         | AI Governance            |            4 |        4 |      16 | High     | Mitigate    | Add contractual model-change notification and reassessment triggers.                                        |
| VR-004    | Incomplete data deletion evidence           | Privacy                  |            3 |        5 |      15 | High     | Mitigate    | Require deletion testing and certification.                                                                 |
| VR-005    | Limited audit rights                        | Contractual              |            3 |        4 |      12 | High     | Contract    | Negotiate risk-based audit and assurance rights.                                                            |
| VR-006    | Subprocessor/model-provider dependency      | Supply Chain             |            3 |        4 |      12 | High     | Monitor     | Maintain dependency inventory and material-change notification.                                             |
| VR-007    | AI service outage                           | Resilience               |            2 |        4 |       8 | Moderate | Mitigate    | Validate SLA, RTO/RPO, DR testing and exit procedures.                                                      |
| VR-008    | Model performance degradation               | Model Assurance          |            3 |        4 |      12 | High     | Monitor     | Require performance and drift monitoring.                                                                   |
| VR-009    | Privacy or regulatory breach                | Privacy / Compliance     |            3 |        5 |      15 | High     | Mitigate    | Strengthen notification, transfer and regulatory cooperation controls.                                      |
| VR-010    | Vendor lock-in                              | Contractual / Resilience |            3 |        3 |       9 | Moderate | Mitigate    | Require data portability and practical exit procedures.                                                     |



## Evidence

| Evidence ID   | Evidence                        | Domain                   | Status   | Assessment / Next Action                                  |
|:--------------|:--------------------------------|:-------------------------|:---------|:----------------------------------------------------------|
| EV-001        | ISO/IEC 27001 certificate       | Security                 | Provided | Validate scope, validity and service coverage.            |
| EV-002        | SOC 2 Type II report            | Security                 | Provided | Validate reporting period and scope.                      |
| EV-003        | Penetration test summary        | Security                 | Provided | Review date, scope and critical findings.                 |
| EV-004        | Vulnerability management policy | Security                 | Provided | Validate critical-vulnerability SLA.                      |
| EV-005        | Encryption architecture         | Security                 | Provided | Validate encryption and key management.                   |
| EV-006        | MFA / IAM evidence              | Security                 | Provided | Validate privileged and customer-admin MFA.               |
| EV-007        | Privacy / DPA documentation     | Privacy                  | Provided | Validate processing, retention, transfer and deletion.    |
| EV-008        | Subprocessor list               | Privacy / Supply Chain   | Provided | Validate locations and critical providers.                |
| EV-009        | AI governance policy            | AI Governance            | Partial  | Request complete policy and ownership model.              |
| EV-010        | AI risk framework               | AI Governance            | Partial  | Request classification and assessment methodology.        |
| EV-011        | AI system inventory             | AI Governance            | Partial  | Request current inventory and dependencies.               |
| EV-012        | Fairness testing report         | AI / Model Assurance     | Partial  | Request methodology, results and remediation.             |
| EV-013        | Model/system card               | AI Assurance             | Partial  | Request limitations and evaluation information.           |
| EV-014        | Human oversight documentation   | AI Governance            | Partial  | Clarify recruiter review and escalation responsibilities. |
| EV-015        | AI incident process             | AI Governance            | Provided | Validate notification triggers.                           |
| EV-016        | Model change process            | AI Governance            | Gap      | Contractual notification and reassessment required.       |
| EV-017        | Audit rights clause             | Contractual              | Gap      | Negotiate risk-based assurance rights.                    |
| EV-018        | Deletion evidence               | Privacy                  | Partial  | Require end-to-end deletion testing.                      |
| EV-019        | Business continuity test        | Resilience               | Provided | Validate scope and recovery results.                      |
| EV-020        | Exit plan                       | Resilience / Contractual | Partial  | Require practical portability and termination steps.      |



## Contract Controls

| Control ID   | Control Area             | Requirement                                                                            |
|:-------------|:-------------------------|:---------------------------------------------------------------------------------------|
| CC-01        | Data Use                 | No unauthorised secondary use or shared-model training without explicit authorisation. |
| CC-02        | AI Incident Notification | Notify of material AI, security, privacy or safety incidents within a defined SLA.     |
| CC-03        | Audit & Assurance        | Provide risk-based audit, assessment and independent-assurance rights.                 |
| CC-04        | Secure Termination       | Return/export customer data and provide verifiable deletion.                           |
| CC-05        | Material AI Changes      | Notify of material model, training-data, architecture or capability changes.           |
| CC-06        | Fairness Assurance       | Maintain and provide appropriate fairness testing and remediation evidence.            |
| CC-07        | Subprocessors            | Maintain a current subprocessor list and notify material additions.                    |
| CC-08        | Security Assurance       | Maintain agreed security controls and vulnerability commitments.                       |
| CC-09        | Business Continuity      | Maintain tested continuity and recovery capabilities.                                  |
| CC-10        | Regulatory Cooperation   | Support regulatory inquiries, evidence requests and compliance obligations.            |



## Findings

| Finding ID   | Finding                                | Severity    | Observation                                                                                      | Due               | Remediation                                                                                  |
|:-------------|:---------------------------------------|:------------|:-------------------------------------------------------------------------------------------------|:------------------|:---------------------------------------------------------------------------------------------|
| V-001        | AI Governance Documentation Incomplete | High        | AI governance policy, inventory and risk methodology evidence is incomplete.                     | Before production | Complete AI governance framework, accountable ownership, inventory and AI impact assessment. |
| V-002        | Fairness Testing Evidence Incomplete   | High        | Recruitment fairness evidence does not demonstrate complete coverage and remediation thresholds. | Before production | Provide methodology, scope, results, thresholds and remediation evidence.                    |
| V-003        | Model Change Notification Insufficient | High        | Contractual language does not clearly require notification of material AI/model changes.         | Before contract   | Add material-change notification, reassessment and objection/exit provisions.                |
| V-004        | Audit Rights Limited                   | Medium-High | Assurance is available but direct customer audit rights are constrained.                         | Before contract   | Negotiate risk-based audit and evidence-access rights.                                       |
| V-005        | Data Deletion Evidence Partial         | Medium      | Deletion controls are documented but end-to-end verification is incomplete.                      | Before production | Provide deletion testing and certification.                                                  |

