# Students Examination Performance Dataset Exploration
## by Dorothy Kambua Thomas


## The Dataset

The Student Examination Performance dataset consist of data about the performance of various students in school. The data includes various information about each student:

> Gender
> Race/ethnicity
> Parental level of education
> Lunch details eg, standard, free, or reduced
> Completion of test preparation course
> Test scores

To add on this, I also added a total score, which is a sum of all the test scores, inorder to analyze the data further. This analysis is solely to investigate the relationship between the variables mentioned above and the overall total score, which represents the student's overall performance.

## The Summary of Findings

I performed univariate, bivariate and multivariate exploration on the dataset. The key conclusions derived from each exploration are:

Univariate exploration: 

The female counts exceed the male counts by around 50.

The majority of the students' parents have attended some college, with the least parents having completed the master's degree level.

Majority of the students did not do the test preparation course prior to doing the test.

It is clear that students who are able to afford the standard lunch exceed those who can't, i.e., those who take free/reduced lunch.

Math score distribution is close to normal. Many students had a math score of between 60 and 80.

Reading score distribution is bimodal with peaks at around 65 and another peak at around 75. Few students had scores of less than 40.

Writing score is bimodal distribution with peaks at 50 and 75. Very few students had a writing score of less than 40, with many students scoring between 60 and 80.

Total score is a unimodal distribution with a peak at around 210 total score. Very few students had a total score of less than 100, with most students scoring a total of between 200 and 250 total score. Therefore, many students performed above average.

Bivariate Exploration:

There is a positive relationship between the total score and math score. An increase in math score leads to an in increase in the total score. Therefore, for a student's performance to increase, the math score should also increase.

There is also a positive relationship between the total score and reading score. An increase in reading score leads to an in increase in the total score. Therefore, for a student's performance to increase, the reading score should also increase.

The correlation coefficient between total score and math is 0.92, which is just a bit lower than between total score and reading(0.97) and writing(0.97). However, all these show a strong positive relationship between all the subjects and total score. It is interesting that the correlation of writing and reading with total score is similar, i.e., 0.97.

There is a closer ratio for the females who completed the preparation test and a distant ratio for males who completed the preparation test.

The students whose parents have an associate degree are the ones who mostly completed the preparation test. The students whose parents attended some college are the ones who mostly failed to complete the preparation test.

It is interesting to note that the students who receive standard lunch are the ones who mostly completed the preparation test. Similarly, the students who mostly did not complete the test preparation test are those who take standard lunch.

Multivariate Exploration: 

From the above interactions, it is interesting to note that lunch details, gender, parental education and completion of the test preparation course do not affect the relationship between the test scores. 

Therefore, it is good to conclude that based on this interactions, the overall score of a student can only be affected by the individual scores. The other features have very little or no effect on the relationship between the overall score and other tests.

## Key Insights for Presentation

Math score distribution is close to normal. Many students had a math score of between 60 and 80. 

Total score is a unimodal distribution with a peak at around 210 total score. Very few students had a total score of less than 100, with most students scoring a total of between 200 and 250 total score. Therefore, many students performed above average.

The students whose parents have an associate degree are the ones who mostly completed the preparation test. The students whose parents attended some college are the ones who mostly failed to complete the preparation test.

It is interesting to note that lunch details, gender, parental education and completion of the test preparation course do not affect the relationship between the test scores. Therefore, it is good to conclude that based on this interactions, the overall score of a student can only be affected by the individual scores. The other features have very little or no effect on the relationship between the overall score and other tests.

