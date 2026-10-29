# PayNest Technologies | ISO 27001 ISMS Capstone

![Project](https://img.shields.io/badge/Project-GRC%20Capstone-blue)
![Standard](https://img.shields.io/badge/Reference-ISO%2FIEC%2027001%3A2022-005A9C)
![Sector](https://img.shields.io/badge/Sector-Fintech-008080)
![Deliverable](https://img.shields.io/badge/Deliverable-ISMS%20Assessment-grey)

A risk-based Information Security Management System (ISMS) design and assessment for a growing Nigerian fintech startup.

This capstone translates PayNest Technologies’ security challenges into a defined ISMS scope, ISO/IEC 27001 gap analysis, scored risk register, Annex A control recommendations, baseline Statement of Applicability (SoA), and continual-improvement approach.

> Educational case study. The repository contains assessment and planning artifacts—not a deployed payment platform, independently verified security audit, or claim of ISO 27001 certification.

## Project Overview

PayNest Technologies provides digital payment services to individuals and small businesses in Nigeria.

As the company grows, it handles increasing volumes of customer information, transaction data, employee records, financial information, application source code, and cloud-hosted systems. Its security governance and processes have not developed at the same pace.

This project demonstrates how an analyst can structure an ISO/IEC 27001:2022-aligned improvement program around business scope, information assets, risk ownership, control selection, and evidence needs.

## Problem Statement

The case study identifies eight foundational weaknesses:

- No clearly defined ISMS scope
- Incomplete security policies
- No formal information asset inventory
- Inconsistent risk assessments
- No formal security-control selection
- No Statement of Applicability
- Irregular security-awareness training
- Inconsistent third-party security checks

These gaps create potential exposure to unauthorized access, payment-service disruption, data breaches, fraud, supplier compromise, and loss of customer trust.

## Objectives

1. Define the boundaries of PayNest’s proposed ISMS.
2. Identify gaps against ISO/IEC 27001 requirements and relevant Annex A controls.
3. Document key risks, scores, proposed treatments, and responsible roles.
4. Recommend controls that address the identified risks.
5. Prepare a baseline Statement of Applicability.
6. Establish a Plan–Do–Check–Act improvement approach.
7. Present the findings in a professional capstone report.

## Key Deliverables

| Deliverable | Included Content |
|---|---|
| ISMS scope statement | Business activities, information, personnel, technology, physical environments, and third-party interfaces |
| Gap analysis | Current-state weaknesses, associated requirements, and potential impacts |
| Risk register | Eight risks with likelihood, impact, score, treatment, and owner |
| Annex A recommendations | Risk-to-control mappings and selection rationale |
| Baseline SoA | Selected controls, applicability, justification, and reported implementation status |
| PDCA improvement section | Continual-improvement narrative and an embedded diagram |
| Final report | Consolidated findings, recommendations, and references |

The project’s central strength is traceability: organizational gaps lead to risks, risks inform control selection, and the SoA records the rationale and assessment status.

## Assessment Workflow

```text
Business Context and ISMS Scope
               |
               v
ISO 27001 Gap Analysis
               |
               v
Risk Identification and Scoring
               |
               v
Treatment and Control Recommendations
               |
               v
Baseline Statement of Applicability
               |
               v
Implementation, Evaluation, and Improvement Planning
```

## Proposed ISMS Scope

The proposed ISMS covers the people, processes, information, technology, cloud services, and working environments supporting PayNest’s digital payment services.

Included activities and assets:

- Customer onboarding and identity verification
- Payment processing, transaction management, and reconciliation
- Customer, transaction, employee, and financial records
- Payment applications, APIs, and source code
- Production, development, and test cloud environments
- Corporate networks, endpoints, and communication channels
- Cloud hosting, payment gateways, and outsourced development
- Employees, contractors, temporary staff, and remote workers accessing PayNest systems

The scope includes interfaces with relevant suppliers rather than assuming PayNest directly controls all third-party infrastructure.

## Gap Analysis Highlights

| Area | Identified Weakness | Proposed Direction |
|---|---|---|
| Context and scope | No approved boundaries or documented interface mapping | Define and approve the ISMS scope |
| Leadership | Security responsibilities and reporting lines are unclear | Assign sponsorship, accountability, and control ownership |
| Policy | Policies are incomplete | Establish approved overarching and topic-specific policies |
| Asset management | No formal inventory, ownership, or classification | Create an asset register and handling requirements |
| Risk management | Assessments are inconsistent | Define repeatable criteria, assessment practices, and treatment approvals |
| Control selection | No formal treatment plan or SoA | Record selected controls and their justification |
| Awareness | Training is irregular | Introduce role-based training and effectiveness evaluation |
| Supplier security | Third-party checks are inconsistent | Formalize due diligence, agreements, and ongoing review |
| Technical protection | Formal access, development, cloud, and monitoring practices are not demonstrated | Define and validate risk-based safeguards |

Where the scenario provides no evidence of a practice, the analysis identifies an assurance gap; this is not equivalent to independently proving that the practice is absent.

## Risk Assessment Method

The report uses a three-point scale:

| Rating | Likelihood | Impact |
|---|---|---|
| 1 | Low | Low |
| 2 | Medium | Medium |
| 3 | High | High |

```text
Risk score = Likelihood × Impact
```

Scores support relative prioritization. The report does not define formal score-band thresholds or approved risk-acceptance criteria.

### Risk Register Summary

| ID | Risk | Likelihood | Impact | Score | Assigned Role |
|---|---|---:|---:|---:|---|
| R1 | Unauthorized access from weak access controls | 3 | 3 | 9 | Head of IT/Cloud Operations |
| R2 | Data breach from insecure cloud configuration | 3 | 3 | 9 | Head of IT/Cloud Operations |
| R3 | Malware infection on employee endpoints | 2 | 3 | 6 | HR Manager and Information Security Manager |
| R4 | Customer-data loss from missing backups | 2 | 3 | 6 | Head of IT/Cloud Operations |
| R5 | Third-party compromise affecting PayNest systems | 3 | 2 | 6 | Legal/Compliance Lead |
| R6 | Application vulnerabilities from insecure coding | 3 | 3 | 9 | Head of Engineering |
| R7 | Prolonged outages from inadequate incident response | 2 | 3 | 6 | Information Security Manager |
| R8 | Insider misuse without adequate monitoring | 2 | 3 | 6 | Head of IT/Cloud Operations |

These are scenario-based assessments and proposed accountable roles, not verified operational assignments.

## Annex A Control Recommendations

| Risk Area | Selected Controls Referenced in the Report |
|---|---|
| Unauthorized access | A.5.15 Access control; A.5.16 Identity management; A.5.17 Authentication information |
| Cloud misconfiguration | A.5.23 Information security for use of cloud services; A.8.9 Configuration management |
| Malware | A.8.7 Protection against malware |
| Data loss | A.8.13 Information backup |
| Supplier compromise | A.5.19–A.5.23 supplier, ICT supply chain, and cloud-related controls |
| Insecure development | A.8.25 Secure development life cycle; A.8.28 Secure coding |
| Incident response | A.5.24–A.5.27 incident-management controls |
| Insider misuse | A.8.15 Logging; A.8.16 Monitoring activities |

The detailed report includes additional recommendations covering privileged access, vulnerability management, cryptography, continuity, remote working, and separation of environments.

Controls are proposed for treatment planning. Their inclusion does not demonstrate implementation or effectiveness.

## Baseline Statement of Applicability

The report includes a baseline SoA recording:

- Selected control identifiers and descriptions
- Applicability decisions
- Justification for inclusion
- Reported implementation status

Statuses include:

- Not implemented
- Partially implemented
- Partially implemented / needs validation

This is a selected-control baseline, not a complete, independently validated certification-ready SoA. Further work should review all Annex A controls, document exclusion rationale where appropriate, and validate status against evidence.

## Continual Improvement

The report frames ISMS development through Plan–Do–Check–Act:

| Stage | Intended Focus |
|---|---|
| Plan | Establish scope, governance, risk methods, policies, and treatment priorities |
| Do | Implement approved controls and maintain implementation records |
| Check | Monitor performance, evaluate controls, conduct internal audits, and hold management reviews |
| Act | Correct weaknesses and improve the ISMS based on findings |

The source document contains an embedded PDCA diagram. A standalone image is not included in the supplied repository materials.

## Tools, Formats, and Technologies

| Item | Role |
|---|---|
| ISO/IEC 27001:2022 | Reference standard for the assessment |
| Annex A | Reference control set used in recommendations and the SoA |
| DOCX | Capstone report format |
| Markdown | Repository documentation |
| Three-point risk matrix | Likelihood and impact scoring approach |
| PDCA | Continual-improvement structure |

### Technologies Discussed, Not Deployed

- Cloud-hosted infrastructure
- Payment applications and APIs
- Source-code repositories
- Corporate endpoints and networks
- Payment gateways
- SAST/DAST as recommended testing approaches

The report does not identify a specific cloud provider, programming language, database, CI/CD platform, or security-testing product.

## Repository Structure

Suggested layout using the supplied artifact:

```text
.
├── README.md
└── PayNest-Capstone-Project.docx
```

## Getting Started

### Prerequisites

- A DOCX-compatible document viewer
- Git, only if cloning the repository

No application installation, cloud credentials, dependencies, or build commands are required.

### Review the Report

Download `PayNest-Capstone-Project.docx` and open it in a compatible viewer.

Alternatively, replace the placeholders and clone the repository:

```bash
git clone [https://github.com/](https://github.com/)<github-username>/<repository-name>.git
cd <repository-name>
```

Open the report to review the full assessment.

## Usage

### For Recruiters and Hiring Managers

Review the report to evaluate:

- ISMS scope definition
- Requirements-based gap analysis
- Risk scoring and ownership
- Risk-to-control traceability
- Statement of Applicability development
- Fintech security governance
- Professional GRC reporting

### For Learners and Reviewers

1. Read the case-study context and proposed scope.
2. Compare each gap with the associated requirement.
3. Trace risks to treatment recommendations and Annex A controls.
4. Review the baseline SoA and its implementation-status assumptions.
5. Identify evidence needed to validate the proposed control environment.

Validate mappings, applicability, treatment adequacy, and legal obligations before adapting the report to a real organization.

## Limitations and Review Notes

- Findings are based on a case-study narrative, not live-system assessment.
- No control testing, evidence collection, or implementation results are supplied.
- Risk scoring is simplified and requires approved criteria for operational use.
- Residual-risk scores, acceptance decisions, and treatment deadlines are not documented.
- The selected-control SoA requires further completeness and accuracy review.
- Some risk-register treatments need closer alignment with their corresponding risks, particularly malware and supplier compromise.
- Country-specific legal and regulatory obligations require separate validation.
- The report is not a formal certification-readiness determination.

## Future Enhancements

Potential additions—not currently included—are:

- Standalone risk-register and SoA spreadsheets
- Complete Annex A applicability review
- Asset register and data-flow diagram
- Approved risk methodology and acceptance thresholds
- Residual-risk assessment and treatment approvals
- Remediation tracker with owners, dates, dependencies, and evidence
- Control-effectiveness test plans
- Internal-audit and management-review templates
- Exported PDCA diagram
- PDF version of the capstone report

## Contributing

To suggest a correction or enhancement:

1. Open an issue describing the proposed change and rationale.
2. Distinguish case-study evidence from assumptions.
3. Submit focused changes through a pull request.
4. Explain any revised risk scores, control mappings, or applicability decisions.

Do not upload real customer information, payment data, credentials, proprietary source code, or confidential organizational records. Use synthetic examples for supporting templates.

## Author

Maureen Uzoewulu  
GRC Analyst — Capstone Portfolio

- GitHub: <GitHub profile URL>
- LinkedIn: <LinkedIn profile URL>
- Contact: <optional professional email>

## References

The capstone cites:

- ISO/IEC 27001:2022 — Information security management systems — Requirements.
- ISO 27001 gap-analysis and implementation course materials.
- American Council of Training and Development — PayNest capstone project: Implementing ISO/IEC 27001 for a growing startup.

See the report for its reference details.

## License

<Specify reuse permissions and add a corresponding LICENSE file if appropriate.>

Distinguish original project content from third-party course materials and copyrighted standards.
