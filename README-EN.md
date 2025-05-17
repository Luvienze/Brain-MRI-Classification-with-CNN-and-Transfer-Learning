# 🧠 Brain MRI Classification with CNN and Transfer Learning
This project is a deep learning application for classifying brain tumors from MRI images using Convolutional Neural Networks (CNN) and Transfer Learning. Developed in MATLAB, the project also includes a user-friendly Graphical User Interface (GUI) for practical usage.

## 👥 Team
This project was developed by a team of five members as part of the Deep Learning course. Each team member trained a different neural network model.

## 🧪 Models Used
- ✅ GoogLeNet

- ✅ VGG16

- ✅ MobileNet

- ✅ ResNet50

- ✅ MyCNN (a custom lightweight model developed by our team)

## 🗂️ Dataset
**Source:** Kaggle - Brain MRI Images for Brain Tumor Detection
(https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection?resource=download)

**Image Type:** Grayscale brain MRI scans

**Classes:**

- No Tumor
- Tumor

## 🔧 Data Preprocessing
Before training the models, the following preprocessing steps were applied:

- Image formats were inconsistent (.JPG, .JPEG, .PNG) → All converted to .jpg.

- Images were a mix of grayscale and RGB → All converted to RGB.

- Image sizes varied → All resized to 224x224 pixels.

- Dataset was split into training, validation, and test sets.

## 💻 Application Interface
Developed using MATLAB App Designer.

Users can choose one of the pre-trained models to classify new MRI images.

The GUI displays selected model, prediction results, and performance metrics.

## 📊 Evaluation Metrics
Each model was evaluated using:

- Accuracy

- Confusion Matrix

Other metrics like training time and model size were also considered for comparison.

## 📌 Results
Pre-trained models (GoogLeNet, VGG16, MobileNet, ResNet50) benefited from transfer learning, achieving high accuracy in a shorter training time.

The custom MyCNN model, while lighter, still achieved competitive results.

The study provides a comparative view of different architectures and highlights deep learning’s potential in clinical decision support systems.

## 🖼️ Screenshots
Below are some screenshots from the application and training results. These images showcase the graphical user interface and a guide to use the project.

## GUI
![uygulama-arayüzü](https://github.com/user-attachments/assets/cc90e997-1242-4df9-9e2b-38ed64b1bbc3)

### Upload Image
![görsel-seçimi](https://github.com/user-attachments/assets/b864f659-fd9e-475b-89b2-40c35a3dba1a)

### Upload Model
![ağ-seçim-ekranı](https://github.com/user-attachments/assets/495739cd-32a4-4a64-9df5-10ec8f8209b5)

### Upload Optimizer
![optimizasyon-seçimi](https://github.com/user-attachments/assets/998f9a4d-e896-4d34-81d5-2ee2a21b822c)

![yüklenen-model](https://github.com/user-attachments/assets/fef82d1d-583b-47d6-9b6e-8693fd8c623d)

### Classiffication
![sonuç](https://github.com/user-attachments/assets/7fcce754-927b-4584-ad2c-5a3b56c48f2b)




