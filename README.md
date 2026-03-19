# 📊 **Customer Churn Prediction System – Detailed Report**

---

## **1. Introduction**

Customer churn refers to the phenomenon where customers stop doing business with a company. In highly competitive industries such as telecom, banking, and subscription-based services, retaining customers is more cost-effective than acquiring new ones. Therefore, predicting customer churn has become a crucial task for businesses.

This project focuses on building a machine learning-based classification system to predict whether a customer will churn or not based on historical data. The project demonstrates the complete Data Science lifecycle, from data preprocessing to model evaluation.

---

## **2. Problem Statement**

The objective of this project is to develop a predictive model that can classify customers into:

* **Churn (1)** – Customer likely to leave
* **Not Churn (0)** – Customer likely to stay

The system aims to assist businesses in identifying high-risk customers and taking preventive actions.

---

## **3. Objectives**

* To analyze customer data and identify patterns related to churn
* To preprocess and clean the dataset for model building
* To implement multiple machine learning algorithms
* To compare model performance and select the best model
* To develop a prediction system for real-time use

---

## **4. Dataset Description**

The dataset used contains customer-related information such as:

* Demographic details (gender, senior citizen)
* Account information (tenure, monthly charges, total charges)
* Services subscribed (internet, phone, etc.)
* Target variable: **Churn**

This structured dataset is suitable for classification problems and reflects real-world business scenarios.

---

## **5. Methodology**

## 🔄 Project Workflow

1. **Data Collection**

   * Imported dataset from CSV file

2. **Data Cleaning**

   * Removed unnecessary columns
   * Handled missing values
   * Converted data types

3. **Data Preprocessing**

   * Converted categorical data into numerical format
   * Applied feature scaling

4. **Exploratory Data Analysis (EDA)**

   * Visualized churn distribution
   * Analyzed feature relationships

5. **Model Building**

   * Logistic Regression
   * K-Nearest Neighbors (KNN)
   * Decision Tree
   * Random Forest

6. **Model Evaluation**

   * Accuracy score
   * Confusion matrix
   * Model comparison

7. **Final Model Selection**

   * Logistic Regression selected based on best performance

---

### **Results:**

* Logistic Regression achieved the highest accuracy (~80.7%)
* Random Forest performed slightly lower (~78.6%)
* KNN and Decision Tree showed comparatively lower performance

---

## **8. Final Model Selection**

Based on performance comparison, **Logistic Regression** was selected as the final model.

**Reason:**

* Highest accuracy
* Simplicity and interpretability
* Efficient for the given dataset

---

## **9. Prediction System**

A prediction function is implemented that:

* Accepts customer data as input
* Processes the input
* Outputs whether the customer will churn or not

This makes the system usable for real-world applications.

---

## **10. Technologies and Libraries Used**

| Library      | Purpose                                |
| ------------ | -------------------------------------- |
| Pandas       | Data manipulation and preprocessing    |
| NumPy        | Numerical computations                 |
| Matplotlib   | Data visualization                     |
| Seaborn      | Advanced visualizations                |
| Scikit-learn | Machine learning models and evaluation |

---

## **11. Advantages of the System**

* Helps in early identification of churn customers
* Supports data-driven decision making
* Easy to implement and scalable
* Applicable across multiple industries

---

## **12. Limitations**

* Performance depends on data quality
* Limited to structured data
* Does not include real-time deployment

---

## **13. Future Scope**

* Hyperparameter tuning for improved accuracy
* Deployment using web frameworks (Streamlit/Flask)
* Integration with real-time business systems
* Use of advanced models like XGBoost or Deep Learning

---

## **14. Conclusion**

This project successfully demonstrates the use of machine learning techniques to predict customer churn. A complete data science pipeline was implemented, and multiple models were evaluated. Logistic Regression performed best, highlighting that simpler models can sometimes outperform complex ones depending on the dataset. The system provides valuable insights and can help businesses improve customer retention strategies.

---

## **15. References**

* Scikit-learn Documentation
* Public Telecom Churn Datasets
* Standard Data Science Practices

---

## **👨‍💻 Author

By Jenish Lad
