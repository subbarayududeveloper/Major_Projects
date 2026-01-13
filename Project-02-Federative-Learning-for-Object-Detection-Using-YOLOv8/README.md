# Project 02 – Federated Learning for Object Detection using YOLOv8

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
