# Heart Disease Risk Detection System

This project is a *machine learning-based system* for predicting the risk of heart diseases using patient data. The model uses a *Random Forest Classifier* to predict the likelihood of heart disease based on various health parameters.

## Overview

The *Heart Disease Risk Detection System* analyzes medical data such as age, cholesterol levels, and blood pressure to predict the risk of heart disease. Using the *Random Forest Classifier*, this project helps in early identification of potential heart disease risks, which can aid in timely medical intervention.

## Features

- Predicts heart disease risk using a trained Random Forest model.
- Provides evaluation metrics such as accuracy, precision, recall, and ROC curves.
- Can be extended with additional features or improved with hyperparameter tuning.

## Technologies Used

- *Python*: Programming language.
- *scikit-learn*: For building and training the Random Forest model.
- *pandas*: For data manipulation and preprocessing.
- *numpy*: For numerical operations.
- *matplotlib & seaborn*: For data visualization.
- *google colab*: For interactive development and analysis.

## Data

The dataset used for this project is sourced from *Kaggle* and contains various features related to patients' health, such as:

- age
- sex
- chest pain type (4 values)
- resting blood pressure
- serum cholestoral in mg/dl
- fasting blood sugar > 120 mg/dl
- resting electrocardiographic results (values 0,1,2)
- maximum heart rate achieved
- exercise induced angina
- oldpeak = ST depression induced by exercise relative to rest
- the slope of the peak exercise ST segment
- number of major vessels (0-3) colored by flourosopy
- thal: 0 = normal; 1 = fixed defect; 2 = reversable defect

### Source

You can find the dataset on Kaggle at the following link: [Kaggle - Heart Disease Dataset] https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

## Modeling

The model used for predicting heart disease risk is a *Random Forest Classifier*, a powerful and flexible machine learning algorithm. The steps involved in building the model include:

1. *Data Preprocessing*:
    - Handling missing values.
    - Encoding categorical variables.
    - Feature scaling (optional).
    
2. *Training*:
    - Using the Random Forest algorithm to train the model on the dataset.
    
3. *Evaluation*:
    - Evaluating the model using metrics such as accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.


## Results

### Model Performance

- *Accuracy*: 84.62%
- *ROC-AUC Score*: 0.91


### Interpretation

- *Accuracy* of 84.62% signifies that the model correctly predicts heart disease status approximately 85% of the time.
- *ROC-AUC* of 0.91 demonstrates that the model has a high ability to distinguish between patients with and without heart disease.
- The ROC curve shows a significant area under the curve, indicating robust performance.

The model is capable of predicting heart disease risk with good accuracy and can be further improved with more advanced techniques like feature engineering and deeper hyperparameter tuning.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.
