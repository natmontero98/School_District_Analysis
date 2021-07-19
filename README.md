# School_District_Analysis
School District Analysis using Python, Pandas and Jupyter Notebook

## Overview of the school district analysis
Maria, Chief Data Scientist for the city school district, asked for our help analyzing the results and scores of standardized test across a variety of schools and grades, to provide insight about performance trends and patterns. 
These insights will help strategic decision making.

## Results: 
Due to evidence of academic dishonesty in the scores for Thomas High School nineth graders, our district analysis was repeated. The scores of these group of students were upholded (replaced with NaNs). The new results showed the following:

### How is the district summary affected? 
The district summary was not affected substantially. 
* The average math and reading score were almost not affected at all.
* The percentage of students who passed math deacreased by roughly 1 decimal point. 
* The percentage of students who passed reading deacreased by roughly 1 decimal point. 
* The overall passing percentage decreased by roughly 2 decimal points.

### How is the school summary affected?
* In the school summary the only significant change corresponds to the Thomas High School passing averages (math, reading and overall). As we can see in the tables below, they went from over 90 to only over 60.
<img width="597" alt="Captura de Pantalla 2021-07-18 a la(s) 23 12 19" src="https://user-images.githubusercontent.com/85467925/126101772-b1312ab6-663b-4f2f-9ba0-a9c07ba40422.png">
<img width="722" alt="Captura de Pantalla 2021-07-18 a la(s) 23 14 20" src="https://user-images.githubusercontent.com/85467925/126101891-3fed5626-96e3-4db7-91a7-fd3d2dd8c985.png">

* The average scores decreased by less than 1 decimal point. 

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
After replacing the ninth graders' scores with NaNs, the performance of Thomas High School went down significantly. But when we only took into account the other grades, it's performance went back up to 90 -100 % passing range. This positioned the school as the 2nd with best performance of the whole district. 
### How does replacing the ninth-grade scores affect the following:
### Math and reading scores by grade
These were not affected, because the grades 10th to 12th kept the same exact data. The only difference is that now our table doesn't show any data for the 9th grade of Thomas High School. 
### Scores by school spending
Stayed the same. 
### Scores by school size
Stayed the same.
### Scores by school type
The scores for the "Charter" type had some small variations, average reading score increased byt roughly 0.1, passing math percentage decreased. by 0.1, passing reading percentage decreased by 0.03 and the overal passing percentage decreased by 0.04.

## Summary: 
After reading and math scores have been replaced we saw these changes in the school district analysis. 
The average passing percentage for math and reading decreased substantially, because we had less data in the scores column, but we kept the same number of students. 
After we got the averages for the grades 10th to 12th only, and replaced the scores,  the overal results went back to roughly the same numbers we had at the beginning. Withouth taking into account the results from the nineth graders, the Thomas High School remained as the second top performing school of the district.
