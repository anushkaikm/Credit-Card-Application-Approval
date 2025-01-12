# Credit Card Application Approval Prediction  

## 📜 Introduction  
The traditional process of approving credit card applications is heavily reliant on manual reviews or simplistic decision rules. These methods are not only time-consuming but also prone to human errors, leading to suboptimal decisions. This project aims to modernize and streamline this process by developing a machine learning model capable of automating decision-making with high precision and efficiency.

By leveraging a rich dataset from Kaggle, we designed a classification system that reduces delays, enhances accuracy, and minimizes human intervention, ensuring better customer satisfaction and improved business profitability.

---

## 🛠️ Features  
- **Automated Decision-Making**: Replaces manual reviews with a robust machine learning pipeline.  
- **Comprehensive Data Preprocessing**: Handles missing values, outliers, skewness, and scaling.  
- **Algorithm Comparison**: Evaluates multiple machine learning models to identify the best performer.  
- **Class Imbalance Management**: Ensures fair predictions for both approved and rejected applications.  

---

## 📊 Datasets  
### 1. **Credit Card Data**  
- **Key Features**:  
  - Demographics: Gender, marital status, property ownership, etc.  
  - Financials: Annual income, employment duration.  
  - Lifestyle: Housing type, phone access.  

### 2. **Credit Card Labels**  
- **Key Features**:  
  - `Application Status`: Approval (0) or Rejection (1).  

---

## 🔧 Preprocessing Steps  
1. **Data Merging**: Combined datasets on a common key (`ID`).  
2. **Missing Value Handling**: Used statistical imputation techniques (e.g., mode, median).  
3. **Outlier Treatment**: Applied capping (5th and 95th percentiles) for robust data.  
4. **Feature Transformation**: Converted skewed numerical features and scaled them using Min-Max scaling.  
5. **Encoding**: Applied ordinal and one-hot encoding for categorical features.  

---

## 🧠 Models Used  
- **Logistic Regression**  
- **Support Vector Machine (SVM)**  
- **Random Forest**  
- **Gradient Boosting**  
- **Decision Tree**  
- **k-Nearest Neighbors (kNN)**  

**Best Model**:  
Random Forest achieved the best performance with:  
- **Accuracy**: 93%  
- **Precision & Recall**: Balanced across classes.  
- **ROC-AUC Score**: Robust distinction between approved and rejected applications.  

---

## 🚀 Results  
- Automated credit card approvals with 93% accuracy.  
- Reduced manual review time and human errors.  
- Balanced recall for both approved and rejected applications, ensuring fairness.  

---

## 👩‍💻 Author  
**Anushka Mondal**  

---

## 🙏 Acknowledgments  
I would like to express my gratitude to the following for their invaluable support and resources:  

- **Kaggle**: For providing the datasets that served as the foundation of this project.  
- **San Francisco State University**: For fostering a learning environment that encourages the application of machine learning techniques to solve real-world problems.  
- **Professors and Mentors**: For their guidance and feedback throughout the project lifecycle.  
- **Open-Source Community**: For the libraries and tools, such as Python, scikit-learn, pandas, and matplotlib, that made this project possible.  

This project is a culmination of collaborative efforts, continuous learning, and the application of data science principles. Thank you to everyone who contributed directly or indirectly to its success.  
