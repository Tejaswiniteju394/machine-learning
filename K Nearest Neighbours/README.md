# K-Nearest Neighbors (KNN) Project

## Overview

**K-Nearest Neighbors (KNN)** is a simple, non-parametric, supervised machine learning algorithm used for **classification** and **regression**. It works by finding the **'k' closest data points** (neighbors) to a given input and making predictions based on the **majority vote** (for classification) or **average** (for regression) of those neighbors.

## Features
- Easy to understand and implement
- No training phase — it's a **lazy learner**
- Adaptable for both classification and regression tasks
- Distance-based learning (typically Euclidean distance)

## How KNN Works
1. Choose the number of neighbors **k**.
2. Calculate the distance from the query point to all other points in the dataset.
3. Identify the **k nearest neighbors**.
4. For classification: return the **most frequent class** among neighbors.
5. For regression: return the **average value** of neighbors.
