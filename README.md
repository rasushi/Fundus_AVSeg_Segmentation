# Fundus AVSeg Segmentation

## 📌 Project Overview
This project focuses on **artery–vein segmentation** in retinal fundus images using the **Fundus-AVSeg** and **DRIAVE** dataset.  
Our aim is to **improve accuracy, sensitivity, and interpretability** of vessel segmentation by leveraging deep learning architectures (e.g., Attention U-Net, transformer-based U-Net) along with advanced loss functions and explainable AI techniques.

Artery–vein segmentation plays a critical role in **ophthalmology** for diagnosing and monitoring diseases such as:
- Diabetic Retinopathy (DR)
- Retinal Vein Occlusion (RVO)
- Hypertensive Retinopathy
- Other vascular and systemic conditions

By providing accurate and interpretable segmentation maps, this project can assist clinicians in **early detection and treatment planning**.

---

## 📂 Dataset: Fundus-AVSeg
**Fundus-AVSeg**  and **DRIAVE** are public datasets containing high-resolution color fundus images with **manual annotations** for arteries and veins.  
It includes:
- Retinal fundus images in standard RGB format
- Pixel-wise ground truth masks for artery, vein, and background
- Predefined training, validation, and testing splits

**Key features of the datasets:**
- Images captured using high-quality fundus cameras
- Clear labeling of vessel structures for artery–vein differentiation
- Designed for benchmarking AV segmentation models

---

## 🎯 Project Goals
1. **Improve Accuracy** – Use advanced architectures (e.g., Attention U-Net, transformer-based variants) and fine-tuned hyperparameters.
2. **Boost Sensitivity** – Focus on small and thin vessel detection using hybrid loss functions like **Dice Loss + Focal Tversky Loss**.


---



