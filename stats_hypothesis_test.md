# Notes on framework for bussiness experiments ii
## Statistical Hypothesis Testing

---

A statistical hypothesis test makes an assumption about the outcome, called the null hypothesis.

For example, 
the null hypothesis for the Pearson’s correlation test is that there is no relationship between two variables. **The null hypothesis for the Student’s t test is that there is no difference between the means of two populations.** or in little words **are the samples the same??**.|

The test is often interpreted using a p-value, which is the probability of observing the result given that the null hypothesis is true, not the reverse, as is often the case with misinterpretations.

**p value** help us decide if we should reject the null hypotesis (H0:samples are the same)

**p-value (p)** : Probability of obtaining a result equal to or more extreme than was observed in the data.
In interpreting the p-value of a significance test, you must specify a significance level, often referred to as the Greek lower case letter alpha (a). A common value for the significance level is 5% written as 0.05.

The p-value is interested in the context of the chosen significance level. A result of a significance test is claimed to be “statistically significant” if the p-value is less than the significance level. This means that the null hypothesis (that there is no result) is rejected.

**P-value (p)** : Are numbers between 0 and 1 that quantify how confident we should be that sample A is different than smaple B.

**the closest to zero** the more sure the samples are different. a p values threshold of 0.05 is pretty common in the science world, and it means  that every 100 experiments we will get 1 **false positives**. 0.2 is 2 out of 10.

**Hypotesis testing** : Having two samples is the idea of trying to determinate if they are the same or not.


As we remember the **p value** help us decide if we should reject the null hypotesis (H0:samples are the same):

**p <= alpha: reject H0**, different distribution. go on the experiment could be worth.

**p > alpha: fail to reject H0**, same distribution.

Where:

Significance level (alpha): Boundary for specifying a statistically significant finding when interpreting the p-value.
We can see that the p-value is just a probability and that in actuality the result may be different. The test could be wrong. Given the p-value, we could make an error in our interpretation.

#There are two types of errors; they are:

**tp --|-- fp**
   
**fn --|-- tn**

**Type I Error**. Reject the null hypothesis when there is in fact no significant effect (false positive). The p-value is optimistically small.

**Type II Error**. Not reject the null hypothesis when there is a significant effect (false negative). The p-value is pessimistically large.
