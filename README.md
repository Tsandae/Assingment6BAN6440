# Assingment6BAN6440
# Otomoto Marketing Segmentation - ANN Optimization Project

## Project Overview

This project focuses on optimizing an artificial neural network for marketing segmentation at Otomoto, a company aiming to improve customer targeting through data-driven strategies. By testing multiple optimization algorithms, we aimed to enhance the model's accuracy in predicting customer churn.

---

## Dataset

The dataset used is teleconnect.csv, which contains customer demographics, subscription details, service usage patterns, and a binary churn indicator.

---

## Project Steps

### Step 1: Recreated the Existing Model
- A baseline ANN model was implemented using Keras with 2 hidden layers.


### Step 2: Selected Optimization Algorithms
- Chosen optimizers:
  - **SGD**: Stochastic Gradient Descent (benchmark baseline)
  - **Adam**: Adaptive Moment Estimation (adaptive learning rates)
  - **RMSprop**: Root Mean Square Propagation (handles noisy gradients well)

### Step 3: Applied Optimization Algorithms
- Trained the same ANN model with each optimizer for 20 epochs.
- Batch size: 32
- Loss function: Binary crossentropy
- Metrics: Accuracy

### Step 4: Evaluated the Models
- Accuracy and classification reports were generated for all three optimizers.
- Performance visualizations included:
- Loss and accuracy curves
---

## Recommendations
- **Adam** is the preferred optimizer for this segmentation task.
---

## Libraries Used

- Python 3.x
- pandas, numpy
- sklearn
- tensorflow / keras
- matplotlib, seaborn
