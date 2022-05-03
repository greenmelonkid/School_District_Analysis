# School District Analysis

## Resources

Software: Python 3.7.6 and Jupyter Notebook 6.0.3
Data: schools_complete.csv and students_complete.csv

## Overview

Originally, the purpose of this analysis was to find the reading, math, and overall scores by percent across
15 high schools. While conducting the research, it was determined that the Thomas High School 9th grade math 
and reading scores were tampered with. Due to this information, it was necessary to refactor the data by 
excluding those particular grades until further notice. All parameters were calculated again with this omission.

## Results

After removing the 9th grade math and reading scores from Thomas High School, many aspects were affected:

### District Level Results

District Summary with Thomas High School

![district summary with THS](https://user-images.githubusercontent.com/99292945/166406739-ff5d38c5-9752-41b7-9960-7c41b5f9eaca.png)

District Summary without Thomas High School

![District Summary without THS](https://user-images.githubusercontent.com/99292945/166406740-271d7579-3a8e-4561-978e-cad48fef0110.png)

When comparing the district summary with and without the Thomas High School 9th grades
scores, there are only slight differences between all of the factors, the biggest difference
being the overall passing percentage was .3% lower without Thomas High School's grades.

### School Level Results

School Summary with Thomas High School

![school summary WITH THS](https://user-images.githubusercontent.com/99292945/166406748-5e18685c-228a-4ce6-8681-3fd2db6c8eb8.png)

School Summary without Thomas High School

![school summary without THS](https://user-images.githubusercontent.com/99292945/166406749-e14bbdea-34ff-440f-b70b-7a3853434b88.png)

The changes didn't seem to affect Thomas High School's ranking very much. They are
still in the top 5 schools based on passing scores.

Top 5 schools with Thomas High School

![Top 5 schools WITH THS](https://user-images.githubusercontent.com/99292945/166406753-dbbd0982-61ab-4915-9a74-75fcd049178b.png)

Top 5 schools without Thomas High School

![Top 5 schools without THS](https://user-images.githubusercontent.com/99292945/166406754-77582f50-e729-4d8e-8bdd-2d4a25f14997.png)

Test Scores by Category

By changing all the Thomas High School 9th grade scores to null values, the overall
categories changed:

Math Scores by grade with Thomas High School

![math scores by grade WITH THS](https://user-images.githubusercontent.com/99292945/166406741-2ba43f63-3ec6-4177-b509-5e3d20c429f4.png)

Math Scores by grade without Thomas High School

![math scores by grade without THS](https://user-images.githubusercontent.com/99292945/166406742-0cc3d01f-9c13-42b2-8430-d5351086705f.png)

Reading Scores by grade with Thomas High School

![reading scores by grade WITH THS](https://user-images.githubusercontent.com/99292945/166406743-56ef618b-2860-4916-8e80-31505c7a9a80.png)

Reading Scores by grade without Thomas High School

![Reading Scores by Grade without THS](https://user-images.githubusercontent.com/99292945/166406744-0481349c-80b8-4b45-bad9-13602d513678.png)

Scores by school spending

School spending without Thomas High School

![school spending without THS](https://user-images.githubusercontent.com/99292945/166406747-84fee462-a688-4090-821e-6cb571d32ad3.png)

Scores by school size

School scores by school size without Thomas High School

![school size without THS](https://user-images.githubusercontent.com/99292945/166406746-95620166-083a-4d6b-807a-d3eed1e4dd5e.png)

Scores by school type

Scores by school type without Thomas High School

![score type without THS](https://user-images.githubusercontent.com/99292945/166406751-cdd2de11-1052-4577-afab-f510d91b30f3.png)

## Summary

In summary, there were some noticable changes after dropping the Thomas High School 9th grade scores. The overall 
passing levels went down a little bit, but not a whole lot. This could mean that the 9th graders didn't
have very good scores to begin with. Even with the dropped scores, Thomas High School still ranks in the top five
overall passing schools.


