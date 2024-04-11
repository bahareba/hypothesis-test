# <span style='color:darkorchid'> Hypothesis test: Two-Sample t-test <br> Comparing Literacy Rates </span>

## Project Overview
This project analyzes literacy rates in two large states, STATE21 and STATE28, to determine if there's a significant difference in their average district literacy rates. The Department of Education requires this information to allocate resources effectively for improving literacy.


We are going to make randome sample, conduct a two-sample hypothesis test to see is the difference statistically significant or not? 



<br> This project has 4 parts:
* Business Problem
* Data Understanding
* Modeling and Evaluation
* Conclusion

 
## Part 1: Business Problem
<img src="images/problem_10266358.png" width="100" height="100" align=left  >
Department of Education asks to collect data on mean district literacy rates for two of the nation’s largest states: STATE21 and STATE28. <br> STATE28 has almost 40 districts, and STATE21 has more than 70.
<br> Due to limited time and resources, we are only able to survey 20 randomly chosen districts in each state. 
<br> The department asks to determine if the difference between the two mean district literacy rates reflect a true difference between the state populations or it is just due to chance.
<br> This will help the department decide how to distribute government funding to improve literacy.
<br> If there is a statistically-significant difference, the state with the lower literacy rate may receive more funding. 




## Part 2: Data Undrestanding
<img src="images/survey_10266430.png" width="100" height="100" align=left  >

After EDA phase, we'll: 
* Simulate taking a random sample of 20 districts in each state.
* Conduct a two-sample t-test based on the sample data.

 


## Part 3: Modeling and Evaluation
 <img src="images/creative-writing_10266412.png" width="100" height="100" align=left  >
 * Here we can see that, based on sample data, the observed difference between the mean district literacy rates of STATE21 and STATE28 is almost 5%. 
<br> But due to sampling variability, this observed difference might simply be due to chance, rather than an actual difference in the corresponding population means. 
<br> At this point, we use a hypothesis test to determine whether or not the results are statistically significant.


### Conduct a hypothesis test
#### The two-sample t-test is the standard approach for comparing the means of two independent samples.
*   $H_0$: There is no difference in the mean district literacy rates between STATE21 and STATE28.
*   $H_A$: There is a difference in the mean district literacy rates between STATE21 and STATE28.




###  <span style='color:darkorchid'> significance level is 5% or 0.05 </span>
* The p-value is about 0.0170 or 1.7%.
* This means there is only a 1.7% probability that the absolute difference between the two mean district literacy rates would be 5 percentage points or greater if the null hypothesis were true. 
* In other words, it’s highly unlikely that the difference in the two means is due to chance.




## Part 4: Conclusion
<img src="images/value_10266329.png" width="100" height="100" align=left  >

The p-value of 1.7%, is less than the significance level of 5%. 
 


### <span style='color:darkorchid'> Therefore, we will reject the null hypothesis and conclude that there is a statistically significant difference between the mean district literacy rates of the two states: STATE21 and STATE28. </span>


### <span style='color:navy'> Since there is a statistically significant difference in mean district literacy rates, the state with the lower literacy rate, STATE28, will likely receive more resources to improve literacy.  </span>


