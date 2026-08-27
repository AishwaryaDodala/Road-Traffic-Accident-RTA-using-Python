# Road Traffic Accident (RTA) Severity & Analysis Using Python 
# 📌 Project Overview


The **Road Traffic Accident (RTA) Analysis Project** focuses on analyzing road accident data to identify patterns, trends, and key factors associated with accident severity. Using **Python and data analysis techniques**, the project covers data cleaning, exploratory data analysis (EDA), statistical analysis, and data visualization.

The analysis examines factors such as **driver age, gender, driving experience, educational level, vehicle type, vehicle defects, accident location, and accident severity** to uncover meaningful insights and support data-driven recommendations for improving road safety.

### Dataset Overview

The **Road Traffic Accident (RTA) Dataset** contains records of road accidents along with information about drivers, vehicles, road conditions, accident locations, and accident severity. The dataset includes categorical and numerical variables that help analyze the factors contributing to road traffic accidents.

Key attributes include **age band, gender, educational level, driving experience, vehicle type, vehicle service year, vehicle defects, accident location, road conditions, weather conditions, time, day of the week, and accident severity**. The dataset is used for **data cleaning, exploratory data analysis (EDA), visualization, and identifying patterns and factors associated with accident severity**.

### Sample Dataset


| Time | Age_band_of_driver | Sex_of_driver | Type_of_vehicle | Driving_experience | Accident_severity |
| --- | --- | --- | --- | --- | --- |
| 17:02:00 | 18-30 | Male | Automobile | 1-2yr | Slight Injury |
| 01:06:00 | 31-50 | Male | Lorry (41-100Q) | Above 10yr | Serious Injury |
| 14:15:00 | Under 18 | Female | Public (> 45 seats) | 5-10yr | Fatal Injury |

## 🛠️ Technologies & Tools
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn  
- **GenAI :**  feature engineering and risk pattern synthesis

# Analysis 1
## Accidents by Hour Displays accident frequency across different hours of the day, revealing peak danger times and safe periods.
### Peak Danger Times
* **Highest Peak (5:00 PM / 17:00):** Records the single highest crash volume of the day with **1,228 accidents** (9.97% of daily total), driven by evening rush-hour commute congestion.
* **Secondary Evening Peak (4:00 PM – 6:00 PM):** 16:00 (921 crashes) and 18:00 (956 crashes) form an extended high-risk window where traffic volume and fatigue intersect.
* **Morning Commute Peak (8:00 AM):** Represents a secondary spike with **828 accidents**, marking the morning rush hour start.


  <img width="1059" height="485" alt="image" src="https://github.com/user-attachments/assets/38a6a0ef-d9de-4378-b01c-136019cd7035" />

# Analysis 2
## Vehicle Type Illustrates which vehicle types are most frequently involved in accidents across the dataset.
### Most Frequent Vehicles (High Exposure Volume)
* **Automobiles (Passenger Cars):** Represent the single highest collision count with **3,205 accidents** (28.2% of non-missing records).
* **Heavy Freight Lorries (41–100Q):** Rank second with **2,186 accidents** (19.2%), highlighting significant commercial transport involvement.
* **Pick-ups (up to 10Q):** Rank third among defined non-other vehicles with **811 accidents** (7.1%).

### Lowest Frequency Vehicles
* **Light / Micro Transport:** Bicycles (**21 accidents**), Bajaj / Rickshaws (**29 accidents**), and Turbos (**46 accidents**) record the lowest total involvement in the dataset.

<img width="1054" height="589" alt="image" src="https://github.com/user-attachments/assets/257110ec-5eb6-4c70-9049-0f83449676b2" />

# Analysis 3
## Severity vs Weather Shows the relationship between weather conditions and accident severity using colour intensity to highlight patterns.
**Rain Skews Lethality:** **Raining** conditions display the highest fatality rate at **1.73%** (darkest cell intensity in the fatal column), outperforming Normal clear weather ($1.34\%$).
* **Windy Risk:** **Windy** conditions yield the highest serious injury proportion at **16.33%**, followed by clear/normal conditions ($14.65\%$).
* **Fog Visual Anomaly:** **Fog or mist** shows $0.00\%$ fatalities and $10.00\%$ serious injuries due to sample size constriction ($N=10$) and drivers reducing speeds under poor visibility.

<img width="827" height="498" alt="image" src="https://github.com/user-attachments/assets/8645a2b3-54fe-4dd6-bffa-c626dbe98b97" />

# Analysis 4
## Casualties Presents the distribution of casualty numbers, helping identify typical versus extreme accident outcomes.
**Typical Outcomes (Single Casualty):** Over **67%** of accidents involve exactly **1 casualty**, establishing single-victim incidents as the baseline outcome.
* **Extreme Mass-Casualty Outliers:** Multi-casualty incidents ($3+$ casualties) represent low-frequency, high-impact tail events, tapering off to extreme outliers of up to 8 casualties in single multi-vehicle collisions.


<img width="860" height="423" alt="image" src="https://github.com/user-attachments/assets/28d8b9a3-ff1d-4044-9384-826cabe64b10" />




  
