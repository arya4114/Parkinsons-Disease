# Parkinsons-Disease

**Introduction**

This project analyzes a dataset related to Parkinson's disease, using Python and MS Excel to extract meaningful insights. We aim to identify key patterns, correlations, and predictive factors that can help in better understanding and management of the disease.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Representative Data**

Sample of the dataset
![image](https://github.com/user-attachments/assets/edeeb674-bf2a-4323-808a-678c96975dcb)
![image](https://github.com/user-attachments/assets/73d589c2-69cf-4dd7-9f11-4b2cd7996cac)
Status: 1 = Parkinson’s, 0 = Healthy

Frequency of the Status
![image](https://github.com/user-attachments/assets/14e3e5b3-b2d1-44fb-bd78-04631f9b8e55)


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Executive Driven Questions**

The analysis was guided by key business and research questions:
1. What are the distinguishing vocal features of patients with Parkinson’s disease?
   Patients with Parkinson’s disease tend to exhibit higher levels of jitter, shimmer, and lower Harmonic-to-Noise Ratio (HNR) compared to healthy individuals. These features indicate irregularities in voice frequency and amplitude, which are common symptoms of the disease.


2. How do jitter and shimmer values correlate with the presence of Parkinson’s disease?
   Higher jitter and shimmer values correlate strongly with Parkinson’s disease, as they measure frequency and amplitude instability in voice recordings. The correlation coefficients suggest a positive relationship between these features and disease presence.


3. Can we develop an early detection mechanism using this dataset?
   Yes, by leveraging machine learning models trained on these vocal biomarkers, we can develop a non-invasive early detection tool. The model achieved over 85% accuracy, indicating strong potential for clinical applications.


4 . What are the most significant predictors of Parkinson’s disease in this dataset?
The most important predictors include:

a. MDVP:Jitter(%) (Frequency variation in voice)

b. MDVP:Shimmer (Amplitude variation in voice)

c. HNR (Harmonic-to-noise ratio, lower in Parkinson’s patients)

d. MDVP:Fo(Hz) (Fundamental frequency)


5. Are there any outliers or anomalies that could impact the analysis?
   Yes, some extreme values in MDVP:Fhi(Hz) and MDVP:Flo(Hz) suggest potential anomalies. These were handled through outlier detection techniques such as IQR filtering and Z-score normalization.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Analytical Framework**

This study employs a structured analytical approach:
1. Data Preprocessing: Cleaning, handling missing values, and standardizing data.

2. Exploratory Data Analysis (EDA): Statistical summaries, correlation matrices, and visualizations.

3. Feature Engineering: Identifying key vocal characteristics and patterns.

4. Predictive Modeling: Using machine learning techniques (e.g., Logistic Regression, Decision Trees, Random Forest) to classify Parkinson’s patients.

5. Validation & Optimization: Cross-validation, feature selection, and performance tuning.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Data Best Practices**

To ensure data integrity and reliability, the following best practices were followed:
1. Data Cleaning: Removing inconsistencies and ensuring standardized formats.

2. Normalization: Standardizing numerical features to ensure comparability.

3. Handling Imbalanced Data: Using SMOTE or other techniques to balance the dataset.

4. Cross-Validation: Ensuring robustness of predictive models with k-fold validation.

5. Feature Selection: Removing redundant or less significant features to improve accuracy.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Insights and Impact**

1. Significant Predictors: Jitter, shimmer, and HNR were found to be strong indicators of Parkinson’s disease.

2. Model Accuracy: The best-performing model achieved an accuracy of over 85%.

3. Early Detection Potential: The findings suggest that vocal analysis can be a non-invasive early diagnostic tool.

4. Healthcare Application: These insights can support the development of AI-driven tools for early screening and monitoring of Parkinson’s disease.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Tools Used**

1. Programming: Python, Pandas, NumPy, Scikit-learn

2. Visualization: Matplotlib, Seaborn

3. Data Processing: MS Excel, Jupyter Notebook

4. Machine Learning: Logistic Regression, Decision Trees, Random Forest
