**1.	HOW DO THE HIGHEST RANKED UNIVERSITIES STACK UP AGAINST THEIR FACULTY STUDENT RATIO? ALSO WHAT IS THE OVERALL CORRELATION COEFFICIENT? 
**
Within the SELECT statement of the Query, i incorporated the university rank and faculty-student ratio into the SELECT statement, followed by applying the ORDER BY function to arrange the results based on rank in ascending order


**2.	WHICH UNIVERSITIES HAVE AN OVERALL SCORE THAT IS GREATER THAN THE AVERAGE OVERALL SCORE?
**
I used a nested query whereby the inner query utilized the AVG function to initially calculate the average overall score. Subsequently, I constructed an outer query in which i utilized the WHERE statement to filter scores that were below the average as determined by the inner query.


**3.	WHAT ARE THE TOP RANKED UNIVERSITIES AND HOW DO THEY COMPARE AGAINST THE EMPLOYMENT OUTCOME METRIC? 
**
The query I ran, utilized the SELECT statement to list the university rank and employment outcomes, and the ORDER BY function was employed to arrange the rank results in ascending order.


**4.	HOW DO UNIVERSITIES WITH THE HIGHEST INTERNATIONAL RESEARCH NETWORK MATCH UP AGAINST THE UNIVERSITY RANKINGS? 
**
To execute Query, I selected 3 relevant columns i.e. university, rank and international research network. Finally, i arranged them in ascending order using the ORDER BY function and applied the LIMIT function to restrict output to the 20 top universities.


**5.	WHAT IS THE SUSTAINABILITY OF UNIVERSITIES WITH THE HIGHEST ACADEMIC AND EMPLOYER REPUTATION?
**
To execute the Query, I selected 3 relevant columns i.e. university, rank and international research network. Finally, i arranged them in ascending order using the ORDER BY function and applied the LIMIT function to restrict output to the 20 top universities.



















