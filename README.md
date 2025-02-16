# YouTube Analytics Project: SNAKEHIPSUK Channel

## snakeHipsAnalytics.ipynb
## snakeHipsAnalyticsPLayers.ipynb
This Jupyter Notebook contains a comprehensive analysis of SNAKEHIPS videos, including data preprocessing, feature selection, normalization, and various visualizations to gain insights into the dataset.

### Table of Contents
1. Introduction
2. Dataset
3. Installation
4. Usage
5. Analysis Steps
   - Selecting Relevant Columns
   - Normalization/Standardization
   - Correlation Matrix and Heatmap
   - Top 5 Videos by View Count
   - Total View Count by Day of the Week
   - Time Series of Video Views
   - Distribution of Video Durations
   - Word Cloud Visualization
6. Contributing
7. License

### Understanding the Data Columns
- title
- publishedAt_timestamp
- viewCount, likeCount, commentCount
- tagCount
- duration_seconds
- caption_False, caption_True
- definition_hd, definition_sd
- publishDayName

### Feature Engineering
This section focuses on creating new features from the existing ones to potentially improve the model's performance. Two new features are engineered.

### Creating Target Variable and Data Cleaning
This section defines the target variable for the machine learning model and performs some data cleaning.

### Defining the Model Architecture
This code defines a function `get_model` that creates and compiles a neural network model and prints a detailed classification report.

## requirements.txt
Contains the list of required packages for running the Jupyter Notebook.

# Learning Experience Using TensorFlow

Although the dataset for this project consists of only a small number of videos from the SNAKEHIPSUK channel, I chose to implement a neural network model using TensorFlow as part of a learning experience. TensorFlow is a powerful library often used for more complex, large-scale machine learning problems. However, in this case, my goal was to gain hands-on experience with TensorFlow's architecture, model building, and performance evaluation, even though a simpler algorithm might have sufficed for this dataset.

Through this project, I practiced key steps in the machine learning workflow, including data preprocessing, feature engineering, and model evaluation. While the choice of TensorFlow might be considered overkill for a small dataset, it served as an excellent platform to solidify my understanding of neural networks and model training, which can be applied to larger datasets and more complex problems in the future.

# Key Model Performance Metrics

## Precision
- For class 0 (not popular): 0.92
- For class 1 (popular): 0.85

## Recall
- For class 0: 0.86
- For class 1: 0.92

## F1-Score
- Both classes: around 0.88

## Support
- Class 0: 14 samples
- Class 1: 12 samples

## Accuracy
- 0.88

The model demonstrates strong performance overall, with high accuracy and good precision and recall for both classes. The slight difference in precision and recall between the classes suggests that the model might be slightly better at identifying "popular" videos than "not popular" videos.
This README.md provides an overview of the YouTube analytics project for the SNAKEHIPSUK channel, detailing the content and purpose of each file in the repository.
