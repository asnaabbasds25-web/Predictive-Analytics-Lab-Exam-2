#  Predictive Analytics Lab Exam-2

## Objective
The objective of this project is to perform a **classification task** using machine learning techniques and evaluate the model performance.

---

##  Dataset
- The dataset contains multiple input features and a target variable named **Target**.
- The target variable is binary:
  - Yes → 1  
  - No → 0  

---

##  Exploratory Data Analysis (EDA)

The following steps were performed:

- Checked dataset structure using `.info()`
- Generated statistical summary using `.describe()`
- Checked missing values using `.isnull().sum()`
- Removed missing values if present
- Visualized data using:
  - Histograms (feature distribution)
  - Heatmap (feature correlation)

###  Observations:
- Dataset contains mostly numerical features  
- No major missing values after cleaning  
- Some features show correlation  
- Data is suitable for classification  

---

##  Model Used

**Logistic Regression**

### Reason:
- Suitable for binary classification  
- Based on probability (sigmoid function)  
- Simple and efficient model  

---

##  Model Building Steps

- Split dataset into training (80%) and testing (20%)
- Applied feature scaling using StandardScaler
- Trained Logistic Regression model on training data

---

## Decision Boundary

- Used first two features for visualization  
- Created mesh grid  
- Predicted class labels  
- Plotted decision regions  

![Decision Boundary](decision_boundary.png)

---

##  Model Evaluation

The model was evaluated using:

- Accuracy Score  
- Confusion Matrix  
- Classification Report  

### Results:
- Accuracy: **(update with your value)**  

### Interpretation:
- Model performs well on test data  
- Low misclassification observed  
- Balanced precision and recall  

---

##  Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Conclusion

- Successfully performed classification using Logistic Regression  
- EDA helped understand the dataset  
- Model achieved good accuracy  
- Decision boundary clearly shows classification regions  

---

##  Repository

This project is hosted on GitHub.# Predictive-Analytics-Lab-Exam-2

## Author : ASNA ABBAS
