# 🌫️ ELKAformer: Transformer-Based Image Dehazing

This repository contains an optimized implementation of **ELKAformer** for single image dehazing.  
Developed using **PyTorch** and **Google Colab**, this project enhances image clarity and removes haze using transformer-based learning.

---

## 🚀 Features
- Transformer-based encoder-decoder (ELKAformer)
- High-quality image restoration with improved PSNR and SSIM
- Supports paired training on custom haze datasets
- Custom Charbonnier + Perceptual loss for smoother restoration
- Visualization and evaluation integrated in Colab
- Trained using Google Colab GPU

---

## 🧠 Model
- **Architecture:** ELKAformer (Transformer backbone)
- **Framework:** PyTorch
- **Weights:** [`best_model.pth`](best_model.pth)
- **Visualization:**  
  ![Dehazed Output](comparison.png)

---

## 📂 Dataset Structure
