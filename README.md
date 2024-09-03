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
   git clone https://github.com/yourusername/student-dropout-prediction.git
