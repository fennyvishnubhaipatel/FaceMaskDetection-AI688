# FaceMaskDetection-AI688
 
## 📌 Overview
This project presents a Convolutional Neural Network (CNN) model for detecting whether a person is wearing a face mask or not. The model performs binary image classification and achieves high accuracy on real-world data.

## 🎯 Objectives
- Build a CNN-based classification model
- Achieve high accuracy (~95%)
- Improve generalization using preprocessing techniques
- Evaluate using standard performance metrics

## 📂 Dataset
- Source: Kaggle
- Images: ~7000
- Classes: With Mask, Without Mask

## 🔧 Preprocessing
- Resized images to 224×224
- Normalized pixel values (0–1)
- Applied augmentation (rotation, flipping, zoom)

## 🧠 Model Architecture
- Conv2D → ReLU → MaxPooling
- Flatten → Dense → Softmax

## ⚙️ Training
- Optimizer: Adam
- Loss: Categorical Crossentropy
- Epochs: 20
- Batch size: 32

## 📊 Results
- Accuracy: ~95%
- Strong performance with low misclassification

## 📈 Evaluation
- Accuracy, Precision, Recall, F1-score
- Confusion matrix analysis

## 🚀 Applications
- Public safety monitoring
- Healthcare systems
- Smart surveillance

## 🔮 Future Work
- Real-time deployment
- YOLOv8 integration
- Larger dataset training

##  REFERENCES
[1] "Robust face mask detection in complex scenarios using YOLOv8 and context-aware convolutions," (Relevant paper referenced in project).

[2] "A Deep Learning-based Approach for Real-time Facemask Detection.“

[3] "Real-Time Facemask Detection for Preventing COVID-19 Spread Using Transfer Learning Based Deep Neural Network.“

Face Mask Dataset. Available: https://www.kaggle.com/datasets/omkargurav/face-mask-dataset

## 🛠️ Tech Stack
Python, TensorFlow, Keras, OpenCV

## 👨‍🎓 Author
Fenny Patel
Rohit Saresa
AI688-001 (Spring 2026)

## Course Information

Course: AI688 Artificial Intelligence  
Institution: Long Island University 
Semester: Spring 2026
