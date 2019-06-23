# racial-discrimination
Springboard project for EDA and hypothesis testing in Python

### Background:

Racial discrimination continues to be pervasive in cultures throughout the world. Researchers examined the level of racial discrimination in the United States labor market by randomly assigning identical résumés to black-sounding or white-sounding names and observing the impact on requests for interviews from employers.

Data
In the dataset provided, each row represents a resume. The 'race' column has two values, 'b' and 'w', indicating black-sounding and white-sounding. The column 'call' has two values, 1 and 0, indicating whether the resume received a call from employers or not.

Note that the 'b' and 'w' values in race are assigned randomly to the resumes when presented to the employer.

### Results:

Both hypothesis tests rejected the null hypothesis. This means that the true difference of means was not equal to zero.

In other words, the sound of the name, whether black or white, did likely have an effect on the number of call backs applicants received. On the other hand, the confidence interval for the bootstrap approach was arbitrarily close to zero with a small margin of error. The two sample t-test also included zero it its confidence interval with a relatively small margin of error.

This contradicts the hypothesis test results. Since the names were assigned randomly, it is hard to check for lurking variables in the applicants themselves.

It is likely that race is not the most important factor for callbacks while it does seem to have influence. Other factors such as education and years of experience likely play a large role in the selection process too.

I would add these factors into my analysis by bucketing groups further. Checking for resumes with similar amounts of experience, and then checking the effect of the names.



Data: EDA_racial_discrimination/data

Code: EDA_racial_discrimination/sliderule_dsi_inferential_statistics_exercise_2.ipynb

