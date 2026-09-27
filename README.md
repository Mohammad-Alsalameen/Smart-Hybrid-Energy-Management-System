# Smart Hybrid Energy Management System

A Smart Hybrid Energy Management System that combines rule-based optimization with reinforcement learning techniques to improve energy management and decision-making.

## Project Overview

This project explores different approaches for managing energy resources using:

- Rule-Based Optimization
- Optimization-based methods
- Reinforcement Learning

The reinforcement learning part includes three algorithms:

- DQN (Deep Q-Network)
- PPO (Proximal Policy Optimization)
- TD3 (Twin Delayed Deep Deterministic Policy Gradient)

The project also includes datasets, trained models, Jupyter notebooks, and experimental results.

## Repository Structure

```text
Smart-Hybrid-Energy-Management-System/
│
├── data/
│   ├── dataset.csv
│   ├── dataset_clean.csv
│   ├── dataset_train.csv
│   └── dataset_test.csv
│
├── models/
│   ├── dqn/
│   │   └── dqn_model.zip
│   ├── ppo/
│   │   └── ppo_model.zip
│   └── td3/
│       └── td3_model.zip
│
├── notebooks/
│   ├── 01_dataset_analysis.ipynb
│   ├── 02_rule_based_optimization.ipynb
│   └── 03_reinforcement_learning.ipynb
│
└── results/
    ├── optimization/
    │   └── optimization_results_eff09.csv
    ├── rule_based/
    │   └── rule_based_results_eff09.csv
    └── reinforcement_learning/
        └── reinforcement learning results
Methods
1. Dataset Analysis

The project starts with analysis and preprocessing of the energy dataset. The dataset is cleaned and divided into training and testing data.

2. Rule-Based Optimization

A rule-based approach is implemented to provide an optimization baseline for the energy management problem.

3. Reinforcement Learning

Three reinforcement learning algorithms are used and evaluated:

DQN — Deep Q-Network
PPO — Proximal Policy Optimization
TD3 — Twin Delayed Deep Deterministic Policy Gradient

The trained models are stored in the models/ directory, while their experimental results are stored in results/reinforcement_learning/.

Notebooks
Notebook	Description
01_dataset_analysis.ipynb	Dataset analysis and preprocessing
02_rule_based_optimization.ipynb	Rule-based optimization
03_reinforcement_learning.ipynb	Reinforcement learning experiments
Models

The repository contains trained reinforcement learning models:

dqn_model.zip
ppo_model.zip
td3_model.zip

These models can be used for further evaluation and experimentation.

Results

The results/ directory contains the outputs generated during the experiments:

Optimization results
Rule-based results
Reinforcement learning results
Technologies
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Gymnasium
Stable-Baselines3
Scikit-learn
Reinforcement Learning
Project Goal

The main goal of this project is to investigate intelligent energy management strategies by comparing traditional optimization approaches with reinforcement learning algorithms.

