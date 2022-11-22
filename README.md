# KNN Classification

K Nearest Neighbor
KNN is based in feature similarity. We can do classification using KNN Classifier.

K Nearest Neighbor is one of the simplies Supervised learning algorithms.

It classifies a data point based on how its neighbors are classified.

KNN stores all available cases and classifies new cases based on a similarity measure.

### What is *k* in KNN?

k is a parameter that refers to the number of nearest neighbors to include in the majority voring process.
Choosing the right value of a *k* is a process called parameter tuning and it is important for better accuracy.

To choose a value for *k*:

√n, where n is the total number of data points
use GridSearchCV
In case of two classes choose odd *k* value to avoid confusion.

### When do we use KNN?

Data is labeled,
Data is noise free (clean)
Data is small.
KNN is a lazy learner, we don't use it with large data, because ut doesn't learn from the training set immediately, instead, it stores the dataset and at the time of classification, it performs an action on the dataset.

USE CASE: Predict if a person has diabetes or not.
