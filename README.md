# neural-network-challenge-2

## Overview
Create a neural network that HR can use to:
- predict whether employees are likely to leave the company.
- predict the department that best fits each employee.
  
Predict using a branched neural network.

### Details
1. Preprocessing
- Determine the number of unique values in each column.
- Create y_df with the attrition and department columns.
- Create a list of 10 column names to use as X data. 
- Create X_df using your selected columns.
- Split the data into training and testing sets.
- Convert X data to numeric data types. Fit any encoders to the training data, and then transform both the training and testing data.
- Create a StandardScaler, fit the scaler to the training data, and then transform both the training and testing data.
- Create a OneHotEncoder for the department column, then fit the encoder to the training data and use it to transform both the training and testing data.
- Create a OneHotEncoder for the attrition column, then fit the encoder to the training data and use it to transform both the training and testing data.

2. Create, Complie & Train the Model
- Find the number of columns in the X training data.
- Create the input layer. Do NOT use a sequential model, as there will be two branched output layers.
- Create at least two shared layers.
- Create a branch to predict the department target column. Use one hidden layer and one output layer.
- Create a branch to predict the attrition target column. Use one hidden layer and one output layer.
- Create the model.
- Compile the model.
- Summarize the model.
- Train the model using the preprocessed data.
- Evaluate the model with the testing data.
- Print the accuracy for both department and attrition.

3. Summary - briefly answer the following questions
- Is accuracy the best metric to use on this data? Why or why not?
- What activation functions did you choose for output layers, and why?
- Name a few ways that this model could be improved?


   
