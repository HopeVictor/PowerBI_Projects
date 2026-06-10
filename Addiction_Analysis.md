Addiction Behavior & Lifestyle Impact Analysis Dashboard
----

## Table of Contents
* [Project Desciption](#Project-Description)
* [Business Questions](#Business-Questions)
* [Conclusion](#Conclusion)

## Project Desciption
This Power BI project analyzes addiction-related behaviors among 3,000 respondents across different demographic, lifestyle, and health-related factors. The objective is to understand patterns in smoking and drinking habits, identify key drivers of addictive behaviors, and evaluate how factors such as age, education, exercise frequency, sleep duration, BMI, mental health status, and income influence addiction trends.

The dashboard was developed to provide stakeholders with actionable insights that can support public health interventions, awareness programs, and behavioral improvement initiatives

## Business Problem
Substance abuse remains a significant public health challenge. Organizations need to understand:

* Which demographic groups are most affected by smoking and drinking habits.
* How lifestyle factors contribute to addictive behaviors.
* Whether health indicators such as BMI and sleep patterns are associated with addiction.
* Which population segments require targeted intervention programs.

Without a centralized analytical solution, identifying these trends and making data-driven decisions becomes difficult.

## About the Dataset
I got the dataset from [Kaggle](https://www.kaggle.com/datasets/nitindatta/finance-data/data).

Here is the description of each column:  
| Column Name                   | Description                                                                                       |
| ----------------------------- | ------------------------------------------------------------------------------------------------- |
| **id**                        | Unique identifier assigned to each respondent.                                                    |
| **name**                      | Full name of the respondent.                                                                      |
| **age**                       | Respondent's current age in years.                                                                |
| **gender**                    | Gender of the respondent (Male/Female).                                                           |
| **country**                   | Country where the respondent resides.                                                             |
| **city**                      | City where the respondent resides.                                                                |
| **education_level**           | Highest level of education attained by the respondent.                                            |
| **employment_status**         | Current employment status (Employed, Unemployed, Student, etc.).                                  |
| **annual_income_usd**         | Estimated yearly income of the respondent in US Dollars.                                          |
| **marital_status**            | Current marital status (Single, Married, Divorced, etc.).                                         |
| **children_count**            | Number of children the respondent has.                                                            |
| **smokes_per_day**            | Average number of cigarettes smoked daily.                                                        |
| **drinks_per_week**           | Average number of alcoholic drinks consumed per week.                                             |
| **age_started_smoking**       | Age at which the respondent began smoking.                                                        |
| **age_started_drinking**      | Age at which the respondent began consuming alcohol.                                              |
| **attempts_to_quit_smoking**  | Number of attempts made to stop smoking.                                                          |
| **attempts_to_quit_drinking** | Number of attempts made to stop drinking alcohol.                                                 |
| **has_health_issues**         | Indicates whether the respondent has any reported health conditions (Yes/No).                     |
| **mental_health_status**      | Self-reported mental health condition (Poor, Average, Good, etc.).                                |
| **exercise_frequency**        | How often the respondent engages in physical exercise (Daily, Weekly, Rarely, Never).             |
| **diet_quality**              | Assessment of the respondent's dietary habits (Poor, Average, Good).                              |
| **sleep_hours**               | Average number of hours slept per day.                                                            |
| **bmi**                       | Body Mass Index, a measure of body weight relative to height.                                     |
| **social_support**            | Level of emotional or social support available to the respondent (Low, Medium, High).             |
| **therapy_history**           | Indicates whether the respondent has previously attended therapy or counseling sessions (Yes/No). |


## Data Cleaning
This was completed in **Excel** using Power Query.

### Step 1: Checking for Duplicates

### Step 2: Replacing Values




## Data Analysis
* Smoking Prevalence is Extremely High

Across all age groups, smoking rates remain consistently high, averaging around 10 cigarettes per day.

Insight

Smoking appears to be a widespread behavior within the surveyed population, with little variation across age categories.

Business Impact

General anti-smoking campaigns may be insufficient. More targeted behavioral intervention programs may be required.

* Drinking Habits Remain Consistent Across Age Groups

Average alcohol consumption remains approximately 5 drinks per week across all age groups.

Insight

Alcohol consumption appears relatively stable regardless of age.

Business Impact

Alcohol awareness programs should target the broader population rather than focusing solely on younger or older demographics.

* Exercise Frequency Has Minimal Impact

Respondents who exercise daily, weekly, rarely, or never show very similar smoking and drinking patterns.

Insight

Exercise alone does not appear to significantly reduce addictive behaviors within this dataset.

Business Impact

Health programs should combine physical activity initiatives with addiction counseling and behavioral support.

* Mental Health Status Shows Strong Association

Individuals with Poor, Average, and Good mental health all exhibit high smoking and drinking rates, though respondents with poorer mental health show slightly higher addiction indicators.

Insight

Mental health may play a role in sustaining addictive habits.

Business Impact

Integrating mental health support into addiction treatment programs could improve outcomes.

* Education Level Has Limited Influence

Smoking and drinking rates remain relatively consistent across education levels.

Insight

Addiction behaviors are not isolated to a specific educational background.

Business Impact

Awareness campaigns should target all education groups rather than assuming higher education reduces addiction risk.

* BMI Has Little Observable Effect

Average BMI values remain similar across age groups while smoking rates stay consistently high.

Insight

No strong relationship exists between BMI and smoking behavior in this dataset.

Business Impact

BMI may not be an effective predictor for addiction risk assessment.

* Early Smoking Initiation Leads to Higher Consumption

The scatter plot indicates a relationship between the age respondents started smoking and the number of cigarettes consumed daily.

Insight

Individuals who begin smoking at younger ages tend to maintain higher smoking intensity later in life.

Business Impact

Prevention programs targeting teenagers and young adults could significantly reduce long-term addiction rates.

* Income Shows Weak Correlation with Smoking

Annual income demonstrates little influence on smoking frequency.

Insight

Smoking behavior occurs across income levels.

Business Impact

Addiction intervention programs should be designed for broad accessibility rather than income-specific targeting.

## Data Visualization
Here is the dashboard.  
<br/><br/>
![Finance Dashboard](https://github.com/HopeVictor/Power-BI-Projects/blob/main/1.png)

<figure>
  <img src="https://github.com/HopeVictor/Power-BI-Projects/blob/main/1.png" width=100% height=100% alt="alt text">
  <figcaption>Figure: Finance Dashboard</figcaption>
</figure>
<br/><br/>

## Insights Uncovered

## Recommendations


## Conclusion
