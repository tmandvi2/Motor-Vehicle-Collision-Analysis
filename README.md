# Motor-Vehicle-Collision-Analysis
Motor Vehicle Collision dataset analysis using SQL

Introduction
The project investigates motor vehicle collisions in New York City (NYC), aiming to identify patterns in time, location, severity, and contributing factors. It focuses on deriving actionable insights for road safety improvement by answering questions related to collision frequency across boroughs, time-of-day impacts, common contributing factors, and the correlation between vehicle types and accident severity.

Dataset Overview
- Source: Kaggle Open Database (2015–2017 data).
- Content: Includes details like location, injuries, fatalities, contributing factors, and vehicle types.
- Size: 477,732 rows and 31 columns.

Key Research Questions
1. Which NYC boroughs have the highest collision rates, and what are the top contributing factors?
2. How does time of day influence collision frequency and severity, and what trends are observed over the years?
3. What are the most common contributing factors, and how do they vary by borough or time?
4. How do vehicle types correlate with accident severity, including fatalities?

Methodology
Data Preparation:
  - Cleaned missing values and standardized attributes.
  - Added derived columns for time-based analysis (e.g., "Day/Night," "Crash Day").
Tools: PostgreSQL, Python (pandas, matplotlib), Power BI, and Excel.

Key Findings
1. Borough-wise Analysis:
   - Brooklyn: Highest overall collision rate (104,961 incidents, 108 deaths).
   - Highways/Freeways: Second-highest collisions (139,000), reflecting cross-borough traffic complexities.

2. Time-of-Day Trends:
   - Nighttime: Deadlier despite fewer accidents (132,882 incidents, 264 deaths), driven by impaired driving and fatigue.
   - Daytime: More frequent (344,850 incidents) due to higher traffic density.

3. Contributing Factors:
Top Causes:
     - Driver inattention/distraction (69,474 incidents, 66 deaths).
     - Failure to yield right-of-way (21,852 incidents, 34 deaths).
     - Alcohol-Related Accidents: Rare but severe, with high injury rates but lower fatalities.

4. Vehicle Type Severity:
   - Passenger vehicles: Most common in accidents (295,532 incidents).
   - Motorcycles: Highest fatality rate (2.48%).
   - Large trucks: High fatality risk due to size and weight, with a 3.33% fatality rate.

5. Yearly Trends (2015–2017):
     - A significant decline in accidents by 2017, attributed to:
     - Vision Zero initiatives.
     - Reduced speed limits and redesigned intersections.
     - Increased law enforcement and rideshare adoption.

Recommendations
1. Strengthen enforcement of distracted driving laws and public awareness campaigns.
2. Introduce stricter DUI measures, especially on weekend nights.
3. Implement targeted safety measures for motorcycles and commercial vehicles.
4. Enhance infrastructure and traffic management in high-risk boroughs and highways.

Conclusion
The study highlights the critical factors contributing to NYC traffic collisions. It emphasizes the importance of tailored interventions to improve road safety, particularly for high-risk vehicle types, nighttime driving, and high-incident locations.
