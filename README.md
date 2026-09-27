# Smart Hybrid Energy Management System

A Smart Hybrid Energy Management System (SHEMS) that combines optimization-based methods, rule-based optimization, and reinforcement learning techniques for intelligent energy management and decision-making.

## Project Overview

This project investigates different approaches for managing energy resources and evaluating their performance in an energy management system.

The project includes three main approaches:

- Rule-Based Optimization
- Optimization-Based Methods
- Reinforcement Learning

For the reinforcement learning approach, three algorithms are implemented and evaluated:

- **DQN** — Deep Q-Network
- **PPO** — Proximal Policy Optimization
- **TD3** — Twin Delayed Deep Deterministic Policy Gradient

The repository contains the datasets, preprocessing notebooks, trained reinforcement learning models, experimental results, and an interactive dashboard for analyzing and comparing the results.

---

## Project Structure

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
├── results/
│   ├── optimization/
│   │   └── optimization_results_eff09.csv
│   │
│   ├── rule_based/
│   │   └── rule_based_results_eff09.csv
│   │
│   └── reinforcement_learning/
│       └── reinforcement learning results
│
├── dashboard/
│   ├── app.py
│   ├── dataset_clean.csv
│   ├── optimization_results_eff09.csv
│   ├── rule_based_results_eff09.csv
│   ├── comparison_summary_eff09.csv
│   └── evaluation_matrices_FIXED_objective.csv
│
├── README.md
└── requirements.txt
```

---

## Methods

### 1. Dataset Analysis

The project begins with analysis and preprocessing of the energy dataset.

The preprocessing workflow includes preparing the dataset for the optimization and reinforcement learning experiments, as well as dividing the data into training and testing sets.

The main notebook for this stage is:

```text
01_dataset_analysis.ipynb
```

### 2. Rule-Based Optimization

A rule-based approach is implemented as a baseline for the energy management problem.

The corresponding notebook is:

```text
02_rule_based_optimization.ipynb
```

The generated results are stored in:

```text
results/rule_based/
```

### 3. Reinforcement Learning

Three reinforcement learning algorithms are implemented and evaluated:

#### DQN
**Deep Q-Network**

#### PPO
**Proximal Policy Optimization**

#### TD3
**Twin Delayed Deep Deterministic Policy Gradient**

The reinforcement learning experiments are performed in:

```text
03_reinforcement_learning.ipynb
```

The trained models are stored in:

```text
models/
```

and the corresponding experimental results are stored in:

```text
results/reinforcement_learning/
```

---

## Models

The repository contains trained reinforcement learning models:

```text
models/
├── dqn/
│   └── dqn_model.zip
├── ppo/
│   └── ppo_model.zip
└── td3/
    └── td3_model.zip
```

These models can be used for further evaluation and experimentation.

---

## Results

The `results/` directory contains the outputs generated during the experiments.

### Optimization Results

```text
results/optimization/
└── optimization_results_eff09.csv
```

### Rule-Based Results

```text
results/rule_based/
└── rule_based_results_eff09.csv
```

### Reinforcement Learning Results

The reinforcement learning results contain the evaluation outputs for the implemented RL algorithms.

```text
results/reinforcement_learning/
```

---

## Dashboard

The project includes an interactive **Streamlit dashboard** for analyzing and comparing the energy management results.

The dashboard is located in:

```text
dashboard/
```

### RL Algorithms

The dashboard provides a dedicated view for comparing the three reinforcement learning algorithms:

- DQN
- PPO
- TD3

It displays comparison metrics, evaluation results, tables, and visualizations based on the reinforcement learning evaluation data.

The RL evaluation uses:

```text
evaluation_matrices_FIXED_objective.csv
```

### Optimization vs Rule-Based

The dashboard also provides a comparison between:

- Optimization (OPT)
- Rule-Based approach

The comparison includes metrics such as:

- Total Cost
- Savings
- Grid Import
- Grid Export
- Battery Capacity
- Average Tariff
- Equivalent Full Cycles (EFC)
- Daily Cost Trends

The dashboard also provides a date-range filter for analyzing selected periods.

### Dashboard Files

The dashboard uses the following files:

```text
dashboard/
├── app.py
├── dataset_clean.csv
├── optimization_results_eff09.csv
├── rule_based_results_eff09.csv
├── comparison_summary_eff09.csv
└── evaluation_matrices_FIXED_objective.csv
```

---

## Notebooks

| Notebook | Description |
|---|---|
| `01_dataset_analysis.ipynb` | Dataset analysis and preprocessing |
| `02_rule_based_optimization.ipynb` | Rule-based optimization |
| `03_reinforcement_learning.ipynb` | Reinforcement learning experiments |

---

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Mohammad-Alsalameen/Smart-Hybrid-Energy-Management-System.git
```

### 2. Open the Project Directory

```bash
cd Smart-Hybrid-Energy-Management-System
```

### 3. Install the Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Notebooks

Open the notebooks using Jupyter Notebook or JupyterLab:

```bash
jupyter notebook
```

Run the notebooks in the following order:

```text
01_dataset_analysis.ipynb
        ↓
02_rule_based_optimization.ipynb
        ↓
03_reinforcement_learning.ipynb
```

### 5. Run the Dashboard

To launch the interactive dashboard:

```bash
streamlit run dashboard/app.py
```

The dashboard will open in your web browser.

---

## Technologies

- **Python**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Gymnasium**
- **Stable-Baselines3**
- **Scikit-learn**
- **Streamlit**
- **Reinforcement Learning**

---

## Project Goal

The main goal of this project is to investigate intelligent energy management strategies by implementing and comparing optimization-based, rule-based, and reinforcement learning approaches.

The project provides a complete workflow starting from dataset analysis and preprocessing, followed by optimization and reinforcement learning experiments, and finally visualization and comparison of the obtained results through an interactive dashboard.

---

## Author

**Mohammad Al-Salameen**

GitHub: [Mohammad-Alsalameen](https://github.com/Mohammad-Alsalameen)
