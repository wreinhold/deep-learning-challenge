## deep-learning-challenge

## Overview of the analysis: 
This repository was created for an assignment in the UNC Chapel Hill Data Science Bootcamp. The goal was to create a tool to aid a non-profit, Alphabet Soup, in selecting applicants for funding. They wanted to be able to select those with the highest chance for success. I aimed to accomplish this by building a Neural Network on Google Collab. I was given a CSV with over 34,000 records of past recepients that included vital data around their specific requests and the ensuing results from the fundings. 

## Results:

# Data Preprocessing
  * The target for the model was the column "IS_SUCCESSFUL."
  * The features that I used were Application Type, Industry Affiliation, Government Organization Classification, Use Case, Organization Type, Active Status, Income Classification, Special     Considerations for the Application, and Funding Amount Requested.
  * There were also fields for their ID and Organization Name that were removed.

# Compiling, Training, and Evaluating the Model
  * After optimizing my model, I ended with 2 hidden layers and the output layer.
    * There were 20 and 15 neurons respectively.
    * I tested adding more neurons and output layers, however, the accuracy dipped with both.
  * The closest attempt towards target model performance was when I increased the epochs to 150, from 100 with the other attempts.
  * I was ultimately was unable to reach the target model performance. 

## Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.

While the overall results of the deep learning model were unsuccessful, I believe that with more attempts the problem could be solved. After some more reflection, I believe some fields around the Organizations Classification could be reduced as they are likely more redundant. Furthermore, it would be beneficial to use a tool like KerasTuner to determine the best activation function. Increasing the epochs further could also help in the next iteration of the deep learning model.
