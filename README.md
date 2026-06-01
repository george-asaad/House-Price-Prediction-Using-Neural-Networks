# House Price Prediction Using Neural Networks

## Overview
This project uses a Neural Network model to predict house prices based on various property features. The goal is to build a regression model that can estimate housing prices accurately using historical housing data.

## Dataset
The dataset contains information about residential properties, including:
- Number of bedrooms
- Number of bathrooms
- Living area
- Lot size
- Number of floors
- Property condition
- Other housing-related features

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-Learn
- TensorFlow / Keras

## Project Workflow
1. Data Collection
2. Data Cleaning and Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Neural Network Design
6. Model Training
7. Performance Evaluation
8. Prediction and Visualization

## Model Architecture
The neural network consists of:
- Input Layer
- Hidden Dense Layers with ReLU activation
- Output Layer for price prediction

## Evaluation Metrics
The model was evaluated using:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Results
The trained model successfully learned the relationship between housing features and prices, providing accurate predictions on unseen data.

## Project Structure
```

project/
│
├── data/
├── notebooks/
├── models/
├── images/
├── house_price_prediction.ipynb
├── requirements.txt
└── README.md

```

## Installation

```bash
git clone https://github.com/yourusername/house-price-prediction.git

cd house-price-prediction

pip install -r requirements.txt
```

## Run the Project

```bash
jupyter notebook
```

Open:

```text
house_price_prediction.ipynb
```

## Author

George Asaad

Data Engineer | Machine Learning Enthusiast
