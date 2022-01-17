# SchoolDistrictAnalysis

## Overview
The purpose of this analysis was to see the affect that removing a set of scores (9th graders from Thomas High school) had on the original PyCitySchools data tables. These scores were apparently “altered” and thus invalid.

## Results
- District summary:

The average scores and passing percentages decreased a touch after the data change 

Before change:
![](https://github.com/alexlieberman22/SchoolDistrictAnalysis/blob/main/Resources/District_Original.PNG)

After change:
![](https://github.com/alexlieberman22/SchoolDistrictAnalysis/blob/main/Resources/District_New.PNG)

- School summary:

The passing percentages for Thomas High School changed fairly significantly, while all others stayed the same

Before change:

![](https://github.com/alexlieberman22/SchoolDistrictAnalysis/blob/main/Resources/Schools_New.PNG)

After change:

![](https://github.com/alexlieberman22/SchoolDistrictAnalysis/blob/main/Resources/Schools_Original.PNG)

Although the average math and reading scores for Thomas High school are nearly unchanged, the passing percentages increased significantly after excluding the 9th grade data. They are now among the highest across schools.

- Replacing the ninth-grade scores also affected the following:

    - Math and reading scores for the Thomas 9th grade were replaced by “nan”
    - Scores by school spending generally increased for the $585-629 and $630-644 ranges
    - Scores by school size remain unchanged
    - Scores by school type also remain unchanged


## Summary
By removing the set of 9th grade scores from Thomas High school, the overall trend across all the data tables was an increase in score and passing percent’s. If this set of scores was truly invalid, then its presence was having a negative impact on the scores district wide. By removing them we have shown that the overall performance of the district was in fact higher than previously thought.  
