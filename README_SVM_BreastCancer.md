# Task 7: Support Vector Machines (SVM) - Breast Cancer Classification

## Objective
Use Support Vector Machines (SVM) to classify tumors as malignant or benign using both linear and non-linear decision boundaries.

## Dataset
Breast Cancer Wisconsin dataset (`breast-cancer.csv`)

## Tools & Libraries
- Python
- Scikit-learn
- NumPy
- Matplotlib
- Pandas

## Steps
1. Load and preprocess the data
2. Train SVM with:
   - Linear kernel
   - RBF (non-linear) kernel
3. Visualize decision boundaries using PCA (2D)
4. Tune hyperparameters (C, gamma) using GridSearchCV
5. Evaluate using classification report and cross-validation

## How to Run
```bash
pip install pandas numpy matplotlib scikit-learn
python svm_classification.py
```

## Outputs
- Classification performance of both kernels
- Hyperparameter tuning results
- 2D decision boundary plots

## Author
Generated with ❤️ by ChatGPT
