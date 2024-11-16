# Airline Delay Prediction using Gradient Boosting Classifier

This project aims to predict airline delays in India using machine learning techniques, focusing on geographic and flight data. The model implemented in this repository is the **Gradient Boosting Classifier**. The dataset used includes flight-related information such as delays, distances, and geographical data.

## Table of Contents

- [Project Overview](#project-overview)
- [Model Implementation](#model-implementation)
- [Data Overview](#data-overview)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
- [Results](#results)
- [License](#license)

## Project Overview

The goal of this project is to predict flight delays for airlines in India based on various factors, including historical data, geographical details, and flight specifics. The Gradient Boosting Classifier is used as the model to predict whether a flight will be delayed or not.

## Model Implementation

### 1. Gradient Boosting Classifier

This project uses the **Gradient Boosting Classifier** from `scikit-learn` to perform the classification task. The model is trained on historical flight data, which includes various features such as:

- Departure and arrival times
- Distance
- Weather-related factors
- Flight-specific data

The Gradient Boosting algorithm is well-suited for this task as it builds an ensemble of trees, making predictions by aggregating results from multiple weak models.

### 2. Libraries Used
The following Python libraries are used in this project:

- **scikit-learn** for the machine learning model.
- **pandas** for data manipulation.
- **numpy** for numerical computations.
- **geopandas** for working with geographic data.
- **matplotlib** for visualizing the results.

## Data Overview

The dataset used in this project includes details about flights, such as:

- Flight numbers
- Departure and arrival airports
- Flight times
- Delay information
- Geographical data (using GeoPandas to handle locations)

## Installation Instructions

To run this project locally, follow the steps below.

### 1. Clone the repository

```bash
git clone https://github.com/parzaech/flight-delay-predictor.git
cd flight-delay-predictor
```
## Model Evaluation (Gradient Boosting Classifier)

The model was evaluated using the **Gradient Boosting Classifier** on the dataset. Here are the performance metrics:

- **Accuracy**: 0.623
- **Precision**: 
  - Non-delayed flights (0): 0.65
  - Delayed flights (1): 0.59
- **Recall**: 
  - Non-delayed flights (0): 0.71
  - Delayed flights (1): 0.51
- **F1-Score**: 
  - Non-delayed flights (0): 0.68
  - Delayed flights (1): 0.55
- **Support**: 
  - Non-delayed flights (0): 59,824
  - Delayed flights (1): 48,053

The **Gradient Boosting Classifier** performed well, with the highest recall for non-delayed flights, but there is room for improvement in predicting delayed flights.


