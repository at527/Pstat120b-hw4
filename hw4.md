# Homework 4

Andrew Tran
pstat120b
2022-05-01

## Reading

Estimator
: A rule, often expressed as a formula, that tells how to calculate the value of an estimate based on the measurements contained in a sample.

Estimand
: The quantity to be estimated through statistical analysis.

---

## Let ${\hat{\theta}}$ be an estimator.

Bias
: The difference between the expected value of the estimates to the actual value of what's being estimated.
: ${Bias(\hat{\theta}) = E(\hat{\theta}) - \theta}$

Mean square error
: The average of the square of the distance between the estimator and its target parameter. Used to determine how well the estimator estimates the parameter.
: ${MSE(\hat{\theta}) = E[(\hat{\theta} - \theta)^2]}$

Absolute Error
: The differene between the estimator and the actual value of the parameter.

Unbiased
: When the expected value of the estimator equals the estimand.
: ${Bias(\hat{\theta}) = E(\hat{\theta}) - \theta} = 0$

Consistent
: An estimator is consistent when as the number of samples approaches infinity, the expected value of the estimator approaches the estimand.
: ${\lim_{n \to \infty}} P((\hat\theta - \theta) < \epsilon) = 1, \forall{\epsilon}$

---

Bias-variance decomposition of MSE
: ${MSE(\hat{\theta})} = Var(\hat{\theta}) + (Bias(\hat{\theta}))^2$

Weak law of large numbers
: The sample mean is consistent for the population mean. That is, as the number of samples approaches infinity, the average of the samples approaches the population mean.

Chebyshev's inequality
: ${P(|X-\mu| \geq k\sigma) \leq 1/k^2}$

Example of Unbiased estimator
: Mean estimated by ${\frac{1}{n}\Sigma_{i=1}^{n} X_i}$

Example of Consistent estimator
: Variance estimated by ${\frac{E(\Sigma_{i=1}^{n}(Y_i - \bar{Y})^2)}{n}}$