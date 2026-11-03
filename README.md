# People Analytics: Employee Satisfaction, Workload & Stress Analysis

An end-to-end **People Analytics** project analyzing employee sentiment, workload distribution, stress drivers, commute factors, and training effectiveness across 2,766 employees in 8 corporate departments. The project features interactive visualizations and actionable HR/management recommendations designed to improve retention, productivity, and workplace well-being.

---

## Executive Summary & Overall Metrics

Based on the overall organizational dataset (**2,766 Total Employees** across IT, Finance, Operations, Marketing, Sales, Legal, Customer Service, and HR), key company-wide baseline metrics include:

| Metric | Overall Value (Out of 5.00) | Notes |
| :--- | :---: | :--- |
| **Total Headcount** | **2,766** | IT is the largest department (>500 staff), HR/CS are smallest |
| **Job Satisfaction Rate** | **3.38** | Moderate-high baseline across departments |
| **Workload Rate** | **2.98** | Balanced on average, but uneven across job levels |
| **Stress Rate** | **1.74** | Relatively low overall, but spiked by specific commute modes |

---

## Analytical Findings & Visual Insights

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       PEOPLE ANALYTICS DIAGNOSTIC PIPELINE                  │
├──────────────────────────────┬──────────────────────────────┬───────────────┤
│ 1. Workload & Stress         │ 2. Commute & Stress          │ 3. Training & │
│    Imbalances (By Dept/Level)│    Impact Analysis           │    Satisfaction│
│                              │                              │               │
│ • IT department deep-dive    │ • Commute distance vs stress │ • Low/Med/High │
│ • Junior vs Senior load      │ • Mode of transport analysis │   training hrs│
│ • Operational bottlenecks    │ • Remote work potential      │ • Satisfaction│
└──────────────────────────────┴──────────────────────────────┴───────────────┘
```

---

### 1. Workload & Stress Dynamics by Department (IT Deep-Dive)
* **Finding:** IT is the largest department in the company. Aggregate metrics show IT's **Stress Rate (~1.68)** and **Workload Rate (~3.00)** are in the middle tier compared to other departments.
* **Insight:** While overall IT metrics appear stable on the surface, granular analysis reveals structural workload distortions across experience tiers.

---

### 2. Workload Breakdown by Job Level (Entry-Level Bottleneck)
| Job Level | Workload Rate (1.00 – 5.00) | Manpower & Role Context |
| :--- | :---: | :--- |
| **Intern / Fresher** | **3.10** | **Highest workload rate** in the IT department |
| **Junior** | **3.09** | Heavy operational burden with least experience |
| **Lead** | **3.02** | Supervisory & technical coordination load |
| **Senior** | **2.97** | Moderate workload distribution |
| **Mid-Level** | **2.90** | Lowest workload rate among IT tiers |

* **Key Finding:** In the IT department, entry-level employees (**Interns/Freshers at 3.10** and **Juniors at 3.09**) carry the highest workload rate despite having the least manpower, bandwidth, and organizational experience compared to their mid-senior counterparts.
* **Actionable Recommendation:** Senior staff and engineering leads must ensure entry-level employees receive adequate mentoring, task re-balancing, clear documentation, and inclusive team support to prevent early burnout.

---

### 3. Commute Mode vs. Stress Rate Correlation
| Commute Mode | Avg. Commute Distance (KM) | Stress Rate (1.00 – 5.00) | % of IT Workforce |
| :--- | :---: | :---: | :---: |
| **Public Transport** | **17.0 km** | **1.68** | ~70% combined (Public Transport + Car) |
| **Car** | **16.0 km** | **1.68** | ~70% combined (Public Transport + Car) |
| **Walk** | < 5.0 km | ~1.65 | Minor group |
| **Motorbike** | Short | ~1.55 | Lower stress |
| **Bike** | Short | ~1.58 | Lower stress |

* **Key Finding:** Approximately **70% of IT employees** commute via Car or Public Transport. These two groups cover the longest commute distances (**16 km** and **17 km** respectively) and report the highest stress rates (**1.68 / 5.00**). The data indicates a direct positive correlation between longer commute distance and elevated employee stress.
* **Actionable Recommendation:** Evaluate whether IT employees whose responsibilities center around online complaints, software maintenance, and ticket resolution can transition to Work-From-Home (WFH) or flexible hybrid arrangements to reduce commute-induced stress.

---

### 4. Training Hours vs. Job Satisfaction vs. Work Environment
* **Training Cohorts:**
  * **Low Training:** 0 – 32 Hours
  * **Medium Training:** 33 – 44 Hours
  * **High Training:** 45+ Hours

| Training Group | Work Environment Rating | Job Satisfaction Score | Strategic Summary |
| :--- | :---: | :---: | :--- |
| **High (45+ hrs)** | **Highest** | Moderate (~3.34) | High env perception, but training alone does not maximize satisfaction |
| **Medium (33–44 hrs)** | **High** | **Highest (~3.40+)** | **Sweet spot:** Optimal balance of satisfaction & work environment rating |
| **Low (0–32 hrs)** | **Lowest** | **Lowest (~3.16)** | Under-resourced employees report lowest scores across all axes |

* **Key Findings:**
  1. Employees with **High training hours** rate their Work Environment highest, but this does not automatically translate into peak Job Satisfaction.
  2. Employees with **Medium training hours** achieve the optimal "sweet spot", reporting both high Work Environment scores and the highest Job Satisfaction.
  3. Employees in the **Low training group** exhibit the lowest scores in both Work Environment perception and Job Satisfaction.
* **Actionable Recommendations & Next Steps:**
  * **Mandatory Upskilling:** Establish mandatory baseline training (at least 33+ hours) for employees in the Low training cohort to elevate satisfaction and workplace perception.
  * **Qualitative Investigation:** Conduct focus groups for the High training cohort to identify secondary friction factors (e.g., career growth bottlenecks or training-work balance) preventing high training from yielding top satisfaction.

---

## Summary of Strategic Recommendations Matrix

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                       PEOPLE ANALYTICS RECOMMENDATIONS MATRIX               │
├───────────────────┬─────────────────────────────────────────────────────────┤
│ Target Focus Area │ Actionable Strategy & HR Policy                         │
├───────────────────┼─────────────────────────────────────────────────────────┤
│ Entry-Level IT    │ • Rebalance task allocations from Juniors to Mid/Seniors │
│ Workload          │ • Implement structured mentorship & pairing programs    │
├───────────────────┼─────────────────────────────────────────────────────────┤
│ Commute Stress    │ • Introduce WFH / Hybrid policy for digital IT roles    │
│ Mitigation        │ • Reduce peak-hour travel requirements for 16km+ distance│
├───────────────────┼─────────────────────────────────────────────────────────┤
│ L&D Program       │ • Upgrade Low-training employees to 33–44 hr curriculum │
│ Optimization      │ • Audit High-training group for underlying satisfaction │
│                   │   barriers outside of technical training                │
└───────────────────┴─────────────────────────────────────────────────────────┘
```

---

