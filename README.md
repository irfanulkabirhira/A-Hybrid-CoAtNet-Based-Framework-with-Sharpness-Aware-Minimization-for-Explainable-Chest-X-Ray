# 🧠 A Hybrid CoAtNet-Based Framework with SAM for Explainable Chest X-Ray Classification

This repository presents a hybrid deep learning framework that combines **CoAtNet-0**, **Sharpness-Aware Minimization (SAM)**, and multiple **Explainable AI (XAI)** techniques for accurate and interpretable chest X-ray classification.

---

## 📌 Key Features

- 🔥 Hybrid **CoAtNet-0 architecture** (CNN + Transformer)
- ⚙️ **Sharpness-Aware Minimization (SAM)** for better generalization
- 🧠 Multi-level explainability:
  - Grad-CAM (visual explanation)
  - SHAP (feature importance)
  - LIME (instance-level interpretation)
- 📊 Achieves **93% accuracy** on pneumonia classification

---

## 📂 Dataset
![image alt](https://github.com/irfanulkabirhira/NeuroVision-AI-Brain-Tumor-Classification-using-Deep-Learning/blob/9bee5126befecdc68ecd4e2aedbf3135ba61b4b9/Datasest%20Splition.png)
We use the **Epic Chittagong Chest X-ray Dataset (Bangladesh)**:

📎 DOI: https://doi.org/10.17632/wndbd5r26y.2  
📎 Source: Mendeley Data  

---

## 🏗️ Methodology

1. Data preprocessing and normalization  
2. Model training using CoAtNet-0  
3. Optimization with SAM  
4. Evaluation using accuracy and metrics  
5. Explainability using Grad-CAM, SHAP, and LIME  

---

## 🧪 Results

- Accuracy: **93%**
- Improved generalization with SAM
- Enhanced interpretability using XAI techniques

---
python train.py
python evaluate.py
## 🚀 Installation
```
├── dataset/
├── models/
├── training/
├── evaluation/
├── xai/
├── results/
└── README.md
```
👨‍💻 Authors

Md Irfanul Kabir Hira
Mst Moriom Akter Bithee
Md Tanjum An Tashrif
Anichur Rahman
and others
Contact : 
--------
📩 erfanulkabirhira132@gmail.com

Hira, Md Irfanul Kabir et al. (2025).
A Hybrid CoAtNet-Based Framework with Sharpness-Aware Minimization for Explainable Chest X-Ray Classification.
```bash
```
git clone https://github.com/irfanulkabirhira/A-Hybrid-CoAtNet-Based-Framework-with-Sharpness-Aware-Minimization-for-Explainable-Chest-X-Ray.git
cd A-Hybrid-CoAtNet-Based-Framework-with-Sharpness-Aware-Minimization-for-Explainable-Chest-X-Ray
pip install -r requirements.txt
```


