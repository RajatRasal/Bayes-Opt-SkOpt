# Simple Bayesian Search using Scikit-Optimise
---
## Outline
The purpose of this notebook is do to a rudimental analysis of the **Bank Marketing Data Set** to reach a reasonable degree of accuracy when predicting whether a client will subscribe to a term deposit, and then perform a simple **Bayesian search** using the *scikit-optimise* Python library to find a (near) optimal learning rate. 

>  *The data is related with direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe a term deposit (variable y).* - [UCI Machine Learning Repositry](https://archive.ics.uci.edu/ml/datasets/bank+marketing)


### Business Application
In a business setting, a detailed analysis of this dataset might be done to determine how to be go about a telemarketing campaign. By performing an accurate prediction, we get a better sense of which features most affect the chance of a customer subscribing to a particular service provided by the bank. The bank can then focus their efforts on the features which increase the likelihood of the customer subscribing to a service. 

### Academic Application
From an academic standpoint, this analysis is a good way to understand how to use the *scikit-optimise* library to perform Bayesian Optimisation. This may not be the best library to perform a Bayesian search, however this is well known to be a easy to use and provide a wide range of functionality. From some prior reading, this dataset is imbalanced. A major challenge when analysing this will arise from how to handle this, without causing a large bias in the results or overfitting due to the majority label.

## Bayesian Search (taken from notebook)
Below is the Bayesian search algorithm used. Specifics have been removed by can be found in the notebook. **Click on the image below to go to a gist for this code**.

<a href="https://gist.github.com/RajatRasal/8bdc3dc7e71900d61a36a833bf161be3">![bayesian code snippet](./bayesian_code.png)</a>
