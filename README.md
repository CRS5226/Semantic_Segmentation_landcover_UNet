# Semantic Segmentation for Land Cover Mapping using U-Net with ResNet Backbone

## Overview

This project demonstrates advanced semantic segmentation of satellite imagery for land cover classification using a U-Net architecture with ResNet (50, 101, 152) backbones. The approach is designed to accurately map buildings, roads, water, and woodlands/vegetation from high-resolution aerial images, leveraging state-of-the-art deep learning techniques.

## Key Advantages

- **High Accuracy:** Achieves mean IoU scores above 80% on challenging datasets.
- **Robust Feature Extraction:** Utilizes pretrained ResNet backbones for superior feature representation.
- **Flexible & Scalable:** Easily adapts to new land cover classes and datasets.
- **Comprehensive Augmentation:** Employs extensive data augmentation for improved generalization.
- **Open & Reproducible:** Full code and data links provided for transparency and reproducibility.

## Dataset

- **LandCover.ai:** High-resolution aerial imagery from Poland, annotated for buildings, roads, water, and woodlands.
  - [LandCover.ai Dataset](https://landcover.ai.linuxpolska.com/)

## How to Run

You can run the provided Jupyter Notebook on **Google Colab** or **Kaggle** for free GPU acceleration:

- [Kaggle Notebook (source code)](https://www.kaggle.com/code/chitrakshsingh/unet-landcoverai/notebook)

**Steps:**
1. Open the notebook link above in Kaggle or upload it to Google Colab.
2. Make sure to enable GPU support (in Colab: `Runtime > Change runtime type > GPU`).
3. Download the LandCover.ai dataset and update the data paths if needed.
4. Run all cells to train and evaluate the model.

## Project Structure

```
Semantic_Segmentation_landcover_UNet/
│
├── README.md
├── unet-resnet-landcoverai.ipynb
├── latex/
│   ├── paper_code
│   ├── bib_file
│   └── Towards U-Net based Semantic Segmentation for Satellite images.pdf
├── icons8-google-scholar.svg
└── Towards U-Net based Semantic Segmentation for Satellite images.pdf
```

## Research Paper

This project is based on the following peer-reviewed publication:

- [Towards U-Net based Semantic Segmentation for Satellite images (IEEE Xplore)](https://ieeexplore.ieee.org/document/10896139)

The paper provides detailed methodology, experiments, and results. Please cite it if you use this work in your research.

## Useful Links

- [LandCover.ai Dataset](https://landcover.ai.linuxpolska.com/)
- [Kaggle Notebook (source code)](https://www.kaggle.com/code/chitrakshsingh/unet-landcoverai/notebook)
- [Project Paper (IEEE Xplore)](https://ieeexplore.ieee.org/document/10896139)

---

**For questions or contributions, feel free to open an issue or pull request.**
