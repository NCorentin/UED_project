# UED_project
Projet de deeplearning sur la prédiction météorologique à court therme en utilisant le benchmark Weatherbench2

**Settings** :
Geography : France
Variable : 2 meter temperature
Datasets :
Training : 2011-2016
Validation : 2018
Test : 2020-2021
Input : 6 timesteps (6h interval)
Output : 2 timesteps
Batch size : 32
Learning rate : ReduceLROnPlateau from 1e-3
Optimizer : Adam
Loss function : MSE
Epochs : 15

**Architectures** :
- Linear combination
- CNN
- CNN + GRU
- ConvLSTM

  **Best** : ConvLSTM

  **Loss function** :
  - MAE
  - MSE
  - Huber
  - SSIM + MSE
 
  **Best** : MAE
