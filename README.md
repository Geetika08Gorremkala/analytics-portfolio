# Port Authority Traffic and Violation Prediction: A Collaborative Project

## Overview
This project involved a comprehensive analysis of historical traffic and toll violation data from the Port Authority of New York and New Jersey. As a key contributor to a team, my primary objective was to leverage advanced analytical techniques to develop predictive models for future traffic volumes and identify patterns in toll violations, ultimately informing operational improvements and strategic decision-making.

## Contribution

* Conducted weather impact analysis on bridge traffic, performed SARIMA seasonality studies, and contributed to overall project documentation and visualization.
* Led the modeling efforts for XGBoost regression and SARIMA time series, and drafted responses to major project questions.
*  Built and tuned the Random Forest Classifier for toll violations. Created initial drafts of the Power BI dashboard and worked on the violation prediction analytics.
*  Responsible for data cleaning, feature engineering (time variables, vehicle types), and preparation of data for modeling and visualization phases.
*  Executed time series model on data to check reliability.

## Tools & Techniques
* **Tools:** Python (Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Statsmodels, XGBoost), R (forecast, ggplot2), Jupyter Notebook, Microsoft Word, Microsoft PowerPoint, Power BI, Azure AutoML, SQL
* **Techniques:** Time Series Analysis (SARIMA), Regression Modeling (XGBoost), Classification Modeling (Random Forest), Exploratory Data Analysis (EDA), Feature Engineering, Data Cleaning, Model Evaluation (RMSE, MAE, R-squared, Accuracy), Data Visualization

## Process & Approach
As a key contributor to this project, my responsibilities included:

1.  **Data Acquisition & Preprocessing:** The team independently sourced, collected, and meticulously cleaned the historical traffic and toll violation datasets (totaling approximately 50,000 rows and 11 columns). This involved handling missing values, identifying and addressing outliers, ensuring data integrity, and performing data consolidation from multiple sources.
2.  **Exploratory Data Analysis (EDA):** I performed in-depth exploratory data analysis to uncover underlying trends, seasonal patterns (daily, weekly, yearly) in traffic volumes, and to understand the distribution and commonalities of toll violations. I generated various visualizations to illustrate these findings.
3.  **Traffic Forecasting (SARIMA):** I designed and implemented a Seasonal Autoregressive Integrated Moving Average (SARIMA) model, specifically configured as **SARIMA (1,1,1)(1,1,1,52)**, to accurately forecast future traffic volumes, capturing both seasonal and trend components in the time series data. This model provided robust short-term forecasts.
4.  **Traffic Volume Prediction (XGBoost Regression):** The team also developed an **XGBoost Regression model** to predict total traffic volume, leveraging various features including time factors, toll and vehicle types, weather conditions, and facility location.
5.  **Toll Violation Detection (Random Forest Classification):** The team implemented a **Random Forest Classifier** for toll violation detection, aiming to identify potential violations based on available features.
6.  **Model Evaluation & Validation:** We rigorously evaluated the performance of all developed models using appropriate metrics. The XGBoost Regression model for traffic volume achieved an **R² Score of 0.9996 and a Mean Squared Error (MSE) of 32.27**, indicating exceptional accuracy. The Random Forest Classifier for toll violation detection achieved **98% accuracy**. Model validation was also supported by Azure AutoML.
7.  **Report Generation & Presentation:** The team prepared detailed reports (as seen in the accompanying `.docx` files) and presentations (like the accompanying `.pptx` files) to clearly communicate our methodologies, findings, and the impact of the analysis. My contributions included conducting weather impact analysis and performing SARIMA seasonality studies, which were integrated into these reports.

## Results & Impact
Our collaborative efforts on this project led to:

* **Highly Accurate Traffic Predictions:** The XGBoost model provided near-perfect predictions for traffic volume, with an **R² of 0.9996 and an RMSE (derived from MSE 32.27) of approximately 5.68**, enabling precise resource planning for toll booths and infrastructure maintenance.
* **Effective Toll Violation Detection:** The Random Forest Classifier achieved **98% accuracy** in detecting toll violations, offering a robust tool for targeted enforcement and reducing non-compliance.
* **In-Depth Traffic Forecasting:** The SARIMA time series model provided valuable insights into daily and weekly traffic flow seasonality and trends, crucial for strategic operational planning.
* **Operational Efficiency & Strategic Planning:** Insights from both predictive models and time series analysis offer data-driven support for optimizing staffing schedules, reducing congestion during peak hours, and informing future infrastructure investment.
* **Demonstrated Collaborative & Technical Capability:** This project showcases our ability to independently and collaboratively handle a real-world dataset from raw form through cleaning, modeling, analysis, and effective communication of results.

---

## Project Files

* **Data & Visualizations:**
    * [Port Authority of New York and NJ Data Presentation](Port%20Authority%20of%20New%20York%20and%20NJ%20Data.pptx)
    * [Port Authority Project Visualizations (Power BI)](Port_Authority_Project_Visualizations%5B1%5D%20(1).pbix)

* **Project Reports (Documentation):**
    * [Port Authority 1st Report](Port%20Authority%201st%20report.docx)
    * [Port Authority of New York - Project Progress Report 2](Port%20Authority%20of%20New%20York%20-%20Project%20Progress%20Report%202.docx)
    * [Port Authority Report 3](port%20authority%20report%203.docx)
    * [Project Progress Report 4](Project_Progress_Report_4.docx)
    * [Final Project Report With Tools](Final_Project_Report_With_Tools.docx)
    * [Port Authority Time Series Report](Port_Authority_TimeSeries_Report.docx)

* **Presentations:**
    * [Traffic & Violation Prediction Project Presentation](Port-Authority-Traffic-and-Violation-Prediction-Project.pptx)
    * [Traffic & Violation Analysis Report Presentation](Port-Authority-Traffic-and-Violation-Analysis-Report.pptx)

---

## Visuals
(These images are embedded directly below. For better long-term organization and consistency, it's recommended to upload these image files into an `images` subfolder within your project directory on GitHub and link to them relatively.
![prcp by year](https://github.com/user-attachments/assets/5676f007-f19c-4429-9c06-0adf8e34ee99)
![Trafficbyday](https://github.com/user-attachments/assets/1fa27724-0cc6-44e6-87ae-95f7e3e042ee)
![voilationtrends](https://github.com/user-attachments/assets/cfcd2756-6afb-489e-974f-8a146d6a597d)
![12weektotaltraffic](https://github.com/user-attachments/assets/f43d29bd-e742-4ce3-a1e0-ae20a15eaf2e)
![confusionmatrix](https://github.com/user-attachments/assets/cc789a5f-0d0f-42e1-bff2-1182b954a99b)




