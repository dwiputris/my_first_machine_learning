# my_first_machine_learning
In this project, a model is built to predict a subscription plan a telco's customers will choose. The telco, Megaline, is looking for a potential in increase revenue by appealing more customers to its more premium package, called Ultra. Given a dataset of its current subscribers' monthly average use of calls, messages, and internet data, a machine learning is built to classify if a user will subscribe for Ultra or not. Three algorithms are tried in this project:

1. Decision Tree Classifier,
2. Random Forest Classifier, and
3. Logistic Regression

The project is started by observing the datasets, and some exploratory data analysis. It is then continued by experimenting with the three algorithms. The experiments incorporate some tuning of hyper-parameters in order to find a combination of ones that result in the best validation metric, that is accuracy score.

Before conclusion of the best performing model between the three, a sanity check is done to the best model. For an imbalanced dataset, it is easy to get a high accuracy score by simply classifying all observations as the majority class. Hence for this imbalanced dataset, validation metrics: precision and recall, are checked.

It is found that the chosen model has accuracy score and precision of above 80%, recall for non-Ultra above 90%, and recall for Ultra around 50%.
