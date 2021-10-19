# School-District-Analysis

## Prjoect Overview
The purpose of this project is to analyze a dataset from a local school district after it was discovered that Thomas High School's 9th grade test scores had been altered. The dataset contains information about each school's name, type, size and budget, and each student's name, school, gender, math score and reading score. The statistics we want to obtain from the newly modified dataset include total budget per school, per student capita, average math score per school, average reading score per school, the percentge of students who passed math and reading per school, and the overall passing percentge per school. We also want to determine how school type (charter vs district), school size and per student spending effects math and reading test scores. 

## Results
- For the district summary, removing the math and reading test scores for 9th graders from Thomas High School slightly increased the percent of overall students passing reading and math. Aside from that, the district summary changed very little. 
- For the school summary, the only data that was affected was Thomas High School's reading and math scores. Otherwise, the summary for all other schools remained the same. (Images of the school summaries before and after data from Thomas High School was omitted are displayed below.) 
- Replacing the Thomas High School 9th grade scores didn't change math and reading scores for any other grade or school. Altering the data for Thomas High School also didn't change the results for math and reading scores by school spending, school size or school type. 

School summary before Thomas High School data was omitted:
![original summary](https://github.com/mayamtims/School-District-Analysis/blob/main/Resources/original_per_school_summary.png)

School summary after Thomas High School data was omitted:
![ommitted summary](https://github.com/mayamtims/School-District-Analysis/blob/main/Resources/post_per_school_summary.png)


## Summary
Because the number of 9th graders at Thomas High School is very small compared to the total amount of students in the district, removing this class did not impact the results of the analysis very much. However, this change did minimally alter the results of the average reading scores, the average math scores, the percentage of students who passed reading at Thomas High School and the percentage of students who passed math at Thomas High School. 