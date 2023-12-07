Model Card for Movie Success Prediction Suite

# Model Details
Owners: Swetha Shankar, Shubham Jain
Version: 1.0
Date: 12/07/2023
Model Type: Linear Regression and Deep Learning
Framework: PyTorch for model building, Scikit-learn for preprocessing
Intended Use
Primary Use: Predicting movie ratings, popularity, and revenue based on historical data
Users: Movie industry analysts, producers, and marketing departments
Out-of-scope: Real-time predictions, non-movie datasets

# Factors
Features Used:
vote_average: User ratings from the MovieLens dataset
budget: The budget allocated for the movie production
num_genres: Number of genres a movie is associated with
num_production_companies: Number of production companies involved in the movie
release_year, release_month, release_day: Date of movie release

# Metrics
Performance Metrics:
Mean Squared Error (MSE) for regression accuracy
R-squared (R^2) for variance explanation in predictions

# Evaluation Data
Data Source: MovieLens dataset
Split: Data was randomly split into 70% for training, 15% for validation, and 15% for testing

# Training Data
Data Source: Same as evaluation data
Preprocessing: Standardization, missing value imputation, and data merging

# Quantitative Analyses
Model Performance:
The MSE and R^2 on the test set are used to quantify model performance
Error Analysis:
Differences between predicted and actual values were analyzed to understand model shortcomings

# Ethical Considerations
Bias and Fairness: The model may reflect biases present in user ratings and historical movie popularity
Privacy: Data used does not contain personal information, adhering to privacy concerns

# Caveats and Recommendations
Model Interpretability: Linear models offer clear interpretability, while the neural network's complexity may limit this
Generalizability: The model's predictions are as good as the data it was trained on and may not generalize to all types of movies or over time without updates
Data Quality: The accuracy of predictions is highly dependent on the quality of data, and data from additional sources could improve the model's robustness
