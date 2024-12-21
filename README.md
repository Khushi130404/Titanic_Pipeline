# Titanic_Pipeline

This project predicts whether a person survived the Titanic disaster based on various features such as age, fare, passenger class (Pclass), number of siblings/spouses aboard (SibSp), number of parents/children aboard (Parch), embarkation point (Embarked), and more. The project leverages machine learning techniques, specifically pipelines and ColumnTransformer, for efficient preprocessing and modeling.

## Project Features

### 1. Data Preprocessing
- Handles missing values in the dataset.
- Encodes categorical variables.
- Scales numerical features for optimal model performance.

### 2. Pipeline Integration
- Uses Pipeline and ColumnTransformer for seamless data preprocessing and model training.

### 3. Model Training
- Trains a classification model to predict survival status.

### 4. Serialization
- Saves the trained model as a .pkl (pickle) file for future use.

### 5. Prediction
- Loads the serialized model to predict survival outcomes on new data.

## Libraries
- pandas
- numpy
- scikit-learn
- pickle (built-in Python library)
