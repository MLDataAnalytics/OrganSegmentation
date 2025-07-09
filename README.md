# VersatileSegmentation: Versatile Medical Image Segmentation via Model Self-Disambiguation

[![CVPR 2024](https://img.shields.io/badge/CVPR-2024-4CAF50?style=for-the-badge&logo=googlescholar)](https://openaccess.thecvf.com/content/CVPR2024/html/Chen_Versatile_Medical_Image_Segmentation_Learned_from_Multi-Source_Datasets_via_Model_CVPR_2024_paper.html)
[![arXiv](https://img.shields.io/badge/arXiv-2311.10696-B31B1B?style=for-the-badge&logo=arxiv)](https://arxiv.org/abs/2311.10696)

This repository contains the official code for our CVPR 2024 paper: **"Versatile Medical Image Segmentation Learned from Multi-Source Datasets via Model Self-Disambiguation."**

Our work introduces a novel method for **versatile medical image segmentation, specifically focusing on abdominal organs**. This approach effectively addresses challenges posed by training segmentation models on diverse, multi-source datasets, enhancing generalizability and performance.

---

## ✨ Overview

Medical image segmentation is crucial for diagnosis, treatment planning, and research. However, training robust models is often hampered by the variability across different data sources (e.g., scanners, protocols, patient populations). Our method, **Model Self-Disambiguation**, tackles this by enabling a single model to learn comprehensive segmentation capabilities from heterogeneous datasets without explicit domain labels.

The primary application highlighted in our paper is the accurate segmentation of **abdominal organs**.

![Abdominal Organs Segmentation Visualization](https://github.com/MLDataAnalytics/OrganSegmentation/blob/main/Figures/visual_comparision_label.png)
*^ Visual comparison showing examples of abdominal organ segmentation.*

---

## 🚀 Key Contributions & Features

* **Model Self-Disambiguation:** A novel training paradigm that allows a single segmentation model to learn effectively from multiple, diverse medical imaging datasets.
* **Enhanced Generalizability:** Improves the model's ability to perform well on unseen data from different sources.
* **Abdominal Organ Segmentation:** Demonstrates state-of-the-art performance on segmenting key abdominal organs.
* **Robustness:** Designed to handle variations inherent in real-world multi-source medical data.

---

## 🛠️ Setup and Usage

Detailed instructions for setting up the environment, preparing datasets, training the model, and running inference will be provided soon!

* **Installation:** (Coming Soon!)
* **Dataset Preparation:** (Coming Soon!)
* **Training:** (Coming Soon!)
* **Inference:** (Coming Soon!)
* **Pre-trained Models:** (Coming Soon!)

Please check back for updates! We are actively preparing the code and comprehensive documentation to ensure a smooth user experience.

---

## 📝 Citation

If you find our work useful or inspiring for your research, please consider citing our paper:

```bibtex
@InProceedings{Chen_2024_CVPR,
    author    = {Chen, Xiaoyang and Zheng, Hao and Li, Yuemeng and Ma, Yuncong and Ma, Liang and Li, Hongming and Fan, Yong},
    title     = {Versatile Medical Image Segmentation Learned from Multi-Source Datasets via Model Self-Disambiguation},
    booktitle = {Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
    month     = {June},
    year      = {2024},
    pages     = {11747-11756}
}
```

---

## 🙏 Acknowledgment

This project has been generously supported in part by the National Institutes of Health (NIH) through grants **AG066650**, **U24NS130411**, and **R01EB022573**. We are grateful for their support in making this research possible.
