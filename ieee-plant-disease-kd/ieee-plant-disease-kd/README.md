# Mobile-Friendly Plant Disease Detection and Classification using Metadata and Asymmetric Knowledge Distillation

This repository documents my research contribution to an IEEE-published study focused on **efficient plant disease detection for mobile and resource-constrained environments** using **asymmetric knowledge distillation** and **metadata-aware learning**.

The work emphasizes accuracy–efficiency trade-offs and practical deployment considerations for real-world agricultural applications.

---

## 📌 Research Overview

Plant disease detection models often suffer from high computational cost, making them unsuitable for mobile or low-power devices.  
This research proposes a **teacher–student framework** where:

- A high-capacity **teacher model** learns rich visual and metadata representations
- A lightweight **student model** is trained using **asymmetric knowledge distillation**
- Additional **metadata features** improve classification performance without increasing inference cost

The goal is to maintain strong predictive performance while significantly reducing model size and latency.

---

## 🧠 Methodology

The proposed system includes:

1. **Teacher–Student Knowledge Distillation**
   - High-capacity teacher guides a compact student network
2. **Asymmetric Distillation Strategy**
   - Teacher and student architectures are intentionally different
3. **Metadata Integration**
   - Contextual features (e.g., crop type, environmental data) augment visual signals
4. **Mobile-Friendly Optimization**
   - Focus on inference speed, memory footprint, and deployability

---

## 🛠️ Tech Stack

- **Programming Language:** Python  
- **Frameworks:** PyTorch, TensorFlow  
- **Libraries:** NumPy, Pandas, Scikit-Learn  
- **Techniques:**  
  - Knowledge Distillation  
  - Convolutional Neural Networks  
  - Metadata-aware Learning  
- **Domain:** Computer Vision, Applied Machine Learning

---

## 📄 Publication

**Platform:** IEEE Xplore  
**Paper Title:**  
*Mobile-Friendly Plant Disease Detection and Classification using Metadata and Asymmetric Knowledge Distillation*

🔗 **IEEE Xplore Link:**  
https://ieeexplore.ieee.org/document/10912090

> This repository highlights my individual research contribution.  
> For complete author details and citation information, please refer to the official IEEE publication.

---

## 🔬 Code Availability

The original experiments were conducted as part of academic research.  
A clean, modular re-implementation suitable for public release is **in progress** and will be added to this repository.

Planned additions:
- Training pipeline for teacher and student models  
- Distillation loss implementation  
- Evaluation scripts and benchmarks  

---

## 👤 Author

**Sai Vishaal Saibaskar**  
MS in Data Science (AI & ML)  
Research-focused ML practitioner with experience in efficient ML systems and model optimization.

🔗 **LinkedIn:** https://www.linkedin.com/in/sai-vishaal-saibaskar/

---

## 📌 License

This repository is intended for research and portfolio purposes.  
If you use ideas or methodology from this work, please cite the IEEE publication.

