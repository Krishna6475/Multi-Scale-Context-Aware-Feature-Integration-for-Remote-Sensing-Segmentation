# Context-Aware Multi-Scale Feature Integration for Segmentation in Remote Sensing

## Overview
This project focuses on **context-aware multi-scale feature integration** for **instance segmentation in remote sensing images**. The goal is to enhance segmentation accuracy by leveraging **multi-scale context aggregation**. The proposed model is compared against **CATNet**, **DeepLabV3**, and **HRNet** on multiple remote sensing datasets.

## Models Used
- **CATNet**: The baseline model for instance segmentation.
- **Proposed Model**: A novel approach based on **DeepLabV3** with enhanced multi-scale feature integration.
- **HRNet**: Used as a comparison model to evaluate performance.

## Datasets
The segmentation models are trained and evaluated on the following remote sensing datasets:
- **iSAID** (Instance Segmentation in Aerial Images Dataset)
- **NWPU VHR-10** (Very High-Resolution Remote Sensing Dataset)
- **DIOR** (Dataset for Object Detection in Optical Remote Sensing Images)
- **HRSID** (High-Resolution Ship Detection Dataset)

## Methodology
1. **Preprocessing**: Image normalization and annotation conversion.
2. **Feature Extraction**: Multi-scale context-aware feature aggregation.
3. **Segmentation**:
   - **Baseline**: CATNet
   - **Proposed Model**: DeepLabV3 with enhanced multi-scale fusion
   - **Comparison**: HRNet for performance benchmarking.
4. **Evaluation Metrics**:
   - **IoU (Intersection over Union)**
   - **mAP (Mean Average Precision)**
   - **Dice Coefficient**

## Results & Comparisons
The proposed model demonstrates **improved segmentation accuracy** over CATNet and HRNet across different datasets, highlighting the effectiveness of **multi-scale feature integration**.

## Conclusion
This project presents an optimized segmentation approach using **DeepLabV3-based context-aware feature aggregation**. The experimental results confirm superior segmentation performance compared to existing models in remote sensing applications.

## Technologies Used
- **Python** (TensorFlow, PyTorch, OpenCV)
- **Deep Learning** (CNN-based segmentation models)
- **Remote Sensing Datasets** (iSAID, NWPU, DIOR, HRSID)
- **Evaluation Metrics** (Accuracy, Precision, Recall, Dice Coefficient)


