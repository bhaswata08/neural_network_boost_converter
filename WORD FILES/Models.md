# 1. KNN:
## Distance function: 
* Euclidian $$\sqrt{\sum_{i=1}^k(y_i-\hat{y_i})}$$
## Advantages: 
1. Lazy learner
## Disadvantages:
1. Lazy Learner
2. Low dimensionality
## Difference between KNNUnif and KNNDist
- **KNNUnif**: This stands for k-Nearest Neighbors Uniform. In this model, all neighbors have equal vote in the prediction. This means that each of the k nearest neighbors has the same influence on the outcome, regardless of their distance from the target point.

- **KNNDist**: This stands for k-Nearest Neighbors Distance. In this model, closer neighbors have more influence on the prediction than those further away. This means that each of the k nearest neighbors weighs their vote according to their distance to the target point. The closer a point is, the more it influences the prediction.