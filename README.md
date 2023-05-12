# SCTP-Data-Analyst---My-3rd-Capstone-

### An Analysis into MOE Y2022 Primary 1 Registration Phase

The MOE Primary 1 Registration Phases Dashboard provides an overview of the registration phases for parents who are planning to register their child in a Singapore primary school. The data is based on a raw dataset from the "Kiasu Parents" website and is visualized using Microsoft Power BI software.

Key Insights: The dashboard highlights the following key insights:
Overview: The dashboard provides a clear overview of the key parameters in the registration, including the number of schools, vacancies, etc. 
Phase Analysis: The dashboard shows each Phase, helping to identify patterns in the number of applicants, vacancies, over-subscribed schools, and highest/lowest application towns/schools.
Conclusion: Overall, the MOE Primary 1 Registration Phases Dashboard provides valuable insights for parents who are navigating the Phases’ details. The visualizations and key insights help to make sense of the complex data and provide a clear understanding of the Phases.

### Data Collection, Transformation, Cleaning
Data Extraction: The MOE Primary 1 Registration Phases Dashboard was created using a raw dataset from the "Kiasu Parents" website, which was initially in jpeg format. To extract the relevant data, OCR software such as [Nanonets](https://nanonets.com/blog/table-extraction-deep-learning/) and [Text_Grab](https://github.com/TheJoeFin/Text-Grab) were used. However, due to the poor resolution of the original jpeg files, the OCR software was only able to capture 10%-20% of the data accurately. As a result, the available data had to be manually entered into Excel and saved in CSV format to ensure accuracy and completeness.

![image](https://i.imgur.com/vO0j5nd.jpg)

Data Cleaning & Transformation: In Excel, data cleanings such as removing unwanted rows and columns were performed to ensure that only relevant data was included. In Power BI, data cleaning/transforming involved adding new columns and new calculations, also called measures. These measures were used to derive new insights and create additional visualizations.

![image](https://i.imgur.com/egaiUBx.jpg)

![image](https://i.imgur.com/WeV7tXJ.jpg)

![image](https://i.imgur.com/d0gzg4J.jpg)


### What have I learned from this analysis?

Applicants were assured of a place if they apply in **Phase 1**. 
 - **highest application rate** is **74%**, Chong Zheng Primary.

In **Phase 2A**, “popular” schools **start to get oversubscribed**. 
- Merger of old Phase 2A(1) and 2A(2) into one Phase.
- Reserved places for Phase 2B (20 seats) and 2C (40seats).

**Phase 2B** saw the **largest number** (57 **schools**) with **0 application**.

In **Phase 2C**, **4 Towns** (Bishan, Central, Marine Parade, Novena) were **fully subscribed**.
- These towns have only 3 schools in it.
Also, it is the **highest application count** of 15.1k **among all phases**.

End of **Phase 2CS**, the **Total Take-Up Rate reaches 91%** (3.6k places remaining).

One recommendation for future parents: "Every school, is a good school, does not mean every school is the same school. But it does mean, every school good in its own way, seeking to bring out the best in every child."

### Further Improvement (ver. 2.0)
- To include Y2021 datasets for analysis against Y2022 (meaning I have to manually key-in Y2021 datasets !!!!)

Click *[here](https://www.linkedin.com/in/chee-keong-ng-5a5920117/)* for my Linkedin page 

