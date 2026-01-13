### Neuromorphic Emotion Recognition Using Spiking Neural Networks (SNN)

---

Description

This project implements emotion recognition using neuromorphic computing concepts, specifically Spiking Neural Networks (SNNs). Unlike conventional deep learning models, SNNs process information using discrete spike events, making them biologically inspired and energy efficient.

## The system analyzes emotional patterns and performs classification based on spike-based neural activity, demonstrating the applicability of neuromorphic intelligence in affective computing.

### Problem Statement

--
Traditional emotion recognition systems rely on deep neural networks that are computationally intensive and power-hungry. These limitations restrict their deployment in real-time and edge-based environments.

An efficient, brain-inspired alternative is required to:

Reduce power consumption

Enable event-driven computation

## Support real-time emotion recognition

### Solution Approach

---

The proposed solution follows a neuromorphic workflow:

Emotion-related input data preprocessing

Encoding inputs into spike trains

Training a Spiking Neural Network (SNN)

Emotion classification using spike activity

Performance evaluation using suitable metrics

## This approach leverages temporal dynamics and event-based learning.

### Technologies Used

---

Python

Google Colab / Jupyter Notebook

Spiking Neural Networks (SNN)

NumPy

PyTorch / SNN frameworks

## Matplotlib

### Project Structure

```Project-02-Neuromorphic-Emotion-Recognition/
│── README.md
│── src/
│   └── Neuromorphic_Emotion_Recognization_Using_SNN.ipynb
│── assets/
│   └── output plots / results
│── datasets/
│   └── emotion dataset (if applicable)
```

### How to Run the Project

---

Open the .ipynb file in Google Colab or Jupyter Notebook

Install required dependencies

Upload the dataset (if external)

Execute all cells sequentially

## Analyze spike activity and emotion predictions

### Output

---

Emotion classification results

Spike activity visualizations

## Model evaluation metrics

### Use Cases

---

Affective Computing

Human–Computer Interaction (HCI)

Brain-inspired Artificial Intelligence

## Edge and low-power AI systems

### Future Scope

---

This project can be further enhanced by:

Deploying on neuromorphic hardware (Intel Loihi, SpiNNaker)

Real-time emotion recognition from EEG or video streams

Hybrid CNN–SNN architectures

Optimization for edge AI devices

## Access to neuromorphic processors would significantly improve performance and energy efficiency.

### # Project 02 – Federated Learning for Object Detection using YOLOv8

## Description

This project implements a privacy-preserving object detection system using **Federated Learning** combined with **YOLOv8**. Instead of centralizing data, multiple clients collaboratively train a shared object detection model while keeping their local datasets private.

The approach is particularly suitable for sensitive domains such as healthcare, surveillance, and smart cities where data sharing is restricted.

---

## Problem Statement

Traditional object detection systems require centralized data collection, which raises serious privacy, security, and regulatory concerns. There is a need for a distributed learning framework that enables high-performance object detection without sharing raw data.

---

## Solution Approach

- Implement YOLOv8 as the base object detection model
- Distribute training across multiple simulated clients
- Perform local training at each client
- Aggregate model weights using Federated Averaging (FedAvg)
- Evaluate the global model on validation data

---

## Technologies Used

- Python
- YOLOv8
- Federated Learning (FedAvg)
- PyTorch
- NumPy
- OpenCV

---

## Project Structure

```Project-02-Federated-Learning-YOLOv8/
│── README.md
│── src/
│ ├── federated_training.py
│ └── client_training.py
│── assets/
│ └── output images / metrics
type nul > README.md

```

---

## How to Run the Project

1. Install required dependencies
2. Configure client datasets
3. Run federated training script
4. Evaluate the global YOLOv8 model

---

## Output

- Object detection results using YOLOv8
- Federated training performance metrics
- Improved privacy-preserving model training

---

## Use Cases

- Smart surveillance systems
- Healthcare imaging
- Autonomous vehicles
- Privacy-preserving AI systems

---

## Future Scope

- Support for real-time federated inference
- Secure aggregation techniques
- Deployment on edge devices
- Integration with secure APIs (restricted access)

---

## Author

Subbarayudu Endluri
