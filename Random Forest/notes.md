
## 
===> 


## Random Forest algorithm
===> Random forest is a supervised learning algorithm. It has two variations – one is used for classification problems and other is used for regression problems. It is one of the most flexible and easy to use algorithm. It creates decision trees on the given data samples, gets prediction from each tree and selects the best solution by means of voting. It is also a pretty good indicator of feature importance.

Random forest algorithm combines multiple decision-trees, resulting in a forest of trees, hence the name Random Forest. In the random forest classifier, the higher the number of trees in the forest results in higher accuracy.


## Random Forest algorithm intuition 
===> Random forest algorithm intuition can be divided into two stages.

In the first stage, we randomly select “k” features out of total m features and build the random forest. In the first stage, we proceed as follows:-

Randomly select k features from a total of m features where k < m.
Among the k features, calculate the node d using the best split point.
Split the node into daughter nodes using the best split.
Repeat 1 to 3 steps until l number of nodes has been reached.
Build forest by repeating steps 1 to 4 for n number of times to create n number of trees.
In the second stage, we make predictions using the trained random forest algorithm.

We take the test features and use the rules of each randomly created decision tree to predict the outcome and stores the predicted outcome.
Then, we calculate the votes for each predicted target.
Finally, we consider the high voted predicted target as the final prediction from the random forest algorithm.


## Difference between Random Forests and Decision Trees
===> I will compare random forests with decision-trees. Some salient features of comparison are as follows:-

Random forests is a set of multiple decision-trees.
Decision-trees are computationally faster as compared to random forests.
Deep decision-trees may suffer from overfitting. Random forest prevents overfitting by creating trees on random forests.
Random forest is difficult to interpret. But, a decision-tree is easily interpretable and can be converted to rules.


## 
===> 


## 
===> 














