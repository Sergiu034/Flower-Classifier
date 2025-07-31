# 🌸 Flower Classification with MobileNetV3

## 📌 Description
This repository demonstrates how to classify various types of flowers using the **MobileNetV3** neural network architecture implemented with PyTorch. The notebook covers everything from data preprocessing, training, and evaluation to model deployment.

## 🚀 Features
- Data preprocessing and augmentation for image classification.
- Implementation of MobileNetV3 convolutional blocks in PyTorch.
- Training and evaluation workflows.
- Demonstration of accuracy and performance metrics.

## 🛠️ Technologies
- Python
- PyTorch
- MobileNetV3
- Google Colab (for development and execution)

## 📂 Project Structure

├── ProiectIS.ipynb

├── dataset/

│   ├── train/

│   └── test/

└── README.md

## 📈 Results

**Maximum Test Accuracy:** ~76.7% (Epoch 19)  
**Final Training Accuracy:** ~74.0%

**Accuracy Trend:**
- **Training accuracy:** Increased from ~19% (Epoch 1) to ~74% at the final epoch.
- **Test accuracy:** Increased from ~16.7% to ~76.7% by Epoch 19, then stabilized between 72–75%.

### 🔍 Class-wise Performance:
| Class        | Performance (Recall)                         |
| ------------ | -------------------------------------------- |
| 🌹 Roses     | Consistently high recall (≥ 0.9)             |
| 🌻 Sunflower | Strong recall (≥ 0.85 in later epochs)       |
| 🌸 Lavender  | Strong recall (≥ 0.85 in later epochs)       |
| 🌷 Tulips    | Moderate recall (variable: 0.3–0.6)          |
| 💮 Lilies    | Low recall (consistently between 0.1–0.5)    |

These results indicate that the model performs strongly for Roses, Sunflowers, and Lavender, while further improvements are needed for Tulips and Lilies.
