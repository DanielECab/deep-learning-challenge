Overview of the analysis: Explain the purpose of this analysis.

The purpose of this anaylsis is to predict if applicants for Alphabet Soup will be succesful after receiving funding from the non profit.

Results: Using bulleted lists and images to support your answers, address the following questions:

What variable(s) are the target(s) for your model?
*Target variables were the IS_SUCCESFUL column data from the CSV.

What variable(s) are the features for your model?
*Classifications which were the application types
*Income amounts for each classification
*Special Considerations
*Asking amount for each data set

What variable(s) should be removed from the input data because they are neither targets nor features?
I would say special considerations should be removed from the data as they are probably no necessary to the data set. As well as name and EIN which were removed from the very start since they do not contribute to the model in any way.

How many neurons, layers, and activation functions did you select for your neural network model, and why?
I had 3 layers in total, the first layer at 75 nuerons, the second at 50 and the third and 25. Activation function used was sigmoid, which was picked because it is the model im comfortable with using. 

Were you able to achieve the target model performance?
No, I was unable to hit the target of 75% accuracy.

What steps did you take in your attempts to increase model performance?
I tried different amounts of nuerons, even cutting it down to one layer. As well as reducing the epochs. Eventually I settled on a larger amount of nuerons decreasing per layer, and moving the epochs to 100. This led to some of the accuracy scores reaching 74% but the average was still sitting at around 73.4%

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and then explain your recommendation. 
Overall the results for this model were not the best, I was not satisfied with the accuracy being under 75%. As far as using a different model I dont have a reccomendation as to what would be best for this dataset.