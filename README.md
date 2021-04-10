# pandas-challenge
Bootcamp Pandas Homework 04/19/2021


## Pycity Schools
### Overview
This project took the information about schools and their students reading and writing scores to do analysis on the 
average pass rates. Analysis performed in this included:
1. Top and Bottom Schools by Average Total Students Passed
2. Average Score by Grade

Analysis was also performed on the relation between the scores per school and the following:
1. Average School Spending Per Student
2. School Size
3. School Type

### Group Definitions
#### Average School Spending Per Student
This metric was found by taking the total budget and dividing by the total number of students. The results were grouped 
together into the following groups:
- $575-$600
- $600-$625
- $625-$650
- $650-$675

#### School Size
This metric was found using the total number of students. The results were grouped together into the following
- Small - Less than 1,000 students
- Medium - Between 1,000 and 2,000 students
- Large - Between 2,000 and 5,000 students

#### School Type
This metric was found using the classification for each school. The results were grouped together into the following:
- District
- Charter

### Observations/Trends
1. Charter school students are more likely to pass than district school students. The average pass rate for charter schools was 90.43% compared to 53.67% for district schools.
2. There was a negative trend between average spending and school performance. Schools who spent more per student had worse results.
    - This trend seems more skewed by school type again. Charter schools tended to spend less money than district schools.
    - However, when broken out by school type. Charter schools had a positive relationship when spending more. District schools had a negative relationship when spending more.


