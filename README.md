**Employees Burn Out : Analysis and Prediciton**  
This project focuses on predicting the burnout rate of employees based on various factors such as their work environment, workload, and mental fatigue. The dataset contains several features that provide insights into the employees' characteristics and work conditions. Here is a description of each feature:

**Features Description**:
- Employee ID: A unique identifier assigned to each employee.
- Date of Joining: The date and time when the employee joined the organization.
- Gender: The gender of the employee (Male/Female).
- Company Type: The type of company where the employee is working (Service/Product).
- WFH Setup Available: Indicates whether the work-from-home facility is available for the employee (Yes/No).
- Designation: The designation of the employee in the organization, ranging from 0.0 to 5.0, where a higher value indicates a higher designation.
- Resource Allocation: The amount of resources allocated to the employee for work, represented by the number of working hours. It ranges from 1.0 to 10.0, with a higher value indicating more resources.
- Mental Fatigue Score: The level of mental fatigue faced by the employee, ranging from 0.0 to 10.0. A score of 0.0 indicates no fatigue, while 10.0 indicates complete fatigue.
- Burn Rate: The target variable that needs to be predicted for each employee, indicating the rate of burnout while working. It ranges from 0.0 to 1.0, where a higher value signifies a higher level of burnout.

**Project Overview:**
The objective of this project is to develop a predictive model that can accurately estimate the burnout rate of employees based on the provided features. The model aims to assist HR teams and organizational management in identifying potential burnout risks among employees and implementing strategies to mitigate them.

**Methodology:**
The project involves several key steps:

- Data Loading: The dataset is retrieved and loaded into a pandas DataFrame.
- Data Cleaning: Data preprocessing techniques are applied to handle missing values, remove unnecessary symbols, and convert data types.
- Exploratory Data Analysis (EDA): Exploring the dataset to gain insights into the distribution of features, identify correlations, and understand patterns.
- Model Building: Various regression models such as K-Nearest Regressor, Support Vector Regressor, Decision Tree Regressor, Random Forest Regressor, and LightGBM Regressor are trained and evaluated.
- Hyperparameter Tuning: Fine-tuning the hyperparameters of the selected model to improve performance.
- Model Evaluation: Assessing the performance of the models using metrics such as Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
- Conclusion and Recommendations: Drawing conclusions from the analysis and providing recommendations based on the findings.

**Model Deployment on Huggingface** : https://huggingface.co/spaces/batraccoon/Burn_Out_Score_Prediction
**Source of dataset** : https://www.kaggle.com/datasets/blurredmachine/are-your-employees-burning-out/