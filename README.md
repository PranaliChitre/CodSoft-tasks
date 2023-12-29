TASK no. 1
Titanic Survival Rate Prediction Project Using Naive Bayes:
1. Dataset:
Use the Titanic dataset, which typically includes information such as passenger class, sex, age, number of siblings/spouses aboard (SibSp), number of parents/children aboard (Parch), fare, and survival status.
2. Data Preprocessing:
Handle missing values: Impute or drop missing values, especially for crucial features like age and fare.
Encode categorical variables: Convert categorical variables like 'Sex' into numerical values (e.g., male=0, female=1).
Feature selection: Choose relevant features that might influence survival.
3. Split Data:
Split the dataset into training and testing sets to evaluate the model's performance.
4. Naive Bayes Model:
Use the Gaussian Naive Bayes algorithm for this project, as it assumes that the features follow a Gaussian distribution.
Train the model using the training dataset.
5. Predictions:
Use the trained model to make predictions on the test set.
6. Model Evaluation:
Assess the model's performance using graphs


TASK no. 3
IRIS dataset project:
In this Python project using the Iris dataset, you employed pandas for data manipulation and visualization, numpy for numerical operations, and matplotlib for creating scatter plots to visualize the relationships between sepal and petal dimensions for each species. After encoding the categorical target variable with LabelEncoder, you split the dataset into training and testing sets. Utilizing the Support Vector Machine (SVM) algorithm from scikit-learn, you trained a classification model and evaluated its performance on the test set, achieving accuracy using `model.score`, and further analyzing results with a confusion matrix and classification report. The project concludes with a heatmap visualization of the confusion matrix, providing a comprehensive overview of the model's predictive capabilities.
