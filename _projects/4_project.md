---
layout: page
title: Point-of-Interest Recommendation via Graph Neural Networks
description: A Master's thesis project focusing on developing a recommender system using Graph Neural Networks on heterogeneous graphs.
img: assets/img/POI_GNN_Pipeline.png
importance: 3
category: work
---

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/POI_GNN_Pipeline.png" title="POI Recommendation Pipeline" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
<div class="caption">
  The pipeline illustrating the process of recommending points of interest using Graph Neural Networks on heterogeneous graphs.
</div>

## Project Overview

This project presents the outcomes of a Master's thesis and internship conducted at Universidad Autónoma de Madrid. The primary objective was to develop a recommender system utilizing Graph Neural Networks (GNNs) applied to heterogeneous graphs, specifically targeting Point-of-Interest (POI) recommendations.

## Features

- **Graph Neural Network Implementation**: Developed models employing GNNs to capture complex relationships within heterogeneous graph structures.
- **POI Recommendation**: Focused on recommending locations of interest to users based on their preferences and behaviors.
- **Data Analysis**: Conducted comprehensive analyses on datasets, including the Yelp dataset, to extract meaningful insights.
- **Model Evaluation**: Implemented both classification and regression models to evaluate the performance of the recommender system.

## Usage

To explore and utilize the project:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/DarioDiPalma-DDP/Point-Of-Interest_recommendation-through-GNNs-on-heterogeneous-graphs.git
   ```
2. **Set Up the Environment**:
   Ensure Python 3.8 or later is installed. Create a virtual environment and install the necessary dependencies:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install --upgrade pip
   pip install -r requirements.txt
   ```
3. **Explore Notebooks**:
   The repository includes several Jupyter notebooks:
   - `Model_V2_Classification.ipynb`: Contains the classification model implementation.
   - `Model_V2_Regression.ipynb`: Contains the regression model implementation.
   - `Yelp Data Analysis.ipynb`: Provides data analysis on the Yelp dataset.
   
   Open these notebooks using Jupyter to review the code and results.

## Dependencies

- **Python**: Version 3.8 or later
- **PyTorch**: For building and training neural network models
- **PyTorch Geometric**: Extension library for GNNs
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Jupyter Notebook**: For interactive code execution and visualization

## Links

- [GitHub Repository](https://github.com/DarioDiPalma-DDP/Point-Of-Interest_recommendation-through-GNNs-on-heterogeneous-graphs)
- [Universidad Autónoma de Madrid](https://www.uam.es/)

For detailed information and updates, please refer to the [GitHub repository](https://github.com/DarioDiPalma-DDP/Point-Of-Interest_recommendation-through-GNNs-on-heterogeneous-graphs).
