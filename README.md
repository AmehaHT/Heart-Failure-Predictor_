# Heart-Failure-Predictor_

Introduction:

The Heart Failure Predictor is a project centered around developing a machine learning model to accurately predict heart failure occurrences utilizing Python and Scikit-Learn. Through meticulous data cleansing and employing logistic regression, an accuracy rate of 89% was achieved.

Tools and Technologies:

Python
Scikit-Learn for model development
Pandas for data cleansing
Seaborn for data visualization
Methodology:

1. Data Cleansing and Visualization:
   
Utilized various visualization techniques such as scatterplots, histograms, and box plots to identify missing data, outliers, and inconsistencies.
Employed Pandas for data filtering and cleansing, removing duplicates and filling missing values with column-wise mean or median.

2. Model Selection:
   
Selected Logistic Regression owing to its aptness for binary classification tasks.
Compared logistic regression's performance with other algorithms like decision trees and support vector machines, establishing logistic regression as the most accurate.

3. Model Training and Evaluation:
   
Addressed data imbalance by implementing oversampling, duplicating instances of the minority class to equalize class representation.
Employed cross-validation to ascertain model robustness and prevent overfitting.

Challenges:

Data Imbalance: Overcame this challenge by oversampling the minority class.
Model Selection: Through comparative analysis, ensured the chosen logistic regression model was the most fitting for the task.

Outcome:

Developed a machine learning model boasting an 89% accuracy rate in predicting heart failure, substantiating the model's potential as a reliable tool for early diagnosis and medical analytics.

Future Work:

Explore more sophisticated resampling techniques and delve into ensemble methods to further enhance model performance.
Examine feature importance and explore feature engineering to potentially uncover more insightful relationships within the data.
