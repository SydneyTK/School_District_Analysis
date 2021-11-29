# School_District_Analysis
Using Jupyter Notebook and programming in Python. Module 4. 

# Overview of the School District Analysis 
To help the scool board make decisions regarding budgets and priorities it was requested that analysis be done on the standardize test scores. Within this analysis it was asked that trends and patterns specifically be outlined by comparing the test reults to other school and student metrics. Overall the board is hoping to see trends in school and student's preformances. Unfortunately the grade 9 students at Thomas High School were not honest while taking the reading and math exams, so data manipulation had to be done to remove thier grades before fair analyisis could begin. 
# Results 
## How is the district summary affected?
-Metrics that were not affected by grades i.e.) total schools, total students, and total budget obviously stayed the same at 15, 39,170, and $24,649,428 respectfully 
-Averages and percentages were affected when the grade 9 grades from Thomas High School were removed, further detail can be found below.
![District_Summary.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources)  
## How is the school summary affected?
-This summary was not affected other than the data for Thomas High School, further details of the affect removing 9th grade marks had on the data can be found below. 
![School_Summary.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources)  
## How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
The average math and reading scores did not change when the 9th grade data was removed. The averages stayed the same at 83.350937 and 83.896082 respectfully. 
Thomas High School did not have a high percentage of students passing when the 9th grade reading and writing scores were included, they were some of the lowest in the school district:
-The percentage of students passing math was 66.911315	
-The percentage of students passing reading was 69.663609
-Finally the overall passingpercentage was 65.076453
The above metrics greatly increased when the dishonest data was removed: 
-The percentage of students passing math was 93.185690
-The percentage of students passing reading  97.018739
-Finally the overall passingpercentage was 90.630324
![By_School_Preformance.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources)  
## How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
-other than having the NaN value appear for the Thomas High School 9th graders all the other grades math and reading scores are the same
![Math_By_Grade.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources) 
![Reading_By_Grade.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources) 
### Scores by school spending
- as Thomas High School was in the $630-$644 spending bucket only those average math, average reading, percentage passing math, percentage passing reading and overall passing percentage were changed. 
-most noticebly the a verave reading score increased from 78.5 to 81.6.
![Spending_Ranges.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources) 
### Scores by school size
- Thomas High School was always a medium sized school, 1000-2000 studnets with or without the grade nines included 
- the most noticable change when looking at the metrics by school size is the increase in the average reading score to 83.9 when the nith graders were removed
-the large school size reading average increaed as well to 81.3, most likely due to the lower total student denominator 
![By_School_Size.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources) 
### Scores by school type
- as Thomas High School is a charter school these sumary statistics are the only ones affected
-most noticably the reading scores increased from 83.5 to 83.9
-the district schools reading average increaed as well to 8 from 77, most likely due to the lower total student denominator 
![By_Type.JPG](C:\Users\Sydney Kieswetter\Class\School_District_Analysis\Resources) 
# Summary
When the Thomas High School 9th grade scores were removed some changes were:  
-average reading scores when analysing them by school type, size or spending were the statistic most consistantly and greatly affected
-by grade reporting became more difficult as there would now be a null value. 
-by reducing the number of students our denominator of total number of students in the district did slightly reduce. The impact of this was noticed when looking at smaller buckets like large school types, or disteict schools.
-with the grade 9's include Thomas High School would have been reported as one of the lowest preformaing schools, but switched to one of the highest after the dishonest grades were removed. 
