# MLOps Pipeline using DVC and MLflow

## Overview
This project implements an end-to-end MLOps pipeline for a loan default prediction system (LoanGuard AI). It focuses on solving real-world issues such as model failures, lack of reproducibility, and poor experiment tracking by integrating data versioning, experiment tracking, model versioning, and model lifecycle management.

## Objective
- Build a reproducible machine learning pipeline
- Version and manage datasets using DVC
- Track experiments using MLflow
- Manage model versions and lifecycle
- Improve reliability of ML systems in production

## Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- DVC (Data Version Control)
- MLflow

## Project Workflow

### 1. Data Versioning (DVC)
- Track datasets and changes over time
- Reproduce previous experiments
- Ensure data consistency across runs

### 2. Experiment Tracking (MLflow)
- Log parameters, metrics, and models
- Compare multiple model performances
- Identify best-performing model

### 3. Model Versioning
- Save and version trained models
- Maintain history of model improvements
- Enable rollback to previous versions

### 4. Model Registry Lifecycle
- Register models in MLflow
- Promote models through stages:
  - Staging
  - Production
  - Archived

## How It Works
1. Initialize workspace and tracking systems
2. Version dataset using DVC
3. Train multiple machine learning models
4. Evaluate models using performance metrics
5. Log experiments using MLflow
6. Register and manage models in MLflow registry
7. Promote models through lifecycle stages

## Usage
Run using Jupyter Notebook or Google Colab.
Execute the cells step-by-step to:
- Set up the project workspace
- Train machine learning models
- Track experiments using MLflow
- Perform model evaluation and comparison

## Learning Outcomes
- Understanding of MLOps pipeline design
- Hands-on experience with DVC and MLflow
- Ability to track, compare, and manage models
- Knowledge of model lifecycle management in real-world systems

## Author
Shanaaz  
    
