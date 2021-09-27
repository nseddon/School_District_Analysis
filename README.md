# School_District_Analysis

## Overview of the school district analysis: 
The original purpose of the analysis was to determine key district metrics for the school system.  The defined metrics to be measured included:
     - Top 5 and bottom 5 schools, based on passing rates.
     - Average math score received by students in each grade level.
     - Average reading score received by students in each grade level.
     - School performance based on budget per student.
     - School performance based on the school size.
     - School performance based on the type of school.
    
Upon completion of the analysis, possible academic dishonesty was alleged amongst 9th graders of Thomas High School.  Upon request by the board, 
the following was performed:
    - replaced all 9th grade test scores exclusively for Thomas High School with NaN (Not Available Now).
    - Re-perform the above original analysis with this altered data.
    - Determine the overall impact of the removal of these scores for the school and the district.

## Resources
- Data Source: schools_complete.csv, students_complete.csv
- Software: Python 3.7.6, Anaconda 4.10.1

## Results: 
### How is the district summary affected?
Original Analysis District Summary
![Original_district_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_district_summary.PNG)

Updated Analysis District Summary
![Updated_district_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_district_summary.PNG)

By removing the 9th grade class from the testing results, the district overall saw a minor decrease in the average testing scores in math, with no deviation in the average for reading.  However, the passing percentage of both math and reading showed a slight decline, with an overall passing percentage reduction by 0.1%.

### How is the school summary affected?
Original Analysis School Summary
![Original_per_school_averages.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_per_school_averages.PNG)

Updated Analysis School Summary
![Updated_school_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_school_summary.PNG)

It can be seen that Thomas High Schools average Math and Reading Scores both decrease as a result of the removal of the 9th grade scores.  No scores were impacted at other schools.

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
Original Top Schools Summary
![Original_top_schools_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_top_schools_summary.PNG)

Updated Top Schools Summary
![Updated_top_school_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_top_school_summary.PNG)

Even with the reduction removal of the 9th grade scores, Thomas High School still remained in the top 5 schools for overall performance.

Original Bottom Schools Summary
![Original_bottom_schools_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_bottom_schools_summary.PNG)

Updated Bottom Schools Summary
![Updated_bottom_schools_summary.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_bottom_schools_summary.PNG)

There was no impact on the bottom five schools as a result of the removal of Thomas High School 9th grade data.


### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
Original Math Scores by Grade
![Original_math_scores_by_grade.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_math_scores_by_grade.PNG)

Updated Math Scores by Grade
![Updated_math_scores_by_grade.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_math_scores_by_grade.PNG)

Original Reading Scores by Grade
![Original_reading_scores_by_grade.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_reading_scores_by_grade.PNG)

Updated Reading Scores by Grade
![Updated_reading_scores_by_grade.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_reading_scores_by_grade.PNG)

We can see that the original scores of the 9th grade class were in line with the other grades being reported from Thomas High School.  As stated above, Thomas High School did have a slight decline in their average scores in both math and reading, and a slight declined in their passing percentage.  This change was not enough to affect their overall rank versus other schools in the system.

#### Scores by school spending
Original Schools by Spending
![Original_scores_by_spending.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_scores_by_spending.PNG)

Updated Schools by Spending
![Updated_scores_by_spending.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_scores_by_spending.PNG)

There was no apparent change in the overall scores per spending with the adjusted total students from removing the 9th grade scores.

#### Scores by school size
Original Scores by School Size
![Original_scores_by_size.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_scores_by_size.PNG)

Updated Scores by School Size
![Updated_scored_by_size.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_scored_by_size.PNG)

There was no apparent change in the overall scores by school size with the adjusted total students from removing the 9th grade scores.

#### Scores by school type
Average Scores by School Type
![Original_scores_by_type.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Original_scores_by_type.PNG)

Average Scores by School Type
![Updated_scores_by_type.PNG](https://github.com/nseddon/School_District_Analysis/blob/main/Resources/README%20examples/Updated_scores_by_type.PNG)

There was no apparent change in the overall scores by school type with the adjusted total students from removing the 9th grade scores.

## Summary: 
In summary, the original analysis showed a higher math average score and reading average score for Thomas High School.  With the replacement of the 9th grade scores with NaNs, the only noticeable change was for Thomas High Schools internal scores, and all three passing percentages.  Since the total student count for the district was adjusted as a result of removal of the 9th graders from Thomas High, no noticeable impact was seen on the total District scores.

Future analysis should consider a secondary analysis, maintaining the full student count of the District to note the impact of the removal on the District as a whole.
