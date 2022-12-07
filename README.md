# Neural_Network_Charity_Analysis

## Purpose
The purpose of this analysis was to identify if applicants will be successful if funded by Alphabet Soup by using Nueral networks.

## Results
### Data Preprocessing
* What variable(s) are considered the target(s) for your model?

classification,application type, affiliation

* What variable(s) are considered to be the features for your model?

Is Sucessful

* What variable(s) are neither targets nor features, and should be removed from the input data?

EIN, Name, USE_CASE

### Compiling, Training, and Evaluating the Model
* How many neurons, layers, and activation functions did you select for your neural network model, and why?

We chose 5 layers to get more complex learning, 16,8,4,2,1 neurons as this is a good way to get optimal results via doubling. We chose to use relu fucntions as the results are not linear.

* Were you able to achieve the target model performance?

We were not able to reach the target model.

* What steps did you take to try and increase model performance?

We added 2 more hidden layers, more nuerons and we removed use case.


## Summary 

Overall the model had an accuracy of .73 and a loss of .56. We removed USE_CASE using 50 epoch.

We recommend increasing the number of neurons and layers along with epochs.
