# Task-13-PCA-Dimensionality-Reduction
# Task 13: PCA – Dimensionality Reduction

## 📌 Overview
This task demonstrates **Principal Component Analysis (PCA)** for dimensionality reduction on an image dataset.  
The goal is to reduce the number of features while preserving maximum variance and then compare model performance.

## 🧰 Tools Used
- Python
- Scikit-learn
- Matplotlib

## 📂 Dataset Used
- **ASL-68287-train.csv** :contentReference[oaicite:2]{index=2}  
This dataset contains flattened image pixel values along with class labels.

## ✅ Steps Performed
1. Loaded the dataset and separated features (X) and labels (y)
2. Applied **StandardScaler** for feature scaling
3. Applied **PCA** with multiple component values: **2, 10, 30, 50**
4. Calculated and tracked **Explained Variance Ratio**
5. Plotted **Cumulative Explained Variance**
6. Reduced dataset dimensionality using PCA
7. Trained **Logistic Regression** on:
   - Original dataset
   - PCA reduced datasets
8. Compared accuracy of original vs reduced dataset models
9. Visualized a **2D PCA scatter plot**

## 📊 Deliverables
- Explained variance plot
- Reduced datasets (PCA 2, 10)
- Accuracy comparison report (PDF)
- Final output and observations

## 📌 Accuracy Comparison (Sample Format)
| Model | Features | Accuracy |
|------|----------|----------|
| Logistic Regression (Original) | Full | ... |
| Logistic Regression + PCA(2) | 2 | ... |
| Logistic Regression + PCA(10) | 10 | ... |


## 📈 Conclusion
PCA successfully reduced the dataset dimensionality while maintaining reasonable accuracy.  
This task highlights the trade-off between:
- **Dimensionality reduction**
- **Explained variance**
- **Model accuracy**

## 📎 Files Included
- `PCA-Dimensionality-Reduction.ipynb` 
- `ASL_reduced_PCA_2.csv`
- `ASL_reduced_PCA_10.csv`
- `Accuracy_Comparison_Report_Task13_PCA.pdf`

