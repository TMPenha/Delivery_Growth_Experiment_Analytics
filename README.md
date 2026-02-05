# Growth Experiment Analytics

## Overview

This project analyzes the impact of a promotional A/B experiment designed to evaluate how discount incentives affect user behavior, retention, and revenue. The goal is to combine data engineering, statistical analysis, and business reasoning to guide data-driven growth decisions.

The analysis simulates a real-world growth experiment pipeline, from raw data processing to actionable business insights.

---

## Objectives

- Build a clean analytical dataset from raw sources
- Evaluate experiment impact using A/B testing
- Identify behavioral segments with different responses
- Estimate financial viability of the promotion
- Recommend strategic improvements

---

## Methodology

The project follows a structured analytics pipeline:

Raw data → ETL → Analytical dataset → A/B analysis → Segmentation → Business insights


## Key components:

- Apache Spark for scalable ETL
- Statistical comparison of test vs control groups
- Behavioral segmentation analysis
- ROI modeling and business recommendations

---

## Project Structure

Delivery_Growth_Experiment_Analytics/
│
├── notebooks/
│ ├── 01_etl_spark.ipynb → Data ingestion and preparation
│ ├── 02_ab_analysis.ipynb → Experiment impact analysis
│ ├── 03_segmentation.ipynb → Behavioral segmentation
│ └── 04_business_insights.ipynb → Financial evaluation & strategy
│
├── reports/
│ └── final_report.pdf
│
└── README.md

## How to Run

This project is designed to run in **Google Colab**.

1. Open notebooks in order:
   - `01_etl_spark.ipynb`
   - `02_ab_analysis.ipynb`
   - `03_segmentation.ipynb`
   - `04_business_insights.ipynb`

2. Execute all cells sequentially.

Dependencies are installed inside each notebook.

---

## Key Analyses

- User retention comparison
- Purchase frequency impact
- Revenue uplift evaluation
- Segment-specific experiment performance
- Financial ROI estimation

---

## Business Insights

The analysis highlights:

- Which user groups respond best to incentives
- Financial sustainability of promotional campaigns
- Opportunities for targeted experimentation
- Strategy recommendations for growth optimization

---

## Assumptions & Limitations

- Financial modeling uses estimated promotional costs
- Behavioral segments are simplified for demonstration
- Results reflect experiment scope and dataset constraints

---

## Future Improvements

- Advanced causal inference methods
- Dynamic segmentation models
- Experiment automation pipelines
- Real-time analytics integration

---

## Author

Data experiment and analytics case study focused on scalable data workflows, statistical reasoning, and business impact.

---
