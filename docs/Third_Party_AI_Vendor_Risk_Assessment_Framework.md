# Project 4 — Third-Party AI Vendor Risk Assessment Framework

**Organisation:** Northstar Financial Services (fictional)  
**Vendor:** TalentSphere AI, Inc. (fictional)  
**Product:** TalentSphere RecruitAI — AI recruitment and candidate-screening SaaS  
**Assessment Date:** September 2026  
**Decision:** **APPROVE WITH CONDITIONS**  
**Calculated Score:** **75.05%**  
**Portfolio Score:** **76%**  
**Risk Posture:** **Medium — with Medium-High AI Governance concerns**

> Fictional portfolio case study. All organisation, vendor, evidence, scores and decisions are simulated.

## 1. Executive Summary
Northstar Financial Services is evaluating TalentSphere RecruitAI to support candidate screening, ranking and recruiter workflows. Because the service processes applicant information and may influence employment decisions, conventional SaaS due diligence alone is insufficient. This assessment combines cybersecurity, privacy, AI governance, model assurance, compliance, resilience, supply-chain and contractual controls.

The assessment is evidence-based: vendor claims are not treated as sufficient evidence without supporting documentation. The decision is **Approve with Conditions** because the vendor demonstrates a credible conventional security and resilience baseline, while material AI-governance and contractual gaps remain.

## 2. Fictional Business Scenario
Northstar has approximately 5,000 employees across the US, UK, EU and Middle East. It is building an enterprise AI governance programme and requires a repeatable third-party AI assessment process.

RecruitAI is proposed for résumé/CV parsing, skills extraction, candidate classification, candidate ranking, recruiter recommendations, recruitment analytics and workflow assistance.

### Why the service is high-interest
- personal candidate data may be processed;
- AI outputs may influence employment decisions;
- model behaviour can change;
- third-party models/subprocessors may be involved;
- fairness and explainability are relevant;
- vendor outage could affect recruitment operations.

## 3. Assessment Objectives
1. Evaluate cybersecurity controls.
2. Assess privacy and personal-data risks.
3. Assess AI governance maturity.
4. Evaluate model and AI assurance.
5. Review regulatory and legal readiness.
6. Assess resilience and business continuity.
7. Assess AI/cloud/subprocessor supply-chain risk.
8. Identify contract and exit gaps.
9. Produce an evidence-backed risk score.
10. Recommend Approve, Reject or Approve with Conditions.

## 4. Assessment Lifecycle
```text
Business Requirement → Vendor Intake → Criticality Assessment →
80-Question Questionnaire → Evidence Collection → Security/Privacy/AI Review →
Risk Scoring → Gap Analysis → Contract Review → Management Decision →
Conditional Approval/Remediation → Continuous Monitoring → Annual Reassessment
```

## 5. Vendor Criticality
| Factor | Rating |
|---|---|
| Data sensitivity | High |
| Personal data | High |
| Employment impact | High |
| AI dependence | High |
| Business criticality | Medium-High |
| Regulatory exposure | High |
| Supplier substitutability | Medium |
| Operational dependency | Medium-High |
| **Overall criticality** | **High** |

## 6. Domain Assessment
### Security — 85%
Strong baseline with ISO/IEC 27001, SOC 2 Type II, encryption, MFA, vulnerability management, penetration testing and incident-response evidence. Remaining focus is integration of conventional security assurance with AI assurance.

### Privacy & Data Protection — 72%
Moderate posture. Main gaps are end-to-end deletion evidence and clarity over secondary/model-development use.

### AI Governance — 61%
Primary weakness. Gaps include incomplete AI governance documentation, partial AI inventory, incomplete risk methodology, incomplete fairness evidence, unclear human-oversight documentation and insufficient material model-change notification.

### Compliance & Legal — 80%
Acceptable baseline, subject to jurisdiction-specific and employment-use-case review.

### Resilience & Business Continuity — 90%
Strong. Remaining focus is dependency concentration, exit planning, portability and recovery validation.

### Model & AI Assurance — 68%
Medium-High concern around fairness testing, explainability, model limitations, monitoring and model-change governance.

### Third-Party & Supply Chain — 80%
Acceptable, but greater visibility into material AI/model/cloud dependencies and critical subprocessors is required.

### Contractual & Exit Controls — 60%
Material gaps in audit rights, model-change notification, deletion assurance, secondary-use restrictions and exit requirements.

## 7. Vendor Risk Scorecard
| Domain | Weight | Score | Weighted Contribution |
|---|---:|---:|---:|
| Security | 25% | 85% | 21.25 |
| Privacy & Data Protection | 15% | 72% | 10.80 |
| AI Governance | 20% | 61% | 12.20 |
| Compliance & Legal | 10% | 80% | 8.00 |
| Resilience & Business Continuity | 10% | 90% | 9.00 |
| Model & AI Assurance | 10% | 68% | 6.80 |
| Third-Party & Supply Chain | 5% | 80% | 4.00 |
| Contractual & Exit Controls | 5% | 60% | 3.00 |
| **Total** | **100%** | — | **75.05%** |

### Decision thresholds
| Score | Risk | Default |
|---:|---|---|
| 90–100 | Low | Approve |
| 80–89 | Low-Moderate | Approve |
| 70–79 | Medium | Approve with Conditions |
| 60–69 | Medium-High | Conditional Approval / Remediation |
| <60 | High | Reject or Major Remediation |

A critical unresolved finding can override the numerical score.

## 8. Risk Register
| ID | Risk | L | I | Score | Rating | Treatment |
|---|---|---:|---:|---:|---|---|
| VR-001 | Inadequate AI governance documentation | 4 | 5 | 20 | Critical | Mitigate |
| VR-002 | Recruitment bias or discriminatory outcomes | 3 | 5 | 15 | High | Mitigate |
| VR-003 | Uncontrolled material model changes | 4 | 4 | 16 | High | Mitigate |
| VR-004 | Incomplete data deletion evidence | 3 | 5 | 15 | High | Mitigate |
| VR-005 | Limited audit rights | 3 | 4 | 12 | High | Contract |
| VR-006 | Subprocessor/model-provider dependency | 3 | 4 | 12 | High | Monitor |
| VR-007 | AI service outage | 2 | 4 | 8 | Moderate | Mitigate |
| VR-008 | Model performance degradation | 3 | 4 | 12 | High | Monitor |
| VR-009 | Privacy or regulatory breach | 3 | 5 | 15 | High | Mitigate |
| VR-010 | Vendor lock-in | 3 | 3 | 9 | Moderate | Mitigate |

Risk score = Likelihood × Impact, using a 1–5 scale.

## 9. Key Findings
### V-001 — AI Governance Documentation Incomplete
**Severity:** High  
**Observation:** AI governance policy, inventory and risk methodology evidence is incomplete.  
**Due:** Before production  
**Remediation:** Complete AI governance framework, accountable ownership, inventory and AI impact assessment.

### V-002 — Fairness Testing Evidence Incomplete
**Severity:** High  
**Observation:** Recruitment fairness evidence does not demonstrate complete coverage and remediation thresholds.  
**Due:** Before production  
**Remediation:** Provide methodology, scope, results, thresholds and remediation evidence.

### V-003 — Model Change Notification Insufficient
**Severity:** High  
**Observation:** Contractual language does not clearly require notification of material AI/model changes.  
**Due:** Before contract  
**Remediation:** Add material-change notification, reassessment and objection/exit provisions.

### V-004 — Audit Rights Limited
**Severity:** Medium-High  
**Observation:** Assurance is available but direct customer audit rights are constrained.  
**Due:** Before contract  
**Remediation:** Negotiate risk-based audit and evidence-access rights.

### V-005 — Data Deletion Evidence Partial
**Severity:** Medium  
**Observation:** Deletion controls are documented but end-to-end verification is incomplete.  
**Due:** Before production  
**Remediation:** Provide deletion testing and certification.

## 10. AI Vendor Questionnaire
The repository contains an **80-question questionnaire** across eight domains.

| Domain | Questions |
|---|---:|
| Security | 20 |
| Privacy & Data Protection | 12 |
| AI Governance | 16 |
| Compliance & Legal | 8 |
| Resilience & Business Continuity | 8 |
| Model & AI Assurance | 8 |
| Third-Party & Supply Chain | 4 |
| Contractual & Exit Controls | 4 |
| **Total** | **80** |

Scoring: 0 absent/unacceptable; 1 initial; 2 partial; 3 defined; 4 mature/evidenced; 5 optimised/independently assured.

## 11. Evidence Requirements
The evidence register covers security assurance, privacy/DPA, AI governance, AI assurance, resilience, subprocessors and contract/exit controls. Strong evidence includes ISO/IEC 27001, SOC 2 Type II, penetration testing, encryption, MFA, privacy documentation and BCP testing. Partial evidence remains in AI governance, fairness, model documentation, human oversight, deletion and exit planning.

## 12. Contractual Requirements
1. **Data Use:** No unauthorised secondary use or shared-model training without explicit authorisation.
2. **AI Incident Notification:** Notify of material AI, security, privacy or safety incidents within a defined SLA.
3. **Audit & Assurance:** Provide risk-based audit, assessment and independent-assurance rights.
4. **Secure Termination:** Return/export customer data and provide verifiable deletion.
5. **Material AI Changes:** Notify of material model, training-data, architecture or capability changes.
6. **Fairness Assurance:** Maintain and provide appropriate fairness testing and remediation evidence.
7. **Subprocessors:** Maintain a current subprocessor list and notify material additions.
8. **Security Assurance:** Maintain agreed security controls and vulnerability commitments.
9. **Business Continuity:** Maintain tested continuity and recovery capabilities.
10. **Regulatory Cooperation:** Support regulatory inquiries, evidence requests and compliance obligations.

## 13. Conditional Approval
### Decision: **APPROVE WITH CONDITIONS**

### Before production
- complete AI governance framework;
- provide current AI inventory;
- complete AI impact assessment;
- provide fairness-testing evidence;
- confirm human-oversight responsibilities;
- provide deletion verification;
- validate model monitoring;
- document model-change process.

### Before contract execution
- add material AI/model-change clause;
- strengthen audit rights;
- restrict secondary use;
- define incident notification;
- define secure termination/deletion;
- define subprocessor notification.

### After go-live
- quarterly remediation review;
- annual formal reassessment;
- material-event reassessment;
- evidence refresh;
- AI performance monitoring;
- fairness monitoring;
- security assurance review.

## 14. Approve / Reject / Conditional Decision Model
**Approve:** residual risk within appetite and material controls evidenced.  
**Reject:** critical risk cannot be mitigated, essential requirements are refused, regulatory obligations cannot be satisfied, or exit options are unacceptable.  
**Approve with Conditions:** viable control environment plus remediable gaps and time-bound conditions.

**Northstar decision: Approve with Conditions.**

## 15. Ongoing Monitoring
Reassessment triggers include major model changes, new AI capabilities, new data categories, new processing countries, new subprocessors, security/privacy incidents, fairness findings, major outages, regulatory changes, acquisitions, new API/tool access and material contract changes.

| Activity | Frequency |
|---|---|
| Security assurance | Annual |
| AI governance review | Annual |
| Formal vendor risk assessment | Annual |
| High-risk remediation review | Quarterly |
| Critical-vendor monitoring | Continuous / event-driven |
| Full reassessment | Trigger-based |

## 16. Executive KPIs
| KPI | Target |
|---|---:|
| Critical findings overdue | 0 |
| Security incident notification compliance | 100% |
| Material AI-change notification | 100% |
| Current assurance evidence | ≥95% |
| High-risk remediation completion | ≥90% |
| Fairness testing completion | 100% |
| Critical subprocessors assessed | 100% |
| Annual vendor review completion | 100% |
| AI incidents within SLA | 100% |

## 17. Framework Alignment
### NIST AI RMF
**Govern:** policy, accountability, third-party governance and documentation.  
**Map:** use case, context, stakeholders, risks and impacts.  
**Measure:** testing, fairness, performance and assurance.  
**Manage:** treatment, remediation, incidents and continual improvement.

### NIST CSF 2.0
The project aligns supplier governance to CSF 2.0 cybersecurity supply-chain outcomes covering supplier prioritisation, contractual requirements, due diligence, ongoing monitoring and supply-chain incident planning.

### ISO/IEC 27001
Used as the information-security management baseline for governance, access control, supplier security, incident management, resilience, monitoring and risk management.

### ISO/IEC 42001
Used as the AI-management-system reference for AI governance, risk management, accountability, lifecycle controls, transparency, human oversight, monitoring and continual improvement.

## 18. Governance Operating Model
```text
Board / Risk Committee
        |
AI Governance Committee
        |
+-------+-------+-------+
|               |       |
CISO            DPO    Legal
        \        |       /
         +-------+------+
                 |
       Procurement / Vendor Risk
                 |
          Business AI Owner
                 |
              AI Vendor
```

## 19. RACI
| Activity | Procurement | Security | Privacy | Legal | AI Governance | Business Owner |
|---|---|---|---|---|---|---|
| Vendor intake | R | C | C | C | C | A |
| Criticality | C | R | C | C | A | A |
| Questionnaire | R | R | R | C | R | C |
| Evidence review | C | A/R | A/R | C | A/R | C |
| AI risk assessment | C | C | C | C | A/R | R |
| Contract controls | R | C | C | A/R | C | A |
| Approval | C | C | C | C | A | A |
| Monitoring | R | R | R | C | A/R | R |
| Reassessment | R | R | R | C | A/R | A |

## 20. Management Recommendation
**Approve with Conditions.** TalentSphere has a credible conventional security and resilience foundation. However, unrestricted production use would be premature because AI governance, fairness assurance, model-change governance and contractual protections are incomplete.

**Recommended path:** security baseline acceptable → privacy acceptable with gaps → AI governance gaps → contractual gaps → time-bound remediation → conditional approval → production after mandatory controls close.

## 21. Professional AI GRC Capability Demonstrated
This project demonstrates third-party AI due diligence, AI vendor questionnaire design, cybersecurity control assessment, privacy assessment, AI governance maturity assessment, model assurance, supply-chain risk analysis, contractual control design, risk scoring, evidence management, remediation planning, executive decision support, framework mapping and ongoing vendor monitoring.

> **Professional positioning:** I assess third-party AI vendors across cybersecurity, privacy, AI governance, regulatory, resilience and model-assurance domains, translating evidence into risk scores, control gaps, contractual requirements and executive approval decisions.

## 22. Repository Structure
```text
project-04-third-party-ai-vendor-risk/
├── README.md
├── SOURCES.md
├── docs/
├── questionnaire/
├── registers/
├── templates/
└── evidence/
```

## 23. Definition of Done
- [x] Fictional enterprise and vendor
- [x] Vendor criticality assessment
- [x] 80-question questionnaire
- [x] Evidence requirements
- [x] Weighted scorecard
- [x] Risk register
- [x] Key findings
- [x] Contract requirements
- [x] Conditional approval
- [x] Management recommendation
- [x] Monitoring model
- [x] Executive KPIs
- [x] RACI
- [x] NIST AI RMF alignment
- [x] NIST CSF 2.0 alignment
- [x] ISO/IEC 27001 alignment
- [x] ISO/IEC 42001 alignment
- [x] Reusable templates

## 24. Portfolio Value
The project demonstrates a complete consulting workflow:

**Business requirement → vendor due diligence → evidence → control assessment → AI risk → scorecard → remediation → contract controls → approval decision → continuous monitoring**

This makes the project suitable as an AI GRC portfolio case study rather than merely an academic discussion.

## Disclaimer
This is a fictional portfolio case study. Vendor names, evidence, scores, risks and decisions are simulated. Frameworks and regulations should be checked against current authoritative publications before real-world use.
