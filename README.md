# Support-Vector-Machine-SVM-

## 📌 Objective
This project applies Support Vector Machines (SVM) using both linear and non-linear (RBF) kernels on the Breast Cancer dataset for binary classification.



## 📁 Dataset
- **Source**: [Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- **Classes**: Malignant (M) and Benign (B)
- **Target**: Diagnosis (`M = 1`, `B = 0`)
- **Features**: 30 numerical features related to cell nuclei characteristics



## 🛠️ Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib
- Pandas



## ✅ Tasks Completed

1. **Data Preprocessing**
   - Removed irrelevant columns (`id`, `Unnamed: 32`)
   - Converted diagnosis to binary values
   - Standardized the features

2. **Dimensionality Reduction**
   - Used PCA to reduce features to 2D for visualization

3. **Model Training**
   - Trained two SVM models:
     - Linear kernel
     - RBF (Gaussian) kernel

4. **Visualization**
   - Plotted decision boundaries for both models using 2D PCA data

5. **Hyperparameter Tuning**
   - Tuned `C` and `gamma` using `GridSearchCV`

6. **Model Evaluation**
   - Cross-validation accuracy
   - Confusion matrix and classification report



## 🔍 Results

- Best parameters found by GridSearchCV
- Average cross-validation accuracy
- Visualized decision boundaries
- RBF kernel generally performed better on this dataset




