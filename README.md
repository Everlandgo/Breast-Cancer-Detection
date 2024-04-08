# Breast-Cancer-Detection
The aim of the project is to identify the best machine learning algorithm for breast cancer
classification using the Breast Cancer Wisconsin dataset. Logistic regression, random forest,
decision tree, bayesian classification and k-nearest neighbour were chosen as candidate
algorithms. Before anything, due to an initial imbalance of the dataset, oversampling was
performed to achieve a balanced dataset.Then for each algorithm, to achieve the optimum
performance of the models, hyperparameter tuning was conducted with k fold cross
validation. After collecting the best hyperparameters, new model sets were trained for each
algorithm using the best hyperparameters. The test set was then used to collect predictions
of the model for performance evaluation. Evaluation metrics including accuracy, precision,
recall, and F1 score were employed. The results indicated that Logistic Regression has the
best performance among the five selected classification algorithms, making it a promising
choice for breast cancer classification tasks.

<img width="703" alt="Screenshot 2024-04-08 at 11 13 46 PM" src="https://github.com/Everlandgo/Breast-Cancer-Detection/assets/104118335/1062e602-149c-4d9e-9c79-d34b0c1a1d09">
