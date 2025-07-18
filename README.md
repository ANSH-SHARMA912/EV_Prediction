#  EV Adoption Forecasting

# Project Overview
As electric vehicle (EV) adoption surges, urban planners and policymakers need to anticipate infrastructure requirements—especially the demand for EV charging stations. Inadequate planning can lead to bottlenecks, affecting user experience and hindering sustainability goals.

This project aims to **forecast future EV adoption trends** using historical EV registration data. The insights from this model can help in **planning charging infrastructure, resource allocation, and policy development**.


# Problem Statement
Using an electric vehicle dataset (containing information on EV populations, vehicle types, and historical charging usage), build a **regression-based predictive model** to forecast the **number of electric vehicles in upcoming years** based on historical trends in EV growth, vehicle types, and regional data.


# Goal
- Develop a **regression model** that predicts future EV adoption demand.
- Analyze historical EV registration data to identify trends.
- Provide **forecasting results** that can guide sustainable infrastructure planning.


# Dataset Details
The dataset represents the number of vehicles registered by the **Washington State Department of Licensing (DOL)**, with monthly records from **January 2017 to February 2024**. It includes:

- **Date:** Monthly registration date.
- **County:** Geographic region within the state.
- **State:** Region associated with the record.
- **Vehicle Primary Use:** (Passenger: 83%, Truck: 17%).
- **Battery Electric Vehicles (BEVs):** Vehicles powered solely by onboard batteries.
- **Plug-In Hybrid Electric Vehicles (PHEVs):** Vehicles powered partially by onboard batteries.
- **Electric Vehicle (EV) Total:** Sum of BEVs and PHEVs.
- **Non-Electric Vehicle Total:** Vehicles that are not electric.
- **Total Vehicles:** All powered vehicles (including EVs).
- **Percent Electric Vehicles:** Percentage of EVs compared to total registered vehicles.



# Tech Stack
- **Programming Language:** Python  
- **Libraries Used:**  
  - `pandas` for data manipulation  
  - `numpy` for numerical computations  
  - `matplotlib` / `seaborn` for visualization  
  - `scikit-learn` for regression modeling  


