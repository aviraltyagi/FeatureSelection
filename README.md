## FeatureSelection

What is Feature Selection?

It is the process of identifying and selecting a subset of variables from the original data set to use as inputs in a machine learning model. Some predictive modeling problems have a large number of variables that can slow the development and training of models and require a large amount of system memory. Additionally, the performance of some models can degrade when including input variables that are not relevant to the target variable.

We can summarize feature selection as follows:
1) Feature Selection: Select a subset of input features from the dataset.
    - Unsupervised: Do not use the target variable (e.g. remove redundant variables).
        a) Correlation
    - Supervised: Use the target variable (e.g. remove irrelevant variables).
        a) Wrapper: Search for well-performing subsets of features.
            - RFE
        b) Filter: Select subsets of features based on their relationship with the target.
            - Statistical Methods
            - Feature Importance Methods
        c) Intrinsic: Algorithms that perform automatic feature selection during training.
            - Decision Trees
2) Dimensionality Reduction: Project input data into a lower-dimensional feature space.



Advantages of Feature Selection.
1) Better interpretability
2) Reduced redundancy
3) Shorter training times
4) Simpler production code


