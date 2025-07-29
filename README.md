Group 4 - Machine Learning Group Assignment
Project Title
Spaceship Titanic: Predicting Passenger Transport Outcome Using Machine Learning
Team Members – Group 4
Project Description
This assignment focuses on predicting whether a passenger was transported to another dimension during the fictional Spaceship Titanic voyage. Using supervised machine learning techniques, we analyze the dataset, clean and preprocess the data, train multiple models, and evaluate their performance to determine the best approach for prediction.
The notebook follows the complete machine learning workflow from data loading and cleaning to final prediction and submission generation.
File Structure
Code_Group_Colab.ipynb: Main Jupyter notebook with all code, explanations, and outputs.
train.csv, test.csv, sample_submission.csv: Dataset files (must be uploaded to Colab or local directory).
Notebook Overview
1. Importing Libraries
Commonly used packages are imported, including pandas, numpy, matplotlib, seaborn, and scikit-learn. Additional libraries include CatBoost, LightGBM, and XGBoost.
2. Loading the Dataset
Training and test datasets are loaded using pandas. Initial shape and structure of the data are examined.
3. Exploratory Data Analysis (EDA)
EDA includes inspecting value distributions, correlations, and missing data. Graphs and summary statistics are used for visual insight into the dataset.
4. Data Cleaning and Preprocessing
Missing values are handled using imputation.
Categorical variables are encoded using LabelEncoder.
Feature engineering is done to add or transform relevant attributes.
5. Model Training
Multiple machine learning models are trained on the dataset:
LightGBM
CatBoost
Extra Tree Classifier
Histogram Gradient Boosting Classifer
6. Model Evaluation
Each model is evaluated based on accuracy and other classification metrics. Performance is compared to select the best-performing model.
7. Prediction and Submission
The selected model is used to make predictions on the test dataset. A submission file is generated in the required format for the Kaggle competition.
How to Run the Notebook
Open the notebook using Google Colab or Jupyter Notebook.
Upload train.csv, test.csv, and sample_submission.csv to your session.
Run all code cells in order.
The final cell generates a submission file named submission.csv.
License
MIT License
Copyright (c) 2025 Group 4

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Project"), to deal
in the Project without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Project, and to permit persons to whom the Project is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Project.

THE PROJECT IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES, OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE PROJECT OR THE USE OR OTHER DEALINGS IN THE
PROJECT.

Acknowledgements
Dataset: Kaggle Spaceship Titanic competition
Tools: Google Colab, Python, scikit-learn, LightGBM, CatBoost, XGBoost
Thanks to instructors and team members for contributions and feedback.
