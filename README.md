# msbd5012_ha5

# Palindrome Recognition RNN

## Objective
This project trains a vanilla RNN to recognize palindrome numbers with up to 5 digits. Three models are trained on datasets of different sizes (200, 2000, and 20000 examples) with 50% palindromic and 50% non-palindromic numbers. My personal test set includes sizes=1000.

## Model Training and Hyperparameters
- Hidden size: 128
- Learning rate: 0.005
- Loss function: Negative Log-Likelihood
- Optimizer: SGD

### Training Results
Include training loss plots and final test accuracy for each model:
- Model trained by 200 examples: **53.3% accuracy**
  Training Loss:
  ![image](https://github.com/user-attachments/assets/dabdd79e-5663-4dcb-9234-4c32ba2365dc)

- Model trained by 2000 examples: **59.4% accuracy**
- Model trained by 20000 examples: **59.4% accuracy**

## Instructions for Testing
1. Run the script to generate data files.
2. Train each model separately on `data_200.txt`, `data_2000.txt`, and `data_20000.txt`.
3. To test on a new dataset, place it in `test.txt` format as follows:
