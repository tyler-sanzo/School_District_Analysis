# School District Analysis

Providing meaningful insight for a school district through data analysis

## Analysis Overview

Due to possible academic integrity within the freshman class at Thomas High School, we have been tasked with removing the scores in question and redo the analysis in order to uphold state testing standards. The purpose of this is to compare the results with and without the nullified testing scores.

## Results

-The District Summary table was largely unaffected by the removal of the test scores. This is due to the fact that the number of scores removed is very small fraction of the total district scores. The 9th grade class at THS is only 461 students out of 39,170 total in the school district. 

![filename](https://github.com/tyler-sanzo/School_District_Analysis/blob/main/Supplemental%20Images/District%20Summary%20-%20Before%20Cleanup.PNG)
Before Removal

![filename](https://github.com/tyler-sanzo/School_District_Analysis/blob/main/Supplemental%20Images/District%20Summary%20-%20After%20Cleanup.PNG)
AFter

-The School Summary was similarly unaffected by the removal of the scores. While there was a marginal difference in THS's individual outcomes, it still remained in the same position in the top schools in the district (#2).

-As mentioned in the previous point, the replacement of the ninth graders' math and reading scores did decrease the overall passing rate of the school but not enough to affect the rank within the district.

-Replacing the ninth-grade scores also had affect overall on the tables breaking down each schools test scores by grade. The only difference seen is the ninth grade THS scores replaced by 'nan.

-The scores by school spending results were also unaffected and showed identical tables both before and after. This is due the change in the averages within THS's scores were not enough to change the averages within the spending bin they were grouped in.

-Once again, the scores by school size were also unaffected within the precision displayed in this analysis. Results for average scores are outputted to the first decimal place and the passing percentages are rounded to the nearest whole number.

Similarly, the scores by school type were also not changed before and after the removal of the nullified scores.

## Summary

Because the number of scores changed was so small compared to the total, the results were almost identical before and after. The only noticeable change in results can be seen when looking at the most granular level, THS's individual results. A few of the changes were as follows:

-Average math test score fell by around .067%.
-Average reading test score rose by about .05%.
-Percent of students who passed the math test fell by about .09%.
-Percent of students who passed the reading test fell by about .29%.

As we can see, the overall scores even at the most granular level were hardly affected.
