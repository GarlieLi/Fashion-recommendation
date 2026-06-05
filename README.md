# CNN-Based Fashion Recommendation System

## Overview

This project develops a fashion recommendation system using Convolutional Neural Networks (CNNs) and cosine similarity. The system recommends visually similar fashion products based on image features extracted from product images.

## Data Source

Fashion Product Images Dataset (Kaggle)

https://www.kaggle.com/datasets/paramaggarwal/fashion-product-images-small

## Workflow

1. Image preprocessing
2. CNN feature extraction
3. Feature embedding generation
4. Cosine similarity calculation
5. Recommendation generation

## CNN Architecture

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* GlobalAveragePooling2D
* Dense(128) Embedding Layer
* Dropout(0.5)
* Dense(4, Softmax)

## Experiments

* CNN with vs. without Dropout
* Adam vs. SGD Optimizer

Training Parameters:

* Learning Rate: 0.001
* Batch Size: 32
* Epochs: 40

## Results

The CNN successfully learned visual features from fashion images and generated recommendations based on image similarity. Cosine similarity was used to identify and retrieve visually similar products.

## Authors

Jiajia Li, Jing Tan
