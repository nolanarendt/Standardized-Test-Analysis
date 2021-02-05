# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Test Analysis

## Problem Statement
As participation rate increases, total scores decrease. I want to identify states that have above average participation rates and above average total scores. From those that are above average in both categories, I want to identify the states with the best evidence based reading and writing and best math scores. I will then do background research on those states to better understand why they are so successful and what I can advise the department of education about.

## Data Dictionary
|Feature|Type|Dataset|Description|
|---|---|---|---|
|**state_2017**|*object*|sat_2017|State in which SAT scores are recorded in 2017|
|**participation_2017**|*float*|sat_2017|Participation rate of each state in 2017 (Scale of 0 - 1)|
|**evi_based_read_write_2017**|*integer*|sat_2017|Score of students evidence based reading and writing section on SAT in 2017 (Scale 200-800)|
|**math_2017**|*integer*|sat_2017|Score of students math section on SAT in 2017 (Scale 200-800)|
|**total_2017**|*integer*|sat_2017|Total of evidence based reading and writing + math in 2017 (Scale 400-1600)|
|---|---|---|---|
|**state_2018**|*object*|sat_2018|State in which SAT scores are recorded in 2018|
|**participation_2018**|*float*|sat_2018|Participation rate of each state in 2018 (Scale of 0 - 1)|
|**evi_based_read_write_2018**|*integer*|sat_2018|Score of students evidence based reading and writing section on SAT in 2018 (Scale 200-800)|
|**math_2018**|*integer*|sat_2018|Score of students math section on SAT in 2018 (Scale 200-800)|
|**total_2018**|*integer*|sat_2018|Total of evidence based reading and writing + math in 2018 (Scale 400-1600)|
|---|---|---|---|
|**state_2019**|*object*|sat_2019|State in which SAT scores are recorded in 2019|
|**participation_2019**|*float*|sat_2019|Participation rate of each state in 2019 (Scale 0 - 1)|
|**evi_based_read_write_2019**|*integer*|sat_2019|Score of students evidence based reading and writing section on SAT in 2019 (Scale 200-800)|
|**math_2019**|*integer*|sat_2019|Score of students math section on SAT in 2019 (Scale 200-800)|
|**total_2019**|*integer*|sat_2019|Total of evidence based reading and writing + math in 2019 (Scale 400-1600)|
|---|---|---|---|
|**intended_major**|*object*|sat_2019_by_intended_college_major|Each major in college|
|**test_takers**|*integer*|sat_2019_by_intended_college_major|Number of students who took the test in given state by inteded college major|
|**percent**|*float*|sat_2019_by_intended_college_major|Total number of tests divided by each inteded college major|
|**total**|*integer*|sat_2019_by_intended_college_major|Total of reading_writing score + math score by inteded college major|
|**reading_writing**|*integer*|sat_2019_by_intended_college_major|Score of student's reading and writing section by inteded college major|
|**math**|*integer*|sat_2019_by_intended_college_major|Score of student's math section by inteded college major|

## Summary of Analysis
From 2017-2019, participation increased by 9.25%, evidence based reading and writing decreased by 1.46%, math increased by 0.83%, and total score decreased by 1.15%.

No states had above average participation and above average total score in 2017. Massachusetts had above average participation and above average total score in 2018 and 2019. Virginia had above average participation and above average score in 2019.

Masschussets had the highest scoring math section of 551. Virginia had the highest scoring evidence based reading and writing section of 564. 

## Conclusions Recommendations
1. Increase accessibility of the SAT. More students that actually want to pursue higher education will take the SAT, opposed to students who are forced by their state to meet mandated benchmarks.

2. Increase government funding. By increasing government funding, states will be able to attract more quality instructors, fund programs such as early education, equal access across school districts, and develop outcome-based accountability.

3. Advanced placement opportunities. Allow students to take advanced placement courses that will allow them to preview college level material and better understand what they should be studying, or how often they should be studying.

## Sources
1. Building on 20 Year of Massachusetts Education Reform
  - https://www.doe.mass.edu/commissioner/BuildingOnReform.pdf
2. Education Reform: Ten Years after the Massachusetts Education Reform Act of 1993
  - https://ideas.repec.org/a/teg/journl/v1y2005i1p1-36.html
3. SAT scores rise in Virginia and locally, as national and state participation declines
  - https://www.dailypress.com/virginiagazette/va-vg-sat-scores-virginia-0926-20191001-gwq5ul3bsrasriebs3xzfckieu-story.html
4. VDOE :: News: October 25 - Virginia Students Top Nation on SAT
  - https://www.doe.virginia.gov/news/news_releases/2018/10-oct25.shtml
