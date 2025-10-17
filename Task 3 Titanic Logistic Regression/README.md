In this project, I built a logistic regression model to predict whether a passenger survived the Titanic disaster.
The idea was to use a few meaningful passenger details — like age, gender, ticket class, and fare — to see how well a simple model can predict survival.

Data Preparation

Loaded the classic Titanic dataset from Seaborn.

Removed columns that didn’t add much value (deck, class, who, alive, adult_male, alone, embark_town).

Handled missing values:

Age → filled with the median.

Embarked → filled with the most common port.

Converted text features to numbers:

sex: male = 0, female = 1

embarked: one-hot encoded (Q, S)

Final dataset → 891 rows × 9 columns.

Model Building

Split the data (80% train / 20% test)

Trained a Logistic Regression model using Scikit-learn

Target → survived

Features → pclass, sex, age, sibsp, parch, fare, embarked_Q, embarked_S

Results
Metric	Score
Accuracy	81 %
Precision (0 / 1)	0.83 / 0.79
Recall (0 / 1)	0.86 / 0.74
F1-Score (0 / 1)	0.84 / 0.76

Confusion Matrix:

[[90 15]
 [19 55]]


The model predicts survival correctly for about 8 out of 10 passengers.

Insights

Gender and Class had the biggest impact on survival.

Females and 1st-class passengers had much higher survival odds.

Even with a simple model and minimal feature engineering, performance stayed strong (≈ 81 % accuracy).﻿
