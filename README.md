
# 🍀 Ayurvedic Plant Species Identification

This project is a deep learning-based system designed to identify various Ayurvedic plant species from images using TensorFlow and Keras. It leverages a pre-trained CNN model (e.g., ResNet50) with custom classification layers and is trained on a dataset of segmented leaf images.


## 🧪 Features

- Pretrained model (MobileNetV2 or ResNet50) for transfer learning
- Data augmentation for robustness
- Image normalization and preprocessing
- Model training and evaluation with metrics and plots
- Inference on new images with confidence score

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/karthikkharv/leaf-classification.git
cd leaf-classification
```

### 2. Install Dependencies
```bash
pip install tensorflow matplotlib numpy keras
```

### 3. Set Dataset Path
Update the `main_data_dir` in `config.py` with the path to your dataset.

### 4. Train the Model
```bash
python main.py train
```

### 5. Predict a New Image
```bash
python main.py predict --image path/to/image.jpg
```

## 📊 Results

- Accuracy and loss curves are plotted after training.
- Model achieves over 80% accuracy with proper tuning and more epochs.

## 📦 Dataset
[Medicinal Leaf Dataset on Kaggle](https://www.kaggle.com/datasets/riteshranjansaroj/segmented-medicinal-leaf-images)
![Screenshot (54)](https://github.com/user-attachments/assets/6bd2d800-847d-4d63-af59-09736d780ddd)

## 📌 Future Work

- Experiment with other architectures (EfficientNet, Inception)
- Improve dataset with more species and augmented samples
- Deploy as a web/mobile app for real-time classification

## 📄 License
This project is licensed under the MIT License.
