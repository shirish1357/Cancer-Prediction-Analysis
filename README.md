# Cancer-Prediction-Analysis
An exploratory data analysis and predictive modeling of cancer risk factors using machine learning

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)
6. [Results](#results)

## Installation <a name="installation"></a>
There are no additional libraries required beyond the standard Anaconda distribution of Python. The code should run with no issues using Python 3.X. The key libraries used in this project include:
pandas, numpy, matplotlib, seaborn, scikit-learn

## Project Motivation
For this project, I was interested in using machine learning to analyze factors influencing cancer diagnosis. Specifically, I wanted to investigate:

1. Which factors (e.g., age, BMI, lifestyle habits) have the strongest correlation with cancer diagnosis?
2. How do lifestyle choices, such as smoking, alcohol intake, and physical activity, influence cancer risk?
3. Which features are the most important in predicting cancer risk?
4. How well can a machine learning model predict whether a patient is likely to be diagnosed with cancer?

The dataset used in this project was obtained from Kaggle and contains 1,500 patient records with medical and lifestyle attributes.

## File Descriptions <a name="files"></a>

The repository contains the following files:  

Cancer Prediction Notebook.ipynb: An exploratory analysis of the dataset and the Random Forest Prediction model.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Kaggle for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/datasets/rabieelkharoua/cancer-prediction-dataset/data).  Feel free to use the code here as you would like! 

## Results<a name="results"></a>
The main findings of this analysis can be summarized as follows:

1. Previous history of cancer was the strongest predictor, showing a high correlation with cancer diagnosis
2. BMI and alcohol intake had a stronger impact than genetic risk, highlighting the importance of lifestyle choices
3. Smoking was a weaker predictor than expected, possibly due to data biases or underreporting
