# School_District_Analysis
## Overview
The overview of this analysis was to complete the following
    - to create and activated a development environment.
    - navigate and write code in Jupyter Notebook.
    - execute functions like the loc method, replacing data values, cleaning data, and creating new dataframes.
    
## Purpose
### Original analysis
The School Board needs an analysis done to help determine the budgets needed for the next year. The Board wants to see an analysis based on the schools in their control based on the following:
    - type of school
    - number of students in each school
    - budget per school
    - budget per student per school
    - average math and reading score per school
    - passing percentage of math / reading per school
    - overall passing of both math and reading per school
    
Once each factor is determined the Board would then like several other reports to help determine the budgetary needs of the schools. Those additional reports include:
    - Average Math and average reading by grade level for each school
    - Scores by school spending
    - Scores by school size
    - scores by school type
    - top performing schools
    - bottom performing schools
    
### Updated analysis
The School Board was made aware of possible academic dishonesty in testing scores. The School Board needs an updated analysis without the testing scores from Thomas High School Ninth graders. To achieve the new reports:
    - the math and reading scores for all ninth graders at Thomas High School must be changed to NaNs.
    - a new school average with just the 10th, 11th, and 12th graders must be calculated and replace the orignal scores
    - all reports above must be ran again with the new data set.
    
    
## Results
Once the scores for the ninth graders at Thomas High School was changed, Thomas High school overall average dropped. This put Thomas High School in the bottom performing schools. To make the scores fair, Thomas High school averages were replaced to just include 10th- 12th graders. The replacement averages put Thomas High school back in the top performing schools. 
    -Thomas High School scores with Ninth graders counted as Nans.
    
![PyTHSwo9](https://user-images.githubusercontent.com/105830665/179000604-6b78b9ca-e035-4e2a-a91f-f04c141783c2.png)
    -Thomas High School with just 10th-12th graders scores

![PyTHS10_12](https://user-images.githubusercontent.com/105830665/179001480-26c9bc26-e94a-40e1-ad74-01b4ff21af17.png)
    
Now that the data has been corrected, the updated analysis shows very little to no changes from the original analysis ran. If the School Board wanted to see the effect the formatting of the report would need to changed to show at least 3 places behind the decimal.
    -Original District Summary
![PyCityDistSum](https://user-images.githubusercontent.com/105830665/179001810-922f2106-fedf-4ba4-9625-a54083f998d9.png)
    -Update District Summary
![PyChallDistSum](https://user-images.githubusercontent.com/105830665/179001955-63aa35bd-e37c-49f6-8c91-4727c335a42e.png)
    -Original School Type Summary
![PyCityTypeSum](https://user-images.githubusercontent.com/105830665/179002071-4b0d946e-ccb7-45e3-83de-1e0e99e52d9b.png)
    -Update School Type Summary
![PyChallTypeSum](https://user-images.githubusercontent.com/105830665/179002173-8b236794-4f13-43c5-b415-4c006aeb81a6.png)

As you can see in the sample images above, the scores would need to be extended to determine the true effect after the changing of Thomas High School scores.