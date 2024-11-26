---
layout: page
title: Evaluating ChatGPT as a Recommender System
description: Official source code and datasets for the paper - Evaluating ChatGPT as a Recommender System: A Rigorous Approach.
img: assets/img/ChatGPT_EvalPipeline.png
importance: 1
category: work
---

# Evaluating ChatGPT as a Recommender System

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/ChatGPT_EvalPipeline.png" title="ChatGPT Evaluation Pipeline" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  The evaluation pipeline for assessing ChatGPT's performance as a recommender system.
</div>

## Project Overview

This project provides the official source code and datasets accompanying the paper "Evaluating ChatGPT as a Recommender System: A Rigorous Approach." It explores the potential of ChatGPT-3.5 and ChatGPT-4 models in zero-shot recommendation scenarios, offering a comprehensive framework for experimentation and evaluation.

## Features

- **Zero-Shot Recommendations**: Leverages ChatGPT models to generate recommendations without prior training on specific datasets.
- **Baseline Comparisons**: Includes implementations of traditional recommender system baselines for performance benchmarking.
- **Extensive Datasets**: Provides datasets necessary for conducting experiments, including MovieLens and Facebook Book datasets.
- **Evaluation Pipeline**: Offers a structured pipeline to facilitate reproducible experiments and evaluations.

## Usage

To set up and run the experiments:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/sisinflab/Recommender-ChatGPT.git
   ```
2. **Set Up the Environment**:
   Ensure Python 3.8.6 or later is installed. Create a virtual environment and install dependencies:
   ```bash
   conda env create -f conda_env/env.yml
   conda activate Recommender-ChatGPT
   ```
3. **Insert OpenAI API Token**:
   Obtain an API token from OpenAI and insert it into the appropriate configuration file.
4. **Run the Evaluation Pipeline**:
   Execute the main script to start the experiments:
   ```bash
   python code/main.py
   ```
   Results will be stored in the `results` folder.

## Dependencies

- **Python**: Version 3.8.6 or later
- **Conda**: For environment management
- **OpenAI API**: Access to ChatGPT models
- **Elliot**: Framework for recommender systems evaluation
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing

## Links

- [GitHub Repository](https://github.com/sisinflab/Recommender-ChatGPT)
- [Paper: Evaluating ChatGPT as a Recommender System: A Rigorous Approach](https://arxiv.org/abs/2309.03613)
- [Information Systems Lab @ Polytechnic University of Bari](https://github.com/sisinflab/)

For detailed information and updates, please refer to the [GitHub repository](https://github.com/sisinflab/Recommender-ChatGPT).
