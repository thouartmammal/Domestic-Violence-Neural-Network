# Domestic-Violence-Neural-Network

This repository contains a neural network project focused on predicting and analysing domestic violence data.  
The notebook (`domestic_violence.ipynb`) explores dataset preprocessing, handling class imbalance, and building a classification model to identify patterns of domestic violence against women.

---

## Project Structure
- `1_DV_Preprocessing.ipynb` — Jupyter notebook with data exploration and preprocessing.
- `2_DV_NeuralNetwork.ipynb` - model training, and evaluation.
- `README.md` — Documentation of the project.

---

## Dataset
The dataset used in this project comes from Kaggle:  
[Domestic Violence Against Women](https://www.kaggle.com/datasets/fahmidachowdhury/domestic-violence-against-women)

---

## Methods
Key methods and approaches applied:
- **Data Splitting**: Train, validation, and test sets ([reference](https://www.v7labs.com/blog/train-validation-test-set))
- **Class Imbalance Handling**:  
  - Threshold adjustment ([reference](https://machinelearningmastery.com/threshold-moving-for-imbalanced-classification/))  
  - SMOTE oversampling ([reference](https://machinelearningmastery.com/smote-oversampling-for-imbalanced-classification/))
- **Model**: Feedforward neural network trained on preprocessed features.

---

## Getting Started
To run the notebook locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/thouartmammal/Domestic-Violence-Neural-Network.git
   cd Domestic-Violence-Neural-Network
2. Install dependencies
   ```bash
   pip install -r requirements.txt
