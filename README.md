# PredictMyCar
**PredictMyCar** is an advanced machine learning project that provides precise car predictions based on user-defined criteria. The project leverages various data processing techniques and machine learning models to deliver personalized car recommendations.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Models and Techniques](#models-and-techniques)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- 

## Overview

PredictMyCar is designed to assist users in finding the most suitable car based on their preferences. By inputting specific details such as brand, model, vehicle age, fuel type, mileage, engine size, and more, users receive tailored car recommendations powered by machine learning models.

## Features

- **Personalized Car Recommendations:** Receive recommendations based on your specific criteria.
- **Multiple Machine Learning Models:** Utilizes ANN, RNN, and cosine similarity for robust predictions.
- **Data Visualization:** Visualize car prices and other features using matplotlib and seaborn.
- **User-Friendly Interface:** Easily input your preferences and get results instantly.

## Installation

To install and run PredictMyCar, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PredictMyCar.git
   cd PredictMyCar
   
2. Create a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate
   # On Windows use
   `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```


## Usage
Prepare your dataset and ensure it is formatted correctly.

Modify the config.py file to include the path to your dataset.

Run the main script to start the prediction process:

```bash
python predict_my_car.py
```
Follow the prompts to input your car preferences.


## Models and Techniques
PredictMyCar employs several advanced techniques and models, including:

Data Processing: Utilizes pandas and numpy for data manipulation and preprocessing.
Visualization: Matplotlib and seaborn for visual data representation.
Machine Learning Models:
Artificial Neural Network (ANN): For pattern recognition and complex predictions.
Recurrent Neural Network (RNN): Specifically, LSTM for handling sequential data.
Cosine Similarity: To find the most similar cars based on user input.
Data Preprocessing
Data preprocessing steps include handling missing values, encoding categorical variables using LabelEncoder, and scaling features using MinMaxScaler.


## Model Training
ANN Training: Uses a multi-layer perceptron with dropout for regularization.
RNN Training: Utilizes LSTM layers to capture sequential patterns.
Cosine Similarity: Computes similarities between user input and existing car features.
Model Evaluation
Models are evaluated based on explained variance score, R-squared score, mean squared error, and root mean squared error. Visualization of training and validation accuracy and loss helps in assessing model performance.


## Evaluation
The models are evaluated using metrics such as explained variance score and R-squared score. A detailed comparison of Linear Regression, Decision Tree, Random Forest, and Gradient Boosting models is provided.

markdown
Copy code
| Model               | Explained Variance Score | R-Square Score (Accuracy) |
|---------------------|--------------------------|----------------------------|
| Linear Regression   | 0.85                     | 0.84                       |
| Decision Tree       | 0.80                     | 0.78                       |
| Random Forest       | 0.90                     | 0.89                       |
| Gradient Boosting   | 0.88                     | 0.87                       |


## Results
After training and evaluating the models, the project provides car recommendations based on user inputs. Users can choose to view predictions from ANN, RNN, or cosine similarity-based models.


## Contributing
Contributions are welcome! If you'd like to contribute to this project, please fork the repository and use a feature branch. Pull requests are warmly welcome.

Fork the repository.
Create a new branch: git checkout -b feature-branch-name.
Make your changes and commit them: git commit -m 'Add some feature'.
Push to the branch: git push origin feature-branch-name.
Submit a pull request.
