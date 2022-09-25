# PyCity-Schools-Challenge
## Overview
The purpose of the analysis is to assess several aspects of two data files showing school and student data for PyCity high schools. Specifically for the Challenge assignment, the files had to be reevaluated to replace math and reading scores for 9th grade students at Thomas High School, which appear to show signs of academic dishonesty and potentially skewed testing results. Once the math and reading scores for this subset of students at Thomas High School were replaced with NaN values, the client requested the school district analysis be repeated and a written report be submitted describing how these changes affected the original overall analysis.<br />
<br />The analysis included data across 15 schools, 39,170 students, and a budget for the school district of $24,649,428.00. The original data sets provided by the client include [schools_complete.csv](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f1cf64828634a90e3ce69653bb5f2b4f88333695/Resources/schools_complete.csv) and [students_complete.csv](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f1cf64828634a90e3ce69653bb5f2b4f88333695/Resources/students_complete.csv), both located within the Resources folder. 
## Results: Using bulleted lists and images of DataFrames as support, address the following questions.
- How is the district summary affected?<br />
    The total schools, total students, total students remained the same, however the percentage of students passing math, reading and both math and reading decreased by <=1 percentage point each, which is significant given that fewer than 500 student grades for 9th graders at Thomas High School could shift the percentage passing in both subjects and overall for the entire school district of more than 39k total students. 
    ![Chart 1](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f35a753ba8d4ea3dc225879ecef78d9b718560af/Challenge_Screenshots/new_district_summary.png)

- How is the school summary affected?<br />
    The instructions for this Challenge assignment were extremely  unclear and I was unable to update the school summary. In the interest of time, I had to turn this assignment in so that I do not get further behind in class. 
- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    It didn't. I was unable to replicate the changes I made to my calculations in the tables. 
- How does replacing the ninth-grade scores affect the following:
    - Reading Scores by Grade<br />
        ![Chart 5](https://github.com/banasibb/PyCity-Schools-Challenge/blob/9b85f2b0907c7580334d3a463cd31af0bcf30e74/Challenge_Screenshots/new_Reading_Scores_by_grade.png)
    - Math Scores by Grade <br />
        ![Chart 6](https://github.com/banasibb/PyCity-Schools-Challenge/blob/9b85f2b0907c7580334d3a463cd31af0bcf30e74/Challenge_Screenshots/new_math_Scores_by_grade.png)
    - Scores by school spending<br />
        ![Chart 3](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f35a753ba8d4ea3dc225879ecef78d9b718560af/Challenge_Screenshots/new_spending_summary_df.png)
    - Scores by school size<br />
        ![Chart 2](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f35a753ba8d4ea3dc225879ecef78d9b718560af/Challenge_Screenshots/new_size_summary_Df.png)
    - Scores by school type<br />
        ![Chart 4](https://github.com/banasibb/PyCity-Schools-Challenge/blob/f35a753ba8d4ea3dc225879ecef78d9b718560af/Challenge_Screenshots/new_type_summary_Df.png)

## Summary: Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- After removing the 461 9th graders from Thomas High School, the total number of students included in the student data analysis dropped to 38,709 (note this is distinct from the total number of students included in the school data set and analysis).
- The original percentage of students passing math was 74.98% and changed to 74.76%. <br />
- The original percentage of students passing reading was 85.81% and changed to 86.83%. <br />
- The original percentage of students passing math and reading was 65.17% and changed to 64.85% <br />
