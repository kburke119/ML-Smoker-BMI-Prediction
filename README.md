# Machine-Learning-Smoker-Prediction

## Table of Contents

- [Presentation](#presentation)
- [About](#about)
- [Summary](#summary)
- [Visualizations](#visualizations)

## Presentation
[Prensentation Link]()

## About

Our team's goal was to use machine learning to determine if a person is a smoker or non smoker based on the data points age, bmi, sex, and hospital charges. 

[Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)

Our dataset contained the following column headers:
- **age**: age of primary beneficiary
- **sex**: insurance contractor gender, female, male
- **bmi**: body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- **children**: number of children covered by health insurance / Number of dependents
- **smoker**: smoker/non-smoker
- **region**: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- **charges**: individual medical costs billed by health insurance

## Summary
- We started by cleaning the dataset with Python, Pandas, and Numpy.
- Removed unwanted columns, converted data types, and converted text to float values.
- Separated the data into labels and features then reviewed our X and y variables. 
- Split our data into training and testing sets. 
- Incorporated scaling so our machine learning model would interpret these features as the same weight.
- Made predicitions on our test data and evaluated the model (accuracy score .956)
- Allowed users to input their age, bmi, sex, and hospital charges.
- Our model makes the prediction if the user is a smoker or non smoker based on the inputs above.

## Visualizations

