# basicml
Code-First Basic Machine Learning. Part of Code With Rahul.


.
├── ClassificationOnTitanic.ipynb
├── ClassificationWithLogisticRegression.ipynb
├── data
├── images
├── LICENSE
├── README.md
└── results

1. Start with ClassificationWithLogisticRegression.ipynb . This notebook introduces the basic concepts of
Regression and Classification, in the context of a simple and simulated 1-feature classification problem. You
will learn about losses, probabilities, maximum likelihood, cross-entropy, the basic api of `sklearn`, and 
decision theory: the coversion of probabilities to classifications.
2. In ClassificationOnTitanic.ipynb we'll take a real world dataset (with simulation to create more data) and
see what we must do to make it amenable to classification using two different models: Logistic Regression, and
k Nearest-Neighbors. We'll illustrate one methods of dealing with categorical data. We'll motivate the scaling of
numerical data and how you must take care not toleak data into your problem from the future. We'll also learn about training sets, validation sets and test sets. We'll see that validation sets can be used either to test perfomance on future data, or
to pick complexity "hyperparameter"s which prevent the model from overfitting. We also see how to use your model on future data: the process of inference

As a post reading exercise, find out about regularization and the regularization hyperpaerameter C in Logistic regression. Use this knowledge to write code that produces a results table for logistic regression like the one in `results/results_lr.csv`
