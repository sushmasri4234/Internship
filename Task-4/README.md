## 🧠 Breast Cancer Classification using Logistic Regression

This project performs binary classification (Malignant vs. Benign tumors) using Logistic Regression on a breast cancer dataset.

### 📁 Dataset

The dataset used is `data.csv`, which contains measurements of tumors along with diagnosis labels:
- `diagnosis`: `'M'` for malignant (1), `'B'` for benign (0)
- Features include `radius_mean`, `texture_mean`, `perimeter_mean`, and many other numeric variables.



### 📌 Project Steps

1. **Load and Preprocess Data**
   - Load CSV file into a DataFrame.
   - Drop irrelevant columns (`id`, `Unnamed: 32`).
   - Convert target column `diagnosis` into binary format (`M` → 1, `B` → 0).

2. **Train-Test Split and Standardization**
   - Split dataset into training and testing sets (80-20).
   - Standardize features using `StandardScaler`.

3. **Train Logistic Regression Model**
   - Fit `LogisticRegression` from `sklearn.linear_model`.

4. **Model Evaluation**
   - Evaluate using:
     - Confusion Matrix
     - Precision, Recall, F1-Score
     - ROC-AUC score
     - ROC Curve Plot

5. **Threshold Tuning**
   - Adjust decision threshold to control sensitivity/specificity.

6. **Sigmoid Explanation**
   - Visualize the sigmoid function to understand how logistic regression maps outputs to probabilities.



### 🛠 Requirements

Install necessary Python libraries:

```bash
pip install pandas numpy scikit-learn matplotlib
```



### 🚀 How to Run

```bash
python logistic_regression_breast_cancer.py
```

Replace the feature columns in the script if you want to try other combinations.



### 📊 Sample Visualization

- **ROC Curve** and **Sigmoid Function** plots are shown to interpret the model's behavior.



### 🔍 Future Work

- Try different feature sets or polynomial features.
- Add grid search for hyperparameter tuning.
- Evaluate other classification models (e.g., SVM, Random Forest).
