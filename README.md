# Technical-Assessment-Predictive-Modeling-for-Feature-shipment-prediction

**Dataset**
The dataset contains 1,300 historical software shipment records with project-related attributes such as:
Planned Shipment Date
Team Size
Feature Complexity
Number of Dependencies
Sprint Length
Number of Blockers
Holidays in Sprint
Priority
Historical Average Delay
Estimated Bug Count

Target Variable:
delay_days

**Objective**
Develop a regression model capable of predicting shipment delays while minimizing Mean Absolute Error (MAE).

**Methodology**
1. Data Preprocessing
Loaded the dataset
Checked for missing values
Checked for duplicate records
Converted shipment dates to datetime format

2. Feature Engineering
Extracted useful time-based features from the shipment date:
Year
Month
Day
Week
Quarter

3. Exploratory Data Analysis (EDA)
Performed:
Statistical summary
Distribution plots
Correlation analysis

4. Model Development

The following regression models were trained and evaluated:

Linear Regression 
Random Forest Regressor
XGBoost Regressor

**Evaluation Metrics**

The models were evaluated using:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
R² Score

Linear Regression achieved the best performance on this dataset, indicating that the relationship between the engineered features and shipment delay is largely linear.
Feature Complexity was the most influential predictor of shipment delay.
Projects with more blockers and dependencies tend to experience higher delays.
Historical delay patterns contribute significantly to future shipment predictions.
Increasing model complexity did not improve performance for this dataset, highlighting the importance of selecting models based on data characteristics.


**How to Run:**
Clone the repository.
Install the required libraries.
Open the notebook.
Upload the file: Software_feature_shipment_data_set.csv
Run all cells sequentially.
