
# Gender-Based Computational Thinking Analysis

This repository presents a comprehensive analysis of gender-based differences in computational thinking (CT) strategies across programming skill levels and developmental stages using a combination of statistical methods, machine learning models, and transformer-based approaches.

## Dataset
- **File:** sample_ct_gap.csv
- **Attributes:** Gender, Age, Programming_Skill_Level, Abstraction_Score, Decomposition_Score, Algorithmic_Thinking_Score, Debugging_Score, Pattern_Recognition_Score, Improvement_Score

## Methodology Overview
- **Descriptive Analysis:** Mean, Median, Std Dev, Shapiro-Wilk Normality Test
- **Inferential Statistics:** T-tests, ANOVA, Chi-square, Wilcoxon, McNemar, Friedman, Cohen's d
- **Explainable AI:** SHAP and LIME for feature importance interpretation
- **Predictive Modeling:** Logistic Regression, Random Forest, SVM, LSTM, GRU, Bi-LSTM, and BERT
- **Performance Evaluation Metrics:** Accuracy, Precision, Recall, F1-Score, ROC AUC

## Hardware & Libraries
- CPU: Intel Core i7
- GPU: NVIDIA RTX 3060
- RAM: 16 GB
- Python 3.10
- Libraries: pandas, scikit-learn, transformers, PyTorch, SHAP, lime


## Key Findings
- 60-40 significant gender _M-F_ differences in CT strategy scores based on statistical tests.
- Programming skill level was the most influential factor in predictive modeling.
- BERT achieved the highest classification accuracy of **94.7%** with **AUC = 0.893**.

## Citation
If you use this work, please cite appropriately.

---

For more information, contact the research author.
