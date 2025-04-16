  Wisconsin Breast Cancer Classification

This project applies **Logistic Regression** to the **Wisconsin Diagnostic Breast Cancer (WDBC)** dataset to classify tumors as benign or malignant based on various cell nucleus features.

---

# Dataset Overview

- **Source**: UCI Machine Learning Repository
- **Instances**: 569 patients
- **Features**: 30 numeric features computed from digitized images of breast mass FNA (fine needle aspirate)
- **Target**: Diagnosis (0 = Benign, 1 = Malignant)

---

 Model Building
 Algorithm: Logistic Regression  
We split the dataset into training and test sets (80/20 split), scaled the features, and applied logistic regression to predict tumor classification.

---

Evaluation Metrics

Confusion Matrix
![Correlation Matrix](Images/Correlation_Matrix.png)  

ROC Curve
![ROC](Images/ROC.png) 

- **Accuracy**: ~97%
- **Precision** and **Recall** are both high, indicating strong performance.
- **AUC = 1.00** — note: this may indicate potential overfitting due to multicollinearity.

---

 Multicollinearity Analysis

We found several **highly correlated features** (e.g., `radius_mean` with `area_mean`), which may contribute to overfitting.

---

Next Steps

- Reduce feature redundancy
- Try regularization techniques (e.g., L1/L2)
- Compare with other models (Random Forest, SVM)
- Cross-validation for robustness

---

Skills Demonstrated

- Clinical data interpretation
- Data preprocessing & visualization
- Logistic regression & evaluation
- Handling imbalanced classes
- Identifying multicollinearity
- Git + GitHub workflow

---

 Files

- `analysis.ipynb`: All code steps
- `Images/`: Folder with all figures used
- `wdbc.data`: Dataset used for classification

---

## 👩🏻‍💻 Author

**Ana Carolina Pacífico**  
Biomedical Scientist & Bioinformatics Enthusiast  
[LinkedIn](https://www.linkedin.com/in/ana-carolina-pacífico) | [GitHub](https://github.com/CarolPacifico0)
