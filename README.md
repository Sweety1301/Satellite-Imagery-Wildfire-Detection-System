# Overview
Wildfires pose a serious threat to ecosystems, infrastructure, and human life. This project presents a deep learning–based wildfire detection system that classifies satellite images into Wildfire and No Wildfire categories.

The system leverages transfer learning and introduces a hybrid CNN architecture combining ResNet152 and InceptionV3 to achieve high accuracy and robustness.

---
# Features
- Satellite image–based wildfire classification
- Transfer learning with state-of-the-art CNNs
- Custom Hybrid ResIncepNet architecture
- Data augmentation for better generalization
- Model comparison with training time analysis
- Confusion matrix & ROC-AUC evaluation
- Single-image inference with confidence scores
---
# Models Used
- ResNet152
- InceptionV3
- Hybrid ResIncepNet (ResNet152 + InceptionV3)
---
# Dataset
- Source: Kaggle Wildfire Prediction Dataset
- Binary classification:
    --wildfire
    --no wildfire
- Split into training, validation, and test sets
---
# Tech Stack
- Python, TensorFlow / Keras, NumPy, Pandas, Matplotlib, Scikit-learn, KaggleHub
---
# Architecture (Hybrid Model)
- Shared input image
- Feature extraction using:
- ResNet152
- InceptionV3
- Global average pooling
- Feature concatenation
- Fully connected classifier
- Sigmoid output
---
# Results
Model	Accuracy
| Model            | Accuracy |
|------------------|----------|
| ResNet152        | 94.5%    |
| InceptionV3      | 97.25%    |
| Hybrid ResIncepNet | 97.29% |

The hybrid model achieves the best performance and surpasses several existing research approaches.

---
# Evaluation Metrics
- Accuracy
- Confusion Matrix
- ROC Curve & AUC
- Training Time Comparison
---
# Comparison With Existing Research
The proposed hybrid model demonstrates competitive performance compared to recent wildfire detection studies, achieving higher accuracy with efficient training time.

---
# Future Improvements
- Multi-class wildfire severity detection
- Temporal satellite image analysis
- Lightweight model deployment
- Real-time monitoring system
- Web or mobile application integration
