# **Cardiovascular Disease Prediction System**
The cardiovascular disease prediction system is a tool or model designed to assess an individual's risk of developing cardiovascular diseases (CVD). These diseases include a range of heart and blood vessel disorders such as coronary artery disease, heart attack, stroke, and hypertension. The predictor uses various inputs and risk factors to estimate the likelihood of future cardiovascular events. 

To use this project, you'll need to have Python installed along with several Python libraries. You can install the required libraries using the following command - 'pandas', 'scikit-learn', 'matplotlib', and 'seaborn.

# **Steps involved in the project**
**1. Load and Preprocess Data:**
* Load the cardiovascular dataset.
* Handle missing values, if any.
* Normalize numerical features and encode categorical features.
            
**2. Train Models:**

Train the following machine learning models on the preprocessed dataset:
* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Decision Trees
* Logistic Regression
* Random Forest

    
**3. Evaluate Models:**

*Evaluate the performance of each model using metrics such as accuracy.

**4. Compare Performance:**

*Compare the performance of the five models to identify the best-performing model for CVD prediction.

# **Dataset**

The dataset used in this project contains various features relevant to cardiovascular health, such as age, gender, blood pressure, cholesterol levels, smoking status, physical activity, and medical history. Each record is labeled with the presence or absence of cardiovascular disease.

The features involved in the dataset are:

    id                int64
    age               int64
    gender         category
    height          float64
    weight          float64
    ap_hi           float64
    ap_lo           float64
    cholesterol    category
    gluc           category
    smoke          category
    alco           category
    active         category
    cardio            int64
    dtype:           object 

The sample dataset is as follows:

![image](https://github.com/user-attachments/assets/8def0012-f7bb-4b22-b2a5-2fc4efbd4d49)

**Histogram Chart**

![image](https://github.com/user-attachments/assets/96d7c746-50d9-46b6-8770-16b992ee7619)

**Count Plots**

![image](https://github.com/user-attachments/assets/c6407265-7d7e-492b-94c7-2219e918ea8f)


# **Models Used**
***Support Vector Machine (SVM):** A powerful classifier that works well with high-dimensional data.

***K-Nearest Neighbors (KNN):** A simple, instance-based learning algorithm.

***Decision Trees (DT):** A tree-structured model that splits the data based on feature values.

***Logistic Regression (LR):** A linear model for binary classification problems.

***Random Forest (RF):** An ensemble method that combines multiple decision trees to improve accuracy.

# **Evaluate the Model**

Accuracy charts and Correlation Matrix are used to showcase the evaluation of the Matrix

**Accuracy Chart**

![image](https://github.com/user-attachments/assets/42a02023-e23f-4f13-837d-22478d9838df)

**Correlation Matrix**

![image](https://github.com/user-attachments/assets/c62c545d-8ead-49fe-b2de-6246b500241a)


