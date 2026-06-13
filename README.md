# 🖼️ CIFAR-10 Image Classifier using TensorFlow

## 📌 Project Overview

This project is a Deep Learning-based Image Classifier built using TensorFlow and Keras. The model is trained on the CIFAR-10 dataset, which contains 60,000 color images belonging to 10 different classes.

The goal of this project is to classify images into their respective categories using a Convolutional Neural Network (CNN).

---

## 🚀 Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 📂 Dataset

The CIFAR-10 dataset contains the following 10 classes:

1. Airplane ✈️
2. Automobile 🚗
3. Bird 🐦
4. Cat 🐱
5. Deer 🦌
6. Dog 🐶
7. Frog 🐸
8. Horse 🐴
9. Ship 🚢
10. Truck 🚚

Dataset Size:

* Training Images: 50,000
* Testing Images: 10,000
* Image Size: 32 × 32 RGB

---

## 🧠 Model Architecture

The model uses a Convolutional Neural Network (CNN) consisting of:

* Conv2D Layer (32 Filters)
* MaxPooling2D Layer
* Conv2D Layer (64 Filters)
* MaxPooling2D Layer
* Conv2D Layer (64 Filters)
* Flatten Layer
* Dense Layer (64 Neurons)
* Output Layer (10 Classes)

---

## ⚙️ Project Workflow

1. Load CIFAR-10 Dataset
2. Normalize Image Data
3. Build CNN Model
4. Compile the Model
5. Train for 10 Epochs
6. Evaluate Performance
7. Visualize Accuracy Graph
8. Save Trained Model

---

## 📊 Results

### Training Performance

* Training Accuracy: ~78%

### Testing Performance

* Test Accuracy: **69.51%**

The model successfully learned image patterns and achieved a good classification performance for a beginner-level CNN model.

---

## 📈 Accuracy Graph

The graph shows the improvement in training and validation accuracy over 10 epochs.

(Add your graph screenshot here after uploading to GitHub)

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Image Classification
* Deep Learning Fundamentals
* Convolutional Neural Networks (CNN)
* TensorFlow & Keras
* Data Preprocessing
* Model Training & Evaluation
* Data Visualization

---

## 💾 How to Run

```bash
pip install tensorflow matplotlib numpy
```

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
image_classifier.ipynb
```

and execute all cells.

---

## 👨‍💻 Author

**Valarmathi R**

B.Tech CSBS Student
Aspiring AI Engineer 🚀

GitHub: https://github.com/valarmathircsbs-pixel
