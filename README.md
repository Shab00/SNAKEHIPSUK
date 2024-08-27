# SNAKEHIPSUK
I am working on a YouTube analytics project focused on the SNAKEHIPSUK channel. The project involves utilizing machine learning and data science techniques to predict columns in a CSV file containing relevant data.

# Snakehips Analytics

This repository contains a Jupyter Notebook (`snakehips_analytics.ipynb`) that performs various data analysis and visualization tasks on a dataset of Snakehips videos. The notebook includes steps for data preprocessing, feature selection, normalization, and visualization.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Steps](#analysis-steps)
  - [Selecting Relevant Columns](#selecting-relevant-columns)
  - [Normalization/Standardization](#normalizationstandardization)
  - [Correlation Matrix and Heatmap](#correlation-matrix-and-heatmap)
  - [Top 5 Videos by View Count](#top-5-videos-by-view-count)
  - [Total View Count by Day of the Week](#total-view-count-by-day-of-the-week)
  - [Time Series of Video Views](#time-series-of-video-views)
  - [Distribution of Video Durations](#distribution-of-video-durations)
  - [Word Cloud Visualization](#word-cloud-visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The `snakehips_analytics.ipynb` notebook provides a comprehensive analysis of Snakehips videos, including data preprocessing, feature selection, normalization, and various visualizations to gain insights into the dataset.

## Dataset

The dataset contains information about Snakehips videos, including titles, descriptions, tags, view counts, like counts, comment counts, and more.

## Installation

To run the notebook, you need to have Python and Jupyter Notebook installed. You can install the required packages using the following command:

```bash
pip install -r requirements.txt

Usage
To start the Jupyter Notebook, run the following command:

Analysis Steps
Selecting Relevant Columns
We select the most relevant columns for our analysis and machine learning tasks to focus on the features that are most likely to impact the model's performance.

Normalization/Standardization
We normalize or standardize the numerical columns to ensure that they contribute equally to the model, improving the performance and stability of machine learning models.

Correlation Matrix and Heatmap
We calculate the correlation matrix for the numerical columns and visualize it using a heatmap to understand the relationships between different numerical features.

Top 5 Videos by View Count
We sort the dataset by view count in descending order and visualize the top 5 videos with the highest view counts using a bar chart.

Total View Count by Day of the Week
We aggregate the total view counts by the day of the week and visualize the results using a bar chart to understand the distribution of view counts across different days.

Time Series of Video Views
We convert the publishedAt_timestamp to a date format, aggregate the total view counts by date, and visualize the results using a time series plot to understand the trend of video views over time.

Distribution of Video Durations
We visualize the distribution of video durations using a histogram to understand the spread and frequency of different video lengths in the dataset.

Word Cloud Visualization
We preprocess the text data from the title, description, and tags columns, and visualize the most frequent words using a word cloud to gain insights into the common themes and topics.

Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
