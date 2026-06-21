# 🩸 Diabetic Foot Ulcer Detection and Classification

An automated medical imaging and diagnostic system developed to detect and classify Diabetic Foot Ulcers (DFU). This project implements a hybrid deep learning architecture combining **EfficientNet-B0** for advanced feature extraction and a customized **Artificial Neural Network (ANN)** for multi-class classification into severity grades.

---

## 🚀 Key Features

* **Hybrid Deep Learning Model:** Integrates pre-trained **EfficientNet-B0** weights (Transfer Learning) with a custom **ANN** head for robust classification.
* **Large-Scale Training:** Trained and validated on a curated dataset of **10,000+ medical images**.
* **Data Augmentation Pipeline:** Implemented real-time image scaling, rotation, shearing, and flipping to handle class imbalance and prevent overfitting.
* **Multi-Class Severity Grading:** Successfully classifies ulcer images into three distinct categories:
    * 🟢 **Healthy Skin**
    * 🟡 **Grade 1 (Superficial Ulcer)**
    * 🔴 **Grade 2 (Deep Ulcer)**
* **High Diagnostic Performance:** Achieved an overall classification accuracy of **88%** on the validation dataset.

---

## 🛠️ Tech Stack

* **Core Language:** Python 3.9+
* **Deep Learning Framework:** TensorFlow / Keras
* **Base Architecture:** EfficientNet-B0 (Transfer Learning)
* **Classification Head:** Artificial Neural Network (ANN)
* **Image Processing:** OpenCV, Pillow, NumPy
* **Data Visualization:** Matplotlib, Seaborn

---

## 📥 Trained Model Weights & Dataset

Due to the large file size (**~53.49 MB**), the final trained hybrid model weights (`.h5` / `.pkl`) are hosted externally. You can download the model assets to run inference locally using the link below:

🔗 **[Download Trained Model Weights (Google Drive)](https://drive.google.com/drive/folders/1Vx1oLyiywRvVg8cRcejDw0pK0hwAYuuq?usp=drive_link)**

> ⚠️ *Note: After downloading, place the model file inside the root directory or your designated `/models` folder before executing the test scripts.*

---

## 🖥️ Local Setup & Installation

### 1. Clone the Repository
```bash
git clone [https://github.com/hadija1016/Diabetic-foot-ulcer-detection-and-classification.git](https://github.com/hadija1016/Diabetic-foot-ulcer-detection-and-classification.git)
cd "ANN RESEARCH"
