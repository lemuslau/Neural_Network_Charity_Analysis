# Neural Network Charity Analysis

## Overview:
The purpose of this analysis was to create a binary classifier by using a neural network to decide which companies should recieve loans from Alphabet Soup. This analysis uses python's TensorFlow library to create, train, and evaluate data gathered from previous loans.

## Results:

Data Preprocessing
What variable(s) are considered the target(s) for your model?
- The target varibale in this model was the "IS_SUCCESSFUL" column.

What variable(s) are considered to be the features for your model?
- Features excluding the EIN and Name columns are features for the model 

What variable(s) are neither targets nor features, and should be removed from the input data?
- Unnecessary data that were not targets or features were the EIN and Name columns. 

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- In the initial model I used 2 layers, with neurons 8 and 5 with provided me with 731 trainable params but with accurancy of 73%. 
Were you able to achieve the target model performance?
- After the 3 tries for optimization I was unable to raise my models accurancy past 73%.
What steps did you take to try and increase model performance?
- For my 3 attempts I attempted to change the neourons to a higher number with different epochs. 
<img width="415" alt="Optimization 1" src="https://user-images.githubusercontent.com/102635884/189710227-4042295f-8d70-469a-8f12-26c64ec7d2df.PNG">

<img width="424" alt="Optimization 2" src="https://user-images.githubusercontent.com/102635884/189710265-ffeea38c-fb81-4a64-ab27-2accbbbb16f5.PNG">

<img width="426" alt="Optimization 3" src="https://user-images.githubusercontent.com/102635884/189710294-ee65fdf6-d495-4d22-8682-c0c353e40c24.PNG">

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
- Due to the fact that I changed my neorons I would consider adding additional layers as the next recommendation as that could play a role in improving accurancy.. 
