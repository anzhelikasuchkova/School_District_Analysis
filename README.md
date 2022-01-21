# School District Analysis

## Project Overview
Analysis on high school district performance using Jupyter Notebook with Python, Pandas Library, and Numpy Library. 

1. How is the district summary affected?
2. How is the school summary affected?
3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
4. How does replacing the ninth-grade scores affect the following:
    - Math and reading scores by grade
    - Scores by school spending
    - Scores by school size
    - Scores by school type

## Resources
- Data Source: schools_complete.csv
- Data Source: students_complete.csv
- Sofware: Jupyter Notebook 6.4.5
- Library: Pandas
- Library: Numpy
- Language: Python 3.9.7

## Analysis Results
### 1. How is the district summary affected?

Original District Summary
<img width="935" alt="Original District Summary" src="https://user-images.githubusercontent.com/93845867/150443554-1bc1884e-cabe-405d-8754-2c985516ce98.png">

Updated District Summary
<img width="930" alt="Revised District Summary" src="https://user-images.githubusercontent.com/93845867/150443559-f1e696d4-4417-4a9e-8905-e9117d8ae677.png">

- **Average Math Score** decresed by 0.1%. 
- **Average Reading Score** stayed the same. 
- **% Passing Math** decreased by 0.2%. 
- **% Passing Reading** decreased by 0.1%. 
- **% Overall Passing** decreased by 0.3%. 

### 2. How is the school summary affected?

Original School Summary
<img width="994" alt="Original School Summary" src="https://user-images.githubusercontent.com/93845867/150446501-0f57dad4-c761-4566-81f1-78da7354417b.png">

Updated School Summary
<img width="998" alt="Revised School Summary" src="https://user-images.githubusercontent.com/93845867/150446817-3ad01200-005d-4d8b-8285-434d59eb4bd4.png">

Removing the 9th grade students from the data set had a large impact by dropping from **91%** to **65%** for the overall passing rate.

### 3. How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?

Original Thomas High School’s Performance Relative to Other Schools
<img width="999" alt="Original Schools" src="https://user-images.githubusercontent.com/93845867/150452993-6d6ce214-0a54-46f6-8208-bfae487628ca.png">

Updated Thomas High School’s Performance Relative to Other Schools
<img width="1003" alt="Updated Schools" src="https://user-images.githubusercontent.com/93845867/150453018-910ebf31-1818-4829-a8e1-30d6eece3a1e.png">

Original Top 5 Schools 
<img width="991" alt="Best Schools Original" src="https://user-images.githubusercontent.com/93845867/150453835-efe7d389-139f-4873-9870-91fd405d610f.png">

Updated Top 5 Schools
<img width="999" alt="Updated Best Schools" src="https://user-images.githubusercontent.com/93845867/150453858-b4bd74a4-09d3-4dc8-a7e5-74714f23059c.png">

- The overall passing percentages of Thomas High School decreased. 
- School's overall standing didn't change.

### 4. How does replacing the ninth-grade scores affect the following:
- Math and reading scores by grade

Original Math Scores

<img width="307" alt="Original Math Avg" src="https://user-images.githubusercontent.com/93845867/150454974-2b61915b-5d70-4114-9bad-f13a16e04ed5.png">

Updated Math Scores

<img width="309" alt="Updated Math Avg" src="https://user-images.githubusercontent.com/93845867/150454998-3eb7c688-5d81-4acc-8b22-ed2128321ac7.png">

Original Reading Scores

<img width="314" alt="Original Read Avg" src="https://user-images.githubusercontent.com/93845867/150455017-3b5bc7e2-e1cc-48d6-b373-0e181a6f146b.png">

Updated Reading Scores

<img width="303" alt="Updated Read Avg" src="https://user-images.githubusercontent.com/93845867/150455039-ae961c46-3f5c-4487-872e-3b20c404b93d.png">

- Scores by school spending

Original Scores by School Spending

<img width="804" alt="Original Scores by School Spending" src="https://user-images.githubusercontent.com/93845867/150455754-675d012c-951b-4bc5-9b88-a6689522540a.png">

Updated Scores by School Spending

<img width="644" alt="Updated Scores by School Spending" src="https://user-images.githubusercontent.com/93845867/150455776-cb06a9f7-58dd-45ec-9c07-01515c215488.png">

In **$630-644** spending range Reading Passing Percentage decreased by 0.1% so Overall Passing Percentage decreased by 0.1%.

- Scores by school size
 
Replacing the ninth-grade scores had very little impact.

- Scores by school type

Replacing the ninth-grade scores had very little impact.

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
