# School_District_Analysis.


## Overview of the school district analysis: explain the purpose of this analysis


Beginning
**analyzing information for a variety of sources, and in a variety of formats.**
**preparing all standardized test data for analysis, reporting ,insights and presentation to provide insights about performance trends and patterns.**
**to inform discussions and strategic decisions at the school and district level.**
**analyze data on student funding and students' standardized test scores.**
**Your task is to aggregate the data and showcase trends in school performance.**
**assist the school board and superintendent in making decisions regarding the school budgets and priorities.** 

Ending summary
**the students_complete.csv file shows evidence of academic dishonesty; specifically, reading and math grades for Thomas High School ninth graders appear to have been altered.** 
**asked you to replace the math and reading scores for Thomas High School with NaNs while keeping the rest of the data intact.** 
**repeat the school district analysis that you did in this module and write up a report to describe how these changes affected the overall analysis.**



## Analysis of change in School District data

### District Summary changes
![alt text](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/district_summary_original.PNG)
![alt text](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/district_summary_updated.PNG)
- School Summary changes
![alt text](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/school_summary_original.PNG)
![alt text](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/school_summary_updated.PNG)
- Thomas High School relative to other schools

- Ninth-grade score replacement impact on grades

### Math and reading scores by grade

[math scores by grade original](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/math_scores_by_grade_original.PNG)
[math scores by grade updated](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/math_scores_by_grade_updated.PNG)
[reading scores by grade original](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/reading_scores_by_grade_original.PNG)
[reading scores by grade updated](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/reading_scores_by_grade_updated.PNG)
  
### Scores by school spending
 
[scores by school spending original](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_spending_original.PNG)
[scores by school spending updated](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_spending_updated.PNG)
 
### Scores by school size

[scores by school size original](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_size_original.PNG)
[scores by school size updated](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_size_update.PNG)
 
### Scores by school type

[scores by school type original](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_type_original.PNG)
[scores by school type updated](https://github.com/kwporras/Module_4_Challenge/blob/6741076209a62d8e73116299a4ed629ad8e1aaca/Challenge%204/Resources/scores_by_school_type_update.PNG)


## School District Summary
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.



The script below is used to define how data in a readable csv will be indexed. In the future if a csv file is provided the candidate name or county name may not be in the same columns as csv file in the [resources file](Resources/election_results.csv). By changing the row index the script can be adjust to correctly read a different csv column layout.        
![alt text](https://github.com/kwporras/Challenge-3/blob/f84a76aac82899721c48edec85bfddcd5d698444/Resources/Create_a_variable_to_track.PNG)

Additionally, if another variable in a CSV file that needs to be tracked, the below script provides a general useable outline. Use the script above create a new row index, then place that index in the "Insert index number here" spot. Then county_list and county_votes would be replaced and appropriated named for the data that one would wish to track.  
![alt text](https://github.com/kwporras/Challenge-3/blob/f84a76aac82899721c48edec85bfddcd5d698444/Resources/Selection_of_county_and_candidate_data.PNG)






##### Resources
- Data Source: clean_students_complete.csv, missing_grades.csv, schools_complete.csv, students_complete.csv
- Software: Python 3.9.6, Conda 4.10.3, 
- Jupyter-notebook 6.4.0



