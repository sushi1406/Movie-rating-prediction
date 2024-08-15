
# IMDb India Movies - Rating Prediction

## Project Overview
This project focuses on predicting movie ratings based on various features such as genre, duration, director, and actors. The goal is to analyze historical data of Indian movies and develop a machine learning model that can accurately estimate a movie's rating.

## Dataset Description
The dataset used in this project is the **IMDb India Movies** dataset, containing information about Indian movies released over the years. The dataset includes the following features:

- **Name**: The title of the movie.
- **Year**: The year the movie was released.
- **Duration**: The length of the movie in minutes.
- **Genre**: The category or categories the movie belongs to (e.g., Drama, Comedy).
- **Rating**: The IMDb rating of the movie (target variable).
- **Votes**: The number of votes the movie received on IMDb.
- **Director**: The name of the movie's director.
- **Actor 1**: The lead actor/actress.
- **Actor 2**: The second lead actor/actress.
- **Actor 3**: The third lead actor/actress.

### Data Source
The dataset can be found on [Kaggle](https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies).


### Workflow

1. **Data Loading**: Load the dataset and inspect its structure.
2. **Data Preprocessing**: Handle missing values, encode categorical features (such as Genre, Director, Actors), and scale numerical features.
3. **Exploratory Data Analysis (EDA)**: Visualize the data to understand the relationships between features and the target variable (Rating).
4. **Feature Engineering**: Create or modify features to enhance the model's predictive power. This might include creating dummy variables for genres or aggregating vote counts.
5. **Modeling**: Train different machine learning models, such as:
   - **Linear Regression**

6. **Evaluation**: Evaluate the models using appropriate metrics like R-squared (R²) and Mean Squared Error (MSE) to assess their performance.
7. **Prediction**: Use the best-performing model to predict ratings for new movies.

## Models Used

- **Linear Regression**



## Evaluation Metrics

- **R-squared (R²)**: This metric shows how well the independent variables explain the variability of the dependent variable (movie rating).
- **Mean Squared Error (MSE)**: This measures the average of the squares of the errors—that is, the average squared difference between the estimated and actual values.

## Results

The performance evaluation of logistic regression is below:  

**Mean squared error**:  0.4465441653985704
**Mean absolute error**:  0.49219025407656397
**R2 score**:  0.7641133663863862

