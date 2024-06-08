# FreezeGuard: Predicting Gait Freeze Events using Wearable Sensors

FreezeGuard is a project aimed at predicting gait freeze events using wearable sensor data. This project involves data collection, preprocessing, model training, and evaluation to predict freezing events in gait.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Evaluation](#evaluation)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Data Collection**: Using wearable sensors to collect gait data.
- **Data Preprocessing**: Cleaning and preparing data for model training.
- **Model Training**: Training machine learning models to predict freeze events.
- **Evaluation**: Assessing model performance using various metrics.

## Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**
- **Scikit-learn**
- **NumPy**

## Data
The dataset used in this project consists of sensor data collected from wearable devices. The data includes various features that help in predicting gait freeze events.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/dasdebanna/FreezeGuard-Predicting-Gait-Freeze-Events-using-Wearable-Sensors.git
    ```
2. Navigate to the project directory:
    ```bash
    cd FreezeGuard-Predicting-Gait-Freeze-Events-using-Wearable-Sensors
    ```
3. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. Open the `problem-solution.ipynb` notebook.
3. Follow the instructions in the notebook to preprocess the data, train the model, and evaluate the performance.

## Model Training
The model training process involves:
1. **Loading the dataset**: Import the dataset and load it into a Pandas DataFrame.
2. **Data preprocessing**: 
    - Handle missing values.
    - Normalize the data to ensure all features contribute equally to the model.
    - Feature extraction to create meaningful input features from raw data.
3. **Splitting the data**: Divide the data into training and testing sets using a train-test split approach.
4. **Model selection**: Choose appropriate machine learning algorithms (e.g., Random Forest, SVM).
5. **Training the model**: Train the selected model using the training data.
6. **Hyperparameter tuning**: Optimize model performance by tuning hyperparameters using techniques like Grid Search or Random Search.
7. **Model evaluation**: Assess the model on the training data using cross-validation to prevent overfitting.
8. **Saving the model**: Save the trained model for future use with libraries like `joblib`.

## Evaluation
Model performance is evaluated using various metrics such as:
1. **Accuracy**: Proportion of correctly predicted instances out of the total instances.
2. **Precision**: Proportion of true positive predictions out of the total positive predictions.
3. **Recall**: Proportion of true positive predictions out of the actual positives.
4. **F1-Score**: Harmonic mean of precision and recall, providing a balance between the two.
5. **Confusion Matrix**: Visual representation of the performance of an algorithm.
6. **ROC Curve and AUC**: Evaluate the trade-off between true positive rate and false positive rate.

The evaluation process includes:
1. Making predictions on the test set.
2. Calculating performance metrics to determine the model’s effectiveness.
3. Analyzing misclassifications to identify areas for model improvement.
4. Comparing different models and selecting the best-performing one.

## Contributing
Contributions are welcome! Please follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-branch
    ```
3. Make your changes and commit them:
    ```bash
    git commit -m "Add new feature"
    ```
4. Push to the branch:
    ```bash
    git push origin feature-branch
    ```
5. Create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
