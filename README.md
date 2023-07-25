# deep-learning-challenge
Module 21 Challenge


- Overview of the analysis: Explain the purpose of this analysis.
  - The purpose of this analysis is to determine the charactistics that determine whether a non-profit will successfully use the grant money awarded.

- Results: Using bulleted lists and images to support your answers, address the following questions:

* Data Preprocessing
        * What variable(s) are the target(s) for your model?
                * the variable IS_SCCUSSFUL
        * What variable(s) are the features for your model?
                * status
                * ASK_AMT
                * APPLICATION_TYPE
                * CLASSIFICATION
                * INCOME_AMT
                * ASK_AMT
        * What variable(s) should be removed from the input data because they are neither targets nor features?
                * EIN
                * NAME
                *SPECIAL_CONSIDERATION
                * USE_CASE
                * ORGANIZATION
* Compiling, Training, and Evaluating the Model
        * How many neurons, layers, and activation functions did you select for your neural network model, and why?
                * 126
                * 3 layers
                * 2 relu layers and one sigmoid
        * Were you able to achieve the target model performance?
                * This model acheived 70% accuracy, so was unable to hit the 75% target. I tried numerous combinations of laters, activation functions, and units, with the majority of the outcomes only acheiving 53% accuracy.
        * What steps did you take in your attempts to increase model performance?
                * I tried numerous combinations of laters, activation functions, and units, with the majority of the outcomes only acheiving 53% accuracy.
                * Attempted removing classification data to simplify the model
                * increased the amount of units per layer
                * tried fewer layers (2) and more (4)
                * used different combinations of activations functions, including tanh, relu, selu,elu, sigmoid.
- Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
        * this model has a fairly decent accuracy percentage by not ideal. For determining the likelihood of success for chairities receiving money, it would be better to find a model with a slightly better accuracy rating. This may include adding some data back into the dataframe, or using different activation functions.
