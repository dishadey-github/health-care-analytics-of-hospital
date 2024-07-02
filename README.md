# Health Care Analytics Report of XYZ Hospital

## Health Care Analytics Report Preview
![Heath Care Analytics Report of Hospital](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/0147692c-f5d0-43c9-830e-4f0d00f87e8e)

#### Overview
This health care analytics report provides a comprehensive overview of the patient population in the hospital. The analysis focuses on various health metrics and risk factors, offering insights into the overall health status, prevalent health risks, and demographic trends. By understanding these key metrics, healthcare providers can make informed decisions to improve patient care and allocate resources more effectively.

#### Data Source
The data is derived from a sample dataset (Patient_History_data.xlsx) containing 5191 patient records, with various attributes related to their health status, habits, and demographics.

##### Activities to perform in the Power Query
1. Open Power Query Editor:\
Click on Transform Data to open the Power Query Editor. In view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

2. Inspect and Clean Data:\
Verify that dataset is loaded correctly.\
Check for any inconsistencies or missing values and handle them accordingly.


### Key Performance Indicators (KPIs)

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/f85a9cbb-2b92-4b38-b476-727542c245b1)

#### Number of Patients
Card: The card displays a single value indicating the total number of patients.\
Value: 4844\
Insight: This KPI represents the total count of patient records analyzed.\
Risk: A high patient volume may indicate a need for more resources and staff to maintain quality care.

#### Female Patients Not Overweight
Card: A single value indicating the number of female patients who are not overweight.\
Value: 1344\
Insight: This metric highlights the subset of female patients who fall within a healthy weight range.\
Risk: While a substantial portion is not overweight, the presence of overweight patients indicates potential risks for weight-related health issues that need to be addressed.

#### Smoking with High Health Risk
Card: A single value showing the number of patients who smoke and have a high health risk.\
Value: 352\
Insight: Indicates how many patients are at significant risk due to smoking.\
Risk: These patients are at an increased risk for severe health complications, necessitating targeted smoking cessation programs and interventions to reduce this risk.

#### Exercise < 30 mins with High and Moderate Health Risks
Card: A single value showing the number of patients who exercise less than 30 minutes and have high or moderate health risks.\
Value: 792\
Insight: Represents patients with insufficient physical activity contributing to their health risks.\
Risk: This highlights the need for promoting physical activity among patients, as inactivity can exacerbate existing health conditions and lead to further complications.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/d736fb46-7c06-4998-8d0a-fc066f6a148f)

#### Percentage of Heart Attack
Chart: A pie chart showing the percentage of patients who have had a heart attack.\
Values:\
Yes: 2.8%\
No: 97.2%\
Insight: Demonstrates the prevalence of heart attacks among the patient population.\
Risk: Despite the low percentage, heart attacks have severe consequences. Preventive measures should still be emphasized, especially for high-risk individuals.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/f40529da-9d6b-4124-9955-8e41d24058d4)

#### Percentage of Stroke
Chart: A pie chart showing the percentage of patients who have had a stroke.\
Values:\
Yes: 1.7%\
No: 98.3%\
Insight: Indicates the occurrence rate of strokes among patients.\
Risk: Similar to heart attacks, strokes have serious health impacts. Continuous monitoring and preventive strategies are essential to keep this percentage low.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/20874ac5-bc85-420b-8506-54b72f84efd1)

#### Average Weight by Occupation Type
Chart: A bar chart displaying the average weight of patients categorized by their occupation type.\
Values:\
Others: ~66 kg\
White-collar Job: ~66 kg\
Blue-collar Job: ~66 kg\
Unemployed: ~60 kg\
Insight: Shows the average weight of patients based on their employment status, highlighting any trends related to occupation.\
Risk: Certain occupation types might be associated with lifestyle factors that influence weight. Understanding these correlations can help design targeted health programs.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/61a3b163-da55-41a6-82d2-10a5979771ee)

#### Count of Overweight by Race
Chart: A horizontal bar chart showing the number of overweight patients categorized by race.\
Values:\
Chinese: 1940 patients\
Malay: 460 patients\
Indian: 300 patients\
Others: 90 patients\
Insight: Reveals the distribution of overweight individuals across different racial groups.\
Risk: Tailored interventions based on cultural and demographic factors may be required to effectively address overweight and obesity issues within different racial groups.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/37ab0496-7d3d-446a-ba48-f0ac20dacc30)

#### Count of Health Risk
Chart: A bar chart showing the count of patients categorized by their health risk level.\
Values:\
Normal: ~2000\
Moderate: ~800\
High: ~100\
Critical: ~20\
Insight: Highlights the distribution of patients across various health risk levels, emphasizing areas of concern.\
Risk: Patients in the moderate and high-risk categories require closer monitoring and more intensive health interventions to prevent escalation to critical conditions.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/63d4058f-0ee4-4295-ba71-d500e6b3e8e0)

#### Count of Health Risk by Age Group
Chart: A stacked bar chart showing the count of patients with different health risks, segmented by age group.\
Values:\
<40: Mainly normal\
40-49: Mix of normal, moderate, and some high and critical\
50-59: Similar distribution as 40-49\
60-69: Increased counts of moderate and high risks\
70+: Higher counts in high and critical risks\
Insight: Demonstrates how health risks vary across different age groups, indicating trends and risk factors associated with aging.\
Risk: Aging populations are at increased risk for health complications. Resources should be allocated to manage chronic conditions and provide preventive care for older patients.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/4de7c946-46d8-40be-a4ed-b46cc45368e8)

#### Count of Health Risk Categories
Chart: A bar chart showing the count of patients categorized by health risk levels (e.g., Good, Very Good, Not Good, Poor).\
Values:\
Good: ~3500\
Very Good: ~400\
Not Good: ~300\
Poor: ~10\
Insight: Displays the overall health ratings of patients, indicating the general health status of the population.\
Risk: The high number of unhealthy patients indicates a need for comprehensive health improvement programs and lifestyle interventions.

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/af34ea1f-703f-434c-9501-c684efef4c73)

![image](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/deb5d0e8-9fc7-44b8-8830-723424e20cac)

#### Filters
- Gender
- BMI
- Age Group
- Health Risk

# Health Care Analytics Report of XYZ Hospital (with filters)
Filter 1
- Gender - Female
- BMI - 17.9
- Age Group - All
- Health Risk - High

![Filter 1](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/948bfc69-43ed-4a5a-a527-0f9c942e056b)

Filter 2
- Gender - Male
- BMI - All
- Age Group - 60-69
- Health Risk - High

![Filter 2](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/50e99492-6b1a-4eab-9ab6-930b2d12a38f)

Filter 3
- Gender - Female
- BMI - All
- Age Group - 50-59
- Health Risk - Critical

![Filter 3](https://github.com/dishadey-github/health-care-analytics-of-hospital/assets/60807918/2b58ec75-4b61-451f-ba55-048892e98a3d)


#### Conclusion
This health care analytics report provides valuable insights into the health status and risks of the hospital's patient population. By understanding these key metrics and trends, healthcare providers can make informed decisions to improve patient care, allocate resources effectively, and design targeted interventions to address specific health risks.
