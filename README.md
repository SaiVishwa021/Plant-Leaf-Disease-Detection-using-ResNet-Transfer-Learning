# 🌿 Plant-Leaf-Disease-Detection-using-ResNet-Transfer-Learning

This is a Deep Learning-based project that detects and classifies **plant leaf diseases** using **Transfer Learning** with pretrained CNN architectures in **PyTorch**. The model is trained using the **One Cycle Learning Rate Policy (OneCycleLR)** to achieve faster convergence and better generalization.

---

## 📌 Project Overview

Plant diseases reduce agricultural productivity and cause major economic losses. This project aims to build an automated system that can classify plant leaf images into different disease categories using a robust deep learning pipeline.

This repository contains:
- End-to-end training pipeline
- Validation & evaluation
- Test prediction visualization
- Model inference on single images

---

## ⚙️ Tech Stack Used

- **Python 3**
- **PyTorch**
- **Torchvision**
- **Transfer Learning (ImageNet pretrained weights)**
- **OneCycleLR Scheduler**
- **Adam Optimizer**
- **Matplotlib**
- **NumPy**
- **Google Colab / Jupyter Notebook**

---

## 💻 Hardware Support

This project supports:
	•	GPU (CUDA) for NVIDIA
	•	MPS for Apple Silicon Macs
	•	CPU fallback if no GPU is available

Device selection is handled automatically.


## 🧠 Model Architecture

This project uses a **Transfer Learning approach** by fine-tuning a pretrained CNN model (e.g., ResNet / EfficientNet depending on your implementation).

Key techniques:
- ImageNet normalization (`IMAGENET_MEAN`, `IMAGENET_STD`)
- Data augmentation for training robustness
- GPU acceleration (CUDA / MPS)
- OneCycleLR for stable training

---

## 📊 Dataset

The dataset is organized into 3 folders:

- `train/` → Training images
- `valid/` → Validation images
- `test/` → Testing images

Each folder contains subfolders representing disease classes.

Example:
```
train/
├── Apple___Black_rot/
├── Tomato___Leaf_Mold/
├── Potato___Early_blight/
└── …
```

## 🚀 Training Pipeline

Training is performed using:
- **Cross Entropy Loss**
- **Adam Optimizer**
- **OneCycleLR scheduler**
- **Gradient Clipping**
- **Weight Decay Regularization**

## 📈 Results & Evaluation

The model performance is evaluated using:
	•	Training loss
	•	Validation loss
	•	Validation accuracy

<img width="2085" height="735" alt="image" src="https://github.com/user-attachments/assets/918b2607-e18e-47c8-9570-a602139b3fab" />

