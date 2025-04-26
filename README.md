# Skin Cancer Malignant Vs Benign (CVNLP) 🦠

📄 Licensed under CC BY-NC 4.0 — For educational & non-commercial use only.

## Overview ✨

A group project for **Computer Vision** combined with **Natural Language Processing**, focusing on applying **ML** & **AI** to solve a data problem of your choice. It classifies Skin Cancer images as either **Malignant** or **Benign**. It explores practical solutions to real-world challenges in:
- **Image Recognition**.
- **Designs a CNN Architecture**.
- **Selects Relevant Evaluation Metrics**.

## Project Overview 📌

This notebook explores:
- Image Data Preprocessing & Augmentation.
- CNN Model Architecture & Training.
- Model Evaluation Metrics (Accuracy, Confusion Matrix, and ROC Curve).
- Practical considerations for applying AI in Medical Diagnosis.

## Results 📈
- Best Model Accuracy: 79.59% (Good).
- Test Loss: 0.4041
- Confusion Matrix Analysis:

|                      | **Predicted Benign** | **Predicted Malignant** |
|----------------------|----------------------|---------------------|
| **Actual Benign**    | 133 (True Negative)  | 52 (False Positive) |
| **Actual Malignant** | 17 (False Negative)  | 136 (True Positive) |

1. True Positives (136):
Correctly predicted malignant cases.

2. True Negatives (133):
Correctly predicted benign cases.

3. False Positives (52):
Benign cases wrongly classified as malignant.

4. False Negatives (17):
Malignant cases wrongly classified as benign.

- So, based from this analysis, the model shows strong performance in detecting Malignant Skin Cancers, with `True Positive 136 Correct Malignant Predictions` & only `False Positive 17 Incorrect Predictions`.

- While Benign cases were sometimes wrongly classified as Malignant `(False Positive 52)`.

## How to Use 🚀 
- Open the `.ipynb` notebook file in the files or click the link here [Google Colab](https://colab.research.google.com/drive/1LNrY0mR3pStWBkjPMkwKcl5UtXQKFS8U?usp=sharing).

> 📁 **Note**: This is for **educational purposes only** — no real credentials, access, or confidential data are used.

## License 🔒 
This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)**  

🔗 [View Full License Terms](https://creativecommons.org/licenses/by-nc/4.0/)

## Coding Information 🛠
- Python

- TensorFlow/Keras:
  - TensorFlow: Open source library developed by Google. Used for build, train, and deploy Neural Network (CNNs).
  - Keras: Open-source library that provides Python interface for Neural Network.

- Google Colab: Free online platform to write & run a code.

## Big thanks to my teammates: 🙌
1. Jerry Wingsky ([@jrywsky](https://linktr.ee/JerryWingsky))
2. Prohabita Nuzhat
3. Lisa Luximon
