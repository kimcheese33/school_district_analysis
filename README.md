# School District Analysis
## Overview

The purpose of the module was to analyze school district data to determine how various factors, such as school size, budget, and type can effect math and reading scores. The purpose of this challenge was to analyze how removing data, math and reading scores from 9th graders at Thomas High School, would affect our outcomes. We also learned how pandas and jupyter notebook can be used to perform various analyses on a large dataset. We were able to clean and slice and dice the data using dataframes and various methods to present the data in different ways. 

## Results

- How is the district summary affected?

In the district summary, Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing were slightly affected when looking at the values rounded to the tenths place. Total Schools, Total Students, Total Budget, and Average Reading Score were unaffected. In the new district summary, the columns that were affected were slightly lower:

Old District Summary:

<img src="https://github.com/kimcheese33/school_district_analysis/blob/main/Images/old_district_summary.png" width=700" height="100" />

- How is the school summary affected?

After removing the scores, the new district school summary score-related values for Thomas High School increased pretty significantly. The scores went from the 60s range to the 90s range, failing to passing as shown below:


- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Replacing the scores for Thomas High School resulted in them being placed in the top five best scoring schools in the district:



- How does replacing the ninth-grade scores affect the following:

  - Math and reading scores by grade
   
   The values were the same except the 9th grade value for Thomas High School shows 'nan' instead of a grade value.

  - Scores by school spending
  
   Since Thomas High School falls in the $630-644 spending range per student, the only values that changed were for that row. The values in the new analysis were slightly lower except for Average Reading Score.

  - Scores by school size
  
  Since Thomas High School falls in the Medium school size, the only values that changed were for that row. The values in the new analysis were slightly lower except for Average Reading Score.

  - Scores by school type
  
  Since Thomas High School is a Charter school, the only values that changed were for that row. The values in the new analysis were slightly lower except for Average Reading Score.


## Summary

