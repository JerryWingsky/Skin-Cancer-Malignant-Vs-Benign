# Skin Cancer Malignant Vs Benign (CVNLP) 🦠

📄 Licensed under CC BY-NC 4.0 — For Educational & Non-Commercial Use Only.

🔗 [View Full License Terms](https://creativecommons.org/licenses/by-nc/4.0/)

## Overview ✨

A **Group Project** for **Computer Vision** combined with **Natural Language Processing**, focusing on applying **ML** & **AI** to solve a **Data Problem** of your choice. It classifies **Skin Cancer Images** as either **Malignant** or **Benign**. It explores practical solutions to **Real-World Challenges** in:
- **Image Recognition**.
- **Designs CNN Architecture**.
- **Selects Relevant Evaluation Metrics**.

## Project Overview 📌

- Image Data Preprocessing & Augmentation.
- CNN Model Architecture & Training.
- Model Evaluation Metrics (`Accuracy`, `Precision`, `Recall`, `F1-Score`, `Confusion Matrix`, and `ROC Curve`).
- Practical Considerations -> Applying AI in Medical Diagnosis.

## Results 📈
- Best Model Accuracy: 79.59% (Good).
- Test Loss: 0.4041
- Accuracy, Precision, Recall, and F1-Score:

<p align="center">
<img src="https://github.com/user-attachments/assets/2755f03c-7991-4a22-bcd0-1b4b2c812134" alt="Image" width="500"/>
<br/>
<strong><em>Figure 1: Accuracy, Precision, Recall, and F1-Score Results</em></strong>
</p>

- Confusion Matrix Analysis:

|                      | **Predicted Benign** | **Predicted Malignant** |
|----------------------|----------------------|---------------------|
| **Actual Benign**    | 133 (True Negative)  | 52 (False Positive) |
| **Actual Malignant** | 17 (False Negative)  | 136 (True Positive) |

1. True Positives (136):
Correctly Predicted **Malignant** Cases.

2. True Negatives (133):
Correctly Predicted **Benign** Cases.

3. False Positives (52):
**Benign** Cases Wrongly Classified As **Malignant**.

4. False Negatives (17):
**Malignant** Cases Wrongly Classified As **Benign**.

## Results 🤔
- So, based on this **Analysis**, the **Model** shows **Strong Performance** in detecting **Malignant Skin Cancers**, with `True Positive 136 Correct Malignant Predictions` & **ONLY** `False Positive 17 Incorrect Malignant Predictions`.

- While **Benign Cases** were sometimes **Wrongly Classified** as **Malignant** with `False Positive 52`.

## How to Use 🚀 
- Open the `.ipynb` **Notebook File** in the **Files**.

> 📁 **Note**: This is for **Educational Purposes Only** — no **Real Credentials**, **Access**, or **Confidential Data Are Used**.

## Coding Information 🛠
Fronte-End:
- Jupyter Notebook.
- Matplotlib & Seaborn Visualizations.
- Image Display.

Back-End:
- Python (`If-Else`, `fFunctions`, `Loops`, etc).
- Data Handling & Preprocessing (`ImageDataGenerator`).

- `TensorFlow`/`Keras`:
  - `TensorFlow`: **Open Source Library** developed by **Google**. Used for **Build**, **Train**, and **Deploy Neural Network (CNNs)**.
  - `Keras`: **Open Source Library** that provides **Python Interface** for **Neural Network**.

- Google Colab: Free online platform to write & run a code.

## Big thanks to my teammates: 🙌
1. Jerry Wingsky ([@jrywsky](https://linktr.ee/JerryWingsky))
2. Prohabita Nuzhat
3. Lisa Luximon
