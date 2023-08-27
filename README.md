# Thomas High School & District Analysis

---

### Overview of School District Analysis

In this analysis, I helped the school board to examine outcomes using various essential metrics, aiming to discern the performance levels of individual schools in Mathematics and Reading. Regrettably, indications of academic dishonesty came to light, specifically concerning the Math and Reading grades of ninth-grade students at Thomas High School (THS). This raised concerns about data integrity. To uphold the state-testing standards, I employed methodologies that would produce a valid analyses for the entire school board while addressing the data discrepancies at THS. To achieve this, I substituted NaNs (Not Available) for the math and reading scores of Thomas High School students, preserving the integrity of the remaining dataset and facilitating the desired outcomes.

---

### Results:

Because I needed to swap out the 9th-grade Math and Reading scores for Thomas High School (THS) with NaNs, this change had a slight effect on the overall results across the district. The average scores and passing percentages across the district experienced a minor decrease. Initially, prior to the replacement of the 9th-grade Math and Reading scores, THS had averages of 66.91% and 69.66% for Math and Reading, respectively. Adjusting these averages for Math and Reading to 93.18% and 97.13%, respectively, resulted in an overall passing percentage of 90.63%.

Although the exclusion of THS 9th graders caused a notable shift in Math, Reading, and Overall percentages at the school level, these changes didn't have a noticeable impact on aggregated metrics like Scores by school spending, Scores by school size, or Scores by school type. Ultimately, the total number of THS 9th graders represented just 1.18% of all students in the district. Below is a summary of the effects on all 7 metrics:

- **District Summary:**
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/756f683053241e765a176a84a73a6d38ebd4f2d8/Results_Table_View/District%20Summary.png" width="1000" height="80"> 

- **School Summary:**
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/756f683053241e765a176a84a73a6d38ebd4f2d8/Results_Table_View/School%20Summary%20THS.png" width="1000" height="300"> 

- **Thomas High School Ranking:**  
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/756f683053241e765a176a84a73a6d38ebd4f2d8/Results_Table_View/THS%20Ranking.png" width="1000" height="300"> 

- **Scores by School Spending:** Results remained unchanged
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/Spend%20Summary%20by%20Scores.png" width="1000" height="250"> 

- **Scores by  School Size:** Results remained unchanged 
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/School%20Size%20by%20Score.png" width="1000" height="190">

- **Scores by School Type:** Results remained unchanged 
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/School%20Type%20by%20Scores.png" width="1000" height="150"> 
--- 

### Data Dictionary

#### Dataset 1: Schools
| Feature      | Description                       | DataType |
|--------------|-----------------------------------|----------|
| School ID    | Unique school identifier          | Integer  |
| school_name  | Name of the school                | Text     |
| type         | Type of the school                | Text     |
| size         | Number of students                | Integer  |
| budget       | School's budget                   | Integer  |

#### Dataset 2: Students
| Feature        | Description                     | DataType |
|----------------|---------------------------------|----------|
| Student ID     | Unique student identifier       | Integer  |
| student_name   | Student's name                  | Text     |
| gender         | Student's gender                | Text     |
| grade          | Student's grade level           | Text     |
| school_name    | Name of student's school        | Text     |
| reading_score  | Reading score                   | Integer  |
| math_score     | Math score                      | Integer  |
