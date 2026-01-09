# Project 01 – PAN Card Tampering Detection

## Description

This project focuses on detecting tampering in PAN Card images using image processing techniques. The system compares an original PAN card image with a suspected image to identify structural differences and potential forgery.

The project is implemented using Python in Google Colab and leverages computer vision techniques to highlight altered regions in the PAN card.

---

## Problem Statement

PAN card forgery is a common issue in identity verification processes. Manual verification is time-consuming and prone to human error. There is a need for an automated system that can detect tampered PAN cards efficiently and accurately.

---

## Solution Approach

The solution follows an image comparison-based approach:

- Load original and suspected PAN card images
- Resize images to a standard dimension
- Convert images to grayscale
- Apply **Structural Similarity Index (SSIM)** to compare images
- Identify differences and highlight tampered regions using contour detection

---

## Technologies Used

- Python
- Google Colab
- OpenCV
- scikit-image
- NumPy
- imutils

---

## Project Structure

```
project-01/
│── README.md
│── src/
│ ├── Pan_Card_Tampering_Detection.ipynb
│ └── Pan_Card_Tampering_Detection.py
│── assets/
│ └── sample images / output screenshots

```

## How to Run the Project

1. Open the `.ipynb` file in Google Colab
2. Upload the required PAN card images
3. Run all cells sequentially
4. Observe the similarity score and highlighted tampered regions

---

## Output

- Similarity score indicating the percentage match between images
- Visual comparison of original and tampered PAN cards
- Highlighted tampered regions using bounding boxes

---

## Sample Outputs

### Original vs Tampered vs Difference

![PAN Card Comparison](./image-1.png)

### Highlighted Tampered Regions

![Tampering Detection](./image-2.png)

---

## Reference Video

[![PAN Card Tampering Detection Project](https://img.youtube.com/vi/M6CxhjvL-5A/0.jpg)](https://youtu.be/M6CxhjvL-5A)

---

## Use Cases

- Identity verification systems
- Fraud detection
- Document validation automation

---

## Future Scope

The current implementation is based on image-level comparison using computer vision techniques. In the future, this system can be enhanced by integrating official government or financial APIs for PAN verification.

Such APIs would enable real-time validation of PAN card details against authoritative databases, improving accuracy and reliability. However, these APIs are typically restricted and accessible only to authorized institutions and higher officials, and are not available for student or public use.

With appropriate access, the system could be extended to support:

- Real-time PAN verification
- Automated fraud detection at scale
- Integration with banking and KYC platforms

---

## Author

Subbarayudu Endluri
