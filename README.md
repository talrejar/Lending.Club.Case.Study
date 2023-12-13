# Project Name
> Dive in the data analytics of a financial company who is the largest online loan marketplace facilitating business loans, personal loans and financing of medical procedures. Objective is to perform data analytics to identify various contributing factors for a financial company to identify what are the attributes of consumer and loan which results in the default or losses for the company. To analyse the above scenario, we will perform exploratory data analysis and apply univariate & bivariate analysis and identify driving variables or factors


## General Information
Data Cleaning:

- Identify the empty rows for each column from the given data frame and drop the
columns wherein the empty value is more than 50%>. This is followed across data industry standard as common practise and also instructed by the instructor in the previous classes
- Omitted the missing value rows for each column
- Identified columns are identified wherein, only one unique value is available hence,
dropped those rows
- Few more columns were dropped to retain the relevant or needed data for the
analysis like unique ids, customer behaviour variables 

Univariate Analysis:
- Evaluated various variables and plotted in bar form
- As per data, most of them occur in the month of December
- To be precise, 13.98% loans are defaulted

Bivariate Analysis:
- As part of analysis, identified two variables are considered to see how defaulter behaviour changes
- Heatmap is used to analyse which US states have more defaulters in comparison
- Identifying default driving factors which have more influence on the defaulting
behaviour of the borrower



## Conclusions
- Borrowers with previous history of default is bigger indicator of default or loss
- Avoid approving higher value loans with previous default or history of single default
- Small business loans have been regulated and reduced
- Interest rates to spiked for loans with dti greater than 20
- Enable eligibility criteria for loan approval to be <30% of the borrower’s income
- As per heatmap, Location of the borrower definitely plays important role in driving default behaviour
- Also, default driving factors include ‘sub_grade’, ‘grade’, ‘int_rate’, and ‘addr_state’



## Technologies Used
- library - numpy 1.24.3
- library - pandas 2.0.3
- library - seaborn 0.13.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [@talrejar] - feel free to contact me!


