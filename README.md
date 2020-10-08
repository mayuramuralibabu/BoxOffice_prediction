# BoxOffice_prediction
# TMDB Movie Data Exploration
The goal of the project is to derive insights on the TMDB movie datset and
perform regression and classification models to predict revenue of the movie. 
This model could be leveraged by production companies for making go/no-go screening decisions.

TMDB Movie Dataset available on Kaggle. Link: https://www.kaggle.com/tmdb/tmdb-movie-metadata
This dataset was generated from The Movie Database API. 
This product uses the TMDb API but is not endorsed or certified by TMDb.
Their API also provides access to data on many additional movies, actors and 
actresses, crew members, and TV shows. 

## Methodology
### Preprocessing raw dataset
1) EDA on all features - using Scikit-learn, Matplotlib, Seaborn, GGplot(Rpy2)
2) Correlation Analysis and Normalization of Continuous and Discrete features.
3) Label Encoding and OneHot Enocoding on Categorical features.
### Model Training and Analysis
1) For predicting Revenue of all movies with selected important features
    1. Linear Regression
    2. RandomForest Regression
    3. LGBTM Regression
2) Parameter Tuning, Cross Validation, Regularization and Data Balancing
3) Classification based on Country of Production, Budget and Movie_Review 
   1. DecisionTree Classification
   2. KNeighbors Classification
   3. RandomForest Classification
   4. Support Vector Machine
   5. Neural Networks - MLPClassifier
    
