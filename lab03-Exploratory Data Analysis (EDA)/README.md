COVID-19 Integrated Dataset

 Project Overview
This dataset is used for Exploratory Data Analysis (EDA) The analysis focuses on understanding the trends, distributions, and correlations within COVID-19 tracking data.

 Dataset Description
The dataset, titled `IntegratedData.csv`, contains daily reports of COVID-19 cases and deaths across various counties and states. It includes temporal information and mobility-related features to help identify patterns in the spread of the virus.

 Data Dictionary (Columns)
| Column Name | Description |
| :--- | :--- |
| **date** | The date of the record (YYYY-MM-DD). |
| **county** | The name of the county. |
| **state** | The name of the state. |
| **fips** | Federal Information Processing Series code (unique identifier for counties). |
| **cases** | Total cumulative confirmed cases. |
| **deaths** | Total cumulative confirmed deaths. |
| **daily_cases** | New cases reported on that specific day. |
| **daily_deaths** | New deaths reported on that specific day. |
| **day_of_week** | The day of the week (e.g., Monday, Tuesday). |
| **is_weekend** | Boolean flag (True/False) indicating if the day is a weekend. |
| **is_holiday** | Boolean flag (True/False) indicating if the day is a public holiday. |

  Key Analysis Objectives
- Trend Analysis: Identifying how cases fluctuated over months.
- Data Distribution: Understanding the frequency and spread of daily infections.
- Correlation: Examining the relationship between the number of cases and the number of deaths.
- Data Cleaning: Handling missing values to ensure statistical reliability.

Summary Statistics (Post-Cleaning)
- Total Records Analyzed: 173,565 rows.
- Features Included: 11+ numerical and categorical columns.