# Healthcare AI Modelling Framework

A research-oriented framework for developing, evaluating, and interpreting machine learning models for healthcare risk prediction and decision modelling.

This repository focuses on building reproducible pipelines for clinical data analysis, model benchmarking, and explainable AI experimentation.

---

## Project Objective

The goal of this project is to explore how machine learning can support clinical risk assessment by analysing relationships between physiological signals and disease outcomes.

Initial experiments focus on cardiovascular risk modelling using structured clinical datasets.

---

## Dataset

This project uses the Heart Disease dataset available on Kaggle:

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

The dataset includes clinical attributes such as:

- Age and sex
- Chest pain type
- Resting blood pressure
- Serum cholesterol
- Fasting blood sugar
- Electrocardiographic results
- Maximum heart rate achieved
- Exercise-induced angina
- ST depression and slope
- Number of major vessels
- Thalassemia status

The dataset is used for research and educational purposes.  
All patient identifiers have been removed.

---

## Work Completed

### Data Acquisition
- Programmatic dataset download using Kaggle API
- Reproducible data loading pipeline

### Data Exploration
- Dataset structure inspection
- Missing value analysis
- Target distribution visualization
- Statistical summary analysis

### Data Preprocessing
- Missing value handling using median imputation
- Numeric conversion of clinical features
- Correlation analysis for feature relationships

### Baseline Modelling
- Train-test split implementation
- Random Forest baseline model
- Performance evaluation
- Feature importance analysis

---

## Key Insight

Initial results demonstrate that certain clinical features show stronger predictive relevance for cardiovascular risk modelling. These insights guide future feature engineering and model development stages.

---

## Next Steps

- Advanced model benchmarking (XGBoost, Neural Networks)
- Explainability using SHAP
- Uncertainty estimation
- Bias and fairness analysis
- Time-series clinical modelling
- Extension to multi-disease prediction

---

## Research Direction

This framework aims to evolve into a modular platform for:

- Explainable Healthcare AI
- Clinical Decision Modelling
- Risk Stratification Systems
- Trustworthy Machine Learning
- Neuro-inspired AI Extensions

---

## License

MIT License
