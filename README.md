# Facial Emotion Recognition - MLP vs CNN

## Project Overview
This project compares the performance of MLP and CNN models on the FER2013 dataset.

## Models Implemented
- MLP (Baseline)
- CNN (Baseline)
- CNN (Tuned with hyperparameter optimization)

## Hyperparameter Tuning
- Learning Rate
- Batch Size
- Dropout (Regularization)

## Results
CNN significantly outperforms MLP due to spatial feature extraction capability.

## Technologies Used
- Python
- TensorFlow
- Keras
- Matplotlib
- Pandas
## How to Run the Project

1. Clone the repository
2. Install dependencies:
   pip install -r requirements.txt
3. Download the FER2013 dataset from Kaggle
4. Place the dataset inside the project folder
5. Open and run DL_Scaffolded_Project(Review_1).ipynb
## Final Results

| Model | Test Accuracy |
|--------|--------------|
| MLP | 33% |
| CNN (Baseline) | 52% |
| CNN (Tuned) | 56% |
## Experimental Setup

- MLP used as baseline model.
- CNN implemented for spatial feature extraction.
- Comparison performed using train, validation, and test accuracy.
- Hyperparameter tuning conducted for:
  - Learning rate
  - Batch size
  - Dropout (regularization)

