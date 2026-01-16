# Potato Disease Classification

This project trains and serves a convolutional neural network that distinguishes between Early Blight, Late Blight, and Healthy potato leaves.

## Getting Started

1. Ensure Python 3.10+ is available.
2. Inside a virtual environment, install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `potato-disease-classification-model.ipynb`, run Cell 3 to regenerate the pinned requirements file if needed, and execute the remaining cells in order.

## Repository Contents

- `potato-disease-classification-model.ipynb` – end-to-end training workflow.
- `0.keras` – saved TensorFlow model for deployment (e.g., Raspberry Pi).
- `test_model_prediction.ipynb` – lightweight inference example.
- `requirements.txt` – pinned Python package versions used by the notebooks.

## Dataset

The training images originate from the PlantVillage collection on Kaggle: <https://www.kaggle.com/arjuntejaswi/plant-village>.

The raw dataset is not checked into this repository. Download it directly from Kaggle and place it under `PlantVillage/` before running the notebook.

## Model Export

The notebook saves two artifacts (`0.keras` and `potatoes.h5`). Use whichever format best suits your deployment target.
