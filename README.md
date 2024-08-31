# Chicago Car Crashes
**An overview of the Chicago car crash investigation.**

The goal of this project is to analyze and visualize car crash data from Chicago. The goal is to create a classifier that can predict the principal contributing cause of car accidents based on a variety of criteria such as vehicle information, driver characteristics, and road conditions. In addition, interactive maps are developed to show the spatial distribution of accidents.

**Define the Stakeholder and Business Problem**

Stakeholder: City of Chicago Traffic Safety Department

Business Problem: The City of Chicago aims to improve road safety by identifying the primary contributory causes of car accidents. They are interested in understanding the patterns and factors leading to accidents to develop targeted interventions and safety measures.

**Objective**

Goal: Build a classifier to predict the primary contributory cause of car accidents based on features such as vehicle information, driver/passenger details, and road conditions

**Dataset**
The project uses the following datasets:
•	Vehicle Data: Contains information regarding automobiles that have been involved in accidents.
•	Crash Data: Contains information on the accidents itself.
**Data Sources:**
•	Vehicle and Driver/Passenger Data
•	Crash Data

**Preprocessing Steps**

**1. Combine Data:**
   - Merge the Vehicle Data, Driver/Passenger Data, and Crash Data based on a common identifier (e.g., accident ID).

**2. Feature Engineering:**
   - Create features such as weather conditions, time of day, road type, vehicle type, and driver age group.
   - Transform categorical variables into numerical values if necessary.

**3. Handling Missing Values:**
   - Address missing values by imputation or by removing incomplete records, depending on their impact on the dataset.

**4. Target Variable:**
   - Define the target variable as the primary contributory cause of the accident.
   - Consider consolidating categories with few samples to ensure the model has enough data to learn from.

**5. Data Splitting:**
   - Split the data into training and testing sets.

**Deployment and Use**

- Prediction System: Develop a system where new accident data can be input to predict the primary contributory cause.
- Dashboard: Create visualizations to present patterns and trends to stakeholders.

**Next Steps**

- Approval: Get the dataset and business problem approved by the instructor if proposing it.
- Exploration: Conduct exploratory data analysis (EDA) to better understand the dataset and refine feature engineering.
- Model Building: Train and evaluate different classifiers to determine the best performing model.
- Reporting: Prepare a comprehensive report for the City of Chicago, including findings, model performance, and recommendations for safety interventions.


