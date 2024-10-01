
College Basketball Salary Prediction
=========================
### Executive Summary
The primary area of this project is sports analytics. The project aims to predict the salaries of college basketball players drafted into the NBA based on their performance statistics and historical data from current and former pro players. It addresses the challenge of evaluating and translating college performance to professional success, aiding NBA teams in making informed draft and salary decisions. By integrating comprehensive datasets and leveraging machine learning, the project will provide valuable insights for player evaluation, financial planning, and targeted training programs, benefiting NBA teams, college programs, and players.

### The Big Idea:
Machine learning can also revolutionize player evaluation and salary prediction in basketball and other sports. By analyzing vast amounts of performance data from college and professional levels, we can solve this problem by employing a variety of machine learning models, such as linear regression for salary prediction, classification algorithms like logistic regression or decision trees for player success prediction, and clustering techniques for grouping similar players based on performance metrics. 


### Demo

### Methodology

The methodology for predicting NBA salaries for college basketball players 

### Data Collection:

1. Gathered comprehensive data on college basketball players' performance metrics (e.g., points per game, rebounds, assists, shooting percentages, etc.)
2. Collected historical data on NBA players' salaries and performance statistics.
3. Source data from reputable platforms such as NBA.com, Sports-Reference, and HoopsHype

### Data Preprocessing:

1. Cleaned the collected data by handling missing values, removing duplicates, and correcting inconsistencies.
2. Encoded categorical variables (e.g., player positions) using techniques like one-hot encoding
3. Normalized numerical features to ensure all variables are on a similar scale.  
4. Created derived features that might be predictive of NBA success (e.g., efficiency ratings, advanced statistics).


### Exploratory Data Analysis (EDA):

1. Conducted thorough statistical analysis to understand the distributions and relationships within the data.
2. Visualized key trends and correlations between college performance metrics and NBA salaries.
3. Identified potential outliers or anomalies that might affect model performance.

   
### Feature Selection:

1. Used statistical methods such as correlation analysis to identify the most relevant features.
2. Applied feature importance techniques from tree-based models to rank variables.

### Model Development:

1. Split the data into training, validation, and test sets
2. Implement multiple machine learning models, including:
   a. Linear Regression for baseline salary predictions.
   b. Random Forest and Gradient Boosting for more complex, non-linear relationships.
   c. Neural Networks for capturing intricate patterns in the data -> NN model will require more work in the fututre.
   d. Used cross-validation techniques to ensure model robustness.

#### Model Evaluation:

1. Assess model performance using appropriate metrics:
  a. Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) for regression tasks.
  b. Analyzed feature importance to understand which college performance metrics are most predictive of NBA salaries.
  c. Conduct residual analysis to ensure model assumptions are met.

2. Hyperparameter Tuning:
  a. Use techniques like Grid Search, Random Search, or Bayesian Optimization to fine-tune model hyperparameters.
  b. Implement regularization techniques to prevent overfitting.

3. Ensemble Methods: ->  In Progress/ Still needs more work
  a. Explore ensemble techniques like stacking or blending to combine predictions from multiple models.
  b. Weight model contributions based on their individual performance.


#### Prediction and Interpretation:

1. Apply the best-performing model(s) to predict salaries for current college players.
2. Develop visualizations or dashboards to present predictions in an interpretable manner.


#### Future steps for improvement: 

1. Validation with Domain Experts:
  a.Consult with basketball scouts, analysts, or former players to validate model predictions.
  b. Incorporate domain knowledge to refine the model and improve its real-world applicability.

2. Continuous Improvement:
  a. Regularly update the model with new data as it becomes available.
  b. Monitor model performance over time and retrain as necessary.
  c. Incorporate feedback from NBA teams or other stakeholders to enhance the model's utility.


### Organization

#### Repository 


#### Dataset
Cleaned and encoded data set csv file is available in the project folder
- atroitskaia/CollegeBasketballSalaryPrediction/backetball_cleaned_09_26_24.csv

### Credits & References

#### Data Collection:
- https://www.nba.com/stats/players/advanced
- https://hoopshype.com/salaries/players/
- https://www.sports-reference.com/cbb/

