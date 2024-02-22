# Diabetes Prediction Project

## Overview
This project aims to develop a machine learning model to predict diabetes based on various health metrics. Utilizing a dataset with features such as glucose levels, blood pressure, age, and more, we build and evaluate predictive models to identify individuals at high risk of developing diabetes.

## Dataset
The dataset used in this project is the Pima Indians Diabetes Database, sourced from the National Institute of Diabetes and Digestive and Kidney Diseases. It includes data from 768 individuals with 8 features and 1 target variable indicating the presence or absence of diabetes.

### Features
1. **Pregnancies**: Number of times pregnant
2. **Glucose**: Plasma glucose concentration over 2 hours in an oral glucose tolerance test
3. **BloodPressure**: Diastolic blood pressure (mm Hg)
4. **SkinThickness**: Triceps skinfold thickness (mm)
5. **Insulin**: 2-Hour serum insulin (mu U/ml)
6. **BMI**: Body mass index (weight in kg/(height in m)^2)
7. **DiabetesPedigreeFunction**: Diabetes pedigree function
8. **Age**: Age (years)

### Target
- **Outcome**: Class variable (0 or 1) indicating whether the patient has diabetes

## Installation
To set up this project, you will need Python 3.6+ and the following Python libraries installed:
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

You can install these packages using pip:
```
pip install numpy pandas scikit-learn matplotlib seaborn
```

## Usage
1. Clone the repository to your local machine:
```
git clone https://github.com/jafararalikhan/Diabetes-Predicton-AI-ML-DataScience-Project-2.git
```
2. Navigate to the project directory:
```
cd diabetes-prediction
```
3. Run the Jupyter notebooks or Python scripts to train the model and make predictions.

## Model
This project uses several machine learning models to predict diabetes, including Logistic Regression, Random Forest, and Gradient Boosting. We evaluate the models based on accuracy, precision, recall, and F1 score to select the best-performing model for deployment.

## Results
Our findings indicate that the Gradient Boosting model outperforms other models, achieving an accuracy of 85%, precision of 76%, recall of 81%, and an F1 score of 78.5%. These results suggest that Gradient Boosting is a robust method for predicting diabetes in this context.

## Contributing
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.


## Acknowledgments
- National Institute of Diabetes and Digestive and Kidney Diseases for providing the dataset.
- The data science community for offering invaluable resources and support.

---
