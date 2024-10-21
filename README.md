# Outdoor Tennis Prediction

This repository contains the solution for the Outdoor Tennis Prediction task from the machine learning assignment. The goal is to determine whether outdoor tennis can be played based on specific weather conditions.

## Table of Contents

- [Dataset](#dataset)
- [Features](#features)
- [Model Training and Prediction](#model-training-and-prediction)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

## Dataset

The dataset consists of 20 samples with the following columns:

| Temperature | Rainy | Windy | Play Tennis |
|-------------|-------|-------|-------------|
| 30          | No    | No    | Yes         |
| 25          | Yes   | No    | No          |
| 20          | No    | Yes   | No          |
| 15          | Yes   | Yes   | No          |
| ...         | ...   | ...   | ...         |

## Features

- **Temperature**: The temperature in degrees Celsius.
- **Rainy**: Indicates whether it is raining (Yes/No).
- **Windy**: Indicates whether it is windy (Yes/No).
- **Play Tennis**: Target variable indicating if tennis can be played (Yes/No).

## Model Training and Prediction

A Decision Tree Classifier is used to train the model on the dataset. The model is then tested on three new unseen samples to predict whether outdoor tennis can be played.

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>

   cd <directory_name>
   
pip install -r requirements.txt

jupyter notebook


## Requirements
- Python 3.x
- pandas
- scikit-learn
- Jupyter Notebook
