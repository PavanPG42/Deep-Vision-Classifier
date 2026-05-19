# 🧠 Deep Vision Classifier (CNN Project)

## 📌 Overview

This project builds a **Convolutional Neural Network (CNN)** using PyTorch to classify images from the **CIFAR-10 dataset** into 10 categories.

---

## 🚀 Highlights

* Built with **PyTorch**
* Custom CNN architecture
* Uses **CIFAR-10 dataset**
* Data normalization applied
* Optimizer: **Adam**
* ✅ Test Accuracy: **74.43%**

---

## 📂 Project Structure

```bash
Deep-Vision-Classifier-CNN-Project/
│
├── DeepVision Classifier.ipynb
├── README.md
```

---

## 📊 Dataset

* 60,000 images (32×32 RGB)
* 10 classes: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck

---

## ⚙️ Preprocessing

```python
transform = transforms.Compose([
    transforms.ToTensor(),
    transforms.Normalize((0.5,0.5,0.5),(0.5,0.5,0.5))
])
```

---

## 🏗️ Model Architecture

```text
Input: 3×32×32
↓
Conv → ReLU → Pool
↓
Conv → ReLU → Pool
↓
Conv → ReLU → Pool
↓
Flatten → FC → Output (10 classes)
```

---

## 🏋️ Training Setup

* Loss: CrossEntropyLoss
* Optimizer: Adam
* LR: 0.001
* Batch Size: 64
* Epochs: 10

---

## 📈 Result

**Test Accuracy: 74.43%**

---

## 🔧 Improvements

* Batch Normalization
* Dropout
* Data Augmentation
* More epochs / GPU

---

## 🛠️ Installation

```bash
pip install torch torchvision
```

---



## 👨‍💻 Author

**Pavan PG**
