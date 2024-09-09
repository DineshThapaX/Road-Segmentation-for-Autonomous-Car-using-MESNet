# Road-Segmentation-for-Autonomous-Car-using-MESNet

This repository contains the implementation of **MESNet (Multi-Stream Ensemble Segmentation Network)**, a novel deep learning model developed for road segmentation in autonomous driving applications. The model addresses the limitations of existing road segmentation methods by leveraging advanced computer vision techniques to achieve high accuracy and precision in diverse road environments.

## Key Features:
- **Fusion Network Architecture**: MESNet integrates **ResNet-50**, **VGG-16**, and **PSPNet** to enhance both local and global feature extraction, resulting in highly accurate road segmentation.
- **Multi-Scale Feature Extraction**: The model efficiently handles complex road scenes, including urban marked, unmarked, and multiple-lane roads.
- **Real-Time Performance**: Although the model is optimized for accuracy, further work is required to improve real-time processing capabilities. Current speed is **1.78 FPS**.
- **Dataset**: The model is trained and tested on the **KITTI Vision Benchmark Suite**, a popular dataset in autonomous driving research.

## Performance Metrics on KITTI Test Set:
- **Accuracy**: 99.52%
- **Precision**: 0.9805
- **Recall**: 0.9927
- **F1 Score**: 0.9865
- **Intersection over Union (IoU)**: 0.9734
- **Dice Coefficient**: 0.9746

MESNet is a robust model designed to improve the reliability of autonomous vehicle systems in real-world driving conditions, including challenging scenarios like varying weather and lighting.

## For Existing Benchmarks: 
[KITTI Vision Benchmark Suite - Road Segmentation](https://www.cvlibs.net/datasets/kitti/eval_road.php)

