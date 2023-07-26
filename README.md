Pandas_challenge

Contributor: Clover McLaughlin

This repository contains the code and data for an analysis of student performance and different school performance in the district. The analysis was performed using Python and the Pandas library within a Jupyter Notebook.

Overview
The main objective of this analysis is to gain understanding of the educational performance of different schools in the district. The analysis takes many factors that may influence student achievement into account, such as: budgeting, school size, budget per student capita, etc. The analysis is based on two datasets: one containing information on schools, their sizes, and budgets (school_complete.csv), and the other containing data on student performance, including math and reading grades (student_complete.csv).

Analysis Steps

Data Loading: Load (school_complete.csv) and (student_complete.csv) into Panda DataFrame and merge these 2 files to create school_data_complete data frame

District and School Summary: Calculate the total number of schools, students, and the district's budget. Compute the average math score, the average reading scores, % of students that have math score, reading score, and overall score over 70.

Highest and Lowest Performing Schools: Identify the top 5 highest performing schools and the bottom 5 schools based on overall passing rates.

Comparison of Scores Across Grades: Analyze student scores in math and reading across different grade levels to identify trends.

Impact of School Spending: Investigate the relationship between school spending per student and student achievement.

Influence of School Size: Examine the impact of school size on student performance.

Sccores by School Type: Compare the performance of charter schools and district schools.

Output: 
	Create csv output files including and saved under Output folder
	- district_summary.csv
	- per_school_summary.csv
	- Top5_Best_School.csv
	- Bottom5_school.csv
	- Math_score_by_grade.csv
	- reading_scores_by_grade.csv
	- spending_summary.csv
	- size_summary.csv
	- type_summary.csv

Results and Findings

1. Charter schools vs public schools: 

There is 15 schools this district; 8 of which are charter schools and the other 7 schools are public school. Charter schools have lower numbers of students compared to public schools. Charter schools consistently outperform public schools across different measures including: average math score, average reading score, % of students that have math score, reading score, and overall score over 70. Lastly, all top 5 performing school are charter school, and bottom 5 performing school are public school.  

2. Testing score across different grade

Testing score (Math and Reading) remains consistent across different grades (9th - 12th).

3. Spending vs performance

Spending Ranges (per school) and average test score (math and reading) has an inverse relationship indicating schools with small budget per student outperform schools with largers budget per student.





