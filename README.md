# AIRBNB_Python_Power-BI-Data-Visualization-Project
A Power BI dashboard comparing Airbnb data in Chicago and New Orleans.

In the context of Airbnb operations, how can the utilization of Python, Power BI Prep facilitate a comprehensive examination between Chicago and New Orleans.

This inquiry seeks to leverage Pwer BI visual analytics capabilities to uncover and illustrate the shared attributes, disparities, and distinctive patterns inherent to Airbnb's presence in these cities, thus elevating the depth and insightfulness of the study.

For this EDA project, we have chosen the "Airbnb Listings Data" dataset from 2 major cities: Chicago and New Orleans. This dataset provides a comprehensive snapshot of various attributes related to Airbnb listings, such as property type, neighbourhood, pricing, availability, and more. The dataset is ideal for conducting an in-depth exploration of the local Airbnb market and deriving actionable insights.

# Repository files -
listings.csv - Chicago listings dataset

listings (1).csv - New Orleans listings dataset

Air_BNB_Python_Power BI_Project.ipynb - Jupyter Notebook used for data manipulation data wrangling with Python.

cleaned_airbnb_data - Appended cleaned dataset generated after Python Data Wrangling.

AIRBNB_Data_Visualization.pbix - Data Visualization or Dashboard is ready from Power BI.

# Steps to proceed with the dashboard:
# ETL Process
# Data Extraction:
The datasets are hosted on GitHub, and we use Python's requests library to fetch them directly into Jupter Notebook.

# Data Cleaning:
Addressed disorder and inconsistency in the dataset using Jupyter Notebook and Power BI. This involved rectifying discrepancies, eliminating duplicates, and standardizing data formats to ensure consistency across both datasets (Chicago and New Orleans).

# Data Transformation:
Generated supplementary columns from pre-existing categorical data by splitting and transforming extensive descriptive text. These new columns provided a clearer, structured representation of the data, making it more suitable for visualization and analysis. The transformation improved the overall readability and helped enhance insights derived from the data.

# Power BI (Transformation & Load):
Leveraged Power BI Group and Replace feature to resolve inconsistencies in neighborhood names caused by letter casing, spelling variations, or phonetic similarities. After cleaning and transforming the dataset, appended the processed data with previously cleaned datasets, preparing the final data for visualization. The refined dataset was then loaded into Power BI for visual analytics and reporting.

# Divided the visualization findings into 4 categories:
# Property analysis
![Screenshot (48)](https://github.com/user-attachments/assets/2ab1fbb3-1515-4640-af87-51500242cfa5)

# Pricing analysis
![Screenshot (49)](https://github.com/user-attachments/assets/ba2cf58b-0361-4739-9ed8-87f839913caf)

# Host analysis
![Screenshot (50)](https://github.com/user-attachments/assets/4eaf8552-7381-441b-aecd-ca3297f8748b)

# Overview of Airbnb
![Screenshot (51)](https://github.com/user-attachments/assets/0b2d0c55-961a-4662-bb63-e5c51bd158d0)



