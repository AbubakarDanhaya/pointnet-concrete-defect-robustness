# PointNet-Based Robust Semantic Segmentation of Concrete Defects

## Proposed Research Title
**_Robustness Evaluation and Improvement of PointNet for Semantic Segmentation of Concrete Surface Defects Using 3D Point Clouds_**.

## Problem Statement
Deep learning-based segmentation of concrete defects using 3D point clouds may be sensitive to measurement noise, missing points, occlusion and variations in point density. These challenges can reduce the reliability of automated crack and spalling identification, particularly when models are applied to previously unseen bridges.

## Research Aim
To evaluate and improve the robustness and cross-bridge generalisation of PointNet for semantic segmentation of concrete surface defects using 3D point clouds.

## Proposed Novelty
- Systematic evaluation of PointNet under controlled point-cloud degradation.
- Corruption-aware data augmentation to improve segmentation robustness.
- Cross-bridge evaluation to investigate generalisation to unseen concrete structures.

## Dataset
An existing annotated 3D concrete bridge point-cloud dataset containing three semantic classes:
- Sound concrete
- Cracks
- Spalling

Dataset source: [SNEPointNet2](https://github.com/neshatbln/SNEPointNet2).

## Deep Learning Architecture
**PointNet** will serve as the primary semantic segmentation architecture, implemented using PyTorch. Standard PointNet will be compared with a corruption-aware training strategy.

## Evaluation
Performance will be assessed using:
- Overall Accuracy
- Class-wise Precision, Recall and F1-score
- Intersection over Union (IoU) and mean IoU (mIoU)
- Robustness under different corruption levels
- Cross-bridge generalisation

## Expected Contribution
An experimental framework for assessing and improving the reliability of PointNet-based concrete defect segmentation under degraded point-cloud conditions.

*Research in progress.*
