# deep-learning-challenge


Background
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With your knowledge of machine learning and neural networks, you’ll use the features in the provided dataset to create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, you have received a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.


Steps to analyze the data include: 
-Preprocess the data
-Compile, Train, and Evaluate the Model
-Optimize the Model
-Write a Report on the Neural Network Model


Report: 

Overview of the analysis: Supporting a nonprofit foundation, Alphabet Soup, by creating a tool/model that will help select applicants for funding that have the best chance of success. 

Results: Following the processing of the data, followed by optimization done 3 times, an accuracy rate of 73% was achieved. This was done by adding layers and changing the number of neurons in each layers to optimize the model. 

Data Preprocessing:

1) What variable(s) are the target(s) for your model? IS_SUCCESSFUL was the target variable 
2) What variable(s) are the features for your model? Features included all other data columns except IS_SUCCESSFUL column
3) What variable(s) should be removed from the input data because they are neither targets nor features? EIN and NAME were removed from this analysis
 
Compiling, Training, and Evaluating the Model:

1) How many neurons, layers, and activation functions did you select for your neural network model, and why? Three optimization models were ran that included increasing the number of layers and neurons. 
2) Were you able to achieve the target model performance? From the three models ran, 73% was achieved
3) What steps did you take in your attempts to increase model performance? Add additional layers and change the number of neurons

Summary: Although the target accuracy of 75% was not achieved, the process by which optimization and deep learning was applied. Overall the using TensorFlow and Keras did allow for a 73% accuracy in the optimization process that Alphabet Soup can utilize. Additional iterations may lead to meeting the targeted accuracy level. 

