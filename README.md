# BayesianTextClassifierFromScratch
Implement the Bayesian Text Classifier Without Using any Library

Here is a notebook in which I implemented the Bayesian binary classifier from scratch. There is no library to be imported, even Numpy. Firstly I tested the performance on a very small dataset to make sure that the code is working. Then, I used a larger dataset with a length of 1000. The accuracy of the model is 85.3% on this dataset. The dataset includes 1000 comments which are either negative or positive.  Despite the fact that this model is working quite well, it is not able to correctly classify "It was not bad". The model cannot detect relations between words and so is not able to figure out the fact that "not" and "bad" negates each other. That is the main reason why RNNs and LSTM units are widely used to do the same task.
