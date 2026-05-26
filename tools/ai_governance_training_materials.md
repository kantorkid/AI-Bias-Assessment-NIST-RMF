# AI Governance Training Program
## Writing Audit-Ready AI Procedures
### Training Guide for IT and Technical Teams

**Version:** 1.0  
**Audience:** IT Staff, System Administrators, Developers, Technical Leads  
**Duration:** ~90 minutes self-paced  
**Prerequisites:** None  
**Prepared by:** Jake Kantor | AI GRC Practitioner

---

## Module 1 — Why AI Governance Matters for IT Teams

### 1.1 The New Regulatory Reality

AI systems are now subject to binding legal requirements in multiple jurisdictions. As an IT professional working with AI systems you are directly responsible for implementing controls that satisfy these requirements.

**Key regulations you need to know:**

| Regulation | Who It Affects | Core IT Requirement |
|------------|---------------|---------------------|
| EU AI Act | Any org deploying AI affecting EU residents | Technical documentation, logging, robustness testing |
| NYC Local Law 144 | Any employer using AI in hiring in NYC | Annual bias audit, audit trail |
| Colorado AI Act | Any org making consequential AI decisions in CO | Risk assessment, human oversight |
| GDPR | Any org processing EU personal data in AI | Data minimization, DPIA, individual rights |

**The enforcement reality:** The EU AI Act entered full enforcement on August 2, 2026. Penalties reach €35 million or 7% of global annual revenue for serious violations. Non-compliance is no longer a theoretical risk.

### 1.2 Why IT Teams Are in the Critical Path

Regulators don't just want policies on paper. They want evidence that controls are technically implemented and functioning. That evidence comes from:

- System logs you maintain
- Access controls you configure
- Testing results you document
- Monitoring systems you operate
- Incident records you create

**If you can't produce the evidence, your organization cannot demonstrate compliance — regardless of what the policy document says.**

### 1.3 What "Audit-Ready" Means

An audit-ready procedure is one that:

1. **Specifies who** does what — named roles, not job titles
2. **Specifies when** it happens — dates, frequencies, triggers
3. **Specifies how** to verify it happened — evidence requirements
4. **Has a trail** — timestamps, signatures, version history
5. **Is findable** — stored in a known location, not someone's email

---

## Module 2 — Understanding AI Risk Frameworks

### 2.1 NIST AI RMF Overview

The NIST AI Risk Management Framework organizes AI governance into four functions. IT teams have responsibilities in each one.

```
GOVERN → MAP → MEASURE → MANAGE
```

**GOVERN — Setting up the framework**

IT responsibilities:
- Implementing access controls for AI systems
- Maintaining technical documentation
- Establishing logging and audit trail infrastructure
- Participating in risk tolerance discussions

**MAP — Identifying risks**

IT responsibilities:
- Documenting system architecture and data flows
- Identifying attack surfaces and security risks
- Cataloging AI system dependencies
- Flagging technical risks to governance teams

**MEASURE — Assessing risks**

IT responsibilities:
- Running bias and fairness tests
- Conducting adversarial security testing
- Monitoring system performance metrics
- Generating performance reports for audit

**MANAGE — Responding to risks**

IT responsibilities:
- Implementing technical mitigations
- Maintaining monitoring systems
- Responding to AI security incidents
- Executing remediation plans

### 2.2 EU AI Act Technical Requirements for IT

For high-risk AI systems the EU AI Act imposes specific technical requirements that IT teams must implement:

**Article 9 — Risk Management System**
- Maintain documented risk assessment for the AI system lifecycle
- Update risk assessment when system changes

**Article 10 — Data Governance**
- Document training data sources and preprocessing
- Implement data quality controls
- Maintain records of training data for audit

**Article 12 — Record Keeping and Logging**
- Implement automatic logging of AI system operation
- Ensure logs are tamper-evident
- Retain logs per regulatory requirements

**Article 13 — Transparency**
- Maintain technical documentation accessible to regulators
- Ensure instructions for use are available

**Article 15 — Accuracy, Robustness, and Cybersecurity**
- Implement resilience measures against errors and attacks
- Test robustness against adversarial inputs
- Implement appropriate cybersecurity measures

---

## Module 3 — Writing Audit-Ready Procedures

### 3.1 The Anatomy of a Good Procedure

Every audit-ready AI procedure must contain these elements:

**Header Block**
```
Procedure Title: [Descriptive name]
Procedure ID: [Unique identifier e.g. AI-PROC-001]
Version: [e.g. 1.0]
Owner: [Named individual]
Reviewer: [Named individual]
Approval Date: [Date]
Next Review: [Date]
Applicable Systems: [List]
Regulatory Reference: [e.g. NIST AI RMF MEASURE 2.5, EU AI Act Article 15]
```

**Purpose Statement** — One paragraph explaining why this procedure exists and what regulatory requirement it satisfies.

**Scope** — Which systems, teams, and scenarios this procedure covers and explicitly does not cover.

**Definitions** — Any technical terms that could be interpreted differently by an auditor.

**Prerequisites** — What must be in place before this procedure can be executed.

**Procedure Steps** — Numbered, specific, actionable. Each step must have:
- Who performs it
- What they do
- What tool or system they use
- What evidence they produce

**Evidence Requirements** — What documentation proves this procedure was completed.

**Escalation Path** — What happens if something goes wrong.

**Sign-Off** — Who confirms completion with date and signature.

### 3.2 The Ten Commandments of Audit-Ready Writing

**1. Use active voice and name the actor**

❌ Bad: "The model should be evaluated for bias."
✅ Good: "The AI Risk Analyst runs the bias evaluation script monthly."

**2. Be specific about time**

❌ Bad: "Logs should be reviewed regularly."
✅ Good: "The System Administrator reviews access logs every Monday by 10:00 AM EST."

**3. Name the tool**

❌ Bad: "Use appropriate monitoring software."
✅ Good: "Open Grafana dashboard at [URL] and navigate to the AI Model Performance panel."

**4. Specify the evidence**

❌ Bad: "Document the results."
✅ Good: "Export the bias metrics report as PDF and save to SharePoint > AI Governance > Bias Reports > [YYYY-MM]."

**5. Define pass/fail criteria**

❌ Bad: "Check if results are acceptable."
✅ Good: "Flag if TPR disparity between any two demographic groups exceeds 10 percentage points."

**6. Include the escalation trigger**

❌ Bad: "Escalate if there are problems."
✅ Good: "If TPR disparity exceeds threshold notify the AI Risk Officer within 4 business hours using the AI Incident Slack channel."

**7. Version everything**

Every procedure document needs a version number and change log. Auditors check whether you were using the current procedure at the time of the activity.

**8. Date and sign completions**

A procedure that was followed but not signed and dated didn't happen in an audit. Every procedure execution needs a completion record with date, executor name, and signature.

**9. Store where it can be found**

A procedure in someone's personal drive doesn't exist for audit purposes. All procedures and completion records must be in a designated, accessible repository.

**10. Review and update**

Outdated procedures are a compliance risk. Every procedure must have a review date and an owner responsible for keeping it current.

### 3.3 Procedure Writing Exercise

**Scenario:** You need to write a procedure for monthly bias monitoring of an AI-powered hiring tool.

**Step 1 — Write the header block**

Fill in the following:
- Procedure Title: Monthly Bias Monitoring — [System Name]
- Procedure ID: AI-PROC-0__
- Version: 1.0
- Owner: ___________
- Review date: ___________
- Regulatory reference: NIST AI RMF MEASURE 2.5 | NYC Local Law 144

**Step 2 — Write the purpose statement**

Template: "This procedure establishes the process for [what] to ensure [why] in compliance with [regulation]."

Your version:
_______________________________________________

**Step 3 — Write three procedure steps using the correct format**

Format: [Step number]. [Actor] [action] using [tool] and [saves/documents] [evidence] to [location].

Step 1:
_______________________________________________

Step 2:
_______________________________________________

Step 3:
_______________________________________________

**Step 4 — Define the pass/fail criterion**

"Flag for escalation if ___________."

Your version:
_______________________________________________

---

## Module 4 — AI-Specific Technical Procedures

### 4.1 Logging Requirements for AI Systems

AI systems require logging beyond standard application logging. The following events must be logged for audit-ready AI governance:

**Required Log Events**

| Event Type | What to Log | Retention |
|------------|-------------|-----------|
| Model inference | Input hash, output, timestamp, user ID | 24 months minimum |
| Model update / version change | Old version, new version, approver, date | Lifecycle + 5 years |
| Access to model weights | User, timestamp, action | 12 months |
| Bias assessment execution | Who ran it, results, date | 36 months |
| Override of AI decision | Who, why, what decision was changed | 36 months |
| Incident | Type, severity, response, resolution | 5 years |

**Log Integrity Requirements**

Logs used for regulatory compliance must be tamper-evident. Options:
- Write-once storage (AWS S3 Object Lock, Azure Immutable Blob)
- Cryptographic hash chaining
- Blockchain anchoring (emerging best practice)
- Third-party log management with immutability guarantees

### 4.2 Bias Testing Procedure Template

```
PROCEDURE: AI Bias Assessment
ID: AI-PROC-003
Frequency: Quarterly or after any model update
Actor: AI Risk Analyst

Step 1: The AI Risk Analyst retrieves the current model version 
        identifier from the model registry and records it in 
        the bias assessment log.

Step 2: The AI Risk Analyst runs the bias evaluation script 
        [script name/location] against the validation dataset 
        [dataset name/version].

Step 3: The script outputs a bias metrics report including 
        accuracy, TPR, and FPR by demographic group. 
        Save report to [SharePoint path] with filename format:
        BIAS-REPORT-[SystemName]-[YYYY-MM-DD].pdf

Step 4: The AI Risk Analyst reviews results against the 
        acceptable disparity threshold of [X]%.

Step 5: If any group's TPR falls more than [X]% below the 
        highest-performing group:
        → Flag as THRESHOLD EXCEEDED
        → Notify AI Risk Officer within 4 business hours
        → Open AI Incident ticket in [system]
        
Step 6: If results are within threshold:
        → Mark assessment as PASSED
        → Update the bias monitoring dashboard

Step 7: AI Risk Analyst signs and dates the completion record 
        and saves to [SharePoint path].

EVIDENCE REQUIRED:
- Bias metrics report PDF
- Completion record with signature and date
- Incident ticket number (if threshold exceeded)

REGULATORY MAPPING:
- NIST AI RMF: MEASURE 2.5, MANAGE 1.3
- EU AI Act: Article 9, Article 15
- NYC Local Law 144: Annual bias audit requirement
```

### 4.3 Adversarial Testing Procedure Template

```
PROCEDURE: Adversarial Robustness Testing
ID: AI-PROC-004
Frequency: Pre-deployment and after major model updates
Actor: AI Security Engineer

Step 1: The AI Security Engineer retrieves the model version 
        to be tested from the model registry.

Step 2: The Engineer runs the adversarial testing suite 
        [script/tool name] with the following attack types:
        - FGSM at epsilon values: 0.01, 0.05, 0.1
        - PGD attack
        - [Additional attacks per system risk profile]

Step 3: Record clean accuracy and adversarial accuracy for 
        each attack type in the robustness testing log.

Step 4: Compare results against robustness thresholds:
        - Acceptable: adversarial accuracy > [X]%
        - Unacceptable: adversarial accuracy ≤ [X]%

Step 5: If results are unacceptable:
        → Do not approve model for deployment
        → Notify AI Risk Officer and System Owner
        → Open remediation ticket

Step 6: Save test results report to [location] with filename:
        ROBUSTNESS-[SystemName]-[Version]-[YYYY-MM-DD].pdf

Step 7: Security Engineer signs completion record.

EVIDENCE REQUIRED:
- Robustness test results report
- Signed completion record
- Remediation ticket (if applicable)

REGULATORY MAPPING:
- NIST AI RMF: MEASURE 2.6
- EU AI Act: Article 15
```

### 4.4 Model Change Management Procedure Template

```
PROCEDURE: AI Model Change Management
ID: AI-PROC-005
Trigger: Any update to model weights, architecture, or training data
Actor: ML Engineer (initiator), AI Risk Officer (approver)

Step 1: ML Engineer documents the proposed change in the 
        Model Change Request form [link] including:
        - Description of change
        - Reason for change
        - Expected performance impact
        - Risk assessment

Step 2: AI Risk Officer reviews the change request and 
        determines if re-evaluation is required:
        - Minor update (hyperparameter tuning): bias re-test required
        - Major update (new training data): full risk assessment required
        - Architecture change: full risk assessment + security review required

Step 3: Required evaluations are completed per applicable 
        procedures (AI-PROC-003, AI-PROC-004).

Step 4: AI Risk Officer approves or rejects the change with 
        documented rationale.

Step 5: If approved: ML Engineer updates model registry with 
        new version, change date, and approver.

Step 6: System Owner notifies affected stakeholders of 
        model update per communication plan.

Step 7: Update model technical documentation.

EVIDENCE REQUIRED:
- Completed Model Change Request form
- Evaluation results (bias test, robustness test)
- Approval record with approver signature and date
- Updated model registry entry
- Stakeholder notification record

REGULATORY MAPPING:
- NIST AI RMF: GOVERN 1.7, MANAGE 2.2
- EU AI Act: Article 9, Article 11
```

---

## Module 5 — Knowledge Check

Answer the following questions to confirm understanding. Reference the relevant module if you need to review.

**Q1.** An auditor asks for evidence that your organization conducted bias testing on your AI hiring tool in Q1 2026. What specific documents should you be able to produce?

*Your answer:*
_______________________________________________

---

**Q2.** A colleague writes the following procedure step: "Check the model for problems and fix them if needed." What is wrong with this step and how would you rewrite it?

*Your answer:*
_______________________________________________

---

**Q3.** Your AI system shows a TPR of 0.85 for White subjects and 0.61 for Black subjects in a quarterly bias assessment. Your organization's acceptable disparity threshold is 15%. What action do you take?

- [ ] No action required — disparity is within threshold
- [ ] Flag for escalation — disparity exceeds threshold
- [ ] Flag for escalation — disparity is exactly at threshold

*Explain your reasoning:*
_______________________________________________

---

**Q4.** A model update is deployed without going through the change management procedure. Three months later an audit finds the model registry shows the old version. What are the regulatory and operational risks?

*Your answer:*
_______________________________________________

---

**Q5.** Which EU AI Act article requires logging and audit trail capabilities for high-risk AI systems?

- [ ] Article 9
- [ ] Article 12
- [ ] Article 13
- [ ] Article 15

---

## Module 6 — Quick Reference

### Regulatory Citation Quick Reference

| Requirement | NIST AI RMF | EU AI Act | NYC LL144 |
|-------------|-------------|-----------|-----------|
| Risk assessment | GOVERN 1.2 | Article 9 | — |
| Training data documentation | MAP 1.5 | Article 10 | — |
| Bias testing | MEASURE 2.5 | Article 10, 15 | Annual audit |
| Logging | MANAGE 1.3 | Article 12 | — |
| Transparency docs | GOVERN 1.7 | Article 13 | — |
| Human oversight | MANAGE 2.4 | Article 14 | — |
| Robustness testing | MEASURE 2.6 | Article 15 | — |
| Incident response | MANAGE 3.1 | Article 9 | — |

### Evidence Retention Quick Reference

| Document Type | Minimum Retention |
|---------------|------------------|
| Bias assessment reports | 36 months |
| Robustness test results | 36 months |
| Model change records | System lifecycle + 5 years |
| Incident records | 5 years |
| Training data documentation | System lifecycle + 5 years |
| Access logs | 12 months |
| Inference logs | 24 months |

### Escalation Triggers Quick Reference

Immediately escalate to the AI Risk Officer when:
- Bias disparity exceeds organizational threshold
- Adversarial test results fall below robustness threshold
- AI system produces output that appears discriminatory or harmful
- Unauthorized model change is discovered
- Regulatory inquiry is received
- Data breach involves AI training data
- Model behavior changes unexpectedly

---

## Training Completion Record

**Trainee Name:** ___________________________

**Role:** ___________________________

**Completion Date:** ___________________________

**Knowledge Check Score:** ___ / 5

**Attestation:** I confirm that I have completed the AI Governance Training Program and understand my responsibilities for maintaining audit-ready AI governance documentation.

**Signature:** ___________________________

**Manager Signature:** ___________________________

---

*AI Governance Training Program v1.0 | Prepared by Jake Kantor | AI GRC Practitioner*  
*Aligned to NIST AI RMF 1.0 | EU AI Act | ISO/IEC 42001 | NYC Local Law 144*  
*Contact: jake.t.kantor@gmail.com | linkedin.com/in/jakekantor*
