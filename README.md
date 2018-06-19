# Nick-Neural-Network
A Neural Network package I created from scratch. 

The Neural Network can be initiliased with the following parameters:
    Hidden_node_size
    Output_node_size
    Hidden_layers
    iterations
    alpha         (this is the alpha for calculating the new weights/thetas in backwards propogations)
    alpha_const   (this is the alpha for calculating the new weights/thetas of the constant variable in backwards propogations)
    momentum   (a momentum variable to reduce the cyclicality of alphas)

  All these parameters have defaults if not passed (see code for default settings)

This package fits a Neural Network to data given through Fit_NN()

  This takes 2 numpy array, one for the X variables and one for the target vairables.

  
Other functionalities are:

Score():
  This scores any data given from the fitted Neural Network.
  It takes an data in an Numpy array
  
ROC():
  This returns a ROC curve to measure performance of the the fitted function
  It takes numpy arrays of the Actual results and predicted results
  
Get_Parameters:
  Returns the parameters used in the Neural Network 
  
Get_Weights:
  Returns the weights of in the Neural Network
  
Get_Constants:
  Returns the constants of in the Neural Network
  
Get_Cost_History
  Returns a history of the costs for each iteration of the fitting of the Neural Network
  
Get_Output_History:
  Return Output history of the Neural Net for each iteration
  
  
  
  
  
  
  






