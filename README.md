# Thomas High School & District Analysis

---

### Overview of School District Analysis

In this analysis, I helped the school board to examine outcomes using various essential metrics, aiming to discern the performance levels of individual schools in Mathematics and Reading. Regrettably, indications of academic dishonesty came to light, specifically concerning the Math and Reading grades of ninth-grade students at Thomas High School (THS). This raised concerns about data integrity. To uphold the state-testing standards, I employed methodologies that would produce a valid analyses for the entire school board while addressing the data discrepancies at THS. To achieve this, I substituted NaNs (Not Available) for the math and reading scores of Thomas High School students, preserving the integrity of the remaining dataset and facilitating the desired outcomes.

---

### Results:

The decision to exclude Math and Reading scores of 9th graders from Thomas High School (THS) had a minimal effect on both the overall district-wide results and the results specific to THS.

Before the exclusion, the average passing percentages for Math and Reading at THS were 93.27% and 97.31%. After the removal of 9th grade scores, these percentages saw a slight decline to 93.18% for Math and 97.02% for Reading. District-wide results also experienced a slight decrease, shifting Math and Reading passing percentages from 75.0% and 85.8% to 74.8% and 85.7% respectively.

The omission of THS's 9th grade scores did not significantly impact the school-level percentages for Math, Reading, and Overall scores. Similarly, there was no discernible effect on aggregated metrics such as Scores by school spending, Scores by school size, or Scores by school type. The following summary outlines the impact on all seven metrics

- **District Summary:**
<img src= "https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/d04733e14e7620a00f3d77f83ecf22c89559d702/Results_Table_View/District_summary.jpg" width="1000" height="90"> 

- **School Summary:**
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/00c6ffea9c45c587c44fafb8bd525157ecd10457/Results_Table_View/School_summary.jpg" width="1000" height="350"> 

- **Thomas High School Ranking:**  
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/756f683053241e765a176a84a73a6d38ebd4f2d8/Results_Table_View/THS%20Ranking.png" width="1000" height="250"> 

- **Scores by School Spending:** Results remained unchanged
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/Spend%20Summary%20by%20Scores.png" width="950" height="190"> 

- **Scores by  School Size:** Results remained unchanged 
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/School%20Size%20by%20Score.png" width="900" height="150">

- **Scores by School Type:** Results remained unchanged 
<img src="https://github.com/robertoalatorre33/Thomas_HS_District_Analysis/blob/70216ece5dcc625234f00d49ff7c5927971b9003/Results_Table_View/School%20Type%20by%20Scores.png" width="900" height="120"> 

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
