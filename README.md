# AI-Based Crop Disease Prediction System

This repository contains an AI-based solution for predicting crop diseases using images of infected plants. The system leverages transfer learning with ResNet50 to classify diseases and provides pesticide recommendations using a supplemental dataset.

## Features
- **Image Classification**: Predicts crop diseases from images using deep learning.
- **Transfer Learning**: Uses ResNet50 for efficient training with limited data.
- **Pesticide Recommendations**: Provides detailed recommendations for controlling diseases based on a curated dataset.
- **Visualization**: Displays predicted results with images for easy analysis.

---
## Dependencies
- Python 3.8+
- TensorFlow 2.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn

---

## Dataset
- **Image Dataset**: Images of cotton plants with labeled diseases (organized in subfolders).
- **Supplementary CSV**: Contains descriptions and pesticide recommendations for diseases.

---
## Model Architecture
This project uses ResNet50 pre-trained on ImageNet as a feature extractor. The model includes:
1. Global Average Pooling layer.
2. Fully connected Dense layer (1024 neurons with ReLU).
3. Output layer with softmax activation (number of classes based on diseases).

---
## License
This project is licensed under the MIT License.




