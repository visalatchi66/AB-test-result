# AB-test-result

## Introduction:
This project is to understand the results of an A/B test run by an e-commerce website. The goal is to work through this notebook to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.

This experiment involves steps that include:
1. Finding probability
2. A/B test
3. Regression

## Finding probability:
Given that an individual was in the control group,the probability of conversion is 0.1204.Given that an individual was in the treatment group, the probability of conversion is 0.1189.The old page seems to be leading in conversion when compared to the new page.But there are limitations as to potentially influencing factors are not considered.

## A/B Test:
The z-score is lesser than the critical value.Therefore we fail to reject the null hypothesis that the performance of old page is better than new page.

## A regression approach:
 Since the p-value is zero,we fail to reject the null-hypothesis.i.e. the conversion rate in better for old page than new page.
 
 ## Conclusion:
 From all the techniques it's proven that we fail to reject the null hypothesis and the performance of old page is better than the new page given the limited data in hand. 
