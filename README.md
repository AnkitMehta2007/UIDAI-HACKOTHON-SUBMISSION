# 🇮🇳 The Aadhaar Lifecycle Matrix: AI-Driven Policy for a Dynamic India
###  UIDAI Hackathon 2026 Submission

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)

> **Project Vision:** Moving from a "Static Registry" model to a "Dynamic Resource Allocation" framework using Unsupervised Machine Learning.

---

##  Problem Statement: "The Two Indias"
UIDAI's current operational model assumes uniform demand across the country. However, our analysis of **1M+ Enrolment and Update records** reveals a fractured landscape:

1.  **Mature States (e.g., Maharashtra):** Function as **Birth Registries**. >90% of enrolments are infants. Centers are efficient but under-utilized for growth.
2.  **Catch-up States (e.g., Meghalaya):** Function as **Adult Registries**. A surge of adult applicants crowds out infants, causing service collapse.

**The Impact:** A "One Size Fits All" approach leads to a **29x Efficiency Gap** between stable and crisis districts.

---

## The Solution: The Aadhaar Lifecycle Matrix
We developed an ML-driven framework that segments 700+ districts into operational clusters, allowing for dynamic policy interventions.

### Key Features & Innovations
* ** Unsupervised Clustering (K-Means):** Automatically segments districts into "Crisis," "Stable," and "Transitioning" zones based on Enrolment Maturity.
* ** Anomaly Detection (Isolation Forest):** Identifies "Hyper-Efficient" districts and hidden "Migrant Hubs" that defy state-level averages.
* ** Seasonality Detection:** A Heatmap analysis identifying the **"School Rush"** (July/Sept), enabling predictive staffing.
* ** Mobility Index:** A novel metric (Demographic/Biometric Update Ratio) to identify economic migration hotspots like Delhi/Chandigarh.

---

## Key Insights (Data-Driven)

| Metric | Mature Zone (Stable) | Crisis Zone (Catch-up) | Impact |
| :--- | :--- | :--- | :--- |
| **Child Enrolment %** | **> 90%** (Newborns) | **< 30%** (Adults) | Infants excluded in Crisis zones. |
| **Service Ratio** | **29.0** Updates/New | **0.8** Updates/New | Maintenance neglected in Crisis zones. |
| **Intervention** | Shift to Hospital Integration | **"Green Lanes"** Priority | **Camp Mode** during School Rush. |

---

## Repository Structure

```bash
├── data/                   # (Excluded from repo for privacy/size)
├── notebooks/
│   └── Aadhaar_Lifecycle_Analysis.ipynb  # MAIN CODE (Data Pipeline + ML)
├── outputs/
│   ├── Final_Analysis_Plot.png           # The Lifecycle Matrix Graph
│   ├── Seasonality_Heatmap.png           # School Rush Visualization
│   ├── District_Variance_Boxplot.png     # Intra-State Disparity
│   └── UIDAI_Strategic_Roadmap.txt       # Auto-generated Policy Report
├── README.md               # Project Documentation
└── requirements.txt        # Python Dependencies
