# BankUnitedTest

## Take Home Exercise

> 1)	Attached are two csv files. In the programing language of your choice merge the file “Loan Risk.csv” to the file “Loan Position.csv” only keeping the loan numbers in the file “Loan Position.csv”.  The Loan Position file contains the LoanNumber and the Balance on the loan. The Loan Risk file contains the LoanNumber with the corresponding Probability of Default (PD) and Loss Given Default (LGD). 
> 2)	There is missing risk data. Replace the missing data with the average in the data set. Why did you choose the method you applied to determine the average? 
> 3)	Create a random variable called RV for each loan that is uniformly distributed between 0 and 1. Create a second variable called Flag that is a 1 if the random variable generated is less than the Probability of Default (PD). What does this new variable represent? 
> 4)	Create another variable that multiplies Flag with LGD and Balance. What does this new variable represent? 
> 5)	Sum the variable created in the prior step across all loans. What does this variable represent? 
> 6)	Create a loop that runs steps 3-5 10,000 times and stores the variable created in step 5 in a dataset. The final dataset should have 10,000 observations of the sum in step 5. To be clear for each simulation you will store the sum created in step 5 for 10,000 observations of this sum.
> 7)	Consider the final dataset of 10,000 observations. What is the mean of the dataset? What does the mean of the dataset represent? What is the 95th percentile of the dataset? What would the 95th percentile of the dataset represent? What could be causing the difference between the mean and the 95% percentile? How could we reduce the 95th percentile of the dataset?
   
