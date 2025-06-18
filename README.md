# ShivamVyas_EA_Assignment3
EA Assignment for Understanding of  Nueral ODE and PINNS


# Shivam Vyas - Assignment 2

## Overview
This repository contains my solutions for Assignment 2, which covers:

1. Physics-Informed Neural Networks (PINNs) for cardiac activation time estimation, comparing PINN, data-only neural network, and interpolation.
2. Neural Ordinary Differential Equations (Neural ODEs) vs standard neural networks for a classification task.

## Repository Structure
- `src/`: Contains source code for each question.
- `requirements.txt`: Required Python packages.

## How to Run

### Question 1: PINN vs Data-Only NN
- Navigate to `src/`
- Run: `Question1.ipynb`
- The script trains models, plots activation maps and error maps, and prints RMSE results.

### Question 2: Neural ODE vs Standard NN
- Navigate to `src/`
- Run: `Question2.ipynb`
- The script trains both models on the toy dataset, prints training/test accuracy, and plots decision boundaries and loss curves.

## Dependencies
- Python 3.x
- torch
- torchdiffeq
- numpy
- matplotlib
- scipy
- scikit-learn

Install dependencies using:  

!pip install -r requirements.txt

