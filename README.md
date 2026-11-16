# NIST Cybersecurity Framework Risk Assessment | Snag Company

**Project Type:** Governance, Risk, and Compliance (GRC)  
**Framework:** NIST Cybersecurity Framework (CSF)  
**Environment:** Fictional online retail company  
**Focus Areas:** Risk Assessment, Security Controls, Risk Prioritization, and Compliance Documentation

## Project Overview

This project presents a cybersecurity risk assessment for Snag Company, a fictional online retail and customer support business with 50 employees.

The purpose of the assessment was to identify cybersecurity risks, evaluate potential business impacts, document existing security controls, and recommend improvements aligned with the NIST Cybersecurity Framework.

The project demonstrates practical knowledge of Governance, Risk, and Compliance (GRC), cybersecurity risk management, and security assessment documentation.

## Business Environment

Snag Company operates an online retail business and relies on several technologies to support daily operations.

The environment includes:

- Microsoft 365, including Teams, OneDrive, and SharePoint
- Windows employee laptops
- Cloud-based customer relationship management (CRM)
- Cloud file storage
- Remote employee access
- Third-party payment processing
- Endpoint antivirus protection

The organization handles customer contact information, shipping addresses, order histories, employee records, and internal business documents.

## Assessment Objectives

1. Identify critical business assets and cybersecurity risks.
2. Evaluate risk likelihood and potential business impact.
3. Document existing security controls and identify gaps.
4. Recommend risk mitigation strategies.
5. Map recommended improvements to NIST CSF functions and categories.
6. Communicate findings in a professional risk assessment report.

## Risk Assessment Methodology

The assessment followed a structured seven-step process:

1. Identify key organizational assets.
2. Identify potential threats and vulnerabilities.
3. Assign likelihood and impact ratings.
4. Determine overall risk severity.
5. Document existing security controls.
6. Recommend improved security measures.
7. Map recommendations to the NIST Cybersecurity Framework.

Risks were evaluated using qualitative ratings of Low, Medium, High, and Critical.

## Risk Register Summary

The assessment documented 10 cybersecurity risks.

| Risk ID | Identified Risk | Severity |
|---|---|---|
| R001 | Weak or reused employee passwords | High |
| R002 | MFA not required for all users | Critical |
| R003 | Excessive SharePoint and OneDrive permissions | High |
| R004 | Inconsistent laptop patch management | High |
| R005 | Limited security awareness training | High |
| R006 | Backup restoration not tested regularly | High |
| R007 | No formal incident response plan | High |
| R008 | Remote connections from unsecured networks | Medium |
| R009 | Lack of customer data classification | High |
| R010 | Antivirus alerts not centrally monitored | High |

**Highest Priority Risk:** R002 — Incomplete multifactor authentication coverage.

## Key Findings

The assessment identified several important security gaps.

**1. Incomplete Multifactor Authentication**

MFA was enabled only for administrators, leaving other employee accounts at increased risk of unauthorized access.

**2. Excessive User Permissions**

Employees had excessive permissions within SharePoint and OneDrive, creating potential risks of unauthorized data access.

**3. Inconsistent Patch Management**

Employee Windows laptops relied on manual updates, increasing the possibility of unpatched security vulnerabilities.

**4. Limited Security Awareness**

Annual security awareness training provided limited ongoing reinforcement against phishing and social engineering.

**5. Incident Response Readiness**

The organization lacked a formal incident response plan with defined roles, communication procedures, and escalation steps.

## Recommended Security Improvements

| Security Area | Recommendation |
|---|---|
| Identity and Access Management | Require MFA for all employees and review access permissions |
| Endpoint Security | Implement centralized patch management and reporting |
| Security Awareness | Provide monthly awareness tips and quarterly phishing simulations |
| Backup and Recovery | Conduct and document monthly restoration tests |
| Incident Response | Develop a formal incident response plan and conduct tabletop exercises |
| Data Protection | Establish data classification and restrict sensitive information access |
| Security Monitoring | Centralize endpoint detection and alert monitoring |

## NIST Cybersecurity Framework Alignment

The assessment considers security activities related to these NIST CSF functions:

- **Identify:** Maintain an inventory of critical business assets.
- **Protect:** Strengthen authentication, access controls, patch management, and employee awareness.
- **Detect:** Improve endpoint monitoring and security alert visibility.
- **Respond:** Establish incident response planning and communication procedures.
- **Recover:** Improve backup testing and recovery preparedness.

The detailed assessment document contains the original control-mapping table. The mapping can be refined further to align its category identifiers with NIST CSF 2.0.

## Project Deliverable

The primary deliverable is a written cybersecurity risk assessment containing:

- Fictional company profile
- Assessment scope and methodology
- Asset inventory
- Risk register
- NIST CSF control mapping
- Findings summary
- Risk mitigation recommendations
- Executive summary

## Skills Demonstrated

- Governance, Risk, and Compliance (GRC)
- Cybersecurity risk identification
- Qualitative risk assessment
- Risk register development
- Security control evaluation
- NIST Cybersecurity Framework
- Risk mitigation planning
- Technical documentation
- Communication of cybersecurity findings

## Project Limitations

This project is a simulated assessment based on a fictional organization. It does not represent an authorized assessment of a real company.

No penetration testing, vulnerability scanning, or live security control validation was performed.

## Author

**Jamil Charles**  
Master's Student, Cybersecurity Management  
University of Maryland Global Campus

**Career Interests:** GRC Analyst, Cybersecurity Risk Analyst, Security Analyst

## Reference

National Institute of Standards and Technology. (2024). *The NIST Cybersecurity Framework (CSF) 2.0*.
