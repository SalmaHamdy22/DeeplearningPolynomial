
# Polynomial Regression with Keras

The objective of this task aims to make an analysis that explains the relationship between orbital positions and time using a polynomial regression model implemented with a neural network. The goal is to achieve a model with R2 score greater than or equal 0.75.



## Dataset description
The dataset contains 2 features.

The first feature is 'time_steps' and the second feature is 'y' which is the position.

The dataset is processed by checking for nulls and then being used to train a NN model model for polynomial regression.
## Steps to Run the Code in Jupyter Notebook
Open Anaconda:

-> You can upload this code directly to a Jypyter notebook .

Upload or Load the Dataset:

-> Upload the dataset using the file upload functionality (Files tab).

Run the Code:

-> Once the dataset is uploaded or loaded, execute the code cells sequentially in the Jupyter notebook.

The code will handle preprocessing, model training, evaluation, and visualization.
## Dependencies and Installation Instructions
bash

!pip install keras tensorflow numpy matplotlib scikit-learn

## Example Output
After training the neural network, you will visualize the predicted orbital positions compared to the reference orbit. The visualization will show two lines:

Scientist's Orbit (blue): This represents the actual, reference orbit based on a known quadratic function.
Your Orbit (orange): This is the orbit predicted by your neural network model based on the time data.