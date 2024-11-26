---
layout: page
title: RecMOE: Multi-Objective Evaluation for Recommender Systems
description: "A library to compute Pareto fronts and evaluate them using Quality Indicators (QIs) for Recommender Systems."
img: assets/img/RecMOE_Pipeline.png
importance: 2
category: work
---

# RecMOE: Multi-Objective Evaluation for Recommender Systems

## Project Overview

RecMOE is a library designed to compute Pareto fronts and evaluate them using Quality Indicators (QIs) within the context of recommender systems. It accompanies the paper "Broadening the Scope: Evaluating the Potential of Recommender Systems beyond prioritizing Accuracy," presented at The 17th ACM Recommender Systems Conference (RecSys 2023), LBR track.

## Features

- **Pareto Front Computation**: Identifies optimal trade-offs among multiple objectives in recommender systems.
- **Quality Indicators Evaluation**: Assesses the performance of recommendation models using various QIs.
- **Baseline Training**: Provides source codes and datasets to reproduce experiments related to baseline model training.
- **Integration with Elliot**: Utilizes an ad-hoc version of the Elliot framework for comprehensive recommendation evaluations.

## Usage

To set up and utilize RecMOE:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sisinflab/RecMOE.git
   ```
2. **Set Up the Environment**:
   Ensure Python 3.8.0 or later is installed. Create a virtual environment and install dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
3. **Prepare Baseline Training Project**:
   Download the `my_sir_elliot` project folder from the provided link in the repository's README. This folder contains source codes and datasets for training baseline models.
4. **Train Baseline Models**:
   Navigate to the `my_sir_elliot` project directory and run:
   ```bash
   python -u start_experiments.py
   ```
   Results will be stored in the `results` folder within each dataset directory.
5. **Compute Pareto Fronts and Evaluate QIs**:
   In the main RecMOE project directory, execute:
   ```bash
   python main.py
   ```
   Adjust the `main.py` script as needed to specify objectives, reference points, and result storage paths. Detailed instructions are provided within the script.

## Dependencies

- **Python**: Version 3.8.0 or later
- **Elliot Framework**: For recommender systems evaluation
- **NumPy**: Numerical computing
- **Pandas**: Data manipulation and analysis

## Links

- [GitHub Repository](https://github.com/sisinflab/RecMOE)
- [Paper: Broadening the Scope: Evaluating the Potential of Recommender Systems beyond prioritizing Accuracy](https://recsys.acm.org/recsys23/)
- [Information Systems Lab @ Polytechnic University of Bari](https://github.com/sisinflab/)

For detailed information and updates, please refer to the [GitHub repository](https://github.com/sisinflab/RecMOE).
