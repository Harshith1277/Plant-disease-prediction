# 🌿 Plant Disease Prediction Using Deep Learning

A computer vision-based deep learning model to identify diseases in plant leaves from images. This project helps in early and accurate diagnosis of plant diseases, aiding farmers in improving crop productivity and minimizing losses.

## 🔍 Features
- Image classification using CNN
- Detection of multiple plant diseases
- Real-time predictions via web interface (optional)
- Trained on PlantVillage dataset

## 🧠 Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- Jupyter Notebook / Flask (for deployment)

## 📊 Dataset
- **PlantVillage Dataset** (38 class labels)
- Categories include: Healthy, Early Blight, Late Blight, Rust, Mildew, etc.

## 🚀 Usage
1. Preprocess input leaf images (resize, normalize)
2. Run predictions through trained CNN model
3. Output: Disease name and confidence level

## 🔬 Model Architecture
- Convolutional Neural Network (CNN)
- Layers: Conv → MaxPool → ReLU → Dropout → Dense
- Optimized using Adam optimizer and categorical crossentropy loss

## 💡 Applications
- Mobile crop disease detectors
- Smart agriculture solutions
- Automated monitoring in greenhouses

---

> 👨‍🌾 Designed to empower farmers with AI-driven crop health analysis.
