# School_District_Analysis
The school board has has brough tto light of possible evidence of acedemic dishonesty, highlighting two specific areas in academics, reading and math. Due to this evidence, the school has hired an outside resource to look nto the data to prove or disprove the allegations.  They do not know of the full extent of the a;;egations, but in order to uphold the the state testing standard, they have have hired a 3rd party to dig into the data to see what it reveals.

The school board has requested the following deliverables:
1. District Summary snapshot in a table format
2. School summary in a table format.
3. Thomas High School math and reading scores.
4. Spending
    - Results by school size
    - Results by school type


## Development Platforms

 - Jupyter Notebook
 - Python v 3.7.6
 - Pandas library
 - Numby Library

## Resources
 - schools_Complte.csv
 - students_complete.csv

## Results



### District Summary

![image](https://user-images.githubusercontent.com/94253815/146627702-6e947c5d-023f-459f-8cdd-75e820fab993.png)




### School Summary

![image](https://user-images.githubusercontent.com/94253815/146627726-d0e3c462-44a1-419b-9f15-fc1b7ffbc249.png)


### Thomas High School Math scores
Math scores were placed in NaN (not a number) so there was not impact on the claculating the scores. There was no placement of the "0" because it would have negative impact on the results. As noted in the table below, the ninth grade results were placed in a NaN. The following are the results by grade:
 - 9th Grade - NaN
 - 10th Grade - 83.1
 - 11th Grade - 83.5
 - 12th Grade - 83.5
 
![image](https://user-images.githubusercontent.com/94253815/146628529-ee026620-154c-406d-9f06-5ce9f4ed2fc8.png)
![image](https://user-images.githubusercontent.com/94253815/146685694-7e0e8c43-03cc-4ae3-88c7-ec92e37351b0.png)

### Thomas High Scool Reading scores
Just like the math scores, the reading scores were analized the same way.  As a result, the 9th grade reading scores were also placed in a NaN value.  As noted in the table below, the following are the results by grade:
 - 9th Grade - NaN
 - 10th Grade - 84.3
 - 11th Grade - 83.6
 - 12th Grade - 84.3
 
![image](https://user-images.githubusercontent.com/94253815/146628530-962123cd-a561-4264-a2b1-7445ee3b2da8.png)

![image](https://user-images.githubusercontent.com/94253815/146685740-d336a368-04f6-42fa-a86c-9c9824d8bd4f.png)


## Spending


### Results by School size
By analizing the table below, it appears that that when schools spend between $551  - $600 per student, their performance is better.

![image](https://user-images.githubusercontent.com/94253815/146687944-f85c2bf6-40fa-415e-91dc-9d1b9e9f6be2.png)




### Results by School Type
After analizing the data, it appears that charter schools perform betther than district schools
![image](https://user-images.githubusercontent.com/94253815/146628707-b84e640b-5579-4c09-9b05-0a0abeab71fe.png)

Small and meduim schools are similar in overall performance
![image](https://user-images.githubusercontent.com/94253815/146688223-60e4bd2a-9877-4748-9c80-015ef3ac1c50.png)


### Summary
In looking at the total data gathered for the district, and using that to see where Thomas High school scored, here is what was found:
 - Total students in district vs THS - THS has 4% of the total student headcount
 - Also THS has 4% of th total district budget
 - Avg Math score in the district= 78.9% - THS is 83.3%.  Above the district avg.
 - Avg Reading score in the district = 81.9% - THS is 83.8$.  Above the district avg
 - Avg % passing Math in district = 74.8% - THS is 66.9% . Below the district avg.
 - Avg % reading Math in district = 85.7% - THS is 69.6% . Below the district avg.
 - Overall passing % in district = 64.9% - THS is even at 65.0%


