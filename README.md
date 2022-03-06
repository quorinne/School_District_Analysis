# School_District_Analysis



# Overview of School District Analysis


  We will be assisting another Data Scientist by the name of Maria in analyzing data on standardized test scores and school funding. Maria would like us to assist in analyzing this data in order to give insights on performance trends and patterns. These insights will be used by the school’s superintendent and other administrators to make informed decisions at the school and district level. 

    After analyzing the data, we have created several Data Frames to better view and process the information. 

### Average Math Score by grade
  ![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/MathbyGrade.png?raw=true) 
  
### Average Reading score by grade 
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/ReadingbyGrade.png?raw=true) 

### Top 5 and Bottom 5 Schools Before Changing 9th Grade Scores
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/ModuleTopBottom5.png?raw=true) 

### Top 5 and Bottom 5 Schools After Changing 9th Grade Scores
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/ChallengeTopBottom5.png?raw=true)

# Results
 
     *	Average math goes from 83.41% to 83.35%
     *	Average reading goes from 83.85% to 83.89%
     *	Passing math percentage goes from 93.27% to 93.18%
     *  Passing reading percentage goes from 97.31% to 97.02%
     *	Overall passing percentage goes from 90.95% to 90.63%
     *	Total school budget and Per Student Budget were not affected by the change of grades. 
     *	Thomas High School remains in second place performance wise regardless of 9th grade reading and math scores.
  
   One would usually expect the better scoring schools to have a higher budget per student, however, this is not the case with our dataframe. If you look to the Data Frame below you can see that the bottom 5 schools all had higher budgets per student when compared to the top 5 schools.
   
   ### School Performance based on budget per student
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/SpendingSummary.png?raw=true) 
   
   When looking at our Data Frame we noticed two explanations for this. If you look below at the School Type Data Frame you will notice that the top 5 schools are all Charter schools while the bottom 5 schools are all District schools. 
   
   
   ### School Performance based on type of school
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/SchoolType.png?raw=true) 

The other explanation is closely related to the previous. According to the School Size Data Frame below the top 5 schools are all smaller than the bottom 5 schools with presumably smaller class sizes and more student teacher interaction. 

### School Performance based on school size
![alt text](https://github.com/quorinne/School_District_Analysis/blob/main/Resources/SchoolSize.png?raw=true) 


# Summary

  According to the Data in out Top 5 Schools and Bottom 5 Schools Data Frames we can determine that overall performance was affected more by school type and population size than budget size. The top 5 schools are all smaller charter schools while the bottom 5 schools are all larger district schools. There is very little change in math and reading scores after replacing all 9th grade reading and math scores with NaN; the overall difference in less than .1% in math and less than .2% in reading. The larger change occurs within the reading scores. In the passing reading percentage there is a .19% increase after replacing the scores for the 9th graders. This in turn changes the overall passing percentage from 90.95% to 90.63% or .32%. 
