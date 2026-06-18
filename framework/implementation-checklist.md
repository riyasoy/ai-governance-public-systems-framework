# Risk Assessment Checklist for Public AI Systems

## Before Deployment - Assess These 5 Risk Categories

### 📊 1. Bias Risks
- [ ] Training data represents all demographic groups proportionally
- [ ] Fairness metrics tested across: age, gender, ethnicity, disability, socioeconomic status
- [ ] Historical bias in data identified and corrected
- [ ] Impact assessment for marginalized communities conducted
- [ ] Model performance balanced across different groups

### 🔒 2. Privacy Risks
- [ ] Data minimization principle applied (only collect necessary data)
- [ ] Encryption for storage and transmission
- [ ] Access controls with audit logging implemented
- [ ] Consent mechanisms for sensitive data
- [ ] Data retention policy defined and documented
- [ ] Privacy impact assessment completed

### 🔍 3. Transparency Risks
- [ ] Decision explanations provided to affected citizens
- [ ] System documentation publicly available (where appropriate)
- [ ] Appeal process for AI-assisted decisions established
- [ ] AI use disclosed clearly to users
- [ ] Model limitations documented and communicated

### 🎯 4. Accountability Risks
- [ ] Clear responsibility assigned to human overseer
- [ ] Incident response plan documented
- [ ] Regular audit schedule established
- [ ] Responsibility chain documented (developer → deployer → user)
- [ ] Grievance redressal mechanism available

### 🛡️ 5. Cybersecurity Risks
- [ ] Adversarial attack testing completed
- [ ] Model injection vulnerabilities assessed
- [ ] Data breach response plan ready
- [ ] Regular security updates scheduled
- [ ] Input validation and output sanitization implemented

---

## Risk Level Determination

| Impact Level | Examples | Assessment Required |
|--------------|----------|---------------------|
| **High Risk** | Critical infrastructure, healthcare, education, employment, law enforcement | Full assessment + human oversight + rigorous testing + detailed documentation |
| **Limited Risk** | Customer service, recommendations, content filtering | Transparency obligations + basic testing + user disclosure |
| **Minimal Risk** | Games, filters, analytics | No specific requirements |

---

## Post-Deployment Monitoring Checklist

### Monthly
- [ ] Performance evaluation (accuracy, precision, recall)
- [ ] Error rate tracking
- [ ] User feedback collection

### Quarterly
- [ ] Fairness assessment across demographic groups
- [ ] Data drift detection
- [ ] Security vulnerability scan

### Annually
- [ ] Comprehensive security audit
- [ ] Full system re-evaluation
- [ ] Policy compliance review
- [ ] Stakeholder feedback synthesis

### Continuous
- [ ] Real-time monitoring dashboards
- [ ] Automated alert systems for anomalies
- [ ] Incident reporting process
- [ ] Model version tracking

---

## Documentation Requirements

For **High-Risk Systems** (must have all):
- [ ] System design documentation
- [ ] Data source documentation
- [ ] Model training methodology
- [ ] Testing and validation results
- [ ] Bias assessment report
- [ ] Privacy impact assessment
- [ ] Security assessment report
- [ ] Human oversight procedures
- [ ] Incident response plan
- [ ] User guide and explanations

---

## Reference Standards

This checklist aligns with:
- **NIST AI Risk Management Framework (AI RMF 1.0)**
- **EU AI Act** (risk-based approach)
- **ISO/IEC 42001** (AI Management System)
- **OECD AI Principles** (trustworthy AI)

---

**Created for**: AI Governance Framework for Public Systems (Project 3)  
**Author**: Riya Soy | Independent AI Governance Researcher  
**Date**: June 2026
