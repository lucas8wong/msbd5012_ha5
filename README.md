# msbd5012_ha5

# Palindrome Recognition RNN

## Objective
This project trains a vanilla RNN to recognize palindrome numbers with up to 5 digits. Three models are trained on datasets of different sizes (200, 2000, and 20000 examples) with 50% palindromic and 50% non-palindromic numbers. My test set includes sizes=1000.

## Model Training and Hyperparameters
- Hidden size: 128
- Learning rate: 0.005
- Loss function: Negative Log-Likelihood
- Optimizer: SGD

### Training Results (with my test set includes sizes=1000)
Include training loss plots and final test accuracy for each model:
- Model trained by 200 examples: **53.3% accuracy**
  
  Training Loss:
  ![image](https://github.com/user-attachments/assets/dabdd79e-5663-4dcb-9234-4c32ba2365dc)

- Model trained by 2000 examples: **59.4% accuracy**

  Training Loss:
  ![image](https://github.com/user-attachments/assets/346acfdb-e0ef-4d3b-8658-dcbc9488854c)

- Model trained by 20000 examples: **59.4% accuracy**

  Training Loss:
  ![image](https://github.com/user-attachments/assets/419ac961-d998-4493-9628-73d205838019)

## Instructions for Testing
1. Run all cells in **2. Model Definition (Vanilla RNN)**, **3. Training Setup**, **4. Evaluation and Testing**
2. In **6. My Test**, change the test_file_name to the name if your test file
3. Run the cell in **6. My Test**, see the test result in the output window
