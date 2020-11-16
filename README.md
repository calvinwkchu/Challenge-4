# School District Analysis

## Overview of School District Analysis
The purpose of the school district analysis is to not only aggregate data across different schools to identify various trends/patterns occuring within the district, but also evaluate the effects of the academic scandal identified at Thomas High School's grade 9 test scores.

## School District Results
Due to the acadmic scandal, it was decided that grade 9 test scores from Thomas High School were removed as part of our analysis, so we can have a better picture of the verified results.

- The district as a whole experienced a slight decrease in test scores, causing a drop in overall passing percentage from 65.2% to 64.9%.
    - Before: <img src="Resources/before_district_summary.png">
    - After: <img src="Resources/after_district_summarys.png">
- All other schools (besides Thomas High School) were not affected as a result of the data removal, and the results stay the same as before.
- For Thomas High School however, they experienced a slight improvement in their average reading scores but experienced drops in all other areas e.g. average math scores, overall percentage passing scores, etc.
    - Before: <img src="Resources/before_school_summary.png">
    - After: <img src="Resources/after_school_summarys.png">
- As a result of dropping the datapoints, Thomas High School drops ~0.3% points in their overall passing percentage (metric used to measure performance in schools) but maintains as the second best school in the district.
    - Before: <img src="Resources/before_top_schools.png">
    - After: <img src="Resources/after_top_schools.png">
- We also do not see an impact in the math and reading scores of other schools as a result of replacing the values as other school data remains untouched i.e. scores remain intact, besides nineth grade data for Thomas High School is removed.
- We also do not see a meaningful impact on scores by school spending as a result of the removal.
- Likewise, we do not see any meaningful impact on our school size analysis.
- Lastly, we do not see any meaningful impact on school type from the removal.

## Summary
Some key take aways from removing nineth grade test scores at Thomas High School was that the district as a whole experienced a slight decrease in math test scores and lower percentage of students passing. Secondly, we are able to verify that the academic scandal did slightly bump up metrics for Thomas High School as they experienced modest decreases (except average reading scores) in all other metrics. Furthermore, we see the gap between Thomas High School and schools below them narrow when evaluating them against their overall passing percentages. However, the analysis for the district is incomplete or flawed at this time due to the unverified results of the nineth grade at Thomas High School.

