# School-District-Analysis-Challenge
# Overview of the school district analysis
A school board and superintendent had initially tasked us with helping analyze data on student funding and student standarize testing results. We helped aggregate the data snd showcase trends in school performance. After being informed there was academic dishonety for the math and reading scores for ninth grades at Thomas High School, we replaced these values with NaNs and remove these students from any analysis, and kept the rest of score values intact. We repeated the school distric analysis and reported these changes to the original analysis on this report. This analysis will assist the school board and superintentdent in making desicions regarding the school budget and priorities.
The analysis performed were:
1. District Summary
2. School Summary
3. High and Low Performaing Schools
4. Math and Reading Scores by Grade
5. Scores by School Spending
6. Scores by School Size
7. Scores by School Type

# Resources
Data Source: students_complete.csv
Sotware: Python 3.6.1, Jupyter Notebook, 6.1.4

# Code
- The code used to analyze the elections with comments explaining each code line can be found here:
[PyCitySchools_Challenge.ipynb](https://github.com/arelysrsd87/School-District-Analysis-Challenge/blob/main/PyCitySchools_Challenge.ipynb)

## Purpose
# Results
## How each of the seven school districts metrics was affected by changes in the data
- The district summary is affected by having lower values for the % Passing Math, % Passing Reading and % Overall Passing. 
	- The % Passing Math dropped from 75.0 % to 74.8 % after removing the ninth graders students from Thomas High School.
	- The % Passing Reading dropped from 85.8 % to 85.7 % after removing the ninth graders students from Thomas High School.
	- The % Overall Passing dropped from 65.2 % to 64.9 % after removing the ninth graders students from Thomas High School.
- The school summary is affected by having higher values for the % Passing Math, % Passing Reading and % Overall Passing. This is a direct result of only looking at test results for Thomas High School students from 10th to 12th grade. 
	- The % Passing Math increased from 66.91 % to 93.19 % after removing the ninth graders students from Thomas High School.
	- The % Passing Reading increased from  69.66 % to 97.02 % after removing the ninth graders students from Thomas High School.
	- The % Overall Passing increased from 65.08 % to 90.63 % after removing the ninth graders students from Thomas High School.
- Replacing the ninth graders' math and reading scores with NaN values, improves Thomas High School performance relative to other schools. Thomas High School places second on Top Schools, after removing ninth graders' test scores.
- Replacing the ninth-grade scores affect the following:
- NaN values show up for Thomas High School ninth graders' math and reading results. No other results were affected.
- Thomas High School spending budget per student is $ 630 - $644. Looking specifically at how this bin performs , the % Passing Math, % Passing Reading and % Overall Passing increases after removing Thomas High School ninth graders' test score.
	- The % Passing Math increased from 73.5 % to 76.0 % after removing the ninth graders students from Thomas High School.
	- The % Passing Reading increased from 84.4 % to 86.0 % after removing the ninth graders students from Thomas High School.
	- The % Overall Passing increased from 63.9 % to 66.0 % after removing the ninth graders students from Thomas High School.
- No changes on the scores by school size after removing the ninth graders students from Thomas High School.
- No changes on the scores by school type after removing the ninth graders students from Thomas High School.
# Summary
## Four major changes to the school district analysis after reading the math scores have been replaced
- The district summary is affected by having lower values for the % Passing Math, % Passing Reading and % Overall Passing. This is a direct result of having a lower denominator value (lower student count by removing ninth graders from Thomas high School).
- The school summary is affected by having higher values for the % Passing Math, % Passing Reading and % Overall Passing. This is a direct result of only looking at test results for Thomas High School students from 10th to 12th grade. 
- 
- The bins analysis for school size and score type showed no changes due to 