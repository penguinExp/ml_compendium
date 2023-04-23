## Supervised Learning

Supervised learning is a type of machine learning where the algorithm is trained on a labeled dataset. Labeled data means that the input data is already tagged with the correct output. The goal of supervised learning is to learn a function that can accurately predict the output for new, unseen inputs.

Here's an example of how supervised learning works:

Let's say you work for a bank that wants to build an algorithm to predict whether a customer will default on their loan. You have a dataset of past customers with their loan history and whether they defaulted or not. This is a labeled dataset, because each customer in the dataset is tagged with their correct label (defaulted or not). Look at the data below

| Age | Income | Loan Amount | Default |
| --- | ------ | ----------- | ------- |
| 35  | 50000  | 20000       | 0       |
| 28  | 40000  | 15000       | 0       |
| 45  | 60000  | 30000       | 1       |
| 30  | 55000  | 25000       | 0       |
| 50  | 70000  | 40000       | 1       |
| 32  | 48000  | 18000       | 0       |
| 38  | 65000  | 35000       | 1       |
| 42  | 75000  | 45000       | 1       |
| 27  | 35000  | 12000       | 0       |
| 36  | 58000  | 28000       | 0       |

With the help of this data we can train our supervised algorithm to find patterns and predict on upcoming data

#### There are two main types of supervised learning:

1. **Classification**: In classification, the goal is to predict a categorical or discrete value for a given input. The input can have one or more features, and the output is a label that represents a category or class. Examples of classification problems include email spam detection, image recognition, and predicting whether a customer will buy a product or not.

2. **Regression**: In regression, the goal is to predict a continuous value for a given input. The input can have one or more features, and the output is a numeric value. Examples of regression problems include predicting house prices based on their features such as location, number of bedrooms, and square footage, and predicting the amount of rainfall in a given region based on various weather factors.

