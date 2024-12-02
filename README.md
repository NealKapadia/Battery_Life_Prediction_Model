# Battery Cycle Life Prediction and Experiment Optimization

This project uses machine learning to predict the cycle life of batteries based on material properties and operating conditions. It also suggests the next best experiment to maximize battery performance using neural networks and optimization techniques.

## Project Overview

1. **Cycle Life Prediction:**
   - A neural network is trained on battery data to predict the cycle life given various features like material, temperature, current, voltage, energy density, charge rate, and thermal stability.

2. **Experiment Optimization:**
   - **Bayesian Optimization:** Uses a more sophisticated search strategy to suggest the next experiment by balancing exploration and exploitation.

## Instructions

1. **Install Dependencies:**
   - Install all required Python libraries listed in the `requirements.txt` file by running:
     ```bash
     pip install -r requirements.txt
     ```

2. **Run the Code:**
   - Execute the code from the `main.py` file:
     ```bash
     python main.py
     ```

## Files in the Project

- `main.ipynb`: The main script to train the model, predict cycle life, and suggest experiments.
- `requirements.txt`: List of all Python dependencies required for the project.

## Features

- Trains a neural network to predict battery cycle life.
- Visualizes predictions with scatter plots and heatmaps.
- Suggests the next experiment to maximize cycle life using random sampling or Bayesian optimization.
