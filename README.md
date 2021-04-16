# COVID19-Hesitancy-Twitter-NLP

## Purpose
COVID was declared a pandemic in March 2020$^1$ and people globally looked forward to science that could offer preventive measures or treatment. Still, in a pre-vaccine survey about 64% of adults in the United States of America expressed reluctance intake a vaccine if one was available$^2$. Fast forward to January 2021, major players in the pharmaceutical industry have developed vaccines with the following efficacy$^3$:  
- Pfizer/BioNTech: 95%
- Moderna: 95%
- AstraZeneca 70%
- Johnson & Johnson: 66%
And yet, 47% of Americans are still hesitant to take a vaccine$^4$.  


## Methodology
**The purpose of this study is two-fold:**  
To understand public sentiment regarding the COVID-19 vaccination in hopes to identify major factors that cause reluctance in communities.   

Some studies and patient interviews also suggest that people are expressing hesitancy in taking the second dose of the mostly required 2-dose vaccination process.  This study will aim to identify concerns people have with respect to the vaccination process and other logistic aspects (for example: role of the government).

This project conducts sentiment analysis of Twitter data with regards to the COVID-19 vaccines developed by pharmaceutical companies. We selected Twitter as our social media platform since it focuses on keywords and hashtags and allows posting to a wider audience when compared to other social media platforms. This, in addition to the character limit on Twitter compels users to be vocal about their opinions in as concise a way as possible. 

It is important to note that the aim of this project is not to rate and categorize different vaccines but to understand the general sentiment of the public towards (or against) vaccines and quantify this sentiment. We therefore believe analyzing more than one vaccine company as a keyword can help us better understand public perception.  
 
All tweets with keywords and hashtags such as #covid, #covid-19, #antivaxxers, #covidvaccine were included in the study. Only tweets in English were included and were coded in Python to conduct vaccine related sentiment analysis.  
   
Considering the efficiency of data storing and sharing, as well as the reproductivity of work, we normalized original two datasets to better fit the objective of this project. Besides this, we used Amazon Relational Database Service (Amazon RDS) to establish our own database and only queried necessary information for our analysis.

The Pandas package and NLTK (Natural Language ToolKit) were used for sentiment analysis of calculating subjectivity and polarity of all tweets. The plotly package and matplotlib package are used collaboratively in generating comparison of vaccine adoption behaviours in different locations.

We would highlight the methology of data processing and analysis part in following separated sections as 'Database Establishmend and Data Import' and 'Data Analysis'.
