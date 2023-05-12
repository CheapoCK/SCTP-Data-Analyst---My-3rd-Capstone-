# SCTP-Data-Analyst---My-3rd-Capstone-

### An Analysis into MOE Primary 1 Registration Phase

The MOE Primary 1 Registration Phases Dashboard provides an overview of the registration phases for parents who are planning to register their child in a Singapore primary school. The data is based on a raw dataset from the "Kiasu Parents" website and is visualized using Microsoft Power BI software.

Key Insights: The dashboard highlights the following key insights:
Overview: The dashboard provides a clear overview of the key parameters in the registration, including the number of schools, vacancies, etc. 
Phase Analysis: The dashboard shows each Phase, helping to identify patterns in the number of applicants, vacancies, over-subscribed schools, and highest/lowest application towns/schools.
Conclusion: Overall, the MOE Primary 1 Registration Phases Dashboard provides valuable insights for parents who are navigating the Phases’ details. The visualizations and key insights help to make sense of the complex data and provide a clear understanding of the Phases.

### Data Collection, Transformation, Cleaning
Data Extraction: The MOE Primary 1 Registration Phases Dashboard was created using a raw dataset from the "Kiasu Parents" website, which was initially in jpeg format. To extract the relevant data, OCR software such as Nanonets and [Text_Grab](https://github.com/TheJoeFin/Text-Grab) were used. However, due to the low resolution of the original jpeg files, the OCR software was only able to capture 10%-20% of the data accurately. Despite this limitation, the available data was cleaned and processed to create meaningful visualizations in Microsoft Power BI software. The dashboard provides a clear and informative overview of the MOE Primary 1 Registration Phases, based on the available data.


- Raw data in .csv format, download from Kaggle
- Using SQLite, convert .csv into .sql and import into pgAdmin platform for Data Cleaning.
- Using SQL to perform data cleaning: remove empty rows, unwanted columns (example: column “pos”), replacing all N/A with NULL, change Data Type, etc
- After Data Cleaning process: 6 tables, 39206 game titles, 3366 Publishers, 8752 Developers and 80 Platforms.
