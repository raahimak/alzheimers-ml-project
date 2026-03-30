# Alzheimer’s Disease Classification using Machine Learning

## Project Overview
This project aims to classify Alzheimer’s disease using clinical, cognitive, and brain imaging data.  
Machine learning techniques were used to build a classification model that predicts whether a patient is cognitively normal, has cognitive impairment, or has Alzheimer’s disease.

## Dataset
The dataset includes:
- Cognitive test scores (MMSE, ADAS, RAVLT, etc.)
- Demographic information (age, gender, education)
- Brain imaging measurements (cortical thickness, brain volume)
- Diagnosis labels

The data was provided in multiple Excel sheets and merged into a single dataset for analysis.

## Methodology
The following machine learning pipeline was used:

1. Data loading from Excel files
2. Handling missing values
3. Merging multiple datasets
4. Feature selection
5. Encoding categorical variables
6. Standardizing numerical features
7. Splitting data into training and testing sets
8. Training a Random Forest classifier
9. Evaluating the model using accuracy and confusion matrix
10. Analysing feature importance

## Model Used
Random Forest Classifier (Scikit-learn)

## Results
The model achieved high accuracy on the test dataset and was able to successfully classify Alzheimer’s disease based on cognitive and clinical features.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## How to Run the Project
1. Clone the repository
2. Install required libraries:
3. Open the notebook: notebooks/Alzheimer.ipynb
4. Run all cells


## Conclusion
This project demonstrates how machine learning can be applied to medical data to support Alzheimer’s disease classification. The Random Forest model was able to identify important cognitive and brain imaging features that contribute to diagnosis prediction.
