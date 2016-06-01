# README.md
VAhir  
May 27, 2016  

**What**   
The purpose of this project is to provide insights into rolling sales data from 1 of the five boroughs of NYC - *Queens*.
Following transformation/formatting was done on this data :  
  + a)  Date columns were converted to "YYYY-MM-DD" format.  
  + b)  Records with missing sale price were identified and excluded.  
  + c)  Outliers were identified and excluded.  

**Directory Structure**  
Following is the directory structure for this project:  
  
             Root --> README.md
              |
              |------> Data
              | 
              |------> Analysis
              |
              |------> Paper  

In order for to execute this project without issues, you need to have above directory structure on local drive.  


**How**  
 Queens rolling sales data for performing analysis is downloaded using following link :   
http://www1.nyc.gov/home/search/index.page?search-terms=Rolling+sales+update

The data from website is stored as "raw" data in Data directory of the project's repository.  
File Name : **../data/RawSalesDataQueens.csv**

Later following R scripts are used to load this data, analyze it and then output formatted/filtered data.  
The final output data file "FinalQueensData.csv" will be then be used for various graphs/charts.  

File Name :  
**../Analysis/CorrectingDataTypes.R**  
**../Analysis/RemovingOutliers.R**





              
