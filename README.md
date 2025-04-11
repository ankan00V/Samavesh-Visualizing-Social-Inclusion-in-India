# Samavesh-Visualizing-Social-Inclusion-in-India

A Data-Driven Evaluation of the Indira Gandhi National Disability Pension Scheme (IGNDPS)

📘 Overview

This project presents an in-depth exploratory and statistical analysis of the Indira Gandhi National Disability Pension Scheme (IGNDPS) dataset, sourced from the Government of India’s official open data platform, data.gov.in. The goal of the project is to evaluate the scheme’s effectiveness by uncovering hidden patterns, identifying inclusion gaps, and generating insights to inform policy-level decisions.

By leveraging modern data science methodologies and visual analytics, the study aims to assess the geographical distribution, digital penetration (Aadhar and mobile linkage), demographic outreach, and temporal progress of IGNDPS beneficiaries across India. The dataset comprises 14,000+ real-time records from various states and districts, providing a granular view of the scheme’s on-ground implementation.

🗃 Dataset Description

Source: data.gov.in
Total Records: 14,000+
Attributes Include:
Administrative: state_name, district_name
Beneficiary Metrics: total_beneficiaries, total_aadhar, total_mobileno
Caste Composition: sc, st, obc, gen
Time Series Indicator: lastUpdated
🎯 Analytical Objectives

Geographical Coverage Mapping
Assess state-wise and district-wise distribution to identify areas with significant or limited IGNDPS penetration.
Inclusion Index Development
Design and compute a digital inclusion metric using Aadhaar and mobile linkage data to benchmark technological outreach.
Statistical Correlation Analysis
Evaluate dependencies between beneficiary count and digital identification variables using correlation coefficients.
Temporal Trend Monitoring
Track scheme enrollment progression over time using the lastUpdated timestamp field for time-series analysis.
Demographic Impact Modeling
Apply regression analysis to determine how caste-based segments affect scheme participation across regions.
🧪 Methodology and Technologies

Language: Python 3.10+
Libraries & Tools:
Data Analysis: pandas, numpy
Visualization: matplotlib, seaborn, plotly.express
Modeling: scikit-learn (Linear Regression, StandardScaler)
Temporal Analysis: datetime
Feature Engineering:
Inclusion Score = (Aadhar + Mobile) / Total Beneficiaries
Year-Month Index from timestamp for trend analysis
Proportional caste-based demographic ratios
📈 Key Findings

States like Jharkhand, Tamil Nadu, and Andaman & Nicobar Islands showed complete digital inclusion (100% Aadhaar + mobile linkage).
Districts such as North 24 Parganas and Kaushambi lead in both absolute and inclusive beneficiary coverage.
A strong positive Pearson correlation (~0.83) exists between Aadhaar linkage and overall beneficiary count.
Time series plots revealed cyclical enrollment spikes, possibly aligning with awareness campaigns or policy mandates.
Demographic modeling highlighted OBC and SC populations as significantly represented in multiple high-performing regions.
📊 Visual Assets

State/District Bar Plots – For top contributors and lagging regions
Heatmaps – To visualize correlation between features
Scatter Plots with Color Encodings – For multi-variable exploration
Interactive Dashboards (Plotly) – For advanced data exploration
Line Graphs & Area Charts – To capture temporal trends
🧠 Strategic Insights

Digital Identity Integration plays a central role in accessibility and coverage.
Demographic segmentation analysis supports the effectiveness of affirmative action under welfare schemes.
Disparities across states/districts highlight areas requiring targeted outreach and administrative support.
📁 Repository Structure

📦 IGNDPS-Data-Analysis/
├── data/
│   └── realtime_data.csv
├── notebooks/
│   └── igndps_analysis.ipynb
├── visualizations/
│   └── *.png, *.html
├── report/
│   └── Samavesh_IGNDPS_Report.pdf
├── README.md
🚀 Future Roadmap

Integrate geospatial analysis using GeoPandas and state shapefiles.
Develop a real-time Streamlit dashboard for live monitoring and reporting.
Expand the framework to cover other welfare schemes for comparative analytics.
Incorporate machine learning clustering for identifying latent beneficiary patterns.
🧾 Citation & Acknowledgements

Dataset Source: Government of India Open Data Platform – https://data.gov.in
This project is part of a broader initiative to apply data for social good, especially in public policy evaluation and digital inclusion.
