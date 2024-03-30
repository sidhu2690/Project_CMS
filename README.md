# Common Task 1: Electron/Photon Classification

### Problem Description
Binary classification problem for 2-channel images of Electrons and Photons.

## Useful Links

- **Project Folder:** [Click here](https://github.com/sidhu2690/Project_CMS/tree/main/Task1)
- **Ipynb Notebook:** [Click here](https://github.com/sidhu2690/Project_CMS/blob/main/Task1/electron-photon.ipynb)
- **Model Weights:** [Click here](https://github.com/sidhu2690/Project_CMS/blob/main/Task1/model_weights.weights.h5)

## Model Overview

### Optimizer
- **Optimizer:** ADAM with LR on plateau
- **Training Epochs:** 20 epochs


### Results
| Metric            | Value  |
|-------------------|--------|
| Validation Accuracy | 0.7366 |
| Validation AUC      | 0.8058 |

### Training curves
| Accuracy Curve | Loss Curve |
|:--------------:|:----------:|
| ![Accuracy Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/aa798227-1a3e-4931-8fb0-1c0338bbf54f) | ![Loss Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/83c93933-7a75-4c8e-b355-141e8e5aafd8) |



# Common Task 2: Quark-Gluon Classification

### Problem Description
Binary classification problem for Quark and Gluons.

## Useful Links

- **Project Folder:** [Click here](https://github.com/sidhu2690/Project_CMS/tree/main/task2)
- **Datagen :** [Click here](https://github.com/sidhu2690/Project_CMS/blob/main/task2/datagenerator-task2.ipynb)

## Models

### Optimizer
- **Optimizer:** ADAM with LR on plateau
- **Training Epochs:** 20 epochs

### VGG-12

### Training curves
| Accuracy Curve | Loss Curve |
|:--------------:|:----------:|
| ![Accuracy Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/0245023f-4c9a-4f58-a25b-ee814cb4730a) | ![Loss Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/638f80e5-1299-41a4-b6d7-4bca829b3dc7) |

### Results
| Metric            | Value  |
|-------------------|--------|
| Validation Accuracy | 0.7282 |
| Validation AUC      | 0.7929 |


### LeNet

### Training curves
| Accuracy Curve | Loss Curve |
|:--------------:|:----------:|
| ![Accuracy Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/13fff2f2-b1c1-4776-b153-5f15ab2f418d) | ![Loss Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/19e1a606-bc9c-41c0-a37a-3042bd24b1dc) |

### Results
| Metric            | Value  |
|-------------------|--------|
| Validation Accuracy | 0.7229 |
| Validation AUC      | 0.7871 |


# Task 3A: Mass regression

### Problem Description
Predict the mass particle based on image [X_jet (Track pT, DZ and D0, ECAL)] and array features [ieta, iphi and pt]
## Useful Links

- **Project Folder:** [Click here](https://github.com/sidhu2690/Project_CMS/tree/main/Task-3A)
- **Ipynb Notebook:** [Click here](https://github.com/sidhu2690/Project_CMS/blob/main/Task-3A/task-3a.ipynb)
- 
## Model Overview

### Results

| Metric               | Value                |
|----------------------|----------------------|
| Train Loss           | 687.8632             |
| Validation Loss      | 1597.4897            |
| Average Loss         | 649.5648193359375   |
| MSE on Test Dataset  | 1626.389115844128   |
| MAE on Test Dataset  | 32.22285861178238   |


### Training curves
![Loss Curve](https://github.com/sidhu2690/Project_CMS/assets/136654152/7749e1b0-cafd-47b2-b106-5c785a99fb4d)

![Combined Model](https://github.com/sidhu2690/Project_CMS/raw/main/Task-3A/combined_model.png)






