

## Author: Damodar Goud Ediga  
**ID:** 700755572

This repository contains implementations of various deep learning concepts including convolution operations, edge detection, pooling, and neural network architectures like AlexNet and ResNet.

## Table of Contents
1. [Convolution Operations](#convolution-operations)
2. [Edge Detection and Pooling](#edge-detection-and-pooling)
3. [Neural Network Architectures](#neural-network-architectures)
4. [Requirements](#requirements)
5. [Usage](#usage)
6. [Results](#results)

---

## Convolution Operations
This script demonstrates how to perform 2D convolution using TensorFlow. It applies a **3x3 kernel** on a **5x5 input matrix** with different strides and padding options.

### Features:
- Uses TensorFlow's `Conv2D` layer to apply the kernel.
- Supports different stride values (`stride=1`, `stride=2`).
- Supports different padding methods (`VALID`, `SAME`).

### Usage:
```python
python convolution_operations.py
```

---

## Edge Detection and Pooling
This script performs:
1. **Edge detection** using the Sobel filter.
2. **Max pooling and average pooling** on a randomly generated 4x4 matrix.

### Features:
- Reads an image and applies Sobel-X and Sobel-Y filters for edge detection.
- Demonstrates the effect of **max pooling** and **average pooling** using TensorFlow.

### Usage:
```python
python edge_detection_pooling.py
```
Ensure you provide a valid image path for edge detection.

---

## Neural Network Architectures
This script implements two deep learning architectures:
1. **AlexNet**: A deep convolutional neural network known for its success in image classification.
2. **ResNet-like Model**: A simplified version of ResNet using residual connections.

### Features:
- Implements **AlexNet** using `Sequential` API in TensorFlow.
- Implements a **ResNet-like architecture** using functional API with residual blocks.
- Includes dropout layers to prevent overfitting.

### Usage:
```python
python neural_networks.py
```

---

## Requirements
Ensure you have the following dependencies installed:
```bash
pip install tensorflow numpy matplotlib opencv-python
```

---

## Results
- The convolution script prints the output matrices for different stride and padding configurations.
- The edge detection script displays original and filtered images using Matplotlib.
- The AlexNet and ResNet-like models print their architecture summaries.

---
Video Link 
https://drive.google.com/file/d/1x5V0Lv9gVB5cfXf3DK7g_LpumPxG8zJM/view?usp=sharing
---


