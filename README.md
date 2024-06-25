# Spark-Machine-Learning

A Spark Machine Learning predictive analysis of Titanic Survival Data, Low Birth Weight Data, and discussion of Spark concepts.

This was a Spark-based project written in Python. It used a logistic regression model to obtain a 77.6% accuracy predicting Titanic survivors. It all used 6 models to predict whether an infant would have low or healthy birth weight. There was a logistic regression, naive bayes, and gradient boosting model, and these were run twice: once with the original dataset, and once with the minor target class values duplicated to account for heavy imbalance. This saw an accuracy of 81.4% (logistic regression) and recall of 70.6% (naive bayes, using duplication).

"SparkML_Fitch.pdf" contains the text of the analysis along with the supporting figures and tables. 
For the Titanic data, "MachineLearning_Titanic_Fitch.ipynb" contains the Python notebook and "MachineLearning_Titanic_Output_Fitch" is the resultant HTML file.
For the Low Birth Weight data, "MachineLearning_LowBirthWeight_Fitch.ipynb" contains the Python notebook and "MachineLearning_LowBirthWeight_Output_Fitch_Models 1-3" is the resultant HTML file for the first set of models, while "MachineLearning_LowBirthWeight_Output_Fitch_Models 4-6" is the file for the second set of models.
