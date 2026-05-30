# Cloud Cost Audit: Global Insurance Corp

## Executive Summary
This project provides a comprehensive audit of cloud infrastructure expenditures for Global Insurance Corp. The analysis focuses on identifying cost inefficiencies, optimizing resource allocation, and providing actionable insights for infrastructure management.

## Technical Approach
* **Data Ingestion & Preprocessing:** Leveraged Python and Pandas to clean and normalize raw cloud billing data, ensuring data integrity for analysis.
* **Exploratory Data Analysis (EDA):** Performed statistical analysis to identify cost anomalies, peak usage patterns, and underutilized instances.
* **Cost Optimization Strategy:** Developed a framework to prioritize cost-saving initiatives based on ROI and resource impact.
* **Visualization:** Utilized Matplotlib to create visual representations of cost drivers and potential savings.

## Key Findings
* Identified Resource Stagnation: Found significant waste due to manual lifecycle management.
* Proposed Automated Governance: Transitioned to an "Automated Lifecycle" model using Infrastructure as Code (IaC) to enforce TTL (Time-To-Live) tags on non-production assets.
* Implemented Proactive Controls: Designed a serverless-based automated shutdown workflow (triggered after 7 days of inactivity) to ensure cost efficiency without manual intervention.

## Remediation Strategy: Automated Governance
* **Objective:** Transition from manual audits to automated lifecycle management to prevent asset stagnation.
* **Infrastructure as Code (IaC):** Enforced TTL (Time-To-Live) tags on all non-production assets to automate ownership tracking.
* **Automated Lifecycle Hooks:** Implemented serverless functions to trigger shutdown warnings after 5 days of inactivity, with automated termination after 7 days.
* **Continuous Monitoring:** Shifted from static reporting to real-time alerting, notifying department owners at the 3-day inactivity threshold to ensure accountability.

Continuous Monitoring: Shifted from static reporting to real-time alerting, notifying department owners at the 3-day inactivity threshold to ensure accountability.
## Technologies & Libraries
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Environment:** Jupyter Notebooks

## How to View
The full technical analysis can be found [here](https://colab.research.google.com/drive/1R5eo80oPxE-qRQHCIFCoNwCPDcMHyzPa?usp=drive_link).

### Project Updates
* May 30, 2026: *Refined methodology documentation and updated project links for improved accessibility.*

* May 30, 2026: *Github keeps throwing errors using the notebook file. I deleted notebook and replaced with the HTML file.*  
