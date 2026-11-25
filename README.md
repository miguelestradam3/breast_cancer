# 🎗️ Breast Cancer Prediction using Machine Learning

This project demonstrates how to build a machine learning model to predict whether a breast tumor is **benign** or **malignant** using the **Breast Cancer Wisconsin Dataset**. The notebook follows a complete machine learning workflow, including data exploration, preprocessing, handling class imbalance with **SMOTE**, feature scaling, model training, and evaluation.

The project serves as an introduction to applying machine learning techniques to healthcare datasets for binary classification tasks.

---

## 📌 Features

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value handling
- Label encoding for categorical data
- Feature scaling using `StandardScaler`
- Train/Test split
- Class imbalance handling using SMOTE
- Logistic Regression classifier
- Model evaluation using classification metrics

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)
- KaggleHub
- Jupyter Notebook

---

## 📚 Libraries

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
kagglehub
```


## 📊 Dataset

The project uses the **Breast Cancer Wisconsin Dataset**, downloaded through **KaggleHub**.

The dataset contains diagnostic measurements computed from digitized images of breast masses.

### Target Variable

- **Diagnosis**
  - Benign (B)
  - Malignant (M)

Before training, the diagnosis labels are converted into numerical values using **LabelEncoder**.

---

## 🔍 Exploratory Data Analysis

The notebook includes:

- Dataset inspection
- Missing value analysis
- Class distribution analysis
- Data type inspection
- Statistical summaries
- Correlation analysis

These steps help understand the characteristics of the dataset before model training.

---

## ⚙️ Machine Learning Workflow

The notebook performs the following steps:

1. Load the Breast Cancer Wisconsin Dataset
2. Remove unnecessary or missing-value columns
3. Encode the diagnosis labels
4. Split the dataset into training and testing sets
5. Balance the training data using **SMOTE**
6. Standardize the features using `StandardScaler`
7. Train a **Logistic Regression** classifier
8. Generate predictions
9. Evaluate model performance

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy Score
- Confusion Matrix
- Classification Report
- Precision
- Recall
- F1-Score

These metrics provide insight into the classifier's ability to distinguish between benign and malignant tumors.

---

## 🚀 Getting Started

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install them manually:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn kagglehub
```

---

## ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
breast_cancer_prediction.ipynb
```

Run the notebook cells sequentially to reproduce the complete machine learning workflow.

---

## 🎯 Learning Objectives

This project demonstrates how to:

- Work with healthcare datasets
- Clean and preprocess data
- Handle missing values
- Encode categorical variables
- Handle imbalanced datasets using SMOTE
- Standardize numerical features
- Train a Logistic Regression classifier
- Evaluate binary classification models

---

## 🔮 Future Improvements

- Compare additional classification algorithms (Random Forest, XGBoost, SVM)
- Perform hyperparameter tuning
- Apply cross-validation
- Visualize feature importance
- Plot ROC and Precision-Recall curves
- Deploy the model with Streamlit or Flask