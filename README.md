# Artificial Neural Network Implementation

This project demonstrates the implementation of an Artificial Neural Network (ANN) for churn prediction using a banking dataset. The primary objective is to predict whether a customer will stay with the bank based on various features.

## Features
- **Dataset**: Churn modeling dataset, containing customer information such as credit score, geography, gender, age, tenure, balance, and more.
- **Preprocessing**: Includes feature scaling, encoding categorical variables, and splitting the dataset into training and test sets.
- **Model Architecture**:
  - Input layer for features.
  - Hidden layers with ReLU activation.
  - Output layer with sigmoid activation for binary classification.
- **Training**: Model trained using backpropagation and binary cross-entropy loss.
- **Evaluation**: Metrics such as accuracy and loss are used to evaluate performance.

## Repository Contents
- **`ANN_Implementation.ipynb`**: Jupyter Notebook containing the full implementation of the ANN.
- **Dataset**: Ensure the dataset is available in the specified directory for preprocessing.
- **Results**: Includes training accuracy, test accuracy, and confusion matrix analysis.

## Requirements
To run this project, install the following dependencies:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow keras
```
## How to Use
1. Clone this repository:

```bash
git clone https://github.com/yourusername/ann-churn-prediction.git
```

2. Run the notebook cells sequentially to:
- Import necessary libraries.
- Load and preprocess the dataset.
- Build, train, and evaluate the ANN model.

## Results
- The model achieves significant accuracy in predicting customer churn.
- Visualizations include accuracy and loss curves during training.
- Confusion matrix and classification report provide detailed evaluation.



