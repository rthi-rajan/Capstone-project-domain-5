Infrastructure Failure Prediction – TechCore Solutions

Capstone project to understand why systems fail, predict which systems are at risk of failing, and suggest preventive actions that operations teams can take early.

Business Problem

TechCore Solutions is a global technology services provider that manages mission-critical infrastructure for banking, healthcare, retail, manufacturing and government clients. Recurring outages, application failures and performance problems have led to contractual penalties, customer escalations and reputational damage. Today, teams only react after a system has already failed, even though warning signs are often present in the monitoring data. This project aims to make operations predictive.

Business Objectives
Identify the reasons for system failures.
Identify high-risk systems before they fail, so teams can take preventive action early.
Find out which preventive actions (such as maintenance or capacity changes) will help reduce downtime.

Analytical Objectives
Find out which factors are most related to system failures.
Build a machine learning model to predict which systems are at risk of failing.
Identify the characteristics of systems that stay stable, to help decide on preventive measures.

Dataset
Historical operational data collected from several systems (monitoring platforms, service management, infrastructure management and application performance monitoring).
Target: system_failure_flag (1 = failed, 0 = did not fail)
Features: 27 columns covering server details, CPU, memory, disk and network usage, application performance, incident history, maintenance and SLA costs
Some legacy/reference columns (e.g. legacy_monitoring_code, monitoring_batch_id, datacenter_reference) are expected to be removed during preprocessing

The dataset is provided for academic use and is not included in this repository. Place the file in data/raw/ before running the notebooks.

Approach
yet to identify an approach
