# Loss Function Lab

## Project Overview
Loss Function Lab is a machine learning project that explores and compares different loss functions used in regression and classification tasks. The project demonstrates how loss functions influence model training, performance, and sensitivity to outliers.

## Objectives
- Understand different loss functions used in machine learning.
- Compare regression loss functions.
- Study the effect of outliers on regression models.
- Implement binary and multiclass classification using PyTorch.
- Visualize training and validation loss curves.
- Evaluate model performance using appropriate metrics.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- PyTorch
- Google Colab

## Project Tasks

### 1. Regression Loss Functions
Compare Mean Squared Error (MSE), Mean Absolute Error (MAE), and Huber loss. Introduce outliers into the target data and observe their effects on model performance.

### 2. Outlier Sensitivity Analysis
Evaluate regression models under different levels of outlier contamination and visualize the changes in their performance.

### 3. Binary Classification
Build a binary classification model using PyTorch and Binary Cross-Entropy with Logits Loss. Plot training and validation loss curves and evaluate the model using classification metrics.

### 4. Multiclass Classification
Build a multiclass classification model using PyTorch and Cross-Entropy Loss. Visualize the loss curves and evaluate the model using accuracy and macro F1-score.

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²)
- Accuracy
- Precision
- Recall
- F1-score

## How to Run
1. Download the Jupyter Notebook from this repository.
2. Open [Google Colab](https://colab.research.google.com/).
3. Upload the notebook.
4. Install any missing dependencies if prompted.
5. Run the notebook cells in order.

**Note:** The regression section requires the original `dataset.xlsx` file. Upload it to your Colab session at the expected path or update the notebook to load the dataset from its actual location. The classification sections use datasets from scikit-learn.

## Project Outcome
This project demonstrates how different loss functions behave across regression and classification tasks, including the impact of outliers and the use of training and validation loss curves to monitor model learning.

## Author
Srivalli Korada
