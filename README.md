# Student Dropout Prediction with GUI

This project is a machine learning-based system designed to predict student dropout rates using various classifiers. The system also includes a simple graphical user interface (GUI) built with Tkinter that allows users to input student data and receive predictions.

## Features

### Data Preprocessing:
- **Normalization**: Data normalization using Min-Max Scaler to standardize features.
- **Feature Selection**: SelectKBest with Fisher's Score for choosing the most important features.
- **Correlation Analysis**: Heatmaps and correlation plots to visualize relationships between features and the target variable.

### Machine Learning Models:
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **Logistic Regression**
- **K-Nearest Neighbors (KNN)**
- **AdaBoost Classifier**
- **XGBoost Classifier**
- **Support Vector Machine (SVM)**
- **Voting Classifier**: Combined soft and hard voting classifiers for improved prediction accuracy.

### Model Evaluation:
- **Cross-Validation**: 5-fold cross-validation to evaluate model performance.
- **Accuracy Score**: Calculate accuracy, precision, recall, and F1-score for each model.

### GUI:
- **Tkinter-based GUI**: A simple interface that allows users to input student data and predict whether the student will graduate or drop out.
                     ![29](https://github.com/user-attachments/assets/0484b2f0-6721-4ec2-8465-d4407858e454)

## How It Works

1. **Data Loading**: The dataset is loaded from a CSV file and cleaned by renaming columns, handling null values, and encoding target labels.
2. **Feature Selection and Normalization**: The best features are selected using SelectKBest, and the data is normalized.
3. **Model Training and Evaluation**: Multiple machine learning models are trained and evaluated using cross-validation and accuracy metrics.
4. **GUI for Predictions**: A Tkinter-based GUI allows users to input features manually and predicts whether a student will drop out or graduate.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/MazenElfayoumi/student-dropout-prediction.git

2. **Install the required libraries**:

    ```bash
    pip install pandas seaborn matplotlib scikit-learn plotly xgboost tkinter
    ```

## Usage

### Running the Prediction Script

1. **Prepare the Dataset**: Ensure the dataset (`datasetupdated.csv`) is in the correct directory.

2. **Run the Script**:

    ```bash
    python student_dropout_prediction.py
    ```

3. **Input Student Data**: Use the GUI to input features such as age, tuition fees, and curricular units.

4. **View Predictions**: The system will output whether the student is likely to graduate or drop out.

### Example GUI Usage

- **Input Fields**: Fill in the student details such as `Displaced`, `Age`, `Tuition_fees_up_to_date`, etc.

- **Click "Check"**: The GUI will predict the student's status (`true` for graduation, `false` for dropout) and display the result.
