# Machine-Learning
Answers to Q1 :

* linear regresion **MSE** and **R^2** in this case is better than lasso

* 
$R^2$ for test data versus ratio of training data:

* As the ratio of training data increases, the $R^2$ for the test data  increase for all three methods (linear regression, ridge regression, and lasso regression).

* For low ratios of training data, linear regression is likely to overfit the training data, resulting in a lower $R^2$ for the test data compared to ridge and lasso regression.

* Ridge and lasso regression are expected to perform better than linear regression in preventing overfitting, especially at lower ratios of training data. Their $R^2$ for the test data should be higher than linear regression.

* As the ratio of training data increases, the differences in $R^2$ between the three methods  decrease, as all models become better able to generalize to the test data.

* Selected α value versus training data ratio for ridge and lasso regression:

* The selected α value (the regularization parameter) is expected to decrease as the ratio of training data increases for both ridge and lasso regression.

* At lower ratios of training data, a higher α value is likely to be selected to impose stronger regularization and prevent overfitting.

* As the ratio of training data increases, the need for strong regularization decreases, and the selected α value should decrease accordingly.

* The behavior of the α value may differ between ridge and lasso regression. Lasso regression tends to select sparser models by setting some coefficients to exactly zero, while ridge regression shrinks all coefficients towards zero without setting any to exactly zero.
