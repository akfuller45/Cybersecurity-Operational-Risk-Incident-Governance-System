# Cybersecurity-Operational-Risk-Incident-Governance-System
# Cyber Operational Risk & Incident Governance System

## Executive Summary

This project simulates an enterprise Cyber Governance, Risk, and Compliance (Cyber GRC) monitoring system using a cybersecurity breach incident dataset.

The goal of the project is to evaluate breach incidents through an operational risk lens by identifying high-risk incidents, delayed reporting, missing breach impact information, third-party involvement, remediation exposure, and governance control failures.

The project was designed to reflect how operational risk, cybersecurity governance, third-party risk, and compliance teams monitor breach events in an enterprise environment.

---

## Business Problem

Organizations face increasing operational, regulatory, reputational, and financial risk from cybersecurity incidents and data breaches.

A breach event does not only represent a technical security issue. It also creates governance concerns related to:

- delayed reporting
- incomplete incident documentation
- missing impact estimates
- third-party/vendor exposure
- weak remediation tracking
- inconsistent incident ownership
- audit readiness gaps

This project builds a simulated enterprise risk monitoring framework to evaluate these issues and provide executive-level cyber risk visibility.

---

## Project Objectives

The main objectives of this project are to:

- Classify cybersecurity breach incidents by operational risk severity
- Identify missing or incomplete breach reporting information
- Track delayed reporting and breach duration risk
- Flag incidents involving third-party/vendor exposure
- Create a cyber operational risk scoring framework
- Build a cyber risk matrix using likelihood and impact scoring
- Create an incident register with owners, statuses, and remediation actions
- Evaluate governance control effectiveness
- Build an executive cyber risk dashboard
- Support audit readiness and management reporting

---

## Dataset

The project uses a cybersecurity data breach chronology dataset containing breach incident records.

Key fields include:

- organization name
- reported date
- breach date
- end breach date
- incident details
- information affected
- organization type
- breach type
- breach subtype
- total affected
- residents affected
- breach location
- third-party name
- notification delay
- source URL

---

## Key Business Questions

This project answers questions such as:

- Which breach incidents represent the highest operational risk?
- Which incidents have missing or unreported impact counts?
- How many incidents involved third-party/vendor exposure?
- Which breach types occur most frequently?
- Which incidents had delayed reporting?
- Which incidents require escalation or remediation?
- Which risk owners have the highest incident workload?
- Which governance controls are failing most often?
- Where are cyber risk concentrations highest based on likelihood and impact?

---

## Methodology

The project follows an enterprise-style cyber GRC workflow:

1. Data loading and cleaning
2. Date and numeric field standardization
3. Missing data assessment
4. Breach severity classification
5. Operational risk flag creation
6. Cyber risk scoring
7. Governance control testing
8. Incident register creation
9. Remediation tracking
10. Cyber risk matrix development
11. Executive dashboard reporting

---

## Operational Risk Framework

Each breach incident was evaluated using several risk indicators:

| Risk Indicator | Purpose |
|---|---|
| Total Affected | Measures breach impact |
| Missing Impact Flag | Identifies incomplete breach reporting |
| Reporting Delay | Measures time between breach and reporting |
| Breach Duration | Measures length of breach exposure |
| Third-Party Flag | Identifies vendor or third-party involvement |
| Missing Core Dates | Identifies incomplete incident timeline data |
| Missing Incident Details | Identifies weak breach documentation |

---

## Breach Severity Classification

Incidents were classified based on the number of affected individuals.

| Severity Level | Criteria |
|---|---|
| Low | Fewer than 1,000 affected |
| Medium | 1,000 to 9,999 affected |
| High | 10,000 to 99,999 affected |
| Critical | 100,000 or more affected |
| Unreported | Impact count missing or unavailable |

Incidents with missing affected counts were classified as **Unreported** because incomplete impact reporting creates governance uncertainty and may obscure the true exposure of the breach.

---

## Operational Risk Scoring

A risk score was created using multiple operational risk factors.

Risk points were assigned for:

- breach severity
- delayed reporting
- long breach duration
- third-party involvement
- missing core dates
- missing incident details
- unreported affected population

The final score was classified into four operational risk levels:

| Risk Level | Description |
|---|---|
| Low | Minimal operational exposure |
| Medium | Moderate governance concern |
| High | Elevated operational and compliance risk |
| Critical | Requires executive escalation and immediate remediation |

---

## Governance Controls Tested

The project includes automated governance control testing.

| Control ID | Control Name | Risk Area |
|---|---|---|
| CTRL-001 | Reported Date Present | Incident Timeline Completeness |
| CTRL-002 | Breach Date Present | Incident Timeline Completeness |
| CTRL-003 | Incident Details Present | Documentation Quality |
| CTRL-004 | Impact Count Reported | Breach Impact Reporting |
| CTRL-005 | Valid Reporting Delay | Reporting Accuracy |
| CTRL-006 | Breach Type Present | Incident Classification |

Each control was evaluated using pass rates, failed record counts, and effectiveness ratings.

Control effectiveness was classified as:

| Pass Rate | Effectiveness |
|---|---|
| 95% or higher | Effective |
| 85% to 94.99% | Needs Monitoring |
| Below 85% | Ineffective |

---

## Cyber Risk Matrix

A cyber operational risk matrix was created using:

- **Impact Score**: based on breach severity and affected population
- **Likelihood Score**: based on operational risk indicators such as delayed reporting, long breach duration, third-party involvement, and missing documentation

The matrix score was calculated as:

```text
Impact Score × Likelihood Score = Cyber Matrix Score
```

The matrix classifies incidents into:

- Low
- Medium
- High
- Critical

This supports prioritization of cyber incidents for executive review, remediation, and audit readiness.

---

## Incident Register

An operational incident register was created to simulate enterprise cyber risk management.

The incident register includes:

- incident ID
- organization name
- organization type
- breach type
- total affected
- severity level
- reporting delay
- breach duration
- third-party flag
- risk score
- operational risk level
- risk owner
- incident status
- remediation action
- remediation due date
- overdue remediation flag

---

## Risk Owner Assignment

Incidents were assigned to simulated enterprise risk owners based on breach characteristics.

| Risk Owner | Assignment Logic |
|---|---|
| Cybersecurity Team | Hacking, malware, cyber-related breach types |
| Third-Party Risk Management | Incidents involving third-party vendors |
| Privacy Compliance Team | Healthcare or medical-related organizations |
| Data Governance Team | Missing impact reporting |
| Operational Risk Team | General operational breach governance |

---

## Remediation Tracking

Each incident was assigned a remediation action, status, and due date.

Example statuses include:

- Escalated
- Remediation In Progress
- Under Review
- Monitoring

Remediation timelines were based on operational risk severity:

| Risk Level | Remediation Timeline |
|---|---|
| Critical | 7 days |
| High | 14 days |
| Medium | 30 days |
| Low | 60 days |

This simulates how enterprise risk teams prioritize incident response and corrective action planning.

---

## Executive Dashboard

The executive dashboard provides a consolidated view of cyber operational risk exposure.

Dashboard components include:

- total incidents
- critical incidents
- high-risk incidents
- third-party incidents
- missing impact incidents
- overdue remediation items
- average reporting delay
- average risk score
- operational risk distribution
- cyber risk matrix
- incident status distribution
- top breach types
- risk owner workload
- failed governance controls
- cyber matrix risk level distribution

---

## Key Findings

### Finding 1 — Missing Impact Reporting

Some breach incidents did not include reported affected population counts. These incidents were categorized as **Unreported**, representing a governance concern because incomplete impact reporting reduces visibility into breach severity and regulatory exposure.

### Finding 2 — Third-Party Risk Exposure

Incidents involving third-party organizations were flagged as elevated governance concerns. Third-party involvement may indicate vendor oversight risk, contract management exposure, or supply chain cybersecurity weakness.

### Finding 3 — Delayed Reporting Risk

Incidents with reporting delays greater than 30 days were flagged as delayed reporting risks. Delayed reporting can increase regulatory, reputational, and operational exposure.

### Finding 4 — High and Critical Risk Concentrations

The operational risk scoring framework identified incidents requiring management attention based on a combination of breach impact, governance gaps, reporting delays, third-party exposure, and missing documentation.

### Finding 5 — Governance Control Failures

Automated control testing identified records with missing documentation, missing impact counts, incomplete incident timelines, or invalid reporting delays. These failures represent opportunities to strengthen cyber incident governance processes.

---

## Recommendations

### Governance Recommendations

- Implement mandatory breach impact reporting fields
- Standardize breach type and incident classification rules
- Maintain a centralized cyber incident register
- Establish formal incident ownership rules
- Perform recurring governance control testing

### Operational Risk Recommendations

- Escalate critical incidents within seven days
- Monitor high-risk incidents through formal remediation plans
- Track overdue remediation items through executive dashboards
- Create risk owner accountability for all open incidents
- Review breach duration and delayed reporting trends monthly

### Third-Party Risk Recommendations

- Flag all third-party breach events for vendor risk review
- Require third-party remediation documentation
- Track vendor-related breach recurrence
- Incorporate breach history into vendor risk assessments

### Audit Readiness Recommendations

- Maintain evidence of incident review and remediation
- Export control testing summaries for audit review
- Track open, overdue, and escalated incidents
- Document all remediation actions and ownership assignments

---

## Technology Stack

- Python
- pandas
- numpy
- matplotlib
- Jupyter Notebook
- CSV data processing
- GitHub
- Power BI optional for dashboard enhancement

---

## Project Structure

```text
cyber-operational-risk-governance-system/

│
├── data/
│   ├── raw/
│   ├── cleaned/
│
├── notebooks/
│   └── cyber_operational_risk_analysis.ipynb
│
├── outputs/
│   ├── charts/
│   │   └── cyber_operational_risk_dashboard.png
│   ├── tables/
│   │   ├── cyber_incident_register.csv
│   │   └── critical_cyber_risk_register.csv
│   └── reports/
│
├── images/
│   ├── dashboard_preview.png
│   └── cyber_risk_matrix.png
│
├── README.md
├── requirements.txt
├── .gitignore
└── LICENSE
```

---

## Example Outputs

The project produces:

- cyber incident register
- critical cyber risk register
- automated control testing summary
- cyber risk matrix
- operational risk dashboard
- failed control analysis
- remediation tracking metrics
- executive governance summary

---

## Portfolio Value

This project demonstrates skills relevant to:

- Cyber GRC
- Operational Risk Analytics
- Incident Management
- Third-Party Risk Management
- Governance Reporting
- Control Testing
- Audit Readiness
- Data Governance
- Executive Dashboarding
- Compliance Monitoring

---

## Future Enhancements

Future improvements could include:

- interactive Power BI dashboard
- automated PDF executive report
- simulated audit findings section
- vendor risk scorecards
- breach trend forecasting
- machine learning anomaly detection
- geographic breach risk mapping
- real-time incident alerting logic
- workflow automation for remediation tracking

---

## Author

Amiranda Fuller

Governance Analytics | Cyber Operational Risk | Data Governance | Business Intelligence
