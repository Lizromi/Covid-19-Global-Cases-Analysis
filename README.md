# COVID-19 GLOBAL CASES ANALYSIS
## Project Objective: Problem Statement
Analyzing COVID-19 global cases data from 2019 to 2021 to understand the patterns, trends, and impacts of the pandemic on a global scale. This analysis aims to identify key factors influencing the spread of the virus, assess the effectiveness of various containment measures, and provide insights to support future pandemic preparedness and response efforts.
This problem statement sets the stage for a comprehensive analysis of COVID-19 data, focusing on understanding the dynamics of the pandemic over time, its geographical spread, the efficacy of interventions, and implications for public health policies.

## Data Source
The COVID-19 global cases data used in this analysis was obtained from the "30-days-of-Learning-Data-Analysis-Using-Power-BI" repository hosted on GitHub and posted by "theoyinbooke." This repository provides datasets and resources aimed at learning data analysis using Power BI, including a dataset containing COVID-19 global cases data from 2020 to 2023.
The dataset within the "30-days-of-Learning-Data-Analysis-Using-Power-BI" repository offers a structured collection of COVID-19 data, including information on confirmed cases, deaths, and recoveries across different regions and time periods. While the primary focus of the repository is on learning data analysis techniques using Power BI, the COVID-19 dataset serves as a valuable resource for analyzing and understanding the impact of the pandemic.
Accessing COVID-19 data from this GitHub repository allows for exploration and analysis of real-world datasets within the context of learning data analysis skills. The availability of this dataset on an open platform like GitHub promotes transparency and accessibility, enabling researchers, students, and enthusiasts to utilize the data for educational and analytical purposes.
By leveraging this dataset from the "30-days-of-Learning-Data-Analysis-Using-Power-BI" repository, I aim to gain insights into the patterns, trends, and impacts of the COVID-19 pandemic, contributing to our understanding of global health dynamics and informing evidence-based decision-making.

## Data Transformation
Upon retrieving the COVID-19 global cases data from the "30-days-of-Learning-Data-Analysis-Using-Power-BI" repository, several preprocessing steps were undertaken to ensure the data's quality and suitability for analysis.
1. **Data Cleaning**: The raw COVID-19 dataset contained various inconsistencies, such as missing values, duplicate entries, and formatting errors. To address these issues, data cleaning procedures were implemented. Missing values were either imputed or interpolated using appropriate methods, ensuring continuity in the time series data. Duplicate entries were identified and removed to prevent redundancy and maintain data integrity. Additionally, inconsistencies in data formats, such as date formats or geographical naming conventions, were standardized for consistency across the dataset.
2. **Aggregation and Transformation**: The COVID-19 dataset provided daily reports of cases, deaths, and recoveries across different regions. To facilitate analysis and visualization, the data was aggregated and transformed into meaningful summaries. This involved writing DAX aggregation functions to find the sum of confirmed cases, Sum of recovered and death cases.
3. **Quality Assurance**: Throughout the data transformation and preprocessing phase, rigorous quality assurance measures were implemented to verify the accuracy and consistency of the processed data. Robust validation procedures were applied to ensure that data transformations and calculations were performed correctly, minimizing the risk of errors or inaccuracies in subsequent analyses.
After undergoing these preprocessing steps, the COVID-19 global cases data was transformed into a clean, structured, and analytically useful dataset, ready for in-depth analysis and visualization using Power BI.


## Insights Derived
1. **Highest Total Confirmed Cases by Year:**
   - The year 2022 stands out with the highest total number of confirmed COVID-19 cases, reaching a staggering 196,529,309,166. This is followed by 2021, 2023, and 2020, indicating the varying intensity of the pandemic across different years.
2. **Distribution of Confirmed Cases by Month in 2023:**
   - In January 2023, confirmed cases accounted for approximately 6.52% of the total sum of confirmed cases, highlighting the significance of temporal variations within a year.
3. **Highest Average Confirmed Cases by Year:**
   - 2022 witnessed the highest average sum of confirmed cases, with an average of 16,377,442,430.50 cases per year. This is followed by 2023, 2021, and 2020, suggesting the sustained impact of the pandemic over consecutive years.
4. **Regional Disparities in Confirmed Cases:**
   - The United States had the highest sum of confirmed cases, reaching 53,813,184,406, which was 535.50% higher than Korea, South, with the lowest sum of confirmed cases at 8,467,888,968. This stark contrast underscores the regional disparities in COVID-19 prevalence and containment efforts.
5. **Contribution of the United States to Total Confirmed Cases:**
   - The United States accounted for approximately 29.25% of the total sum of confirmed cases, highlighting its significant share in the global burden of COVID-19 infections.
6. **Range of Recovered Cases Across Top 10 Countries:**
   - Among the top 10 countries, the number of recovered cases ranged from 498,203,576 to 4,859,387,857, showcasing variations in recovery rates and healthcare systems' effectiveness in managing the pandemic.
7. **Overall Pandemic Metrics:**
   - Over the years analyzed, the death rate averaged at 1.39%, resulting in a total of 4 billion deaths. The total number of confirmed cases stood at 317 billion, affecting a total of 201 countries globally. The recovery rate averaged at 7%, resulting in a total of 23 billion recovered cases, indicating the resilience and recovery efforts amidst the pandemic.
