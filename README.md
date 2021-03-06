# School_District_Analysis
Project 4 of Data Analytics Bootcamp. Learning to use Python Libraries with school district data.
## Resources
* Python version 3.8.8
* Anaconda version 4.9.2
* Files used: [student_complete.csv](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/students_complete.csv) and [school_complete.csv](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/schools_complete.csv)
## Analysis Overview
The purpose of the analysis was to provide a high - level snapshot of the school district's key metrics, math and reading scores. As well as editing scores affected by academic dishonesty from Thomas High School's 9th grade. The information was requested in a table format.
### Initial School District Summary
* Top 5 and bottom 5 performing schools, based on the overall passing rate
  * ![Top 5 Schools by % Overall Passing](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Top_5_S_D_A.png)
  * ![Bottom 5 Schools by % Overall Passing](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Bottom_5_S_D_A.png)
* The average math score received by students in each grade level at each school
 * ![Average Math Score by Grade Level](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Avg_Math_by_grade.png)
* The average reading score received by students in each grade level at each school
 * ![Average Reading Score by Grade Level](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Avg_Read_by_grade.png)
* School performance based on the budget per student
![School Performance by Budget per Student](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Perform_by_budget_per_student.png)
* School performance based on the school size
![School Performance by School Size](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Perform_by_school_size.png)
* School performance based on the type of school
![School Performance by School Type](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Perform_by_school_type.png)

### Corrected School District Summary  
* Top 5 and bottom 5 performing schools, based on the overall passing rate
  * ![Top 5 Schools by % Overall Passing after Correction](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Top_5_Corrected.png)
  * ![Bottom 5 Schools by % Overall Passing after Correction](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Botton_5_Corrected.png)
* The average math score received by students in each grade level at each school
 * ![Corrected Average Math Score by Grade Level](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Corrected_Avg_Math_by_grade.png)
* The average reading score received by students in each grade level at each school
 * ![Corrected Average Reading Score by Grade Level](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Corrected_Avg_Reading_by_grade.png)
* School performance based on the budget per student
![Corrected School Performance by Budget per Student](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Corrected_Perform_by_budget_per_student.png)
* School performance based on the school size 
![Corrected School Performance by School Size](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Corrected_School_Perfromance_by_School_Size.png)
* School performance based on the type of school
![Corrected School Performance by School Type](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Corrected_Perform_by_school_type.png)

## Results
All the summaries use only the 10th - 12th-grade math and reading scores for Thomas High School. The "nan" scores of the 9th grade were dropped. Had the "nan" scores of the 9th grade been included, all of Thomas High School's passing percentages would be around 30% lower than those presented here.
 
* How is the district summary affected?
  * The % Passing Math, % Passing Reading, and the % Overall Passing decreased in the district summary after the ninth grade math and reading scores from Thomas High School were corrected to nan. Image District Summary Comparison shows the values from the initial District summary are in blue, and the values that changed after the correction are in red. ![District Summary Comparison](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/Change_District_Summary.png)
* How is the school summary affected?
  * The corrected school summary shows a decrease in Thomas High School's Average Math Score, % Passing Math, % Passing Reading, and % Overall Passing. The Average Reading Score showed a slight increase. The image School Summary Comparison indicates the initial scores in blue, the scores that decreased after the correction in red, and the score that increased in green. ![School Summary Comparison](https://github.com/RuthLD/School_District_Analysis/blob/main/Resources/School_summary_compare.png)
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
  * Thomas High School performance was not significantly affected by removing the 9th-grade math and reading scores and only using the 10th - 12th-grade math and reading scores. The school retained its second-place rank in the top 5 schools. The percentage of students passing math was reduced by 0.086481%, and the percentage of students passing reading was reduced by 0.29013%. The overall passing percentage decreased by 0.317688%.
* How does replacing the ninth-grade scores affect the following:
  * Math and reading scores by grade
    * The only change is that the math and reading scores for the ninth grade from Thomas High School show "nan.”
  * Scores by school spending
    * The scores by school spending were not affected.
  * Scores by school size
    * The scores by school size were not affected.
  * Scores by school type
    * The scores by school size were not affected.

## Summary
The District Summary had decreases in the % Passing Math (down 0.2%), % Passing Reading (down 0.3%), and % Overall Passing (down 0.1%). However, the four major changes in the school district analysis are four decreases in Thomas High School's Average Math Score (down 0.067412%), % Passing Math (down 0.2903%), % Passing Reading (down 0.29013%), and % Overall Passing (down 0.317688%). Larger changes were not seen in the District Summary because the Thomas High School's scores consist only of the 10th grade - 12th-grade reading and math scores and the 9th-grade’s "nan" scores were dropped from the analysis. 
