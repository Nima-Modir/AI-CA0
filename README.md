# Perform data visualization and build a classification model based on the Titanic dataset

## Project Description:
### Dataset:
**train.csv**: Contains training data for building the model. Key columns include:

PassengerId

Pclass (Ticket class)

Sex (Gender)

Age

SibSp (Number of siblings/spouses aboard)

Parch (Number of parents/children aboard)

Fare (Ticket fare)

Embarked (Port of embarkation: C = Cherbourg, Q = Queenstown, S = Southampton)

**test.csv**: Used for testing the model (excluding the 'Survived' column).

## Tasks:
### Data Loading: 
Load and inspect the dataset using Pandas functions like head(), info(), describe().
### Data Preprocessing:
Handle missing values, especially in columns like Age, and convert categorical variables (e.g., Sex, Embarked) into numerical form.
Normalize or scale numerical features to prepare them for modeling.
### Data Exploration:
Create visualizations such as histograms and box plots to understand the distribution of features like age, fare, and ticket class.
### Model Training:
Use vectorization techniques to efficiently process the dataset and build a classification model to predict the survival of passengers.
Train the model using the training dataset and evaluate its performance.
