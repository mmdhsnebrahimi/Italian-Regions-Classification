# Artificial Neural Networks: Italian Regions Classification 🇮🇹🌍

## Overview
This repository contains a practical implementation of an Artificial Neural Network applied to a real-world geographic dataset. The primary objective is to classify data samples into specific regions of Italy based on 60 distinct continuous features, utilizing a Radial Basis Function (RBF) Neural Network.

## The Dataset
The project is built around a comprehensive dataset comprising 570 samples. The core challenge is a multi-class classification problem where each data point must be accurately mapped to one of four geographic categories:
1. **North Italy**
2. **South Italy**
3. **Sardinia**
4. **Other Regions**

## Key Features & Workflow
* **Real-World Data Processing:** Handling a complex dataset with 60 features, requiring meticulous preparation to ensure model stability.
* **Feature Standardization:** Normalizing the 60 continuous variables to a standard scale (Mean: 0, Std: 1) to prevent features with larger magnitudes from dominating the network.
* **Categorical Encoding:** Utilizing One-Hot Encoding to perfectly format the four regional classes for the neural network's output layer.
* **RBF Architecture:** Designing and training a robust RBF classifier specifically tuned for this geographic multi-class problem.
* **Visualizing Convergence:** Generating training history plots to monitor the loss reduction and accuracy trajectory across epochs, ensuring optimal generalization.

## Technologies Used
* **Python 3**
* **NumPy & Pandas** (For loading, structuring, and standardizing the geographic data)
* **Matplotlib** (For visual performance tracking)
