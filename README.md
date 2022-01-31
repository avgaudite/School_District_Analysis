# School_District_Analysis

## Overview

### Purpose

To help Maria, Chief Data Scientist for a City School District, analyze data on student funding and students' standardized test scores, and aggregate the data to showcase trends in school performance. This analysis will help the school board and superintendent in making decisions regarding budgets and priorities.

### Results

The analysis was undertaken twice due to academic dishonesty affecting the ninth graders' marks, the result being that the math and reading marks of the ninth graders from Thomas High School were relabelled as NaNs.

![](https://i.imgur.com/Gma0Vu7.png)
![](https://i.imgur.com/j0Qfq2C.png)

461 records were affected out of 39170. The noticeable difference lay in what was decided for the compromised marks.
![](https://i.imgur.com/Cq3JNUA.png)
![](https://i.imgur.com/4A1QtbE.png)



If NaNs are included in the calculations, Thomas High School is no longer a top five school with a 65.1% overall passing percentage.

If NaNs are omitted from the calculations, Thomas High School remains a top five school with a 90.6% overall passing percentage. Changes (of several tenths of a percentage drop) was also seen in the: 

1. Average Math and Reading Scores
2. Percentage of Students passing according to Math and Reading Scores 
3. Overall percentage of students who passed both Math and Reading
4. Spending Range for "% Overall Passing".

"Total Students" was unaffected.

It is up to the board and superintendent to decide whether these are noticeable differences.

### Summary

The status of Thomas High School as a top-performing school hinges on the approach to NaNs: if we consider the ninth graders' NaNs as essentially zeroes, then Thomas High School is a bottom-five school. If they are not included in the calculations, Thomas High School maintains its spot in the top five in the district.


