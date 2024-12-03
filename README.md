# Project - ML Model Development Based on Brazil’s COVID-19 Dataset  

## Description  
Brazil is among the nations most impacted by the COVID-19 pandemic, with over 16 million confirmed cases and 454,429 confirmed fatalities by May 26, 2021 (according to the Johns Hopkins Coronavirus Resource Center).

During the first wave of COVID-19, Brazil faced unprecedented challenges due to the strain on hospital capacity, including high demand for ICU beds, healthcare professionals, personal protection equipment, and medical resources.

To address this issue, a team of data scientists at Sirio Libanês Hospital in Brazil sought to reduce ICU bed strain by developing a machine learning model. The model's goal is to predict whether patients with confirmed COVID-19 cases would require ICU admission.

The dataset used for this project, released on the Kaggle platform (Dataset Link), includes clinical data from COVID-19 patients and the target group (those admitted to the ICU).

This project focuses on building a classification model to predict ICU admission.

## Scope and Deliverables  

1. **Exploratory Data Analysis (EDA)**  
   - Visualize data distributions, relationships, and trends.  
   - Identify missing values and potential outliers.  

2. **Data Pre-Processing**  
   - Handle missing values and outliers.  
   - Normalize and encode features as necessary.  
   - Split the data into training and testing sets.  

3. **Model Creation and Hyperparameter Tuning**  
   - Train and evaluate different classification models.  
   - Optimize the model using hyperparameter tuning.  

4. **Conclusion**  
   - Summarize key findings and model performance.  
   - Provide recommendations based on predictions.  
## Results
* Best Model: [e.g., Random Forest Classifier]
* Performance Metrics:
   *    Accuracy: XX%
   *    
Precision: XX%
Recall: XX%
F1 Score: XX%
Dataset
The dataset used for this project is publicly available on Kaggle: COVID-19 Dataset by Sirio Libanês Hospital.

Method	Train Accuracy	Test Accuracy	Precision	Recall	F1
1	Logistic Regression	0.681	0.811	0.820	0.788	0.804
5	Random Forest	0.726	0.811	0.833	0.769	0.800
3	SVM	0.696	0.764	0.776	0.731	0.752
7	AdaBoost	0.763	0.764	0.814	0.673	0.737
8	Gradient Boost	0.722	0.764	0.814	0.673	0.737
6	Bagging	0.737	0.755	0.795	0.673	0.729
2	KNN	0.674	0.726	0.767	0.635	0.695
4	DecisionTree	0.681	0.604	0.614	0.519	0.562

