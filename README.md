



# 🧠 Pre-trained ResNet18 and ResNet50 on Image Classification Tasks

This repository contains two Google Colab notebooks that demonstrate how to use **pre-trained ResNet18 and ResNet50** models for image classification tasks using PyTorch and Keras.

---

## 📘 Overview

### 🔹 `PreTrained_ResNet18_on_CIFAR10.ipynb`
- Loads and evaluates a **pre-trained ResNet18** on the **CIFAR-10** dataset.
- Includes preprocessing, prediction, and accuracy evaluation.
- Demonstrates transfer learning and testing on a small-scale dataset.

### 🔹 `pretrained_ResNet50.ipynb`
- Loads a **pre-trained ResNet50** from `torchvision.models`.
- Tests it on a custom image (loaded manually or via URL).
- Applies the required preprocessing: resizing, normalization, and tensor conversion.
- Uses the model to predict the top-5 ImageNet class labels for the image.

---

## 📦 Requirements
These notebooks are designed to run in Google Colab with the following packages:
- `torch`
- `torchvision`
- `PIL`
- `matplotlib`
- `numpy`
- `requests` (for downloading test images from URLs)

---

## 📚 Concepts Demonstrated

### ✅ Transfer Learning
Using pre-trained models allows faster convergence and improved accuracy, especially when training data is limited.

### ✅ Model Evaluation
- CIFAR-10 test set classification using ResNet18
- Single image inference with ResNet50 using softmax probabilities and top-k predictions

### ✅ Image Preprocessing
Standard ImageNet normalization:
```python
mean = [0.485, 0.456, 0.406]
std = [0.229, 0.224, 0.225]
````

---

## 🖼️ Output Examples

* ✅ ResNet18 on CIFAR-10: Classification accuracy over test samples
* ✅ ResNet50: Top-5 predicted classes with probability scores on an external image

---

## 📁 Repository Structure

```
├── PreTrained_ResNet18_on_CIFAR10.ipynb     # CIFAR-10 classification using ResNet18
├── pretrained_ResNet50.ipynb                # ImageNet inference using ResNet50
```

---

## 🔧 How to Use

1. Open any notebook in Google Colab
2. Run all cells in sequence
3. Modify paths or image URLs to test your own inputs
4. Analyze predictions and visualize model outputs

---

## ✍️ Author

**Haseeb Ul Hassan**
[GitHub Profile](https://github.com/HaseebUlHassan437)

---


