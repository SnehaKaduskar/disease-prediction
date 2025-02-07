

# Disease Prediction System

This repository contains a machine learning-based disease prediction system designed to predict the likelihood of three major health conditions:
- **Diabetes**
- **Heart Disease**
- **Parkinson's Disease**

The system uses machine learning models trained on various medical datasets to make predictions based on user input data. The models provide insights and predictions to help with early diagnosis.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models](#models)
- [Dataset](#dataset)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The Disease Prediction System provides a machine learning framework for diagnosing three critical diseases:
- **Diabetes Prediction**: Predicts the likelihood of a person developing diabetes based on their health data.
- **Heart Disease Prediction**: Classifies individuals based on heart disease risk.
- **Parkinson's Disease Prediction**: Uses features from speech data to predict Parkinson's disease.

This system provides predictions based on various input parameters and can be a valuable tool for early diagnosis and preventive healthcare.

## Features
- Predicts the likelihood of diabetes, heart disease, and Parkinson’s disease.
- User-friendly input interface for entering health parameters.
- Model evaluation and performance metrics included.
- Support for easy extension to add more disease prediction models.

## Installation

To get started with this project, clone the repository and install the required dependencies:

1. Clone this repository:
   git clone https://github.com/SnehaKaduskar/disease-prediction.git
   

2. Navigate to the project directory:
   ```bash
   cd disease-prediction
   ```

3. Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

## **Usage**

1. After installing the dependencies, you can use the system by running the `main.py` file.

2. For each disease, there are separate functions available to input the data and make predictions.

   Example for Diabetes Prediction:
   ```python
   from diabetes_model import predict_diabetes

   # Example input data
   user_data = [user_age, bmi, blood_sugar_level, etc.]
   prediction = predict_diabetes(user_data)
   print(prediction)
   ```

   Similarly, you can use `heart_disease_model.py` and `parkinsons_model.py` to predict heart disease and Parkinson’s disease.

## Models

1. **Diabetes Model**: A logistic regression model trained on a diabetes dataset.
2. **Heart Disease Model**: A decision tree classifier trained on a heart disease dataset.
3. **Parkinson’s Disease Model**: A random forest classifier trained on speech data from Parkinson’s patients.

Each model is implemented in a separate Python file (`diabetes_model.py`, `heart_disease_model.py`, `parkinsons_model.py`).

## Dataset

The following datasets are used in the project:
- **Diabetes**: A dataset containing medical records and health data for diabetes prediction.
- **Heart Disease**: A dataset containing features like age, blood pressure, cholesterol levels for heart disease prediction.
- **Parkinson’s Disease**: A dataset containing speech data to predict Parkinson's disease.

You can find more details about the datasets in the `datasets/` folder.

## Technologies Used

- **Python** (3.12+)
- **scikit-learn**: For machine learning models and algorithms.
- **pandas**: For data manipulation and analysis.
- **numpy**: For numerical operations.
- **matplotlib**: For data visualization.
- **flask**: (If you're planning to deploy the system as a web app)
  
## Contributing

We welcome contributions to improve this project! To contribute:

1. Fork the repository.
2. Create a new branch for your feature or fix.
3. Commit your changes.
4. Push to your fork.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

You can modify this template according to your specific project details.
# disease prediction
 
![Screenshot 2025-02-05 200105](https://github.com/user-attachments/assets/b6be9492-6c2c-483f-a397-2b3c7a95d9a8)

![Screenshot 2025-02-04 000746](https://github.com/user-attachments/assets/29838d2d-db98-4402-aaba-76ec0cf8f8e1)

