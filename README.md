# CIFAR-10 Image Classification using Deep Learning

## About

This project was designed to gain practical experience with Deep Learning by building and evaluating Convolutional Neural Networks (CNNs) for image classification on the CIFAR-10 dataset.

We first developed a shared baseline model together and then independently experimented with different architectures and techniques to improve performance.

---

## Problem

Develop a CNN capable of accurately classifying images into the 10 CIFAR-10 categories while minimizing overfitting through systematic model experimentation.

**Dataset:** CIFAR-10 (60,000 RGB images, 10 classes)

---

## Project Workflow

- Built a shared baseline CNN.
- Independently developed and tested multiple model variations.
- Compared different architectures, regularization techniques, callbacks, and Transfer Learning (VGG16).
- Selected **Model_cf_9** as the best-performing custom CNN based on validation accuracy and generalization.

### Individual Contributions

After developing the baseline model together, we explored different approaches independently.

- **Casilda** developed and evaluated the models following the naming convention **Model_cf_X** (e.g., `Model_cf_4`).
- **Felipe** developed and evaluated the models following the naming convention **Model_FM_X** (e.g., `Model_FM_5`).

Each contributor experimented with different CNN architectures, regularization techniques, and training strategies before comparing the results. Based on our evaluation, **Model_cf_9** achieved the best overall performance among the custom CNN models.

---

## Best Model (Model_cf_9)

**Architecture**
- 6 Convolutional layers
- Batch Normalization
- Dropout
- Max Pooling
- Dense classifier

**Training techniques**
- EarlyStopping
- ModelCheckpoint
- ReduceLROnPlateau

**Results**
- **Training Accuracy:** 90%
- **Validation Accuracy:** 83%

---

## Results

Include:
- Training & validation curves
- Confusion matrix
- Sample predictions

---

## Installation

```bash
git clone https://github.com/<your-repository>.git
cd <repository>

pip install -r requirements.txt
```

Run the notebook in Jupyter Notebook or Google Colab.

---

## Authors

**Casilda Gil de Santivanes Finat**  
GitHub: https://github.com/Casildagsf/Ironhack-DL-Challenge-Group-8

**Felipe Martignon**  
GitHub: https://github.com/Martigol2/Ironhack-DL-Challenge-Group-8