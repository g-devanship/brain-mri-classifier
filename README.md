# brain-mri-classifier



# 🧠 Brain tumor detection and segmentation

This project detects brain tumors from MRI images using the ResUNet architecture, which combines Residual Networks (ResNet) and U-Net for accurate pixel-wise image segmentation.

---

## 📌 Key Concepts

* CNN (Convolutional Neural Networks): Extract hierarchical features from images
* ResNet: Solves vanishing gradient problem using skip connections
* Transfer Learning: Uses pre-trained networks (like ResNet) to save time and improve performance
* Image Segmentation: Identifies each pixel's class to create a tumor mask
* ResUNet: Combines U-Net structure with ResNet-style residual blocks for better segmentation performance

---

## 🧠 Architecture: ResUNet

* Encoder: Extracts features (downsampling)
* Bottleneck: Densest layer capturing abstract features
* Decoder: Upsamples and refines segmentation map using skip connections

---

## ⚙️ Requirements

* Python ≥ 3.7
* TensorFlow or PyTorch
* NumPy
* OpenCV
* Matplotlib

Install using:

```bash pip install -r requirements.txt```

---

## 📈 Output

The model outputs a segmentation mask that highlights tumor regions on MRI scans.

---


