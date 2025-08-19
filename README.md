# MLflow with DagsHub 

This repository demonstrates how to use **MLflow** for experiment tracking, model management, and deployment, integrated with **DagsHub** as a remote tracking server.  

The included notebook **MLflow.ipynb** walks through:  

##  Project Overview
- Introduction to **MLflow**
- Setting up **DagsHub** for MLflow tracking
- Logging metrics, parameters, and artifacts
- Registering and managing models
- Loading models from the MLflow Model Registry

---

##  Requirements
To run the notebook, install the following dependencies:

```bash
pip install mlflow dagshub jupyter

##  Usage

**Clone the repository:**
```bash
git clone https://github.com/Kahkashan2708/MLflow-DagsHub.git
cd MLflow-DagsHub

**Launch Jupyter Notebook:**
```bash
jupyter notebook

**Repository Structure:**

MLflow-DagsHub/
│── MLflow.ipynb    # Main notebook with MLflow + DagsHub demo
│── README.md       # Project documentation
