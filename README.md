# 🧠 Human Age Prediction — End-to-End ML + Snowflake + Tableau Analytics

> A full-stack Machine Learning project combining Python model development, Snowflake SQL validation, and advanced Tableau analytics dashboards.

Built by **Dhruv Sharma**

---

## 🔎 Project Overview

This project predicts human age using lifestyle, demographic, and behavioral features.

The objective was not just to build a model —  
but to **evaluate it like a production system** using:

- Model error diagnostics
- Bias analysis
- Segment sensitivity testing
- Residual analysis
- SQL validation in Snowflake
- Executive-level dashboards in Tableau

---

# 🏗 Tech Stack

**Machine Learning**
- Python
- Pandas
- NumPy
- Scikit-Learn

**Data Warehouse**
- Snowflake
- SQL Views
- Analytical aggregations

**Business Intelligence**
- Tableau Public
- Advanced Calculated Fields
- Parameter-driven segmentation
- Interactive dashboards

---

# 📊 Dashboard 1 — Human Age Prediction

This dashboard focuses on understanding:
- Actual vs Predicted age
- Age gap distribution
- Lifestyle-based error patterns
- Aging risk segmentation

### 🔹 Preview

![Age Prediction Dashboard](dashboard/age_prediction_dashboard/age_prediction.png)

### Key Insights
- Model prediction closely tracks actual age trend.
- Error distribution centers around zero (minimal systemic bias).
- Lifestyle factors impact prediction spread.
- Risk-based segmentation reveals aging sensitivity clusters.

---

# 📈 Dashboard 2 — Model Evaluation & Segment Sensitivity

This dashboard analyzes model robustness using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- Average Prediction Bias
- Residual Diagnostics
- Error Distribution Histogram
- Segment Sensitivity (Dynamic Parameter)
- High Error Flag Monitoring

### 🔹 Preview

![Model Evaluation Dashboard](dashboard/model_evaluation_dashboard/model_evaluation.png)

### Model Performance

| Metric | Value |
|--------|-------|
| MAE | 4.36 years |
| RMSE | 5.469 years |
| Avg Bias | 0.13 years |
| Predictions Evaluated | 600 |

---

# 🗄 Snowflake Validation Layer

Model outputs were pushed into Snowflake and analyzed using SQL:

- Joined training data with predictions via `PERSON_ID`
- Created analytical views
- Calculated:
  - MAE
  - Bias
  - Age-group error breakdown
  - Lifestyle sensitivity
- Built dashboard-ready tables

This ensures:
✔ SQL validation  
✔ Production-style evaluation  
✔ Warehouse-level metric verification  

---

# 🧪 Advanced Diagnostics

The project includes:

- Residual plot analysis  
- Error vs Age trend  
- Segment-driven sensitivity testing  
- High-error flag detection  

These are production-grade model evaluation techniques.

---

# 📂 Repository Structure

Human-Age-Prediction/
│
├── data/
├── notebooks/
├── models/
├── snowflake_sql/
├── dashboard/
│ ├── age_prediction_dashboard/
│ │ ├── age_prediction.twbx
│ │ └── age_prediction.png
│ └── model_evaluation_dashboard/
│ ├── model_evaluation.twbx
│ └── model_evaluation.png
└── README.md

---

# 🎯 What This Project Demonstrates

✔ End-to-end ML pipeline  
✔ Feature-driven age prediction  
✔ SQL-based evaluation layer  
✔ Error + bias diagnostics  
✔ BI storytelling with Tableau  
✔ Segment sensitivity analytics  
✔ Production-level validation mindset  

---

# 🚀 Business Impact Framing

This project simulates how a healthcare or insurance company might:

- Predict biological aging risk
- Detect abnormal aging patterns
- Monitor model bias across demographic segments
- Validate ML outputs inside a data warehouse
- Deliver executive-ready dashboards

---

# 📬 Connect With Me

**Dhruv Sharma**  
Data | Analytics | Machine Learning  

LinkedIn: *[www.linkedin.com/in/
dhruv-sharma2299/]*  
Tableau Public: *[https://public.tableau.com/app/profile/dhruv.sharma6989]*  

---

> This project reflects production-level thinking — not just model building.
