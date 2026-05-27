# Active Learning-Based Face Mask Detection using Deep Learning

## Overview

This project implements a **Deep Learning–based Face Mask Detection system enhanced with Active Learning strategies** using **PyTorch**. The objective is to classify facial images into **With Mask** and **Without Mask** categories while evaluating how different **uncertainty-based sampling methods** impact model learning efficiency and predictive performance.

The project combines **Computer Vision**, **Convolutional Neural Networks (CNNs)**, and **Active Learning** to study intelligent sample selection techniques for model training.

---

## Features

* Face Mask Image Classification using CNNs
* Deep Learning implementation with **PyTorch**
* Comparison of multiple **Active Learning strategies**
* Training and testing performance evaluation
* Accuracy tracking and visualization
* Model checkpoint saving and experiment logging

---

## Active Learning Methods Implemented

The project compares the following uncertainty-driven sampling approaches:

1. **Largest Margin Sampling**
2. **Smallest Margin Sampling**
3. **Least Confidence Sampling**
4. **Entropy-Based Sampling**
5. **Random Sampling (Baseline)**

These strategies are evaluated to determine their effectiveness in selecting informative training samples and improving learning efficiency.

---

## Tech Stack

**Programming Language:** Python

**Libraries & Frameworks:**

* PyTorch
* Torchvision
* NumPy
* Matplotlib
* Pickle

**Machine Learning Concepts:**

* Deep Learning
* Convolutional Neural Networks (CNN)
* Active Learning
* Uncertainty Sampling
* Image Classification
* Model Evaluation

---

## Project Workflow

### 1. Data Preparation

* Load image datasets using PyTorch data loaders.
* Apply preprocessing and transformation pipelines.
* Organize data into training and testing sets.

### 2. CNN Model Development

* Build a custom CNN architecture using:

  * Convolutional Layers
  * Pooling Layers
  * Batch Normalization
  * Activation Functions
  * Regularization techniques

### 3. Active Learning Strategy Implementation

Implement multiple uncertainty selection techniques:

* Margin-based sampling
* Entropy sampling
* Least-confidence sampling
* Random baseline comparison

### 4. Model Training & Evaluation

* Train CNN models across multiple epochs.
* Measure training and testing accuracy.
* Compare performance between sampling strategies.
* Save trained model checkpoints.

### 5. Visualization & Analysis

Generate comparative plots for:

* Training Accuracy
* Testing Accuracy
* Strategy Performance Comparison
* Learning Behavior Analysis

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/yourrepository.git
cd yourrepository
```

Install dependencies:

```bash
pip install torch torchvision numpy matplotlib
```

---

## Running the Project

Launch the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
Active_Learning_Comparison.ipynb
```

Run all notebook cells to reproduce experiments and visualizations.

---

## Sample Results

The project compares multiple active learning strategies against random sampling to analyze:

* Training performance
* Test accuracy
* Model learning efficiency
* Informative sample selection effectiveness

---

## Future Improvements

* Hyperparameter optimization
* Transfer Learning using pretrained CNN architectures
* Larger image datasets
* Real-time face mask detection deployment
* Integration with webcam/live inference systems

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Computer Vision
* Deep Learning using PyTorch
* Active Learning & Uncertainty Sampling
* CNN Architecture Design
* Experimental Model Comparison
* Performance Visualization & Analysis

---

