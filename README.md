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

IMAGE DISTRICT SUMMARY WITH THS GRADES - SAVED
IMAGE DISTRICT SUMMARY WITHOUT THS GRADES - SAVED

When comparing the district summary with and without the Thomas High School 9th grades
scores, there are only slight differences between all of the factors, the biggest difference
being the overall passing percentage was .3% lower without Thomas High School's grades.

### School Level Results

IMAGE - School Level Summary with THS Grades - SAVED

IMAGE - School Level Summary without THS Grades - SAVED

- The changes didn't seem to affect Thomas High School's ranking very much. They are
still in the top 5 schools based on passing scores.

IMAGE - TOP 5 PERFORMING SCHOOLS WITH THS GRADES - SAVED
IMAGE -TOP 5 PERFORMING SCHOOLS WITHOUT THS GRADES - SAVED

Test Scores by Category

By changing all the Thomas High School 9th grade scores to null values, the overall
categories changed:

- IMAGE - Math scores by grade with THS - SAVED
- IMAGE - math scores by grade without THS - SAVED
- IMAGE - Reading scores by grade with THS - SAVED
- IMAGE - Reading scores by grade without THS - SAVED

Scores by school spending

- IMAGE - WITH THS
- IMAGE - WITHOUT THS - saved

Scores by school size

- IMAGE - WITH THS
- IMAGE - WITHOUT THS - saved

Scores by school type

- IMAGE - WITH THS
- IMAGE WITHOUT THS - saved


## Summary

In summary, there were some noticable changes after dropping the Thomas High School 9th grade scores. The overall 
passing levels went down a little bit, but not a whole lot. This could mean that the 9th graders didn't
have very good scores to begin with. Even with the dropped scores, Thomas High School still ranks in the top five
overall passing schools.


