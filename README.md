# auto-sklearn Examples on Jupyter Notebooks
The motivation of this repository is to show the result of `auto-sklearn` examples.

## Install
You can install `auto-sklearn` and related libraries with the following command:
```
pip install -r requirements.txt
```

## Conclusion
auto-sklearn would be super useful to train better models without thinking feature preprocessing and algorithms carefully.
It is basically implemented on top of the scikit-learn pipeline interface.

- auto-sklearn allows us to train models using cross-validation simply.
- auto-sklearn supports a bunch of metrics for both of classification and regression.
- auto-sklearn allows us to train models in parallel using `multiprocessing` library.
- auto-sklearn allows us to do one-hot-encoding and some feature preprocessing automatically setting each attribute type to numerical or categorical.

## What is auto-sklearn?

[What is auto\-sklearn? — AutoSklearn 0\.2\.0 documentation](https://automl.github.io/auto-sklearn/stable/index.html#)

> auto-sklearn is an automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator:
```
>>> import autosklearn.classification
>>> cls = autosklearn.classification.AutoSklearnClassifier()
>>> cls.fit(X_train, y_train)
>>> predictions = cls.predict(X_test, y_test)
```
> auto-sklearn frees a machine learning user from algorithm selection and hyperparameter tuning. It leverages recent advantages in Bayesian optimization, meta-learning and ensemble construction. Learn more about the technology behind auto-sklearn by reading this paper published at the NIPS 2015.

