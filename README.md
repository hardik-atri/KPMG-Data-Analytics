# KPMG Data Analytics Virtual Internship

## Task 1 - Data Quality Assessment

In this task, we conducted a thorough data quality assessment on the provided dataset. The following issues were identified and addressed:

- **Missing Values**: We handled missing values in the dataset.
- **Invalid Data**: Entries with incorrect date of birth (DOB) having the year 1843 were removed. The gender column values were standardized to "Male" or "Female."
- **Invalid Transaction**: An invalid transaction with customer_id 5034 was removed as there was no corresponding customer with that ID.
- **Duplicate Entries**: Duplicate entries in the dataset were identified and removed.
- **Irrelevant Columns**: Columns deemed irrelevant were removed from the dataset.
- **Inconsistent Data**: Inconsistent values in certain fields, such as "job_title" and "job_industry," were addressed.

## Task 2 - Data Preprocessing and Modelling

In this task, we performed data preprocessing and utilized RFM (Recency, Frequency, Monetary) analysis to segment the customers. The steps involved were:

- **Data Cleaning**: The data was cleaned and prepared for analysis.
- **RFM Analysis**: RFM metrics were calculated for each customer using the transactional data in the dataset.
- **Segmentation**: Customers were segmented into different categories (Diamond, Gold, Silver, Bronze) based on their RFM scores, indicating their customer value.
- **Data Modelling**: The Random Forest algorithm was used to model the data and identify important features.

## Task 3 - Creating Dashboard using Power BI

In this task, we created an interactive dashboard using Power BI, incorporating the important features derived from the data modelling step.

The dashboard provides a comprehensive view of customer segmentation and key insights from the RFM analysis. It allows users to explore and visualize customer segments, their characteristics, and respective customer profiles. The dashboard will assist stakeholders in making data-driven decisions and identifying valuable customer segments.

## About

This repository contains the work done as part of the KPMG Data Analytics Virtual Internship by Forage. The internship equipped us with valuable skills in data quality assessment, data preprocessing, RFM analysis, data modelling, and data visualization using Power BI. The insights gained from this internship will undoubtedly contribute to our proficiency in the field of data analytics and decision-making processes.

