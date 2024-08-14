# Deep-Learning---Predicting-Diabetes-Progression

## Project Overview
This project aims to model the progression of diabetes using the Diabetes dataset from sklearn. The objective is to assist healthcare professionals in understanding how various factors influence the progression of diabetes, which could potentially lead to better treatment plans and preventive measures.

## Key Components

### Loading and Preprocessing:

The dataset was loaded and features were normalized to ensure better performance of the Artificial Neural Network (ANN) model.

### Exploratory Data Analysis (EDA):

Feature Distribution: Analysis revealed varying distributions across features, indicating different levels of influence on the target variable.

Correlation Analysis: Some features were found to have a stronger correlation with diabetes progression, highlighting their potential significance in the model.

Relationships: Visual exploration helped identify linear and non-linear relationships between features and the target variable.

### Building the ANN Model:

Initial Architecture: A simple ANN with one hidden layer was designed and trained, which provided a moderate performance baseline.

Activation Functions: ReLU activation was chosen for hidden layers to introduce non-linearity and improve model learning.
Training and Evaluation:

Model Performance: Initial performance metrics indicated a reasonable fit, but there was scope for improvement.

Metrics: Mean Squared Error (MSE) and R² Score were used to evaluate model accuracy and explanatory power.

### Improving the Model:

Added Complexity: The model was enhanced by adding 5 hidden layers, which increased its capacity to capture complex patterns.

Overfitting: The loss curves suggested potential overfitting, which could be addressed with regularization techniques in future iterations.

Performance Gains: While the additional layers provided marginal improvement, it indicates the original model was already quite effective.

#### Insights Gained
Model Complexity: Adding more hidden layers increased model complexity, but did not significantly improve performance, suggesting the initial architecture was sufficient.

Regularization Need: The model showed signs of overfitting, indicating that regularization techniques like dropout or L2 regularization might be necessary for further improvement.

Hyperparameter Tuning: Further tuning of learning rates, batch sizes, and epochs could enhance model performance.

Feature Engineering: Exploring additional features or transformations may yield better predictive power.

### Conclusion
This project demonstrates the process of building and refining a neural network model to predict diabetes progression. While the model performs reasonably well, there is potential for further enhancement through regularization, hyperparameter tuning, and feature engineering.

