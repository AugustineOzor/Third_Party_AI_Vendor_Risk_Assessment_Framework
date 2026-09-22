# AI Vendor Risk Questionnaire

**Scoring scale:** 0–5, where 0 = absent/unacceptable and 5 = optimised/independently assured. Score, Evidence, Notes, and Remediation columns are blank in the source file, ready to be completed during an assessment.

## Security (SEC-01 to SEC-20)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| SEC-01 | Does the vendor maintain a documented information security programme approved by management? | | | | |
| SEC-02 | Does the vendor maintain current ISO/IEC 27001 certification or equivalent independent assurance? | | | | |
| SEC-03 | Does the vendor maintain a current SOC 2 Type II report covering the service? | | | | |
| SEC-04 | Is MFA mandatory for privileged administrative access? | | | | |
| SEC-05 | Is MFA mandatory for customer administrator access? | | | | |
| SEC-06 | Are least-privilege and role-based access controls implemented? | | | | |
| SEC-07 | Are privileged access rights reviewed periodically? | | | | |
| SEC-08 | Is customer data encrypted in transit? | | | | |
| SEC-09 | Is customer data encrypted at rest? | | | | |
| SEC-10 | Are cryptographic keys centrally managed and rotated? | | | | |
| SEC-11 | Are production systems scanned for vulnerabilities on a defined schedule? | | | | |
| SEC-12 | Does the vendor conduct independent penetration testing? | | | | |
| SEC-13 | Are critical vulnerabilities subject to defined remediation SLAs? | | | | |
| SEC-14 | Does the vendor operate a secure software development lifecycle? | | | | |
| SEC-15 | Are third-party dependencies inventoried and vulnerability-managed? | | | | |
| SEC-16 | Are secrets and API keys protected from source-code exposure? | | | | |
| SEC-17 | Are privileged and security-relevant actions logged? | | | | |
| SEC-18 | Does the vendor maintain continuous or near-real-time security monitoring? | | | | |
| SEC-19 | Does the vendor maintain and exercise an incident-response plan? | | | | |
| SEC-20 | Can the vendor provide independent security assurance evidence relevant to the service? | | | | |

## Privacy & Data Protection (PRI-01 to PRI-12)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| PRI-01 | Does the vendor maintain an inventory of personal data processed by the AI service? | | | | |
| PRI-02 | Are processing purposes documented and limited to defined business purposes? | | | | |
| PRI-03 | Does the vendor apply data minimisation? | | | | |
| PRI-04 | Are retention periods defined for candidate and employee data? | | | | |
| PRI-05 | Can the customer require deletion of its data? | | | | |
| PRI-06 | Does the vendor test end-to-end deletion across production and backup environments? | | | | |
| PRI-07 | Is customer data prohibited from shared-model training without explicit authorisation? | | | | |
| PRI-08 | Can the customer opt out of secondary uses of its data? | | | | |
| PRI-09 | Are data residency and processing locations documented? | | | | |
| PRI-10 | Does the vendor maintain a current subprocessor list? | | | | |
| PRI-11 | Are appropriate safeguards used for international data transfers? | | | | |
| PRI-12 | Does the vendor provide timely privacy-incident notification? | | | | |

## AI Governance (AIG-01 to AIG-16)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| AIG-01 | Does the vendor maintain a formal AI governance policy? | | | | |
| AIG-02 | Does the vendor operate an AI risk management framework? | | | | |
| AIG-03 | Does the vendor maintain an inventory of AI systems and material AI components? | | | | |
| AIG-04 | Is there a named accountable owner for the AI service? | | | | |
| AIG-05 | Are AI systems classified according to risk and impact? | | | | |
| AIG-06 | Does the vendor conduct AI impact assessments for high-impact use cases? | | | | |
| AIG-07 | Are human-oversight responsibilities defined for recruitment decisions? | | | | |
| AIG-08 | Is there a documented process for approving material AI-system changes? | | | | |
| AIG-09 | Does the vendor notify customers of material model changes? | | | | |
| AIG-10 | Does the vendor maintain an AI incident taxonomy and escalation process? | | | | |
| AIG-11 | Are AI systems tested before production deployment? | | | | |
| AIG-12 | Is ongoing model monitoring performed? | | | | |
| AIG-13 | Does the vendor conduct bias and fairness testing relevant to recruitment? | | | | |
| AIG-14 | Are known model limitations and intended-use boundaries documented? | | | | |
| AIG-15 | Does the vendor provide meaningful AI functionality and limitation information? | | | | |
| AIG-16 | Is AI governance independently reviewed on a defined basis? | | | | |

## Compliance & Legal (COM-01 to COM-08)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| COM-01 | Does the vendor maintain a documented regulatory and legal compliance programme? | | | | |
| COM-02 | Does the vendor assess AI regulatory requirements across relevant jurisdictions? | | | | |
| COM-03 | Are records maintained for AI systems subject to regulatory obligations? | | | | |
| COM-04 | Can the vendor contractually support the customer's regulatory obligations? | | | | |
| COM-05 | Can the vendor provide evidence needed for customer or regulator audits? | | | | |
| COM-06 | Does the vendor monitor relevant AI, privacy, employment and cybersecurity regulatory changes? | | | | |
| COM-07 | Does the vendor support legal holds where applicable? | | | | |
| COM-08 | Are intellectual-property rights and responsibilities clearly defined? | | | | |

## Resilience & Business Continuity (RES-01 to RES-08)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| RES-01 | Does the vendor maintain a documented business continuity programme? | | | | |
| RES-02 | Does the vendor maintain and test disaster recovery plans? | | | | |
| RES-03 | Are RTO and RPO defined? | | | | |
| RES-04 | Does the service use resilient/high-availability architecture? | | | | |
| RES-05 | Are service availability commitments documented in an SLA? | | | | |
| RES-06 | Are backups tested for restoration effectiveness? | | | | |
| RES-07 | Does the vendor assess concentration risk from critical cloud/model dependencies? | | | | |
| RES-08 | Does the vendor maintain a documented service-exit strategy? | | | | |

## Model & AI Assurance (MOD-01 to MOD-08)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| MOD-01 | Does the vendor document model architecture or material model components? | | | | |
| MOD-02 | Does the vendor maintain documented training-data governance practices? | | | | |
| MOD-03 | Does the vendor assess training-data quality, provenance and suitability? | | | | |
| MOD-04 | Does the vendor perform benchmark and performance evaluation before release? | | | | |
| MOD-05 | Does the vendor conduct fairness evaluation relevant to employment outcomes? | | | | |
| MOD-06 | Does the vendor provide meaningful explainability information for high-impact outputs? | | | | |
| MOD-07 | Does the vendor monitor model performance and drift? | | | | |
| MOD-08 | Does the vendor maintain a model card, system card or equivalent assurance document? | | | | |

## Third-Party & Supply Chain (SUP-01 to SUP-04)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| SUP-01 | Does the vendor operate a formal third-party risk-management programme? | | | | |
| SUP-02 | Are critical subprocessors assessed before supporting the service? | | | | |
| SUP-03 | Does the vendor maintain an inventory of material AI, cloud, model and technology dependencies? | | | | |
| SUP-04 | Are critical suppliers included in supply-chain incident response and recovery planning? | | | | |

## Contractual & Exit Controls (CTR-01 to CTR-04)

| ID | Question | Score (0–5) | Evidence | Notes | Remediation |
|---|---|---|---|---|---|
| CTR-01 | Does the contract prohibit unauthorised secondary use of customer data? | | | | |
| CTR-02 | Does the contract require notification of material AI, security and privacy incidents? | | | | |
| CTR-03 | Does the contract provide risk-based audit or independent-assurance rights? | | | | |
| CTR-04 | Does the contract require secure termination, data return and verifiable deletion? | | | | |
