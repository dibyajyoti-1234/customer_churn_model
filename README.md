
# Bank Customer Churn Prediction using ANN

This project uses an Artificial Neural Network (ANN) built with TensorFlow to predict whether a bank customer will leave based on features like credit score, geography, gender, age, and more. The dataset (`Churn_Modelling.csv`) is preprocessed, used to train the ANN, and evaluated for accuracy.

## Task Objectives
- **Predict Customer Churn**: Build a model to determine if a customer will leave the bank.
- **Data Preprocessing**: Handle categorical data (label and one-hot encoding), scale features, and split data into training/test sets.
- **Model Development**: Construct and train an ANN with two hidden layers to achieve high prediction accuracy.
- **Evaluation**: Assess model performance using a confusion matrix and accuracy score.
- **Single Prediction**: Demonstrate prediction for an individual customer observation.

## Steps to Run the Project
1. **Prerequisites**:
   - Python 3.8+
   - Install required libraries:
     ```bash
     pip install numpy pandas tensorflow scikit-learn jupyter
     ```
   - Download the dataset `Churn_Modelling.csv` and place it in the project directory.

2. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

3. **Run the Notebook**:
   - Start Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `churn_prediction.ipynb` in the Jupyter interface.
   - Run all cells in the notebook to:
     - Load and preprocess the dataset.
     - Build and train the ANN.
     - Output predictions, a confusion matrix, and accuracy score.
     - Display a sample prediction for a single customer.

4. **Expected Output**:
   - Preprocessed data arrays.
   - Training progress (epochs, loss, accuracy).
   - Prediction for a sample customer (stay/leave).
   - Test set predictions and confusion matrix.
   - Final accuracy score.

## Project Structure
- `churn_prediction.ipynb`: Jupyter Notebook with data preprocessing, ANN model, training, and evaluation.
- `Churn_Modelling.csv`: Dataset with customer information.
- `README.md`: Project documentation.

## Notes
- Ensure `Churn_Modelling.csv` is in the project directory before running the notebook.
- The ANN uses two hidden layers with 6 units each, ReLU activation, and a sigmoid output layer for binary classification.
- The model is trained for 100 epochs with a batch size of 32.

