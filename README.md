# CNN Classifier (AlexNet-inspired)  

This project implements an AlexNet-based convolutional neural network for image classification. The model was trained and evaluated on a dataset split into **80:20 (train:validation)**.  

---

## Model Architecture  

- **Convolutional layers:**  
  - Conv2d (in=1, out=32)  
  - Conv2d (in=32, out=64)  
  - Conv2d (in=64, out=128)  

- **Fully connected layers:**  
  - Linear → Dropout → Linear  

- **Activation function:** ReLU  
- **Loss function:** CrossEntropyLoss  
- **Optimizer:** Adam  

---

## Hyperparameters  

| Parameter       | Value |
|-----------------|-------|
| Learning rate   | 0.005 / 0.001 |
| Epochs          | 20 / 40 |
| Optimizer       | Adam |
| Loss function   | CrossEntropyLoss |

---

## Results  

- **lr = 0.005, epochs = 20**  
  - Accuracy ≈ **86.3%** (Ref: log1.txt)  

- **lr = 0.001, epochs = 20**  
  - Accuracy ≈ **87.44%** (Ref: log2.txt)  

- **lr = 0.001, epochs = 40 (final choice)**  
  - Accuracy ≈ **88.65%**  

---
