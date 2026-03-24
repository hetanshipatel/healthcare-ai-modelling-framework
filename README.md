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
- Advanced model benchmarking (XGBoost, Neural Networks)

---

## Key Insights

Initial experimental results indicate that classical ensemble methods such as Random Forest achieve strong predictive performance on structured clinical datasets.

The neural network model demonstrated similar accuracy to Random Forest, suggesting that deep learning architectures may not always provide performance advantages when dataset size is limited and feature complexity is moderate.

XGBoost did not outperform the baseline model, highlighting the importance of empirical evaluation rather than assuming boosting methods will consistently yield superior results.

These findings align with existing research literature indicating that tree-based ensemble methods often perform competitively on tabular healthcare data.
---

## Next Steps

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
