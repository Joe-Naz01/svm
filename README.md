# Support Vector Machine (SVM) Visualization

This repository contains a Jupyter Notebook designed to visualize and explain the core mechanics of Support Vector Machines (SVM), specifically focusing on the role of Support Vectors.

## Project Overview
Support vectors are the training examples that directly influence the position and orientation of the decision boundary. This project demonstrates that removing non-support vectors from the training set results in the exact same model.

### Key Features:
* **Algorithm:** Linear Support Vector Classification (SVC).
* **Data Visualization:**
    * Custom meshgrid functions to plot decision boundaries.
    * Comparison plots between a model trained on a full dataset vs. a model trained only on support vectors.
* **Key Concept:** Demonstrates that the model's decision boundary remains identical even when the training set is reduced to only its support vectors.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Joe-Naz01/svm.git
   cd svm

   python -m venv .venv
    # Windows: .venv\Scripts\activate
    source .venv/bin/activate
    pip install -r requirements.txt
    jupyter notebook
