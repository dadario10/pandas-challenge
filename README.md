# pandas-challenge
# PyCity Schools Analysis
### Analysis Summary: 

This report breaks down the PyCity Schools system in nine ways. The nine break downs are as follows: 
 - The District Summary
   - Total number of unique schools 
   - Total number of students 
   - Total budget
   - The average math score 
   - The average reading score 
   - The percentage of students who passed math
   - The percentage of students who passed reading 
   - The percentage of students that passed both math and reading 
   - A DataFrame for the above calculations called district_summary 
 - The School Summary
      - School name
      - School type
      - Total students
      - Total school budget
      - Per student budget
      - Average math score
      - Average reading score
      - The percentage of students who passed math
      - The percentage of students who passed reading
      - The percentage of students who passed math AND reading
 - Highest-Performing Schools
      - The top 5 Schools
 - Lowest-Performing Schools
      - The bottom 5 Schools
 - Math Scores by Grade
      - The average math score for students of each grade (9th, 10th, 11th, 12th) at each school
 - Reading Scores by Grade
      - The average reading score for students of each grade (9th, 10th, 11th, 12th) at each school
 - Scores by School Spending
      - The school performance based on average spending ranges per student
 - Scores by School Size
      - The school performance based on school size
 - Scores by School Type
      - The school performance based on the "School Type"
 ### Conclusions

Based on all the information in this analysis, I have come to 2 conclusions. The first is that the larger budgeted schools are connected to a lower overall passing rate while the schools with smaller budgets have a greater overall passing rate. This is made very clear by the fact that the highest overall passing rate of 91.334769\% is connected to a school with a budget of only `$1,081,356.00`. In comparison, the lowest overall passing rate of 52.988247\% is connected to a school with a budget of `$2,547,363.00`. these are not outliers as all the schools with top 5 overall passing rate have a budget equal to or under `$1,319,574.00`, while the bottom 5 schools have a budget equal to or greater than `$1,910,635.00`.
	
    
The second Conclusion I have made is that the Charter school type is a much more effective learning type than the District school type. The Charter school type have an overall passing rate of 90.432244\% while the District school type have an overall passing rate of 53.672208\%. Charter schools have less students in them and this could mean the students have more time with their teachers which leads to greater success. 
