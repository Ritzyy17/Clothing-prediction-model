# Clothing-prediction-model
# Sales Data Clustering and Classification

This project implements a **K-Means clustering** technique to group sales data based on age and a **Gradient Boosting Classifier** to predict style attributes of products. The project also performs a **Grid Search** to fine-tune the Gradient Boosting model for better accuracy.

## Overview

This repository includes code that performs the following:

1. **Clustering**: Group sales data into 5 clusters based on age using **K-Means**.
2. **Classification**: Predict **style attributes** of products using **Gradient Boosting**.
3. **Model Evaluation**: Evaluate the performance of the model using **accuracy** as the metric.

## Steps Involved

### Step 1: K-Means Clustering
- Group the data based on the **Age** feature using K-Means clustering.

### Step 2: Gradient Boosting Model
- Split the dataset into **train** and **test** sets.
- Apply **one-hot encoding** to categorical features.
- Train a **Gradient Boosting Classifier** to predict **Style Attributes**.
- Evaluate the model's performance on the test set using **accuracy**.

### Step 3: Hyperparameter Tuning
- Perform a **Grid Search** to find the best hyperparameters for the Gradient Boosting model.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sales-data-clustering.git
   cd sales-data-clustering
