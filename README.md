Welcome to the Movie Success Prediction Models repository. This suite of models leverages machine learning to predict movie ratings, popularity, and revenue using data from the MovieLens dataset.

# Table of Contents
1. Model Details
2. Getting Started
3. Prerequisites
4. Installation
5. Usage
6. License

# Model Details

This project contains two main types of models:

1. Linear Regression Models: Predict movie ratings and popularity.
2. RevenueNet: A deep learning model to estimate movie revenue based on actor popular
   
The models are built using Python, with PyTorch for model training and evaluation, and Scikit-learn for data preprocessing and feature engineering.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

# Prerequisites
What you need to install the software and how to install them:

```python 
Python 3.8+
Pandas
NumPy
Matplotlib
PyTorch
Scikit-learn
```
Installation
Clone the repository:
```
git clone https://github.com/rtxt007/Revenue-Prediction.git
```
Navigate to the project directory:
```
cd Revenue-Prediction
```
Install the required packages by running this code in command prompt:
```
pip install -r requirements.txt
```

# Usage
After installation, you can run the models using the following command:
```python
python movie_prediction_models.py
```
This script will preprocess the data, train the models, and output the evaluation metrics such as MSE and R^2 scores.
It will ask the users for certain inputs such as 
```
Enter vote_average:
Enter popularity:
Enter budget:
Enter num_genres:
Enter num_production_companies: 
Enter release_year:  
Enter release_month: 
Enter release_day: 
```
and it will yeild the output as 
```
Your expected revenue is:
```
License
Distributed under the MIT License. See LICENSE for more information.

