# School_District_Analysis

The PyCitySchools_Challenge.ipynb was created to compare (as directed by the Module 4 challenge) the effects of removing the Thomas High School's 9th Graders' math and reading scores from the database to the database with no data removed.  As such, we will answer the following questions:

How is the district summary affected?  Average math score drops from 78.99 to 78.93, average reading score drops from 81.88 to 81.86, the Percent passing math drops from 74.98 to 73.88, the percent passing reading drops from 85.81 to 84.65, and overall passing drops from 65.17 to 64.09 percent.  

How is the school summary affected?  By removing the Thomas High 9th grader scores, the top chools for overall passing percentage changes.  The top 3 before the 9th graders were removed were Cabrera, Thomas, and Griffin.  After the scores were removed, the top 3 became Cabrera, Griffin, and Wilson.  The bottom 3 were originally Rodriguez, Figueroa, and Hoang and removing the Thomas scores did nothing to change that.  

How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance, relative to the other schools?  Removing the scores drops Thomas down in overall passing percentage from 2nd to 8th overall of the 15 schools.

How does replacing the ninth-grade scores affect the following?
Math and Reading Scores by Grade: Removing Thomas takes them from the 3rd best at math and 5th highest at reading scores for 9th graders to a NaN where they are now out of the order.  

Scores by School Spending: Removing the scores drops the overall passing percentage for schools that spend between $640-$644 per capita down from 62.86 to 56.39%.

Scores by School Size: The Overall Passing Percentage for medium-sized schools drops from 90.62 down to 85.44%

Scores by School Type:: The Overall Passing Percentage for Charter schools drops from 90.43 to 87.19%.  
