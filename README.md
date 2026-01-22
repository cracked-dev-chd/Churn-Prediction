# Player Churn Prediction & A/B Testing Framework
**Status: Active Development (Core Analysis & Statistical Framework Complete)**

## Project Overview
This project addresses player attrition in a gaming context. By analyzing historical player behavior logs, I developed a predictive model to identify users likely to churn and designed a statistically validated A/B test to measure the impact of a re-engagement feature.

## Key Performance Indicators (Targeted)
* **Model Performance:** 80% Recall (Random Forest).
* **Experimentation:** $p < 0.05$ (Two-sample T-test) for re-engagement feature lift.
* **Business Metric:** Projected 12% reduction in player churn via targeted rewards.

## Tech Stack
* **Languages:** Python (Pandas, Scikit-Learn, SciPy).
* **Database:** PostgreSQL (User-level aggregation and cohort analysis).
* **Visualization:** Streamlit for real-time tracking of DAU/MAU and retention curves.

## Methodology
1. **Data Aggregation:** Transforming raw event logs into user-level features (Recency, Frequency, Monetary).
2. **Predictive Modeling:** Training a Random Forest classifier to flag players at risk of churning.
3. **Statistical Testing:** Simulating an A/B test on a "Level-Up Bonus" feature to confirm a statistically significant retention boost.
4. **Dashboarding:** Building a product dashboard to monitor player health metrics.

## Roadmap
- [x] PostgreSQL database schema for player logs.
- [x] Baseline churn model implementation.
- [ ] Final Streamlit dashboard deployment.
- [ ] Integration of real-time inference pipeline.
