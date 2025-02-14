# Linear Regression ML

This repository contains an implementation of Linear Regression using Python and the scikit-learn library, using a real-world dataset on Chicago taxi trips.

## 📖 Project Overview
Linear regression is one of the fundamental techniques in machine learning used for predictive modeling. It establishes a relationship between a dependent variable (target) and one or more independent variables (features) using a linear equation. The goal is to find the best-fitting line that minimizes the difference between predicted and actual values.

This project applies linear regression to a dataset derived from the **City of Chicago Taxi Trips dataset**. The dataset focuses on a two-day period in May 2022 and includes details about trip distance, duration, fare, company, payment type, and tip rate.

## 📊 Dataset Description
The dataset contains the following key features:
- **TRIP_MILES**: Distance traveled during the trip
- **TRIP_SECONDS**: Duration of the trip in seconds
- **FARE**: Total fare charged for the trip
- **COMPANY**: Taxi company providing the ride
- **PAYMENT_TYPE**: Mode of payment (cash, credit, etc.)
- **TIP_RATE**: Tip percentage relative to the fare

## 🔍 Objective
The goal of this project is to predict the **fare or tip rate** based on trip details using linear regression. The model is trained to find relationships between features and the target variable.

## 📌 Features
- Uses real-world taxi trip data
- Implements data preprocessing and feature selection
- Trains a linear regression model with scikit-learn
- Evaluates model performance using standard metrics
- Visualizes insights using Matplotlib

## 📂 Repository Structure
- `Linear Regression.ipynb` - Jupyter Notebook with step-by-step implementation
- `README.md` - Project documentation

## 🛠 Requirements
To run this project, you need:
- Python 3.x
- Jupyter Notebook
- NumPy, pandas, matplotlib, scikit-learn
