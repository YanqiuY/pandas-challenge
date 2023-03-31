# pandas-challenge

## Summarizes the analysis
### Method Used
1.Using Pandas  and Python to imput csv file and read in jupyter notebook.
2.Using dataframe, groupby to sort and clean the data as needed.

### Calculating Process
1.merged the school and student csv file
2.categorized the data by district, school and made a summary dataframe
3.Based on overall passing, pick the top 5 high performance and low performance schools.
4.Based on different grades, summarized different scores on reading and math.
5.Calculated the data of scores by school spending, school type and school size.

### Results and Conclusion

1. District Summary

![Image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/District%20Summary.png)

The analysis is based on 15 schools, 32,715 students in the district. We have the summary of total budget, average scores and overal passing rate for those 15 schools and their students.
***
<br>

2. School Summary

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/School%20Summary.png)

From school summary table, we can have the information of their school type, total students and school budget of each school, then we could get per studnet budget in one chart. Also we could see the average math & reading scores and overall passing rate of each school.
***
<br>

3. Highest-Performing School(by %ovarall pass)

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Highest-Performing%20Schools%20(by%20%25%20Overall%20Passing.png)

Top 5 high performance shool based on overall passing rate. Their school type are Charter.
***
<br>

4. Bottom-Performing School(by %ovarall pass)

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Bottom%20Performing%20Schools%20(By%20%25%20Overall%20Passing.png)

Top 5 bottom performance shool based on overall passing rate. Their school type are District.
***
<br>

5. Math Scores by Grade

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Math%20Scores%20by%20Grade.png)

6. Reading Score by Grade

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Reading%20Score%20by%20Grade.png)

7. Scores by School Spending

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Scores%20by%20School%20Spending.png)

The less on spending per student, the higher score performance
***
<br>

8. Scores by School Size

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Scores%20by%20School%20Size.png)

Smaller school size, higher score performance
***
<br>

9. Scores by School Type

![image](https://github.com/YanqiuY/pandas-challenge/blob/main/Pics/Scores%20by%20School%20Type.png)

The "Charter" school type has higher score performance than "District" school type

## Draws two correct conclusions or comparisons from the calculations

1. The school type of highest-performance shools is charter, which is same as the results of "Scores by School Type"
2. Among all 15 schools, Average reading score is higher than average math score
3. The total shool budget of Highest-performance school is lower than Bottom-performance school.
