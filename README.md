# ✍️ Handwritten Character Recognition using Deep Learning
## CodeAlpha Internship Task 2 

---

## 📌 Overview
This project focuses on recognizing handwritten digits/characters using deep learning techniques. It is developed as part of the CodeAlpha Machine Learning Internship and demonstrates image classification using neural networks.

---

## 🚀 Features
- 🧠 Deep Learning-based classification
- 🖼️ Image processing and feature extraction
- 🔢 Handwritten digit recognition (0–9)
- 📊 Model training and evaluation
- 📉 Accuracy measurement and prediction

---

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=plotly&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)

---

## 📊 Dataset

The project uses a standard handwritten digits dataset (such as MNIST/digits dataset), which contains images of digits from 0 to 9 used for training and testing the model.

---

## 📁 Project Structure
```bash
├── notebooks/
│   └── handwritten_character_recognition.ipynb
├── images/
│   ├── sample images.png
│   └── class distribution.png
│   ├── cnn_training_history.png
│   ├── cnn_confusion_matrix.png
│   └── cnn_predictions.png
├── requirements.txt
└── README.md
```

---

## 📈 Model Workflow

1. Load dataset  
2. Preprocess image data  
3. Split into training and testing sets  
4. Train model (MLP / Neural Network)  
5. Evaluate performance  
6. Predict handwritten digits  

---

## 📊 Data Analysis

### 🔹 Sample Images
![Sample Images](images/sample_images.png)
The dataset contains handwritten digit images used for training and testing.

---

### 🔹 Class Distribution
![Class Distribution](images/class_distribution.png)

The dataset shows a balanced distribution across all digit classes.

---

## 🤖 Model Training (CNN)

### 🔹 Training History
![Training History](images/CNN_training_history.png)

The model shows steady improvement in accuracy and reduction in loss over epochs.

---

## 📉 Model Evaluation

### 🔹 Confusion Matrix
![Confusion Matrix](images/CNN_confusion_matrix.png)

The confusion matrix indicates strong classification performance with minimal misclassification.

---

## 🔍 Predictions

### 🔹 CNN Predictions on Test Samples
![Predictions](images/CNN_predictions.png)

The model successfully predicts handwritten digits on unseen test data.

---

## 📈 Results

- The model successfully classifies handwritten digits
- Achieved good accuracy on test data
- Demonstrates effectiveness of neural networks for image classification

---

## ⚙️ How to Run

### 🔹 Step 1: Clone Repository
```bash
git clone https://github.com/Rosesharma13/CodeAlpha_HandwrittenRecognition.git
cd CodeAlpha_HandwrittenRecognition
```

### 🔹 Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

### 🔹 Step 3: Run the Project
- Open the notebook in Jupyter Notebook or Google Colab
- Run all cells

---

## 🔮 Future Improvements

- Improve accuracy using advanced CNN architectures
- Extend to handwritten word recognition
- Deploy model as a web application
- Add real-time image input

---

## 🙌 Acknowledgements

- Dataset: MNIST
- Developed as part of CodeAlpha Internship

---

## 📬 Contact
Rose Sharma
