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

- The overall passing percentages of Thomas High School decreased. 

## Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
