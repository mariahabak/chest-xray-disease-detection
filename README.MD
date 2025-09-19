# Chest X-Ray Disease Detection

A deep learning project to classify chest X-ray images as Normal or Pneumonia.

# Project Overview

This project uses convolutional neural networks (CNNs) to detect pneumonia from chest X-ray images. The model is trained on labeled X-ray images and can help in automated detection of pneumonia.



# Dataset
- **Source:** [Chest X-Ray Images (Pneumonia) – Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)
- **Structure:**  
data/
chest_xray/
train/
NORMAL/
PNEUMONIA/
val/
NORMAL/
PNEUMONIA/
test/
NORMAL/
PNEUMONIA/


## Model Performance

| Class       | Precision | Recall | F1-score | Support |
|------------|-----------|--------|----------|--------|
| NORMAL     | 0.89      | 0.80   | 0.84     | 234    |
| PNEUMONIA  | 0.89      | 0.94   | 0.91     | 390    |

- **Accuracy:** 0.89  
- **Weighted F1-score:** 0.89



# Installation

- Clone the repository:
git clone https://github.com/mariahabak/chest-xray-disease-detection.git


Navigate to the project folder:
cd ChestXRay



Create and activate the virtual environment:
python -m venv venv
.\venv\Scripts\activate   # Windows



Install dependencies:
pip install -r requirements.txt



# Results
-The model achieves 89% accuracy on the test set.
-High recall for PNEUMONIA ensures fewer missed cases.
-Balanced precision across both classes indicates reliable predictions.


 # Next Steps / Future Improvements
-Experiment with data augmentation to improve generalization.
-Test with more advanced CNN architectures (e.g., ResNet, EfficientNet).
-Deploy the model using a web or mobile application for practical usage.
-Explore multi-class classification for other lung diseases.
-Implement Explainable AI (XAI) methods to visualize model predictions