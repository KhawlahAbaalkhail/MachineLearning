# Support Vector Machines (SVM)

This assignment focuses on implementing and evaluating a Support Vector Machine (SVM) classifier using the Iris dataset. The project begins with importing the required Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn. After loading the dataset, exploratory data analysis (EDA) is performed to understand the structure of the data, including checking dataset information, statistical summaries, and species distribution.

Several visualization techniques are used, including pairplots and KDE plots, to explore the relationships between features and identify patterns between flower species. The dataset is then divided into training and testing sets using train_test_split.

An SVM model is created using SVC() from Scikit-learn and trained on the training dataset. Predictions are generated using the testing dataset, and the model performance is evaluated using a confusion matrix and classification report to measure accuracy, precision, recall, and F1-score.

To improve the model performance, hyperparameter tuning is applied using GridSearchCV, where different values of parameters such as C and gamma are tested to find the best model configuration. Finally, the optimized model is evaluated again to compare its performance with the original SVM model.
