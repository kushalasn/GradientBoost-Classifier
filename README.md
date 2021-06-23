# GradientBoostAlgo
Ensembles are constructed from decision tree models. Trees are added one at a time to the ensemble and fit to correct the prediction errors made by prior models. This is a type of ensemble machine learning model referred to as boosting.
Naive gradient boosting is a greedy algorithm and can overfit the training dataset quickly.
It can benefit from regularization methods that penalize various parts of the algorithm and generally improve the performance of the algorithm by reducing overfitting.
There are three types of enhancements to basic gradient boosting that can improve performance:
Tree Constraints: such as the depth of the trees and the number of trees used in the ensemble.
Weighted Updates: such as a learning rate used to limit how much each tree contributes to the ensemble.
Random sampling: such as fitting trees on random subsets of features and samples.
The use of random sampling often leads to a change in the name of the algorithm to “stochastic gradient boosting.

Gradient Boosting Hyperparameters
In this section, we will take a closer look at some of the hyperparameters you should consider tuning for the Gradient Boosting ensemble and their effect on model performance.

There are perhaps four key hyperparameters that have the biggest effect on model performance, they are the number of models in the ensemble, the learning rate, the variance of the model controlled via the size of the data sample used to train each model or features used in tree splits, and finally the depth of the decision tree.

We will take a closer look at the effect each of these hyperparameters in isolation in this section, although they all interact and should be tuned together or pairs, such as learning rate with ensemble size, and sample size/number of features with tree depth.
