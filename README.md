# deep-learning-challenge_reja
Module 21 Challenge

## Challenge Overview ##

In this comprehensive analysis, my goal is to empower the nonprofit foundation, Alphabet Soup, with a sophisticated tool to refine its grant allocation procedures. Drawing upon my learnings in machine learning and neural networks from my course, the central objective is to construct a binary classifier. This classifier will be designed using the various features present in the dataset provided.

The primary function of this classifier is to evaluate and predict the likelihood of success for applicants who receive funding from Alphabet Soup. In essence, it acts as a decision-making aid for the foundation, offering insights into which applicants are more likely to thrive in their endeavors with financial support.

To achieve this, a meticulous examination of the dataset is essential. This involves scrutinizing the diverse features and parameters to uncover patterns, trends, and correlations that can be utilized by the classifier. The aim is to develop a robust model that goes beyond simple prediction, providing Alphabet Soup with a powerful tool for making informed and strategic decisions in its grant allocation process.

Ultimately, the overarching objective is to enable Alphabet Soup to select applicants with the highest probability of success in their ventures. By leveraging the capabilities of machine learning and neural networks, this analysis aspires to enhance the foundation's ability to make impactful contributions to the endeavors it supports.

## KEY STEPS & RESULTS ##

## Preprocessing the Data  ##

1. What variable(s) are the target(s) for your model?
   - The dependent variable we are aiming to predict is found in the 'IS_SUCCESSFUL' column within the application_df dataset. 

2. What variable(s) are the features for your model?
   - The feature variables encompass the entirety of columns within the application_df, with the exception of "NAME" and "EIN," which were specifically excluded during the initial preprocessing steps. It's crucial to highlight that the column "IS_SUCCESSFUL" is intentionally omitted from the feature variables, as it functions as the target variable in our analysis rather than a predictor. This ensures that our model is trained to predict the outcome based on the other relevant features present in the dataset.

3. What variable(s) should be removed from the input data because they are neither targets nor features?

   - The variables "NAME" and "EIN" should be removed from the input data as they neither serve as target variables nor contribute as feature variables. The rationale behind their exclusion lies in the fact that these columns do not represent the target variable. It's crucial to emphasize that the 'IS_SUCCESSFUL' column is not considered part of the feature variables, as its role is designated as the target variable for prediction.


## Compiling, Training, and Evaluating the Model  ##

4. How many neurons, layers, and activation functions did you select for your neural network model, and why?
   - For the neural network model, I opted for a configuration with 80 neurons in the first layer and 30 neurons in the second layer during the original analysis. This choice was influenced by the sample results provided in the starter file. The rationale behind selecting this architecture was to establish a balance between model complexity and performance.
  
5. Were you able to achieve the target model performance?
   - By leveraging these configurations, the model achieved an accuracy of 72.4%. This approach was considered appropriate as it struck a practical balance in capturing the underlying patterns in the data without overfitting or introducing unnecessary complexity.
     
6. What steps did you take in your attempts to increase model performance? 

## Summary  ##
