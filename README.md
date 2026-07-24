# Employee Attrition Prediction using Decision Tree and Random Forest

## 📌 Objective

The objective of this project is to build and compare Decision Tree and Random Forest classification models to predict employee attrition based on demographic and work-related features. The project demonstrates the complete machine learning workflow including data preprocessing, model training, evaluation, and comparison.

---

## 📂 Dataset

**Dataset Name:** IBM HR Analytics Employee Attrition Dataset  

**Source:** Kaggle  

**Dataset Link:**  
https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset  

**Note:** The dataset is not included in this repository. Please download it from the Kaggle link above.

---

## 🛠️ Libraries Used

- Pandas  
- NumPy  
- Matplotlib  
- Scikit-learn  

### Modules Used

- LabelEncoder  
- train_test_split  
- DecisionTreeClassifier  
- RandomForestClassifier  
- accuracy_score  
- precision_score  
- recall_score  
- f1_score  
- confusion_matrix  
- ConfusionMatrixDisplay  

---

## ⚙️ Methodology

1. Imported the required Python libraries.  
2. Loaded the dataset using Pandas.  
3. Explored the dataset using `head()`, `info()`, and `describe()`.  
4. Identified numerical features, categorical features, and the target variable (`Attrition`).  
5. Checked for missing values.  
6. Removed unnecessary columns.  
7. Encoded categorical variables using Label Encoding.  
8. Split the dataset into 80% training data and 20% testing data.  

### Model Development

9. Built a Decision Tree Classifier model.  
10. Built a Random Forest Classifier model with 100 estimators.  
11. Trained both models on the same dataset.  
12. Predicted employee attrition on the test data.  

---

## 📊 Results

Both models were evaluated using classification metrics.

### Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  

Confusion matrices were generated for both models to visualize performance.

A feature importance plot was also created for the Random Forest model to identify key factors affecting attrition.

---

## 🔍 Model Comparison

- Random Forest achieved better accuracy and overall performance compared to Decision Tree.  
- Decision Tree showed signs of overfitting and lower generalization ability.  
- Random Forest reduced overfitting by combining multiple decision trees.  
- The dataset appears to be slightly imbalanced, affecting precision and recall values.  

---

## ✅ Conclusion

In this project, both Decision Tree and Random Forest models were used to predict employee attrition. After evaluation, Random Forest performed better in terms of accuracy, precision, recall, and F1 score. This is because Random Forest reduces overfitting by combining multiple trees and averaging their predictions. Decision Trees are simple and easy to interpret but tend to overfit the data, which reduces their performance on unseen data. Random Forest, although more computationally expensive and less interpretable, provides better generalization and more reliable predictions. Therefore, Random Forest is the preferred model for this problem.

---

## 📁 Repository Structure

```
Assignment-5/
│── Assignment-5.ipynb
│── README.md
```

---

## Author

**Name:** Riya Shukla  

**Registration Number:** 23BCE11293  

**Application Number:** IN26012655  

**Batch Number:** 2(B)  

