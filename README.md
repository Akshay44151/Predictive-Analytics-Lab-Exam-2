# Predictive Analytics Lab Exam-2

 Objective

The objective of this lab exam is to perform a binary classification task using machine learning techniques, including data preprocessing, model building, visualization, and evaluation.



Dataset

* File: `Lab_Exam_binary_classification_dataset.csv`
* The dataset contains multiple input features and a binary target variable.
* Some columns contain categorical values (Yes/No) and missing values.

---

 Data Preprocessing

The following preprocessing steps were performed:

* Removed rows with missing target values
* Converted categorical values (Yes/No) into numerical format (1/0)
* Handled missing values in features using mean imputation
* Feature scaling applied using StandardScaler

---

Exploratory Data Analysis (EDA)

* Checked dataset structure and missing values
* Visualized class distribution using count plot
* Generated correlation heatmap for numerical features

---

Model Used

* Logistic Regression was used for classification
* The dataset was split into training and testing sets (80:20 ratio)
* Model was trained using scaled features

---

Model Evaluation

The model performance was evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision, Recall, and F1-score

Both training and testing accuracy were compared to check for overfitting.

---

 Decision Boundary

* Decision boundary was plotted using the first two features
* Outliers were removed to improve visualization
* The plot shows how the model separates the two classes

---

 Tools & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

Conclusion

The Logistic Regression model successfully classified the data with good accuracy.
Data preprocessing and feature scaling improved model performance.
The decision boundary clearly shows separation between the two classes.

---
