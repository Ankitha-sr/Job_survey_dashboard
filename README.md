# Data Professional Survey Breakdown 

An interactive Power BI dashboard that explores a survey of 630 data professionals, covering their roles, salaries, favorite programming languages, job satisfaction, and how hard it was to break into the field.

**Objective**

Understand the data profession from the people working in it:

Which job titles pay the most on average?

Which programming languages are most popular, and does that differ by role?

How satisfied are data professionals with their salary and work/life balance?

How difficult is it to break into data, and where do respondents live?

**Dataset**

Records: 630 survey responses

Fields: 28 columns, including job title, salary range, industry, favorite programming language, satisfaction ratings (0–10), difficulty breaking into data, gender, age, country, education, and ethnicity

Source: Data Professional Survey dataset

**Tools & Techniques**

**Power BI Desktop**

**Power Query (data cleaning):**

Split "Other (Please Specify): ..." answers so free-text responses group under a single "Other" category for job title, programming language, and country

Converted salary ranges (e.g. 41k-65k) into a numeric Average Salary column by splitting the range and averaging the low and high values

Removed columns not needed for analysis and set correct data types

**Visuals**: KPI cards, stacked column chart, bar chart, donut chart, treemap, and gauges

**Key Insights**

Data Analysts make up about 60% of respondents (381 of 630).

Python is the clear favorite language, chosen by about 67% of respondents, followed by R.

Data Scientists report the highest estimated average salary (~$94K), ahead of Data Engineers (~$65K) and Data Analysts (~$55K).

Respondents are more satisfied with work/life balance (5.7/10) than with salary (4.3/10).

About 43% said breaking into data was neither easy nor difficult, while roughly 32% found it difficult or very difficult.

The United States is the most common country (41% of respondents), followed by India and the United Kingdom.

The average respondent age is about 30.
