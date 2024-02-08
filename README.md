[中文版本](README_zh.md)
# Fruit Classification Project

## Project Overview
This project classifies fruits using the K-Nearest Neighbors (KNN) algorithm. By analyzing the physical characteristics of fruits, such as mass, width, height, and color score, our model can accurately classify fruits into different categories.

## Dataset
The dataset used in this project includes the physical characteristics of various fruits, such as mass, width, height, and color score. The dataset is from Kaggle: [Fruit with colors dataset](https://www.kaggle.com/datasets/mjamilmoughal/fruits-with-colors-dataset).

## How to Use
1. Install the necessary Python libraries.
2. Load the dataset.
3. Run the KNN classification model.
4. Evaluate the model's performance.

## Model Evaluation Results
After thorough testing, it was discovered that among the original four features (mass, width, height, and color score), selecting only "width and height" as the basis for classification yields the most accurate results. Utilizing these two features, the model achieved an accuracy of 95%, indicating that considering both width and height is crucial for effectively classifying fruits.

## Requirements
This project requires the following Python libraries:
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

