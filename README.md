# Healthcare AI Modelling Framework

A research-oriented framework for developing, evaluating, and interpreting machine learning models for healthcare risk prediction and clinical decision modelling.

This project demonstrates an end-to-end experimental pipeline for structured clinical data, combining predictive modelling, explainable AI, and robust validation techniques.

---

## 🔎 Project Overview

The objective of this project is to investigate how machine learning models can support clinical risk assessment by learning patterns from physiological and diagnostic features.

The initial study focuses on cardiovascular risk prediction using a structured clinical dataset, with emphasis on:

- Model comparison across different learning paradigms  
- Explainability and interpretability  
- Robust evaluation and validation  
- Practical relevance to healthcare decision-making  

---

## 📊 Dataset

This project uses the Heart Disease dataset available on Kaggle:

https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

The dataset includes key clinical attributes:

- Demographics: age, sex  
- Clinical measurements: blood pressure, cholesterol, blood sugar  
- Cardiac indicators: ECG results, heart rate, angina  
- Diagnostic features: ST depression, vessel count, thalassemia  

All patient identifiers have been removed, and the dataset is used strictly for research and educational purposes.

---

## ⚙️ Methodology

The project follows a structured experimental pipeline:

1. Data acquisition using Kaggle API  
2. Data exploration and statistical analysis  
3. Data preprocessing and cleaning  
4. Model training and evaluation  
5. Explainability analysis  
6. Validation and performance assessment  
7. Model optimisation  

---

## 🧪 Work Completed

### Data Acquisition
- Programmatic dataset download using Kaggle API  
- Reproducible data loading pipeline  

### Data Exploration
- Dataset structure inspection  
- Missing value analysis  
- Target distribution visualisation  
- Statistical summary analysis  

### Data Preprocessing
- Missing value handling using median imputation  
- Numeric conversion of clinical features  
- Correlation analysis for feature relationships  

### Modelling & Evaluation
- Train-test split implementation  
- Random Forest baseline model  
- XGBoost model implementation  
- Neural Network (MLP) implementation  
- Model performance comparison  
- Feature importance analysis  
- ROC-AUC evaluation  
- Cross-validation for generalisation assessment  
- Confusion matrix for clinical error analysis  

### Explainability
- SHAP-based model interpretation  
- Feature contribution analysis for clinical insights  

### Optimisation
- Hyperparameter tuning for XGBoost  
- Significant performance improvement after optimisation  

---

## 📈 Key Insights

- Random Forest demonstrated strong and stable performance on structured clinical data.  
- Neural Networks achieved comparable results, indicating limited advantage of deep learning in small tabular datasets.  
- XGBoost initially underperformed but improved significantly after hyperparameter tuning.  
- SHAP analysis revealed clinically meaningful feature contributions, enhancing interpretability.  
- ROC-AUC results showed strong discriminative performance across all models.  
- Cross-validation confirmed model stability, though near-perfect scores suggest possible dataset simplicity or overfitting.  
- Confusion matrix analysis showed high precision with minimal false negatives, highlighting strong predictive reliability with minor clinical risk.  
- Model performance is highly dependent on dataset characteristics and proper optimisation.  

---

## 🧠 Research Significance

This project demonstrates key principles in applied machine learning for healthcare:

- Empirical model comparison is essential  
- Interpretability is critical for clinical applications  
- High accuracy alone is insufficient without validation  
- Model selection must consider dataset size and structure  

The findings align with existing literature where ensemble tree-based models perform strongly on tabular healthcare data.

---

## 🚀 Next Steps

- Extend validation using additional datasets  
- Explore advanced hyperparameter optimisation techniques  
- Incorporate calibration and uncertainty estimation  
- Evaluate fairness and bias across subgroups  
- Expand to multi-disease prediction frameworks  

---

## 🔬 Research Direction

This framework is designed to evolve into a modular research platform for:

- Explainable Healthcare AI  
- Clinical Decision Support Systems  
- Risk Stratification Models  
- Trustworthy Machine Learning  
- Neuro-inspired AI systems  

---

## 📜 License

MIT License
