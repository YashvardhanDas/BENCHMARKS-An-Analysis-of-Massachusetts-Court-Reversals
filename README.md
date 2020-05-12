# BENCHMARKS - An Analysis of Massachusetts Court Reversals

# Team Members

Yashvardhan 'Yash' Das, Abhimanyu Jain, Yuwan Xiao, Anton Njavro

# About

This project is based on a continuation of the work done by the previous team during the last year. The work associated is in collaboration with BU Spark! and mentored by Ms. Maggie Mulvihill, Associate Professor of the Practice of Computational Journalism, of the College of Communication at Boston University. A partner associated with this project is The Boston Globe. 

The primary motive of implementing this project involves analyzing the rate of reversals associated with court judges and determining the factors associated with the types of courts based on these reversals. This project, which is a combination of data retrieval, its subsequent analysis, and investigative journalism, can serve as a foundation for a probable interdisciplinary team at Boston University which can scrutinize case reversals in all the entire 50 states present in the country.

# Data Collection

The data for our analysis were collected through a combination of different websites. The prime challenge we faced was the irregular structure of the pages that needed to be web-scraped. For some unknown reason, the core structure of the web-pages of cases dating from 2018 - 2019 was significantly modified as compared to the main structure of the web pages dating from 2008 - 2018. 

Our first major dataset contains the data of civil cases pertaining to the period of 2008 - 2018. This has been taken as a subset of the overall dataset that was used by the former team. To make a meaningful analysis of the data, during the pre-processing stage we had to discard a number of columns present in the dataset. The second major dataset that is used in our project contains details of both the civil and criminal cases relating to the period of 2018 - 2019. Since the court website has sensitive information, there were error requests encountered during the scraping process. Strategic time-limits had to be written in the code to successfully download all the required data.
