# PM Vishwakarma Skill Development Dashboard  
### National Skill Ecosystem Monitoring & Evaluation (MEL) Framework

## Overview

This project presents an end-to-end **Monitoring, Evaluation, and Learning (MEL) dashboard** for the **PM Vishwakarma Skill Development Scheme**, designed to track, compare, and analyze performance across **States, Districts, Trades, and Skill Pipeline Stages**.

The dashboard translates raw MIS data into **decision-ready insights** for policymakers, PMUs, consultants, and program managers by combining:
- Skill pipeline tracking
- Dynamic KPI-driven analysis
- Comparative performance views
- Governance-focused metrics

The solution is built using **Power BI** with a strong emphasis on **data modeling discipline, analytical rigor, and MEL principles** rather than cosmetic visualization.

🔗 **Live Dashboard**  
[View Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZWU4ZGU0NzItYzY1MC00YTE4LWIxODctYzM1OWI1NGM3ZTU2IiwidCI6ImZhNGZlYjhkLTNkNDItNDU4My1iNTRjLTMyYjQwNzYzMDI0NSJ9)

---

## 🖼️ Dashboard Preview

![PM Vishwakarma Power BI Dashboard](Dashboard_Photo.jpg)

*Figure: National Skill Development Ecosystem Dashboard for PM Vishwakarma Scheme*

## Problem Statement

Large-scale government skill development programs generate vast MIS datasets but often fail to:
- Clearly track **pipeline leakage**
- Enable **stage-wise performance comparison**
- Support **evidence-based decision-making**
- Distinguish between **scale** and **effectiveness**

This project addresses these gaps by designing a **national-level skill ecosystem performance framework** aligned with MEL best practices.

---

## Skill Development Pipeline Covered

The dashboard tracks the complete lifecycle of beneficiaries across the following stages:

1. Stage 3 Verified Candidates  
2. Pre-Skilling Enrolled  
3. Pre-Skilling Assessed  
4. Basic Skilling Enrolled  
5. Basic Skilling Trained  
6. Basic Skilling Assessed  
7. Basic Skilling Certified  
8. Total Candidates Available  

Each stage is treated as a measurable system checkpoint, not just a count.

---

## Key Analytical Features

### 1. Dynamic KPI Selector (Core Innovation)
- A **disconnected KPI selector** enables users to switch the analytical lens across different pipeline stages.
- All visuals dynamically update based on the selected stage.
- Ensures **single-source logic** without duplicating visuals or measures.

### 2. Stage-wise Comparative Analysis
- **State-wise**, **District-wise**, and **Trade-wise** visuals automatically reorder in descending order of performance.
- Enables instant identification of relative progress without artificial Top/Bottom thresholds.

### 3. Separation of Scale vs Effectiveness
- **Absolute volumes** (enrolled, trained, certified) are shown separately from  
- **Conversion and efficiency indicators** (delivery rate, certification yield, leakage).

This prevents misleading interpretations based solely on scale.

### 4. Governance-Grade Design
- Explicit base measures (no implicit aggregations)
- Layered DAX architecture (Base → Derived → Dynamic)
- Clean interaction control between visuals
- Designed for PMU review settings, Government Departments and Skill Ecosystem Stakeholders on the theme of Public Dashboard

---

## Key Measures & Metrics

### Base Measures
- Verified Candidates
- Pre-Skilling Enrolled / Assessed
- Basic Skilling Enrolled / Trained / Assessed / Certified
- Total Candidates Available

### Derived MEL Indicators
- Verification → Enrollment Rate
- Pre-Skilling Completion Rate
- Training Delivery Rate
- Assessment Coverage Rate
- Certification Yield
- Ecosystem Leakage (absolute and percentage)

### Dynamic Measures
- Dynamic KPI Value (controlled via selector)
- Dynamic Rank (State / District / Trade)
- Dynamic Titles (visual auto-renaming)

---

## Key Insights from the Dashboard

### 1. Zero Training Activity in Tamil Nadu and West Bengal
- The dashboard clearly shows **zero training and certification activity** in **Tamil Nadu** and **West Bengal**.
- This is not a data error but reflects **non-implementation of the PM Vishwakarma scheme** in these states.

### 2. Policy Context (Analytical Interpretation)
- Tamil Nadu CM has publicly expressed concerns regarding potential **caste-based exclusion** in the scheme design.
- The state government indicated the need for a **more inclusive, locally tailored artisan support program**.
- West Bengal has also not implemented the scheme in its current form.

### 3. National Scale and Pipeline Strength

Over 2.95 million candidates have been successfully verified under the PM Vishwakarma ecosystem, indicating strong outreach and beneficiary identification at the national level.

A high proportion of verified candidates transition into Pre-Skilling enrolment (≈96%), reflecting effective mobilisation and onboarding mechanisms.

The pipeline shows minimal friction from enrolment to training, with Training Delivery efficiency nearing 99%, highlighting strong Training Centre execution.

### 4. Assessment and Certification Outcomes

Certification Yield is exceptionally high (≈99.9%), suggesting:

Effective alignment between training content and assessment standards.

Strong coordination between Training Partners and Sector Skill Councils (SSCs).

The close alignment between Basic Skilling Trained, Assessed, and Certified counts indicates low assessment backlog and timely certification.

### 5. Ecosystem Leakage and Dropout Analysis

Despite strong delivery, the dashboard highlights an ecosystem leakage of ~5.84 lakh candidates (≈19.8%) from verification to certification.

This leakage is not concentrated at the training or assessment stage, but primarily occurs before or during Pre-Skilling, pointing to:

Candidate readiness challenges

Local-level mobilisation constraints

Socio-economic or occupational migration factors

This insight is critical for MEL teams to design targeted pre-skilling interventions rather than post-training corrections.

### 6. State-wise Performance Patterns

States such as Karnataka, Madhya Pradesh, Maharashtra, Rajasthan, and Gujarat consistently appear as top contributors across multiple stages of the pipeline.

Tamil Nadu and West Bengal show zero participation, which aligns with policy-level decisions where the PM Vishwakarma scheme has not been implemented in its current form.

In Tamil Nadu, concerns were raised regarding caste-based eligibility and inclusivity, with the state opting to explore an alternative artisan support framework.

West Bengal has similarly not operationalised the scheme.

This distinction is important for interpretation, as zero values reflect policy choices, not implementation failure.

### 7. District-level Concentration

District-wise rankings reveal high concentration of beneficiaries in a limited number of districts, suggesting:

Clustering of traditional artisan occupations

Better administrative readiness in certain districts

This insight can guide future decentralised planning, capacity expansion, and district-specific mobilisation strategies.

### 8. Trade-wise Distribution Insights

Trades such as Mason, Carpenter, Tailor, Barber, and Malakar dominate enrolment and certification numbers.

Several niche trades (e.g., Armourer, Boat Maker, Goldsmith) show lower participation, indicating:

Limited geographic spread

Potential need for trade-specific awareness or demand assessment

This supports evidence-based trade prioritisation rather than uniform expansion.

### 9. Zone-wise Patterns

The South and West zones account for a significant share of enrolments and certifications, while North-East participation remains comparatively low.

This spatial imbalance highlights the need for region-specific skilling strategies, rather than a one-size-fits-all approach.

### 10. Value of the Dynamic KPI Framework

The stage-based KPI selector enables stakeholders to dynamically assess performance at:

Verification

Enrolment

Training

Assessment

Certification

This design allows policymakers and MEL professionals to:

Diagnose bottlenecks stage-wise

Compare States, Districts, Trades, and Zones on a consistent metric

Avoid misleading conclusions based on static or aggregate indicators

### 🧠 Overall Interpretation

The dashboard demonstrates that the PM Vishwakarma skill development ecosystem is operationally strong, with high training and certification efficiency. The primary opportunity for improvement lies upstream in mobilisation and pre-skilling retention, rather than downstream training quality. The analysis also underscores the importance of contextual interpretation, especially in states where non-implementation is a policy decision rather than a performance gap.

**Analytical takeaway:**  
The absence of data from these states must be interpreted as a **policy and governance decision**, not program underperformance. This distinction is critical for fair evaluation.

### (i) Uneven Pipeline Conversion Across States
- Some states show strong verification and enrollment but weaker transitions to training and certification.
- Indicates gaps in **Training Centre capacity, batch planning, or assessment coordination** rather than mobilization alone.

### (ii) Trade-Level Variability
- Certain trades consistently outperform others in certification yield.
- Highlights the need for **trade-specific curriculum, trainer quality, and SSC alignment reviews**.

---

## Tools & Technologies Used

- **Power BI Desktop**
- **DAX (Advanced)**
- **Power Query**
- **Data Modeling & Visualization**
- **MEL Framework Design**

---

## Who This Dashboard Is For

- Goverenment Departments and Stakeholders 
- PMUs / TSAs / Consulting firms  
- MEL & Impact Assessment professionals  
- Skill Development Program Managers  
- Researchers and policy analysts  

---

## How This Project Demonstrates Expertise

This project demonstrates the ability to:
- Translate policy programs into measurable systems
- Apply MEL thinking to large administrative datasets
- Build scalable, reusable analytical architectures
- Communicate insights clearly to non-technical stakeholders
- Distinguish governance issues from implementation performance

---

## Author & Attribution

**Designed and Developed by**  
**Waseem Ahmad Dar**  
Data Analyst | MEL Specialist | Government & Skill Development Consulting

---

## Disclaimer

This dashboard is an analytical and academic exercise based on available MIS data.  
Policy interpretations are contextual and intended for analytical understanding, not advocacy.

---

## Feedback & Collaboration

Feedback, suggestions, and professional collaboration are welcome.
