# Google Capstone Project (Bellabeat)
I worked on the Google Data Analytics Capstone Project involving a company named Bellabeat, For this project I followed the steps of the data analysis process: Ask, Prepare, Process, Analyze, Share, and Act.
## Scenario
I am a junior data analyst working on the marketing analyst team at Bellabeat, a high-tech manufacturer of health-focused products for women. 

Bellabeat is a successful small company, but they have the potential to become a larger player in the
global smart device market. Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart
device fitness data could help unlock new growth opportunities for the company.

Bellabeat has 5 Products
- Bellabeat app: The Bellabeat app provides users with health data related to their activity, sleep, stress,
menstrual cycle, and mindfulness habits. This data can help users better understand their current habits and
make healthy decisions. The Bellabeat app connects to their line of smart wellness products.
- Leaf: Bellabeat’s classic wellness tracker can be worn as a bracelet, necklace, or clip. The Leaf tracker connects
to the Bellabeat app to track activity, sleep, and stress.
- Time: This wellness watch combines the timeless look of a classic timepiece with smart technology to track user
activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide you with insights into your
daily wellness.
- Spring: This is a water bottle that tracks daily water intake using smart technology to ensure that you are
appropriately hydrated throughout the day. The Spring bottle connects to the Bellabeat app to track your
hydration levels.
- Bellabeat membership: Bellabeat also offers a subscription-based membership program for users.
Membership gives users 24/7 access to fully personalized guidance on nutrition, activity, sleep, health and
beauty, and mindfulness based on their lifestyle and goals.
## Ask
Business Task:
Analyze smart device usage trends and provide recommendations to optimize Bellabeat's marketing strategy. The focus is on understanding user behavior related to activity, sleep, and calorie expenditure to improve engagement and sales.

Key Questions:
- What are some trends in smart device usage?
- How do these trends apply to Bellabeat customers?
- How can these insights influence Bellabeat’s marketing strategy?
##### Primary stakeholders: Urška Sršen and Sando Mur, executive team members.
## Prepare
Dataset Used: FitBit Fitness Tracker Data (public dataset from Kaggle)

This dataset contains information from 30 Fitbit users who provided data on daily activity, sleep, steps, and calories burned.

Limitations:
- Small sample size (only 30 users).
- Users are likely to be health-conscious individuals, potentially creating a bias.

Tools Used:  Power BI for data import, cleaning, and visualization.
## Process
Imported FitBit CSV files into Power BI.
Cleaned and transformed the data, ensuring:
No missing or duplicate values.
Data types were correctly formatted (date, numeric, categorical values).
![image](https://github.com/user-attachments/assets/86157d3e-b389-49d7-86c7-428c846589d1)
                                *Table Relationships*

## Analyze
Key Findings & Trends:

### Active Time Analysis
![image](https://github.com/user-attachments/assets/5d2573ac-c684-4ab9-bd4d-fd9c82e7d92b)

Users spend most of their active minutes in light activity compared to moderate or vigorous activity.
Sedentary time dominates daily routines with it making around 82.66% of average active time, while Very active time only makes up around 0.13% of the average active time.

##### Marketing Strategy: Encourage more intense activity through in-app challenges or workout reminders.
### Steps vs Sleep 
![image](https://github.com/user-attachments/assets/78b3703e-d982-4ffb-9079-be3b4a0fda65)

Most users seem to sleep about 6-7 hours, sleep doesn't seem to have a very concrete correlation with steps taking as the trend line is actually going downwards the more sleep users get.
##### Marketing Strategy: Promote the importance of sleep for an active lifestyle.
### BMI vs Active Time
![image](https://github.com/user-attachments/assets/6a8c1819-083c-4a22-8f65-9e53fa9b78ed)

Analyzed 8 users’ BMI vs Active Time trends.
Some users have higher BMI despite high activity levels, showing room for personalized fitness recommendations.
##### Marketing Strategy: Develop personalized wellness plans.
## Sleep by Day of the Week 
![image](https://github.com/user-attachments/assets/950e2a6c-27e8-47d9-9b3f-f9e96fbf9605)


Sleep consistency varies, with users sleeping more on Sundays and comparatively less on Weekdays.
##### Marketing Strategy: Suggest sleep-improvement tips on weekends.
### Total Steps vs Calories Burned 
![image](https://github.com/user-attachments/assets/947b04b2-5d75-48de-98bb-225baff3f158)


More steps strongly correlate with higher calorie burn, reinforcing the importance of daily movement.
##### Marketing Strategy: Promote step-tracking challenges and leaderboard competitions.
### Average Active Time Distribution
![image](https://github.com/user-attachments/assets/7584c333-5b78-4e69-9757-adb3d0bb6535)

Shows how users distribute their daily activity minutes.
Many users have short active periods, indicating low engagement in long-duration workouts.
##### Marketing Strategy: Introduce short, effective workouts through the Bellabeat app.
## Share
Power BI Dashboards & Visualizations:
![image](https://github.com/user-attachments/assets/438441b9-d7aa-4005-91f7-6722f54c5470)

- Created interactive Power BI dashboards to display trends and key insights.
- Used contrasting colors, labels, and tooltips to enhance readability.
- Presented findings in a clear and compelling format for the Bellabeat executive team.
### Act
Key Marketing Recommendations
#### 1. Encourage Active Lifestyles

Introduce gamification with step challenges and rewards.
Develop short workout routines in the Bellabeat app to increase engagement.
#### 2. Promote Sleep & Recovery

Highlight sleep-tracking benefits in marketing campaigns.
Introduce "Weekend Sleep Challenge" to encourage consistent sleep patterns.
#### 3. Personalized Wellness Plans

Offer BMI-based workout & nutrition plans via a Bellabeat premium subscription.
Provide hydration and stress-management tips tailored to activity levels.
#### 4. Improve User Engagement via the Bellabeat App

Add push notifications & reminders for workouts and hydration tracking.
Use social media & email campaigns to educate users about activity-sleep balance.
## Conclusion
The insights gained from Power BI analysis help Bellabeat improve its marketing and user engagement strategies. By promoting active lifestyles, better sleep habits, and personalized wellness plans, Bellabeat can attract and retain more users in the competitive smart device market.

## Technologies Used
- Power BI (Data Cleaning, Aggregation, Visualization)
- DAX for Measures & Calculations
- FitBit Dataset (CSV format)

