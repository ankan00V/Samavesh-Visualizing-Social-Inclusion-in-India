# Samavesh-Visualizing-Social-Inclusion-in-India

An in-depth data science project analyzing the Indira Gandhi National Disability Pension Scheme (IGNDPS) dataset, sourced from data.gov.in. The analysis spans over 14,000+ records across Indian states and districts, uncovering patterns in welfare distribution, demographic representation, and digital inclusion using Python, Pandas, Seaborn, Matplotlib, and Plotly.

🔍 Project Overview

This project applies Exploratory Data Analysis (EDA) and statistical modeling to investigate the structure and reach of the IGNDPS welfare scheme. With a focus on beneficiary demographics, Aadhaar/mobile linkage, and geographical coverage, this study offers a data-driven understanding of how inclusive and efficient the scheme is in real-time implementation.

🗂️ Dataset Information

Source: data.gov.in – Real-Time IGNDPS Dataset
Size: 14,000+ records
Fields Included:
state_name, district_name
total_beneficiaries
Demographic fields: sc, st, obc, gen
Digital markers: total_aadhar, total_mobileno
lastUpdated (timestamp for temporal analysis)
🎯 Project Objectives

Geographical Distribution Analysis
Visualizing spread and disparity of scheme beneficiaries across Indian states/districts.
Inclusion Index Computation
Quantifying Aadhaar/mobile linkage through a custom score for digital integration.
Correlation Analysis
Identifying statistical relationships between digital inclusion and beneficiary counts.
Temporal Trend Analysis
Examining the scheme’s rollout over time using the lastUpdated field.
Demographic Impact Modeling
Using regression to analyze the impact of caste-based classification on scheme coverage.
🔧 Technologies Used

Language: Python
Libraries:
pandas, numpy – Data manipulation
matplotlib, seaborn, plotly – Visualization
scikit-learn – Linear Regression and data scaling
datetime, re – Date parsing and formatting
📊 Visualizations

Choropleth & bar plots for state/district analysis
Time-series graphs for trend tracking
Heatmaps for correlation matrix
Scatter plots with hue-encoded variables
Interactive dashboards using Plotly
🧠 Key Findings

High Inclusion States: Jharkhand, Tamil Nadu, Andaman & Nicobar Islands showed 100% Aadhaar-mobile linkage.
Top Districts: North 24 Parganas and Kaushambi led in total and inclusive beneficiary counts.
Digital Integration: Correlation ≈ 0.83 between Aadhaar linkage and total beneficiaries.
Demographic Representation: OBC and SC groups showed higher enrollment in several states.
Temporal Trends: Time-indexed plots revealed growth plateaus and spikes aligned with policy campaigns.
📁 Project Structure

📦 IGNDPS-Data-Analysis/
├── 📄 realtime_data.csv                # Raw dataset from data.gov.in
├── 📄 igndps_analysis.ipynb           # Jupyter notebook with full EDA & analysis
├── 📄 report.pdf                       # Final report with plots and findings
├── 📄 README.md                        # Project documentation
└── 📊 plots/                           # Saved visualization images
📌 Future Enhancements

Integrate geospatial mapping using GeoPandas and Shapefiles.
Automate data refresh via API integration from data.gov.in.
Build a dashboard app with Streamlit or Dash for real-time monitoring.
Extend to other social schemes (e.g., PMAY, NSAP) for comparative welfare analytics.
🤝 Acknowledgements

Data.gov.in – for open access to national welfare datasets.
Python open-source community for EDA and visualization tools.
Inspiration from social policy researchers and data-for-good initiatives.
