# my_first_machine_learning
In this project, the best model is searched to predict a subscription plan for a telco's customers. 
The telco, Megaline, is looking for a potential in increse revenue by appealing more customers to its more premium package, called Ultra.
Given a dataset of its current subscribers on their monthly calls, messages, and internet data use, a machine learning is built to classify if a user shall subscribe for Ultra or not.
Three algorithms are tried in this project:
1. Decision Tree Clasifier,
2. Random Forest Classifier, and
3. Logistic Regression

The project is started by observing the dataset, and doing some exploratory data analysis.
It is then continued by experimenting the three algorithm. 
The experiment incorporate some tuning of hyperparameters in order to  find combination of ones that result in the best metric of accuracy score.

Before conclusion of the best performing model between the three, a sanity check is done to the best model.
Given that the target observed data is imbalance, validation metrices: precision and recall, are checked.
This is to make sure that the precision and recall for each of two targets are sufficient, so that a blind guess will not lead to a wrong conclusion on the performace of the choosen model.
