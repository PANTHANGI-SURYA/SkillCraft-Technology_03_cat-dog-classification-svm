# SkillCraft-Technology_03_cat-dog-classification-svm
This project implements a Cat and Dog Image Classification system using a Support Vector Machine (SVM). Images are preprocessed with OpenCV, resized, converted into feature vectors, and classified using Scikit-learn. Model performance is evaluated using accuracy and a classification report.
# Cat vs Dog Image Classification using SVM



# 🐱🐶 Cat vs Dog Image Classification using Support Vector Machine (SVM)

## 📌 Project Overview

This project is developed as part of the **SkillCraft Technology Machine Learning Internship (Task 03)**. The objective of this project is to build an image classification model capable of distinguishing between **cats** and **dogs** using the **Support Vector Machine (SVM)** algorithm.

The model processes image data by resizing each image, converting it into a numerical feature vector, and training an SVM classifier to identify the correct class. The project demonstrates the complete machine learning workflow, including data preprocessing, feature extraction, model training, prediction, and performance evaluation.

---

## 🎯 Objective

The primary objective of this project is to:

- Build an image classification model using Support Vector Machine (SVM).
- Classify images into two categories: **Cat** and **Dog**.
- Learn image preprocessing techniques using OpenCV.
- Evaluate the performance of the trained machine learning model using standard evaluation metrics.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| OpenCV | Image Processing |
| NumPy | Numerical Computations |
| Scikit-learn | Machine Learning Algorithms |
| tqdm | Progress Bar for Loading Images |

---

## 📂 Project Structure

```
SCT_ML_03/
│
├── dog_vs_cat_dataset/
│   ├── cats_set/
│   └── dogs_set/
│
├── svm_cat_dog.py
├── README.md
├── requirements.txt
└── output.png
```

---

## 📊 Dataset

The dataset consists of two folders:

- **cats_set** – Contains cat images.
- **dogs_set** – Contains dog images.

Each image is resized to **64 × 64 pixels** before being converted into a flattened feature vector for training the SVM classifier.

---

## ⚙️ Project Workflow

The project follows the standard machine learning pipeline:

1. Load the image dataset.
2. Resize every image to a fixed size (64×64).
3. Convert images into feature vectors.
4. Assign labels:
   - Cat → 0
   - Dog → 1
5. Split the dataset into training and testing sets.
6. Train the Support Vector Machine (SVM) model.
7. Predict the class of unseen images.
8. Evaluate the model using Accuracy Score and Classification Report.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/SCT_ML_03.git
```

Navigate to the project directory:

```bash
cd SCT_ML_03
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Project

Execute the Python file:

```bash
python svm_cat_dog.py
```

---

## 📈 Model Evaluation

The model performance is evaluated using:

- Accuracy Score
- Precision
- Recall
- F1-Score
- Classification Report

Example Output:

```
Accuracy: 51.00%

Classification Report:

              precision    recall   f1-score

Cat             0.51       0.57      0.54
Dog             0.51       0.45      0.48

Overall Accuracy: 51%
```

---

## 💡 Features

- Image preprocessing using OpenCV
- Binary image classification
- Support Vector Machine (SVM) implementation
- Automatic dataset loading
- Performance evaluation using Scikit-learn
- Simple and easy-to-understand project structure

---

## 🚀 Future Improvements

This project can be enhanced by:

- Using Histogram of Oriented Gradients (HOG) features.
- Implementing Hyperparameter Tuning.
- Applying Data Augmentation.
- Using GridSearchCV for better model optimization.
- Building a Graphical User Interface (GUI).
- Deploying the model as a web application using Flask or Streamlit.
- Replacing SVM with a Convolutional Neural Network (CNN) for higher accuracy.

---

## 📚 Learning Outcomes

Through this project, the following concepts were explored:

- Image preprocessing
- Feature extraction
- Binary classification
- Support Vector Machine (SVM)
- Dataset handling
- Model training and testing
- Machine Learning evaluation metrics

---

## 📦 Requirements

The project requires the following Python libraries:

- numpy
- opencv-python
- scikit-learn
- tqdm

Install all dependencies using:

```bash
pip install -r requirements.txt
```

---

## 👨‍💻 Author

**Surya Tej**

Machine Learning Intern

SkillCraft Technology Internship

---

## 📄 License

This project is developed for educational and internship purposes. It is intended for learning, experimentation, and demonstrating the implementation of image classification using Support Vector Machines (SVM).

---

## ⭐ Acknowledgements

Special thanks to **SkillCraft Technology** for providing this internship opportunity and practical machine learning tasks that help strengthen real-world problem-solving skills and hands-on experience.
