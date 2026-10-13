# CICD-for-Machine-Learning

# MLOps: CI/CD Pipeline for Drug Classification

This repository contains an automated MLOps pipeline designed to preprocess data, train a machine learning model, evaluate its performance, and seamlessly deploy it to production.

## Pipeline Features
- **Continuous Integration (CI):** Triggered via GitHub Actions on every commit to `main`.
- **Automated Reporting:** Generates a real-time markdown performance report with metrics and a confusion matrix using **Continuous Machine Learning (CML)**.
- **Continuous Deployment (CD):** Synchronizes code, data, models, and dependencies directly to **Hugging Face Spaces**.

## Folder Structure
- `app/`: Houses the user interface deployment logic.
- `data/`: Stores your dataset (`drug.csv`).
- `model/`: Automatically saves trained pipeline binaries (`drug_pipeline.skops`).
- `results/`: Saves performance summaries and analytical visuals.
