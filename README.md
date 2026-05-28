#   Healthcare-Analytics-using-PowerBI

Introduction 

Created an interactive Heathcare Anaytics Dashboard using Power BI to provide the healthcare professionals and administrators with insights into patient visits, treatment satisfaction, waiting times, and demographic distributions. This dynamic data visualization tool incorporates data modeling principles and various data sources for effective data transformation. By implementing KPIs and utilizing Power Query,it helps them to understand patient details and can identify the areas for improvement and enhance overall patient care.
<br>

## Table of Contents                      
 1. Data Source
 2. Tools
 3. Features
 4. Dashboard
 5. How to Run the Project<br>

### Data Source

Healthcare Data : The primary dataset is used for the analysis is the 'HealthCare_Analytics.csv' which contains data over a period of time of 2019-2020.
<br>

### Tools

*	Power BI

*	Power Query Editor

*	Data Analysis Expressions (DAX)


### Features

#### Data Understanding :

The healthcare dataset includes features like Date, ID, Gender, Age, Race, Moment (AM/PM), Weekday/Weekend, Admin Flag (Patient/Non-Patient), Department Referral, and Satisfaction Score. These fields allow for a detailed look at visitor demographics, visit timings, and department engagement, creating a strong basis for trend analysis and operational insights.

#### Data PreProcessing :

* Collecting Data Source: The data for this project was collected from hospital records, patient feedback forms, and internal healthcare systems.
*  Loading Data into Power BI Data Import: The data was imported into Power BI using CSV files and database connections.
* Checking Data in Power Query Editor Data Review: In the Power Query Editor, the dataset underwent an ETL (Extract, Transform, Load) process, which included normalization by splitting tables to enhance data organization and clarity. Addressed missing values, corrected errors, and standardized data formats to ensure accuracy and usability.
* DAX Calculations and Data Modeling: Data Analysis Expressions(DAX) were utilized to create calculated fields for aggregation, allowing for sophisticated analysis of the healthcare data. We created multiple measures to facilitate our analysis.


#### Visit Trends and Patterns:

* Monthly Visits: From April to October, there was a noticeable increase in visitor counts, particularly during the summer and rainy seasons. This trend indicates that seasonal factors significantly impact hospital traffic.

* Yearly Visits: The Visitor counts increased by 5.8% from 2019 to 2020, suggesting either an increase in health issues or growing trust in the hospital’s services. This rise may reflect both higher demand for healthcare and improved patient satisfaction.

#### Time-Based Distribution:

* Moment Distribution: Visitor flow is evenly split between AM and PM hours, with a slight 0.6% increase during AM visits. This indicates steady demand throughout the day, likely from a mix of appointments and walk-ins.

* Weekday vs Weekend: Weekday visits are 148.83% higher than weekends, reflecting significant weekday traffic. This large difference is due to fewer staff or reduced hours on weekends, encouraging visits during the week.

#### Visitor Wait Time Analysis:
* Average Wait Time: On average, visitors wait about 35 minutes, with 90.9% experiencing waits between 20 to 60 minutes. This indicates a significant area for potential process improvement in reducing wait times.

* Short Wait Times: Only 9.1% of visitors experience shorter wait times of 10 to 20 minutes. This low percentage highlights a clear opportunity to enhance service speed and overall patient satisfaction.


#### Demographic Insights:
* Age Group Distribution: Visitors of all ages (0 to 60) show similar frequency, while the 60+ age group constitutes only 5.25%. This may reflect either fewer visits or a smaller demographic within this age range.

* Gender Distribution: Male visitors outnumber females by 4.86%, while the "Not Specified" category represents a minimal 0.26%. This slight gender disparity highlights the need for targeted engagement strategies.

####  Key Business Recommendations Derived
* Address Feedback Collection:* Over 75% of patients left "No Rating." Implementing a brief, automated text/email feedback loop post-discharge could improve data collection and care metrics.
* Resource Allocation:* General Practice and Orthopedics experience the highest volume of patient referrals, suggesting these departments require higher staffing priority.
* Satisfaction Score Distribution: The average satisfaction score is 5.47 out of 10, indicating that most visitors have a neutral or average perception of the services, showing room for quality improvement.
*  Admin Flag Distribution: 50.04% of visitors are fully registered patients, while 49.96% are either visitors or individuals not registered for treatment. This indicates a significant portion of the hospital's traffic consists of non-registered individuals.

### Dashboard

<img width="1339" height="749" alt="image" src="https://github.com/user-attachments/assets/660d723a-0f39-4490-96ef-2775cceb44e6" />

### How to Run the Project

 * Clone this repository to your local machine.
 * Download and install [Power BI Desktop](https://powerbi.microsoft.com/).
 * Open the .pbix file included in this repository to view and interact with the data.

