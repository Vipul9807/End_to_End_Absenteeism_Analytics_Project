# Employee_Absenteeism_Prediction_System 

Employee absenteeism prediction system built using Python, Logistic Regression, MySQL, and Tableau for data-driven workforce analytics.

<img width="1909" height="1022" alt="Screenshot 2026-03-01 162909" src="https://github.com/user-attachments/assets/eb37c285-bfa6-44d0-90fb-a0609f88dbc6" />

## Executive Summary

Employee absenteeism poses a significant challenge to organizational productivity and workforce planning. The absence of predictive insights often leads to reactive decision-making and inefficient resource allocation.

To address this, an end-to-end Machine Learning solution was developed to predict excessive absenteeism using structured HR data. After comprehensive data preprocessing and feature engineering, a Logistic Regression model was implemented, achieving 77% training accuracy and 75% test accuracy, demonstrating reliable predictive performance.

The model was operationalized through an Object-Oriented Programming module, with outputs stored in a MySQL database and visualized using Tableau dashboards, enabling stakeholders to monitor absenteeism risk and identify key influencing factors.

Business Impact :

- Delivered a predictive system with 75% accuracy on unseen data
- Enabled proactive absenteeism risk identification
- Transformed raw HR data into actionable decision-support insights

## Business Problem

Unplanned employee absenteeism creates operational disruption, reduces productivity, and increases workforce management costs. Most organizations rely on historical reporting to track absenteeism, but lack predictive mechanisms to identify high-risk employees in advance.

This reactive approach limits proactive intervention, impacts resource allocation, and reduces overall operational efficiency. Without data-driven forecasting, absenteeism remains a recurring cost center rather than a manageable business risk.

## Methodology

- Data Preparation & Feature Engineering :
Cleaned and transformed raw absenteeism data, grouped absence reasons, engineered time-based features, and applied feature scaling for model readiness.

- Model Development :
Implemented a Logistic Regression classification model to predict excessive absenteeism, achieving 77% training accuracy and 75% test accuracy.

- Model Operationalization :
Developed a reusable prediction pipeline using Object-Oriented Programming to automate preprocessing and prediction for new data inputs.

- Database Integration & Visualization :
Stored model outputs in a MySQL database and created interactive Tableau dashboards to support stakeholder decision-making.

## Skills & Technologies Used :

- Programming & Data Processing : Python, Pandas

- Machine Learning : Logistic Regression, Model Evaluation (Train/Test Split, Accuracy Measurement) ,Feature Engineering , Data Preprocessing, Feature Scaling (StandardScaler)

- Software Development : Object-Oriented Programming (OOP), Model Serialization (Pickle)

- Database Management : MySQL, Database Integration with Python

- Business Intelligence & Visualization : Tableau , Data Interpretation & Insight Generation

## Results & Business Recommendations

- Developed a Logistic Regression model achieving 77% training accuracy and 75% test accuracy, demonstrating reliable predictive performance.
- Successfully built an end-to-end pipeline integrating Machine Learning, MySQL database storage, and Tableau visualization.
- Identified key absenteeism risk drivers, including absence reason categories, transportation expense, and personal factors.
- Enabled structured prediction outputs for proactive workforce monitoring.

<img width="1412" height="666" alt="Screenshot 2026-03-01 182910" src="https://github.com/user-attachments/assets/1234fc71-005e-45c7-9aec-c1cbb7254652" />

- Implement proactive monitoring: Use predictive risk scores to identify high-risk employees early and initiate preventive HR interventions.
- Target key risk drivers: Focus on recurring absence reasons and operational stress factors revealed through dashboard insights.
- Integrate into HR workflow: Embed the prediction system into routine workforce planning processes.
- Enhance model performance: Explore advanced algorithms (e.g., Random Forest, Gradient Boosting) and incorporate additional HR variables for improved accuracy.

## Project Limitations 

- The Tableau dashboard insights are based on approximately 40 observations from the test dataset, which may limit the generalizability of trends and business conclusions at an organizational scale.
- The predictive model relies on historical absenteeism variables available in the dataset and does not incorporate additional organizational or behavioral factors (e.g., job role, work environment, or employee engagement), which may influence prediction accuracy.

<img width="1885" height="1094" alt="Screenshot 2026-03-03 065054" src="https://github.com/user-attachments/assets/7cfdde70-e0f7-43db-98ac-d7035ce54a4e" />

## Future Scope & Strategic Recommendations

- Develop an automated ETL process to ingest live HR data and enable real-time absenteeism risk monitoring instead of batch-based predictions.
- Experiment with ensemble methods such as Random Forest or Gradient Boosting to improve predictive accuracy and capture non-linear relationships.
- Build a lightweight web application (e.g., using Flask or Streamlit) to allow HR teams to input employee data and instantly receive risk predictions and insights.

  #### ⭐ If you found this project helpful, please consider giving it a star on GitHub!
Your support motivates me to create more data-driven projects and share useful insights.
