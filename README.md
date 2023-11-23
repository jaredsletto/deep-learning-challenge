# deep-learning-challenge
Module 21 Challenge

## Report on the Neural Network Model

# Overview of the analysis:  
The nonprofit foundation Alphabet Soup wanted a tool that can help it select the applicants for funding with the best chance of success in their ventures. I used the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

# Results:
<b>Data Preprocessing </b><br><br>
<b>What variable(s) are the target(s) for your model? </b><br>
The Target Variable or Column is ‘IS_SUCCESSFUL’<br><br>
<b>What variable(s) are the features for your model? </b><br>
The features I used were: <br>
APPLICATION_TYPE <br>
AFFILIATION <br>
CLASSIFICATION <br>
USE_CASE <br>
ORGANIZATION <br>
STATUS <br>
INCOME_AMT <br>
SPECIAL_CONSIDERATIONS <br>
ASK_AMT <br><br>
<b>What variable(s) should be removed from the input data because they are neither targets nor features? </b><br>
I removed ‘EIN’ and ‘Name’ as they were not features or targets. <br><br>
<b>Compiling, Training, and Evaluating the Model </b><br><br>
<b>How many neurons, layers, and activation functions did you select for your neural network model, and why? </b><br>
I chose to add a third and fourth layer to use an additional layer with each activation, ‘relu’ and ‘sigmoid’. <br><br>
<b>Were you able to achieve the target model performance? </b><br>
I was able to achieve the 75% target accuracy. <br><br>
<b>What steps did you take in your attempts to increase model performance? </b><br>
I increased my epoch to 100 and removed 2 features. I added the names back into the data set to increase the number of bins. <br><br>

# Summary:
To summarize, I was successful in creating a tool that can help it select the applicants for funding with the best chance of success in their ventures. It took many attempts, but Alphabet Soup can use this. A linear regression model would also be a good alternative to this. We would not be too concerned with applicants that would be successful and were not selected but would be concerned with applicants that are selected and not successful. We could monitor the Precision over the recall. 
