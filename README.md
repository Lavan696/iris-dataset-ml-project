# Iris Species Classification using Decision Tree Classifier

## Overview

This project focuses on classifying Iris flower species using the **Decision Tree Classifier**.  
The Iris dataset, a classic benchmark dataset in machine learning, contains 150 samples across three species — *Setosa*, *Versicolor*, and *Virginica* — with four distinct features:  
- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

---

## Dataset

- **Number of Classes:** 3  
- **Features:** 4 continuous numeric features (measured in cm)  
- **Samples:** 150 (50 per class)

---

## Model Details

- **Algorithm Used:** Decision Tree Classifier  
- **Calibration:** Performed using `CalibratedClassifierCV` with isotonic calibration to improve probability estimates  
- **Train-Test Split:** 80-20  
- **Cross Validation:** 5-Fold

---

## Visualizations
Extensive visual analysis was performed to better understand the dataset and model behavior:
- **Correlation Heatmap** – visualizes relationships between features  
- **Pair Plot** – shows feature separation across species  
- **Feature Importances Bar Chart** – highlights the most influential features  
- **Calibration Curve** – evaluates how well predicted probabilities are calibrated  
- **Learning Curve** – assesses bias-variance tradeoff  
- **Confusion Matrix** – displays correct and incorrect classifications  
- **ROC Curve (One-vs-Rest)** – illustrates class separability  
- **Precision-Recall vs Threshold** – balances precision and recall across thresholds  
- **Classification Report Heatmap** – summarizes performance per class visually  

---

## Evaluation Metrics

| Metric               | Score      |
|:---------------------|:----------:|
| Cross Val Mean Score | **93.33%** |
| Test Accuracy        | **100%**   |
| Precision            | **100%**   |
| Recall               | **100%**   |
| f1-Score             | **100%**   |
| Log Loss             | **0.05**   |
| Cohen’s Kappa Score  | **100%**   |
| Matthews Corr Coef   | **100%**   |
| Top-K Acc (k = 2)    | **100%**   |

The model achieves near-perfect classification performance across all metrics, indicating robust learning and effective calibration.

---
## Tech Stack
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## How to Run  

1. **Clone the repository**  
`bash
git clone https://github.com/your-username/iris-decision-tree-classifier.git`

---
## Author

**Lavan Kumar Konda**  
Student at NIT Andhra Pradesh  
Passionate about Machine Learning, Data Science, and AI 
**LinkedIn:**[https://www.linkedin.com/in/k-lavan-kumar-konda]
