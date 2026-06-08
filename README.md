 Fruit Freshness Detection Using CNN and MobileNetV2

##Project Overview

This project focuses on detecting the freshness of fruits using Deep Learning and Computer Vision techniques. The system classifies fruit images into fresh and rotten categories using a Custom Convolutional Neural Network (CNN) and a Transfer Learning model (MobileNetV2).

The objective is to automate fruit quality inspection, reducing human effort and improving consistency in food quality assessment.

--------
 ##Objectives

* Develop a CNN-based image classification model for fruit freshness detection.
* Perform image preprocessing and data augmentation.
* Train and evaluate a custom CNN model.
* Implement MobileNetV2 transfer learning.
* Compare CNN and MobileNetV2 performance.
* Analyze model results using evaluation metrics.

-------

 ##Dataset

 Dataset Name: Fruits Fresh and Rotten for Classification

 Source: Kaggle

Dataset Link:
https://www.kaggle.com/datasets/sriramr/fruits-fresh-and-rotten-for-classification

## Classes

*The dataset contains six classes:

1. Fresh Apples
2. Fresh Bananas
3. Fresh Oranges
4. Rotten Apples
5. Rotten Bananas
6. Rotten Oranges

### Dataset Structure

dataset/

├── train/

│ ├── freshapples/

│ ├── freshbanana/

│ ├── freshoranges/

│ ├── rottenapples/

│ ├── rottenbanana/

│ └── rottenoranges/

└── test/

├── freshapples/

├── freshbanana/

├── freshoranges/

├── rottenapples/

├── rottenbanana/

└── rottenoranges/

---

##  Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Kaggle Notebook

---

##  Methodology

### 1. Data Preprocessing

* Image resizing (224 × 224)
* Pixel normalization
* Train-validation split
* Data augmentation

### 2. Data Augmentation

* Rotation
* Horizontal Flip
* Zoom
* Random Transformations

### 3. CNN Model

The custom CNN architecture consists of:

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* Conv2D (128 filters)
* MaxPooling2D
* Flatten Layer
* Dense Layer (256 neurons)
* Dropout (0.5)
* Softmax Output Layer

### 4. Transfer Learning

MobileNetV2 was implemented and compared with the custom CNN model.

---

## Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix
* Classification Report

---

##  Results

The following outputs were generated:

* Accuracy Curve
* Loss Curve
* Confusion Matrix
* Classification Report
* Model Comparison Table

### Model Comparison

| Model       | Training Accuracy | Validation Accuracy |
| ----------- | ----------------- | ------------------- |
| CNN         | XX.XX%            | XX.XX%              |
| MobileNetV2 | XX.XX%            | XX.XX%              |

*(Replace XX.XX with your actual results.)*

---

##  Project Workflow

1. Dataset Collection
2. Image Preprocessing
3. Data Augmentation
4. CNN Development
5. MobileNetV2 Development
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Conclusion

---

##  How to Run the Project

### Step 1

Clone the repository:

```bash
git clone https://github.com/yourusername/fruit-freshness-detection.git
```

### Step 2

Install required packages:

```bash
pip install tensorflow numpy pandas matplotlib seaborn scikit-learn
```

### Step 3

Download the dataset from Kaggle and place it in the appropriate directory.

### Step 4

Run the notebook:

```bash
jupyter notebook Fruit_Freshness_Detection.ipynb
```

---

##  Repository Structure

Fruit-Freshness-Detection/

├── README.md

├── Fruit_Freshness_Detection.ipynb

├── report/

│ └── Project_Report.pdf

├── images/

│ ├── workflow.png

│ ├── accuracy_curve.png

│ ├── loss_curve.png

│ └── confusion_matrix.png

└── requirements.txt

---

##  Future Enhancements

* EfficientNet implementation
* Real-time webcam detection
* Web application deployment
* Mobile application deployment
* Explainable AI using Grad-CAM

---

##  Author

**Your Name**

Machine Learning Project – Phase II

Department of Computer Science / Artificial Intelligence

Academic Year: 2025–2026

---

##  References

1. TensorFlow Documentation
2. Keras Documentation
3. MobileNetV2 Research Paper
4. Kaggle Dataset
5. Deep Learning for Computer Vision Literature
