# deep-learning-challenge
## Data Preprocessing

- What variable(s) are the target(s) for your model?
    - IS_SUCCESSFUL
- What variable(s) are the features for your model?
    - APPLICATION_TYPE
    - AFFILIATION	
    - CLASSIFICATION	USE_CASE	
    - ORGANIZATION	
    - STATUS	
    - INCOME_AMT	
    - SPECIAL_CONSIDERATIONS	
    - ASK_AMT
- What variable(s) should be removed from the input data because they are neither targets nor features?
    - EIN
    - NAME

## Compiling, Training, and Evaluating the Model

- How many neurons, layers, and activation functions did you select for your neural network model, and why?
    - Neurons: 80 for layer 1; 30 for layer 2
    - Layers: 2 Hidden layers, plus the output layer
    - Activation Functions: Relu and Sigmoid
        - Relu works well with non-negative values. It is one of the best deep learning models. It is also faster than Sigmoid. Sigmoid was not used in the hidden layer, because it can cause problems in training. 
- Were you able to achieve the target model performance?
    - I was only able to achieve about 72% accurracy for my models. 
- What steps did you take in your attempts to increase model performance?
    - I increased the number of bins for the classification and application values. I also added an additional hidden layer, and played around with different activation functions. Finally, I lowered and raised the number of epochs. Overall, they all seemed to produce little change to the accuracy of the models. 

## Summary: 
- Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation.
    - Overall, this model did fairly well at predicting if an applicant would be successful if funded by Alphabet Soup, with a 72% accuracy rate. We could use a random forest supervised learning model to produce similar results. 


## OverView:
- Information for this module came from in-class assignments and learning. Additional help was gathered from documentation on Google Drive and Google colab for downloading and saving .hdf5 files. 