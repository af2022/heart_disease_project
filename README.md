# Heart Disease Classifier Project

This project looks into various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not a patient has heart disease - based on their medical attributes.

Feel free to view the Jupyter notebook which contains detailed information going from: 
1. Project Breakdown
2. Data Cleaning 
3. Explortatory Data Analysis 
4. Modelling 
5. Experimentation (Hyperparameter Tuning and best model selection)

Data can be found within the repo and was made publicly available by the UCI website (or Kaggle). 

*Python Packages Used:*
 1. Numpy
 2. Pandas 
 3. Matplotlib 
 4. Seaborn
 5. Sci-Kit Learn
 
 *Machine Learning Techniques Used:* 
 1. Logistic Regression (Base Classifier) 
 2. KNN 
 3. RandomForest (Binary Trees)
 4. Randomized and GridSearch Cross Validation
 5. Precision/Recall, F1 Score and ROC/AUC
 
 
## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

 1. Clone the Repo to download all files 

### Prerequisites

What things you need to install the software and how to install them:

**pypy install** 

 * Run the requirements.txt file if using pypy manager with: `pip3 install -r requirements.txt`
 
**Anaconda/Conda install** 

 * Run the following in a terminal: `conda env create -f heart_disease_project.yml`

## Future Updates
- Potential to split project into a more `Class` based project with my own classes for making models 
- More feature engineering and analysis
- Potential to apply Deep Learning but using only accuracy as the metric for evaluation
