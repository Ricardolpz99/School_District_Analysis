# School District Analysis
## Overview of Project
An analysis of the district schools was carried out, the information was provided by the district authority Maria. In total there were 15 schools to be evaluated and 39,170 students. In the first instance, the school performance of all students was evaluated. However, Maria was notified that grades of ninth graders at Thomas High School were found to be dishonest.
We have now been asked to assess how removing the data for ninth graders affects our analysis.
## Results
### District Summary before and after data clean up
In the district analysis, seven district schools and 8 autonomous schools were evaluated, there are a total of 39,170 students and a budget of $24,649,428. The district summary was minimally affected by removing Thomas High School ninth graders' scores, the average math score went from 79.0 to 78.9, the percentage of people who passed math changed from 75 to 74.8, the percentage of students that passed reading passed from 86 to 85.7, finally the % overall passing passed from 65 to 64.9 (Figures 1 and 2).
#### Figure 1. District Summary after data clean up.
-------
![ District_summary_after.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/District_summary_after.png)
#### Figure 2. District Summary before data clean up.
-------
![ District_summary_before.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/District_summary_before.png)
### School summary before and after data clean up
While the district summary underwent very small changes due to the large number of students in the dataset. The school summary ends with a non-applicable value for the 9th-grade class.
The overall Effects of replacing the ninth graders’ math and reading scores on Thomas High School’s performance vs other schools
Thomas HS has a total of 1,635 students of which 461 are ninth graders, since this is a small population even compared to the one in the district, the summary of the school was affected in a greater proportion. the average math score went from 83.4 to 83.3, the reading score went from 83.8 to 83.9, which was an improvement, the % Passing Math went from 93.3 to 93.2, the %Passing Reading went from 97.3 to 97.0, finally the % Overall Passing changed from 90.9 to 90.6 (Figures 3 and 4)
#### Figure 3. ThomasHS summary after data clean up.
-------
![ ThomasHS_summary_after.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/ThomasHS_summary_after.png)
#### Figure 4. ThomasHS summary after data clean up.
------
![ ThomasHS_summary_before.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/ThomasHS_summary_before.png)
## Effects of replacing the ninth-grade scores in more details
### Math and reading scores by grade
Changing Thomas HS ninth graders' scores changed their math score from 83.6 to NaN and their reading score changed from 83.7 to NaN (Figure 5).
#### Figure 5. Math and reading ThomasHS 9th grade grades.
-------
![ ThomasHS_9th_before.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/ThomasHS_9th_before.png)

### Scores by school spending
Thomas High School is in $630-645 spending bucket, Due to the number of schools in this budget range, none of its values were affected and remained the same (Figure 6).
#### Figure 6. $630-645 Data frame.
-------
![ school_budget.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/school_budget.png)
### Scores by school size
Thomas HS is a medium-sized school, when making the adjustments previously described, no change in the data was observed. 
#### Figure 7. Size data frame
-------
![ size.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/size.png)
### Scores by school type
Thomas HS is a charter school and similarly no change is observed 
#### Figure 7. School type data frame
--------
![ school_type.png]( https://github.com/Ricardolpz99/School_District_Analysis/blob/main/Resources/school_type.png)
## Summary
1. Math and reading scores for ninth graders were eliminated.
2. By replacing the grades of the ninth grade students, the average of the math grades changed by one tenth.
3. The percentage of students approved regardless of each subject changed
4. The percentage of students who passed both courses changed
