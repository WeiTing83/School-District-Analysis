# School-District-Analysis
## Overview 
Thomas High School ninth graders need to alter reading and math grades due to
evidence of academic dishonesty. Therefore, we will replace all math and reading
scores with NaNs for Thomas High School ninth graders. Then, we will re-run school
district analysis and evaluate the impact for school district analysis.
>
## Analysis data
>
### District Analysis Summary
![distric_summary](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/distric_summary.png)

+ All of scores are dropped around 0.1%.
+ There are 461 ninth graders in Thomas High School, which is only 1% of
student population in the school district. Therefore, statistically it doesn't have
big impact to the overall scores. 
>
### School Analysis Summary
![school_summary](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/school_summary.png)

+ After removing scores of Thomas High School ninth graders, passing math
percentage increases from 67% to 93% and passing reading percentage
increases from 70% to 97%. The overall passing percentage increases from
65% to 90%.
+ In Thomas High School, we can estimate the scores of ninth graders got lower
passing percentage than 10-12th grade students. Thus, after removing their
scores, the overall passing percentage significantly get increased.
>
### Top Five Schools
![top_five_schools](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/top_five_schools.png)

+ Thomas High School becomes top two school base on overall passing percentage
+ Top five schools are all charter school
>
### Scores by School Spending
![spending_range](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/speading_range.png)

+ Money spent per student is negative correlation with overall passing percentage.
>
### Scores by School Size & School Type by Size
![school_size_type](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/school_size_type.png)

+  Small and medium schools (&lt;2000 students) have higher overall passing
percentage, and all of them are charter schools.
+ All district schools have over 2000 students. Wilson High school, the only one
charter school which is categorized as a large size school, has overall passing
percentage higher than other large schools.
>
### Scores by School Type & Type by Spending
![type_scores_spending](https://github.com/WeiTing83/School-District-Analysis/blob/main/Resources/type_scores_spending.png)

+ All Charter schools have higher overall passing percentage.
+ Compared to district school, all Charter school spend less money on each
student, but their students have higher overall passing percentage. Thomas High
school has the highest spending per student ($630-644) in charter schools.
>
## Summary
The 9th graders in Thomas High school are only 1% of student population in the district
and 4% in all charter schools. So, changing their data doesn’t significantly impact the
overall school district analysis including passing percentage, spending range, school
size by scores and so on. However, if we focus on school summary for Thomas High
school, altering data for their 9th graders directly cause its overall passing percentage to
increase from 65% to 90% which is top two performance in the whole district.


