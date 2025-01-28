# Zillow-Price-Prediction
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>House Price Prediction using Multilayer Perceptron</title>
</head>
<body>
  <h1>House Price Prediction using Multilayer Perceptron</h1>

  <p>This repository contains the implementation of a house price prediction model using a multilayer perceptron (MLP) neural network. The goal of the project is to predict the sale prices of properties using various features of the houses. The model is built and evaluated using different network architectures and hyperparameters to determine the best approach for accurate predictions.</p>

  <h2>Key Features:</h2>
  <ul>
    <li><strong>Data Preprocessing</strong>: Split the training data into training and validation sets.</li>
    <li><strong>Model Architectures</strong>: 
      <ul>
        <li>A base MLP model with 2 hidden layers of sizes 256 and 128.</li>
        <li>A more complex MLP model with 4 hidden layers of sizes 512, 256, 128, 64.</li>
        <li>A final MLP model with 4 hidden layers and dropout layers to prevent overfitting.</li>
      </ul>
    </li>
    <li><strong>Hyperparameter Tuning</strong>: Optimization of the model through the tuning of various hyperparameters.</li>
    <li><strong>Model Evaluation</strong>: Plot training and validation errors over epochs to visualize model performance.</li>
  </ul>

  <h2>Project Overview:</h2>
  <ul>
    <li><strong>Objective</strong>: Predict house sale prices based on historical data.</li>
    <li><strong>Approach</strong>: Use a multilayer perceptron (MLP) for regression tasks to predict prices.</li>
    <li><strong>Data</strong>: Historical housing data, including various features (e.g., square footage, number of rooms, etc.).</li>
  </ul>

  <h2>Deliverables:</h2>
  <ol>
    <li><strong>Training vs Validation Error Plots</strong>:
      <ul>
        <li>MLP model with 2 hidden layers (256, 128).</li>
        <li>MLP model with 4 hidden layers (512, 256, 128, 64).</li>
        <li>MLP model with 4 hidden layers and dropout layers.</li>
      </ul>
    </li>
    <li><strong>Hyperparameter Tuning Table</strong>: Listing of all model hyperparameters tested and corresponding best validation errors achieved.</li>
    <li><strong>Profit Analysis of the iBuyer Business Model</strong>: Evaluation of the iBuyer model’s profitability based on predicted house prices.</li>
  </ol>

  <h2>Requirements:</h2>
  <ul>
    <li>Python 3.x</li>
    <li>TensorFlow/Keras for building the neural network</li>
    <li>NumPy, Pandas for data manipulation</li>
    <li>Matplotlib for plotting</li>
  </ul>

  <h2>How to Run:</h2>
  <ol>
    <li>Clone the repository.</li>
    <li>Install the necessary dependencies from <code>requirements.txt</code>.</li>
    <li>Run the Jupyter notebook <code>HousePricePrediction.ipynb</code> to train and evaluate the models.</li>
    <li>Review the generated plots and profit analysis in the report.</li>
  </ol>

</body>
</html>

