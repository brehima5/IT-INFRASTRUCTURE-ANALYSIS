# IT INCIDENT ANALYSIS

A data analysis of **50,000 cloud outage incidents** to uncover what's actually driving SLA breaches, revenue loss, and slow resolution times so IT ops teams can stop guessing and start fixing.

---
<img width="1406" height="655" alt="Screenshot 2026-03-18 at 1 16 30 PM" src="https://github.com/user-attachments/assets/0186e179-1a27-434c-8849-9bfe8dfa0f3d" />

[DASHBOARD HERE](https://public.tableau.com/app/profile/thierno.barry7757/viz/IT_17736007769730/Dashboard1?publish=yes)

---

## Data Overview

The dataset covers 50K cloud outage incidents spanning multiple providers, regions, and services. Key fields include:

- **Severity** — Low, Medium, High, Critical
- **Root Cause** — Software, Hardware, Network, Human Error, Security, Unknown
- **Detection Method** — Customer Report, Alert, Automated Monitoring
- **Resolution Metrics** — MTTR, number of engineers involved, SLA violated (yes/no)
- **Impact Metrics** — Customers affected, revenue loss
- **Operational Context** — Cloud provider, region, service, system load, monitoring alerts
---

##  Key Findings

### 1. SLA Compliance Degrades at Higher Severity Levels
Critical incidents exhibit a **70.5% SLA violation rate**, compared to ~17% for Low severity, indicating that current escalation and response processes are insufficient for high-impact events.

### 2. Automated Detection Surfaces More Complex Incidents
Automated Monitoring carries the highest SLA violation rate at **30.8%**, compared to 20.0% for Customer Reports — reflecting that proactive detection catches more complex, cascading issues where current response workflows lag behind.

### 3. System Load Is Not a Reliable Outage Predictor
Pre-outage system load follows a **near-uniform distribution**, confirming that outages occur across all load conditions. Single-metric threshold alerting on load alone is insufficient for proactive incident prevention.

---

##  Tableau Dashboard

I built an interactive Tableau dashboard to visualize the findings above and to monitor Incident management and Impact.
It includes:

[DASHBOARD HERE](https://public.tableau.com/app/profile/thierno.barry7757/viz/IT_17736007769730/Dashboard1?publish=yes)

---
