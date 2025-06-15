# Exploring Bandit Algorithms in Stationary and Non-Stationary Environments

## Project Overview:
This repository contains the code and report for the study comparing several multi-armed bandit algorithms under stationary and non-stationary settings.

The algorithms studied include:
- **Greedy (Q=0):** Pure exploitation with zero-initialized action values
- **Epsilon-Greedy:** Exploration with a small probability ε, tuned via pilot experiments
- **Optimistic Greedy:** Greedy with optimistic initial action values to encourage exploration
- **Gradient Bandit:** A policy-gradient method using softmax action preferences and a tuned learning rate α

Environments tested:
- **Stationary:** Fixed reward distributions
- **Non-Stationary:** Includes gradual drift, mean-reverting dynamics, abrupt changes (with and without reset)

Performance is evaluated over 1000 independent simulations of 2000 time steps each, using:
- Average reward per step
- Percentage of optimal action selections

## Repository Contents:
- `Bandit Algorithms in Stationary and Non-Stationary Environments.ipynb`: Main notebook containing the code, results, and visualizations
- `Report.pdf`: Formal report including plots and analysis of results
- `README.md`: Project overview and instructions (this file)

## How to Run the Code:
### Option 1: Run on Google Colab (Recommended)
1. Click the notebook file: `Bandit Algorithms in Stationary and Non-Stationary Environments.ipynb`
2. At the top, click **"Open in Colab"**
3. Go to `Runtime > Run all` to execute all cells
   
### Option 2: Run Locally with Python 3
1. Make sure you have Python 3 and Jupyter Notebook installed
2. Download the notebook file:
Bandit Algorithms in Stationary and Non-Stationary Environments.ipynb
3. Open Jupyter Notebook on your machine
4. Navigate to the downloaded .ipynb file and open it
5. Run all cells: Kernel > Restart & Run All

## Requirements:
This project uses the following Python libraries, which are already installed in the notebook environment:  
- numpy
- matplotlib
- scipy

## Results:
The notebook generates plots and tables described in the report, summarizing the performance of different bandit algorithms
