# Indian Sign Language Recognition (A–Z)

This repository presents a deep learning–based system for recognizing **Indian Sign Language (ISL) alphabets (A–Z)** from both **static images** and **videos**.  
The project uses a **Convolutional Neural Network (CNN)** built with **PyTorch**, enhanced with **MediaPipe Hand landmarks** for video inputs, and deployed through an interactive **Gradio web interface**.

---

##  Features

- ✅ ISL alphabet recognition (A–Z)
- ✅ Image-based prediction using CNN
- ✅ Video-based prediction using hand landmark extraction
- ✅ Automatic dataset splitting (train/validation)
- ✅ Performance evaluation using accuracy, precision, recall, F1-score
- ✅ Interactive web interface with Gradio

---

##  Methodology

### 1. Dataset Preparation
- Images are organized into alphabet-wise folders (A–Z)
- Dataset is split into training and validation sets automatically

### 2. Image-Based Recognition
- Images are resized and normalized
- A CNN model is trained using PyTorch
- Final classification is performed using softmax outputs

### 3. Video-Based Recognition
- MediaPipe Hands is used to extract hand landmarks from video frames
- Landmarks are aggregated and passed to the trained model
- Final prediction is based on temporal hand movement patterns

### 4. Deployment
- Gradio interface allows users to:
  - Upload images for hand sign recognition
  - Upload videos for ISL alphabet prediction


## 🛠️ Tech Stack

- **Python**
- **PyTorch**
- **TorchVision**
- **MediaPipe**
- **OpenCV**
- **Scikit-learn**
- **Gradio**
- **NumPy / Matplotlib**

  
## 📈 Evaluation Metrics

The model performance is evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
