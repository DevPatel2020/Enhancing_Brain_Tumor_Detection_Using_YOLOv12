# 🧠 Enhancing Brain Tumor Detection Using YOLOv12

> **IEEE-Approved Research Paper**  
> Proceedings of the 3rd International Conference on Inventive Computing and Informatics (ICICI-2025)  
> CHARUSAT University · Devang Patel Institute of Advanced Technology & Research

---

## 📌 Overview

This repository presents our research on **automated brain tumor detection using YOLOv12**, a cutting-edge object detection model. The project explores how YOLOv12 outperforms previous models like YOLOv8, YOLOv9, and CNN-based methods in detecting tumors from MRI scans — achieving **mAP@0.5 of 91.3%**.

---

## 🧾 Paper Details

- **📄 Title:** Enhancing Brain Tumor Detection Using YOLOv12  
- **📚 Conference:** IEEE ICICI-2025  
- **🏛️ University:** CHARUSAT (Devang Patel Institute of Advanced Technology & Research)  
- **🧑‍🤝‍🧑 Authors:** Hari S Patel, Meet K Patel, Dhairya K Patel, Dev K Patel  
- **👩‍🏫 Mentor:** Ms. Mohini Darji  
- **📎 Download Paper:** [paper/Enhancing_Brain_Tumor_Detection_Using_YOLOv12.pdf](paper/Enhancing_Brain_Tumor_Detection_Using_YOLOv12.pdf)

---

## 🧠 Problem Statement

Early detection of brain tumors is critical but traditionally time-consuming and error-prone. Conventional methods struggle with generalization and accuracy. This research proposes an advanced, real-time, and resource-efficient solution using **YOLOv12** to detect tumors in MRI scans with high precision.

---

## ⚙️ Model Details

| Metric        | YOLOv8 | YOLOv9 | Faster R-CNN | ResNet18 | **YOLOv12** |
|---------------|--------|--------|--------------|----------|-------------|
| mAP@0.5       | 0.685  | 0.826  | 0.472        | 0.453    | **0.913**   |
| F1-Score      | 0.697  | 0.718  | 0.380        | 0.453    | **0.884**   |
| Precision     | –      | –      | –            | –        | **0.907**   |
| Recall        | –      | –      | –            | –        | **0.860**   |

> **Highlights:**
> - Real-time detection suitable for low-resource clinical setups  
> - High generalization across diverse MRI datasets  
> - Efficient training using Mosaic, MixUp, HSV augmentations

---

## 📊 Code Notebook

The YOLOv12 training and evaluation pipeline is implemented in:
- [`code/brain-tumor-detection-with-yolov12.ipynb`](code/brain-tumor-detection-with-yolov12.ipynb)

Features:
- Dataset preprocessing and class balancing  
- Advanced data augmentation  
- YOLOv12 large variant with transfer learning  
- Precision-recall analysis and visual detection outputs

---

## 📁 Dataset

- 📌 **Dataset:** Brain MRI Tumor Detection (from Kaggle)  
- 🗃️ **Annotations:** Bounding box format, class labels for tumor types  
- 📥 **Coming Soon:** Dataset will be uploaded under `dataset/` by a collaborator

---

## 🔬 Key Contributions

✅ Performance benchmarking of YOLOv12 vs older models  
✅ Medical imaging optimization for deep learning  
✅ Real-time deployment suitability in healthcare AI  

---

## 📜 Citation

```bibtex
@inproceedings{patel2025yolov12,
  title={Enhancing Brain Tumor Detection Using YOLOv12},
  author={Patel Dev K,Patel Hari S ,Patel Meet K ,Patel Dhairya K and Darji Mohini},
  booktitle={Proceedings of the 3rd International Conference on Inventive Computing and Informatics (ICICI)},
  year={2025},
  organization={IEEE}
}
