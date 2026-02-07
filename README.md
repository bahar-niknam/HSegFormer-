# HSegFormer+
## Hybrid CNN–Transformer with Stage Attention for Brain Tumor MRI Segmentation

This repository provides the implementation of **HSegFormer+**, a hybrid deep learning framework designed for automatic brain tumor segmentation in contrast-enhanced T1-weighted MRI.

The associated manuscript is currently under submission. Detailed architectural specifications and experimental analyses will be made publicly available after publication.

---

## Overview

Accurate brain tumor segmentation from MRI is critical for diagnosis, treatment planning, and disease monitoring. However, reliable tumor delineation remains challenging due to:

- heterogeneous tumor appearance,
- low-contrast and ambiguous boundaries,
- variations in acquisition protocols,
- large inter-patient variability.

**HSegFormer+** addresses these challenges through a hybrid encoder–decoder segmentation framework that combines convolutional feature extraction with transformer-based contextual modeling. The model aims to capture both fine local details and long-range contextual dependencies while maintaining practical inference efficiency.

---

## Architecture Overview

<p align="center">
  <img src="figures/Hseg.jpg" width="95%">
</p>

The overall framework integrates convolutional and transformer representations followed by multi-stage decoding to generate accurate tumor segmentation masks. The architecture is designed to leverage complementary feature representations across multiple semantic levels.

Detailed architectural components are omitted here to preserve submission anonymity and will be released after publication.

---

## Repository Structure
HSegFormer/
│
├── models/ # Network architecture implementation
│ ├── encoder/ # Feature extraction modules
│ ├── decoder/ # Segmentation decoding modules
│ └── hsegformer.py # Main model definition
│
├── datasets/ # Dataset loaders and preprocessing
│
├── losses/ # Training loss functions
│
├── train.py # Model training pipeline
├── evaluate.py # Validation & testing scripts
├── inference.py # Inference on unseen MRI scans
│
├── figures/
│ └── Hseg.jpg # Architecture diagram
│
└── README.md


---

## Citation

Citation details will be provided upon publication.

