# Genetic Algorithms & Machine Learning

This repository contains academic projects focused on optimization algorithms, machine learning, and feature selection techniques, implemented using Python.

The projects explore how machine learning algorithms work internally, including mathematical concepts such as Gradient Descent, Logistic Regression, and evolutionary optimization.

## Projects

### 1. Genetic Algorithm

An implementation exploring Genetic Algorithms as an optimization approach inspired by natural selection and evolutionary processes.

**Key Concepts:**

* Population Initialization
* Chromosome Representation
* Fitness Function
* Selection
* Single-Point Crossover
* Mutation
* Feature Selection

The project uses Logistic Regression accuracy as a fitness evaluation metric to explore feature combinations.

### 2. Logistic Regression from Scratch

A basic implementation of Logistic Regression using NumPy, focusing on understanding the mathematical foundations behind binary classification.

**Implemented Components:**

* Sigmoid Function
* Cost Function (Binary Cross-Entropy)
* Gradient Descent
* Weight and Bias Updates
* Binary Classification
* Prediction using a 0.5 threshold

The model is trained using the Breast Cancer dataset to classify observations into two categories.

### 3. Sequential Forward and Backward Feature Selection

An exploration of wrapper-based feature selection techniques using a Random Forest classifier.

**Methods:**

* Sequential Forward Selection (SFS)
* Sequential Backward Selection (SBS)
* K-Fold Cross Validation
* Accuracy-based Feature Evaluation

The objective is to identify useful feature subsets and examine their impact on classification performance.

## Technologies & Libraries

* **Python** – Main programming language
* **NumPy** – Numerical computations and array operations
* **Pandas** – Dataset loading and manipulation
* **Scikit-learn** – Machine learning models, data splitting, and evaluation
* **MLxtend** – Sequential Feature Selection
* **Matplotlib & Seaborn** – Data visualization

## Dataset

The projects use the Breast Cancer dataset (`breast-cancer.csv`) for classification and feature selection experiments.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/elsen111/genetic-algorithms.git
cd genetic-algorithms
```

### 2. Install dependencies

```bash
pip install numpy pandas scikit-learn matplotlib seaborn mlxtend
```

### 3. Run the notebooks

Open the Jupyter notebooks:

```bash
jupyter notebook
```

Run the notebooks individually to explore the implementations and experiments.

## Repository Structure

```text
genetic-algorithms/
│
├── genetic_algorithm.ipynb
├── logistic_regression.ipynb
├── SEQUENTIAL_BACKWARD_AND_FORWARD_SEARCH.ipynb
├── breast-cancer.csv
└── README.md
```

## Learning Objectives

* Understand the fundamentals of evolutionary optimization.
* Explore the mathematical foundations of Logistic Regression.
* Implement Gradient Descent using NumPy.
* Understand feature selection strategies.
* Apply machine learning techniques to classification problems.
* Gain practical experience with Python-based data analysis.

## Project Context

Academic projects developed to explore optimization methods, machine learning algorithms, and their mathematical foundations through practical Python implementations.
