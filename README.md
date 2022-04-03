# School Distict Analysis

## Overview of the School District Analysis
In this project, student funding and student standardized test scores within a school district will be analyzed to provide insights about performance trends and patterns while dealing with academic dishonesty and at the same time upholding state-testing standards. Key metrics for district and school will be generated, specifically, the following information will be illustrated:
- Top 5 and bottom 5 performing schools, based on the overall passing rate
- The average math score received by students in each grade level at each school
- The average reading score received by students in each grade level at each school
- School performance based on the budget per student
- School performance based on the school size 
- School performance based on the type of school 

## Results
Due to academic dishonesty found within ninth-graders with respect to their reading and math scores in Thomas High School, both of the scores needed to be replaced with NaNs in order to uphold state-testing standards. This section tackles the change in results by replacing the scores with NaNs for Thomas High School.

- How is the district summary affected?
    - Majority of the disctict summary scores has decreased due to the replacement of scores with NaNs. Specifically, the avarage math score has decreased from 79.0% to 78.9%, average reading score stayed the same (81.9%), the percentage of students that passed Math has also decreased from 75% to 74.8%. Similarly, the percemtage of students that passed reading has decreased from 86% to 85.7& and lastly, the percentage of overall passing has decreased from 65% to 64.9%. Please see the illustration below for before and after. 
    
![District Summary Results Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/District_Summary_BeforeNaN.png)
![District Summary Results Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/District_Summary_AfterNaN.png)

- How is the school summary affected?
    - The scores in the school summary were also affected by academic dishonesty. As illustrated by the table below, after replacing the scores with NaNs, the average math and reading scores experienced decline in values. Similarly the % passing math, % passing reading, and % overall passing have also decreased in values by a small percentage. 
![School Summary Results Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/School_Summary_BeforeNaN.png)
![School Summary Results Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/School_Summary_AfterNaN.png) 

- How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
    -Although the math and reading scores were replaced for ninth graders' in Thomas High School, the school's performance did not change relative to the other schools. The scores may have decreased by a few percentage, however, Thomas High School is still placed second, despite the change. This implies that the change had a minimal effect to the school's overall performance in comparison to the other schools. 
![Top Schools Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Top_Schools_BeforeNaN.png)
![Top Schools Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Top_Schools_AfterNaN.png)

- How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
        - Replacing the ninth-grade scores did not have an effect on math and reading scores by grade as illustrated by the table below. 
![Math Scores by Grade Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Math_Scores_byGrade_AfterNaN.png)
![Reading Scores by Grade Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Reading_Scores_byGrade_AfterNaN.png)
    - Scores by school spending
        - The % 0verall passing were the only one affected by the replacement. Specifically, for budgets less than $584 and $585-$629, the % overall passing increased by 0.4% while for budget of $630-$644, the % overall passing decreased by 0.2% and lastly for budget of $646-$675, the % overall passing declined by 0.5%. 
![School Spending Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Spending_BeforeNaN.png)
![School Spending Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Spending_AfterNaN.png)
    - Scores by school size
        - The scores by school size were not affected by the replacement of the ninth-graders' scores. 
![Score by School Size Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Size_BeforeNaN.png)
![Score by School Size Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Size_AfterNaN.png)
    - Scores by school type
        - The scores by school type were also not affected by changing the scores of ninth-graders with NaNs.
![Score by School Type Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Type_BeforeNaN.png)
![Score by School Type Snapshot](https://github.com/kntln/School_District_Analysis/blob/main/Resources/Scores_by_School_Type_AfterNaN.png)

## Summary
To conclude, after replacing the math and reading scores for the ninth grade at Thomas High School, the following changes occured, first, majority of the scores in the district summary decreased with the exception of average reading score. Second, the school summary scores also experienced a decline in values by a small percentage. Third, the % overall passing by school spending experienced an increase of 0.4% for for budgets less than $584 and $585-$629.Lastly, for budget of $630-$644, the % overall passing decreased by 0.2% and for budget of $646-$675, the % overall passing declined by 0.5%. 
