# Vendor AI Governance Questionnaire
**Third-Party AI Risk Assessment | Aligned to NIST AI RMF 1.0 | EU AI Act | ISO/IEC 42001**

---

**Assessment Date:** ___________________________  
**Vendor Name:** ___________________________  
**Product / Service Name:** ___________________________  
**Assessor:** ___________________________  
**Vendor Contact:** ___________________________  
**Response Deadline:** ___________________________

---

## Instructions

This questionnaire must be completed by the vendor prior to procurement of any AI system or AI-powered service. Responses will be used to assess the vendor's AI governance maturity and compliance with applicable regulatory requirements.

**Response Format:** For each question provide a written response. Where evidence is requested attach supporting documentation. Incomplete responses will delay procurement review.

**Evidence Codes:**
- **P** — Policy document
- **R** — Audit report or third-party assessment
- **T** — Technical documentation
- **C** — Contractual provision
- **S** — Screenshot or system demonstration

---

## Section 1 — Organizational AI Governance

### 1.1 Governance Structure

**Q1.1.1** Does your organization have a documented AI governance policy or framework?

- [ ] Yes — attach policy document (P)
- [ ] In development — provide expected completion date: ___________
- [ ] No

*Response:*
_______________________________________________

---

**Q1.1.2** Who is responsible for AI governance within your organization? Provide name, title, and reporting line.

*Response:*
_______________________________________________

---

**Q1.1.3** Does your organization have an AI ethics board, responsible AI committee, or equivalent oversight body?

- [ ] Yes — describe membership and meeting cadence
- [ ] No

*Response:*
_______________________________________________

---

**Q1.1.4** Has your organization adopted any AI governance frameworks? Select all that apply:

- [ ] NIST AI RMF
- [ ] ISO/IEC 42001
- [ ] EU AI Act compliance program
- [ ] OECD AI Principles
- [ ] IEEE Ethically Aligned Design
- [ ] Internal framework — describe: ___________
- [ ] None

*Response:*
_______________________________________________

---

### 1.2 Risk Management

**Q1.2.1** Describe your organization's process for assessing AI risk prior to product deployment.

*Response:*
_______________________________________________

---

**Q1.2.2** Has the AI system being assessed undergone a formal risk assessment? If yes, provide summary findings and attach report (R).

- [ ] Yes — attach report
- [ ] No
- [ ] In progress

*Response:*
_______________________________________________

---

**Q1.2.3** How does your organization classify AI systems by risk level? What criteria are used?

*Response:*
_______________________________________________

---

## Section 2 — Training Data Governance

**Q2.1** Describe the data sources used to train the AI system. Include data types, geographic origin, and collection method.

*Response:*
_______________________________________________

---

**Q2.2** What is the demographic composition of the training dataset? Provide breakdown by relevant protected characteristics (race, gender, age, etc.) where applicable.

*Response:*
_______________________________________________

---

**Q2.3** Was the training data collected with appropriate consent and legal basis? Describe the legal basis for data processing.

- [ ] Explicit consent
- [ ] Legitimate interest — documented in: ___________
- [ ] Contractual necessity
- [ ] Legal obligation
- [ ] Not applicable — no personal data used

*Response:*
_______________________________________________

---

**Q2.4** Are training data provenance records maintained? How long are they retained?

- [ ] Yes — retention period: ___________
- [ ] Partial
- [ ] No

*Response:*
_______________________________________________

---

**Q2.5** Has the training data been audited for quality, completeness, and representativeness?

- [ ] Yes — attach audit report (R)
- [ ] No

*Response:*
_______________________________________________

---

**Q2.6** How does your organization handle data subject rights requests (access, erasure, correction) for data used in AI training?

*Response:*
_______________________________________________

---

## Section 3 — Bias and Fairness

**Q3.1** Has the AI system been evaluated for bias across demographic groups? If yes, which groups were assessed and what metrics were used?

- [ ] Yes — describe methodology
- [ ] No
- [ ] In progress

*Response:*
_______________________________________________

---

**Q3.2** Provide bias assessment results including accuracy, True Positive Rate (TPR), and False Positive Rate (FPR) by demographic group.

| Group | Sample Size | Accuracy | TPR | FPR |
|-------|-------------|----------|-----|-----|
| | | | | |
| | | | | |
| | | | | |

*Attach full report (R)*

---

**Q3.3** What bias mitigation techniques have been applied? Select all that apply:

- [ ] Training data rebalancing
- [ ] Sample re-weighting
- [ ] Threshold calibration by group
- [ ] Adversarial debiasing
- [ ] Post-processing fairness constraints
- [ ] None applied
- [ ] Other: ___________

*Response:*
_______________________________________________

---

**Q3.4** For systems used in employment decisions: has an independent bias audit been conducted per NYC Local Law 144 requirements?

- [ ] Yes — attach audit report (R)
- [ ] Not applicable — system not used for employment decisions in NYC
- [ ] No

*Response:*
_______________________________________________

---

**Q3.5** What is your organization's acceptable disparity threshold for AI system performance across demographic groups?

*Response:*
_______________________________________________

---

**Q3.6** How frequently are bias assessments conducted post-deployment?

- [ ] Continuous / real-time monitoring
- [ ] Monthly
- [ ] Quarterly
- [ ] Annually
- [ ] On-demand only
- [ ] Not conducted post-deployment

*Response:*
_______________________________________________

---

## Section 4 — Transparency and Explainability

**Q4.1** Can the AI system provide explanations for individual decisions? Describe the explainability mechanism.

- [ ] Yes — describe method (LIME, SHAP, attention maps, etc.):
- [ ] Partial — limited to: ___________
- [ ] No

*Response:*
_______________________________________________

---

**Q4.2** Is technical documentation available describing model architecture, training methodology, and performance characteristics?

- [ ] Yes — provide or attach (T)
- [ ] Available under NDA
- [ ] No

*Response:*
_______________________________________________

---

**Q4.3** How does your organization disclose AI system use to affected individuals?

*Response:*
_______________________________________________

---

**Q4.4** Is an appeal or human review mechanism available for individuals affected by AI-assisted decisions?

- [ ] Yes — describe process
- [ ] No

*Response:*
_______________________________________________

---

**Q4.5** For EU-deployed systems: does the system comply with EU AI Act Article 13 transparency requirements?

- [ ] Yes — attach compliance documentation
- [ ] In progress
- [ ] Not applicable
- [ ] No

*Response:*
_______________________________________________

---

## Section 5 — Security and Adversarial Robustness

**Q5.1** Has the AI system been tested for adversarial attacks? What attack types were evaluated?

- [ ] Yes — attacks tested: ___________
- [ ] No

*Response:*
_______________________________________________

---

**Q5.2** Provide model performance on adversarial test sets. Include attack method and epsilon values where applicable.

| Attack Type | Clean Accuracy | Adversarial Accuracy | Epsilon |
|-------------|---------------|---------------------|---------|
| | | | |
| | | | |

*Response:*
_______________________________________________

---

**Q5.3** What security controls protect the AI system from unauthorized access and model extraction?

*Response:*
_______________________________________________

---

**Q5.4** For LLM-based systems: has the system been tested for prompt injection vulnerabilities?

- [ ] Yes — describe testing methodology and results
- [ ] No
- [ ] Not applicable

*Response:*
_______________________________________________

---

**Q5.5** Has the system undergone third-party security penetration testing?

- [ ] Yes — attach report (R)
- [ ] No

*Response:*
_______________________________________________

---

## Section 6 — Human Oversight

**Q6.1** Describe the human oversight mechanisms built into the AI system.

*Response:*
_______________________________________________

---

**Q6.2** Can human operators override, pause, or shut down the AI system? Describe the process.

- [ ] Yes — describe
- [ ] Partial
- [ ] No

*Response:*
_______________________________________________

---

**Q6.3** Are there any decisions the AI system makes autonomously without human review?

- [ ] No — all decisions subject to human review
- [ ] Yes — specify decisions and justification: ___________

*Response:*
_______________________________________________

---

**Q6.4** For EU high-risk systems: does the system comply with EU AI Act Article 14 human oversight requirements?

- [ ] Yes — attach documentation
- [ ] In progress
- [ ] Not applicable
- [ ] No

*Response:*
_______________________________________________

---

## Section 7 — Privacy and Data Protection

**Q7.1** Does the AI system process personal data as defined under GDPR or applicable privacy law?

- [ ] Yes — describe categories of personal data processed
- [ ] No

*Response:*
_______________________________________________

---

**Q7.2** Has a Data Protection Impact Assessment (DPIA) been completed for this system?

- [ ] Yes — provide summary or attach (R)
- [ ] No
- [ ] Not required

*Response:*
_______________________________________________

---

**Q7.3** What privacy-enhancing technologies are implemented? Select all that apply:

- [ ] Differential privacy
- [ ] Federated learning
- [ ] Data anonymization / pseudonymization
- [ ] Encryption at rest and in transit
- [ ] Secure multi-party computation
- [ ] None

*Response:*
_______________________________________________

---

**Q7.4** Where is data processed and stored? List all geographic locations.

*Response:*
_______________________________________________

---

**Q7.5** How long is personal data retained by the AI system? What is the data deletion process?

*Response:*
_______________________________________________

---

## Section 8 — Incident Response and Monitoring

**Q8.1** Does your organization have a documented AI incident response plan?

- [ ] Yes — attach (P)
- [ ] No

*Response:*
_______________________________________________

---

**Q8.2** Describe your notification process for AI-related incidents affecting our organization. What are the notification timeframes?

*Response:*
_______________________________________________

---

**Q8.3** How is the AI system monitored post-deployment for performance degradation, bias drift, or anomalous behavior?

*Response:*
_______________________________________________

---

**Q8.4** Have any AI incidents, regulatory inquiries, or enforcement actions occurred related to this system in the past 24 months?

- [ ] No
- [ ] Yes — describe: ___________

*Response:*
_______________________________________________

---

**Q8.5** What is the process for notifying our organization of material model updates or changes?

*Response:*
_______________________________________________

---

## Section 9 — Regulatory Compliance

**Q9.1** For the geographic scope of this deployment, which regulations apply? Confirm compliance status:

| Regulation | Applicable | Compliant | Evidence |
|------------|-----------|-----------|----------|
| EU AI Act | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| GDPR | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| CCPA/CPRA | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| NYC Local Law 144 | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| Colorado AI Act | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| HIPAA | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |
| FCRA | ☐ Yes ☐ No | ☐ Yes ☐ Partial ☐ No | |

---

**Q9.2** Has the organization obtained ISO/IEC 42001 certification or is certification in progress?

- [ ] Certified — attach certificate
- [ ] In progress — expected date: ___________
- [ ] Not pursuing

*Response:*
_______________________________________________

---

**Q9.3** Is the organization registered with any AI regulatory body or sandbox program?

*Response:*
_______________________________________________

---

## Section 10 — Contractual Requirements

By submitting this questionnaire the vendor acknowledges and agrees to the following contractual requirements as conditions of the procurement relationship:

| Requirement | Vendor Acknowledgment |
|-------------|----------------------|
| Annual bias audit rights granted to procuring organization | ☐ Agreed ☐ Negotiable ☐ Declined |
| Material model changes notified minimum 30 days in advance | ☐ Agreed ☐ Negotiable ☐ Declined |
| AI incidents notified within 24 hours of discovery | ☐ Agreed ☐ Negotiable ☐ Declined |
| Data processing agreement executed prior to deployment | ☐ Agreed ☐ Negotiable ☐ Declined |
| Regulatory compliance representations warranted | ☐ Agreed ☐ Negotiable ☐ Declined |
| Liability provisions for discriminatory AI outputs | ☐ Agreed ☐ Negotiable ☐ Declined |
| Right to terminate for material compliance failure | ☐ Agreed ☐ Negotiable ☐ Declined |

---

## Vendor Certification

By signing below the vendor certifies that all responses are accurate and complete to the best of their knowledge. The vendor agrees to notify the procuring organization promptly of any material changes to information provided in this questionnaire.

**Vendor Representative Name:** ___________________________

**Title:** ___________________________

**Signature:** ___________________________

**Date:** ___________________________

---

## Assessor Review

| Assessment Area | Score (1-5) | Notes |
|----------------|-------------|-------|
| Organizational Governance | | |
| Training Data Governance | | |
| Bias and Fairness | | |
| Transparency and Explainability | | |
| Security and Robustness | | |
| Human Oversight | | |
| Privacy | | |
| Incident Response | | |
| Regulatory Compliance | | |
| **Overall Score** | | |

**Procurement Recommendation:**
- [ ] Approved — vendor demonstrates adequate AI governance maturity
- [ ] Approved with conditions — specify: ___________
- [ ] Deferred — additional information required: ___________
- [ ] Rejected — material governance gaps identified: ___________

**Assessor Name:** ___________________________  
**Assessor Signature:** ___________________________  
**Date:** ___________________________

---

*Vendor AI Governance Questionnaire v1.0 | Aligned to NIST AI RMF 1.0, EU AI Act, ISO/IEC 42001, NYC Local Law 144*  
*Prepared by Jake Kantor | AI GRC Practitioner | jake.t.kantor@gmail.com | linkedin.com/in/jakekantor*
