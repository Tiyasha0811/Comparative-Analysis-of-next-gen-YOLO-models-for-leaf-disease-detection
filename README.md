# Comparative-Analysis-of-next-gen-YOLO-models-for-leaf-disease-detection
A comprehensive benchmarking framework evaluating YOLOv8, YOLOv9, and YOLOv11 for ornamental plant leaf disease detection, introducing novel metrics for subtle pattern recognition and environmental robustness using a curated real-world dataset., OrnaFoliage.
# Comparative Performance of Next-Gen YOLO Models for Ornamental Leaf Health Classification 🌿

This repository accompanies our research on **real-time leaf disease detection in ornamental plants** using **next-generation YOLO models (YOLOv8, YOLOv9, YOLOv11)**.  
The study focuses on *Ixora* and *Bougainvillea* leaves and evaluates model performance under **real-world outdoor conditions** such as varying illumination, occlusion, and subtle disease patterns.

---

## 📌 Key Highlights
- Comparative benchmarking of **YOLOv8, YOLOv9, and YOLOv11** for ornamental leaf disease detection  
- Introduction of the **OrnaFoliage dataset**, curated specifically for non-crop plant pathology  
- Evaluation beyond standard metrics, emphasizing **subtle disease localization** and **environmental robustness**  
- Demonstrates **YOLOv11’s superiority** in early-stage disease detection while maintaining real-time performance

---

## 🌱 Dataset: OrnaFoliage
A curated dataset of **Ixora (*Ixora coccinea*)** and **Bougainvillea (*Bougainvillea spectabilis*)** leaf images:

- **2,500 real images**, augmented to **5,000 samples**
- Healthy and diseased leaves (fungal, bacterial, nutrient deficiency, pest damage)
- Collected from **nurseries and greenhouse environments**
- Annotated in **COCO format**
- Train / Validation / Test split: **70% / 15% / 15%**

---

## 🧠 Models Evaluated
- **YOLOv8** – High inference speed, edge-device friendly  
- **YOLOv9** – Balanced accuracy and generalization  
- **YOLOv11** – Best performance for subtle disease patterns and complex backgrounds  

---

## 📊 Evaluation Metrics
In addition to standard object detection metrics:
- **mAP@0.5, Precision, Recall, F1-score**
- **FPS (Inference Speed)**

Novel metrics introduced for ornamental plant pathology:
- **Disease Localization Accuracy (DLA)**
- **Environmental Robustness Score (ERS)**
- **Subtle Pattern Detection Rate (SPDR)**

---

## 🧪 Experimental Setup
- Image size: **640 × 640**
- Optimizer: **AdamW**
- Epochs: **300**
- Batch size: **16**
- Hardware: **NVIDIA RTX 3080 GPU**
- Data augmentation: flip, rotation, brightness, mosaic, mix-up

---

## 🏆 Key Results
| Model   | mAP@0.5 | Precision | Recall | F1-score | FPS |
|--------|---------|-----------|--------|----------|-----|
| YOLOv8 | 87.5%   | 86.8%     | 86.2%  | 86.5%    | **85** |
| YOLOv9 | 89.7%   | 89.0%     | 88.4%  | 88.7%    | 72 |
| YOLOv11| **92.3%** | **91.5%** | **90.8%** | **91.1%** | 68 |

➡ **YOLOv11 achieves the best trade-off between accuracy, robustness, and real-time performance.**

---

## 🚀 Applications
- Automated ornamental plant health monitoring  
- Smart nurseries and landscaping systems  
- Precision horticulture and early disease diagnosis  
- Benchmarking next-generation object detection models  

---

## 📄 Paper
If you use this work, please cite:

> *Comparative Performance of Next-Gen YOLO Models for Leaf Health Classification in Ornamental Species*

---

## 🤝 Contributions & Future Work
- Expand OrnaFoliage with **multispectral imaging**
- Edge-device deployment (Jetson / mobile inference)
- Evaluation of future YOLO versions and hybrid architectures

Contributions and discussions are welcome!
