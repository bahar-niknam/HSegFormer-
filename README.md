HSegFormer+
Hybrid CNN–Transformer with Stage-wise Attention for Brain Tumor MRI Segmentation

This repository contains the implementation of HSegFormer+, a hybrid CNN–Transformer framework for automatic brain tumor segmentation in contrast-enhanced T1-weighted MRI.

The associated manuscript is currently under blind review. Detailed architectural descriptions, ablation studies, and trained models will be released upon publication.

Overview

Brain tumor segmentation is essential for diagnosis, treatment planning, and longitudinal monitoring, yet remains challenging due to heterogeneous tumor appearance, low-contrast boundaries, class imbalance, and cross-center variability.

HSegFormer+ addresses these challenges through a hybrid encoder–decoder architecture that combines convolutional feature extraction with transformer-based global context modeling. By integrating local spatial detail with long-range semantic dependencies, the model improves boundary delineation and coverage of small or irregular tumor regions while maintaining practical inference efficiency.

Architecture Overview
<p align="center"> <img src="Hseg.jpg" width="95%"> </p>

HSegFormer+ employs a dual-path hybrid encoder that fuses convolutional and transformer representations at multiple semantic stages, followed by an attention-guided decoder with multi-scale feature integration and deep supervision. This design enables precise tumor localization and robust segmentation across varying tumor sizes and contrast conditions.

Architectural and training details are omitted to preserve submission anonymity and will be made available after publication.

Citation

Citation details will be provided upon publication.
