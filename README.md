# 🌾 Rice Leaf Disease Detection Using Deep Learning

## 📌 Project Overview

Rice Leaf Disease Detection is a deep learning project developed to identify and classify rice leaf diseases using image classification techniques. The project uses MobileNetV2 transfer learning and data augmentation to classify different types of rice leaf diseases.

The objective is to develop an automated classification approach that can support the early identification of rice leaf diseases.

## 🎯 Project Objectives

- Analyze and understand the rice leaf disease dataset.
- Perform image preprocessing and visualization.
- Develop a deep learning classification model using MobileNetV2.
- Apply data augmentation to improve image diversity.
- Compare model performance using evaluation metrics.
- Save trained models for future predictions.

## 📂 Dataset Description

The dataset contains **119 rice leaf images** belonging to three disease categories.

| Disease Category | Number of Images |
|---|---:|
| Leaf smut | 39 |
| Brown spot | 40 |
| Bacterial leaf blight | 40 |
| **Total** | **119** |

## 🛠️ Technologies and Libraries Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow (PIL)
- OpenCV

## 🤖 Models Developed

### 1. MobileNetV2 Model

A pretrained MobileNetV2 architecture was used with transfer learning to classify rice leaf images into three disease categories.

**Model file:** `RiceLeaf_Disease_Detection_Model.keras`

### 2. MobileNetV2 with Data Augmentation

An augmented model was developed using image transformation techniques to increase training image diversity and support better model generalization.

**Model file:** `RiceLeaf_Augmented_Model.keras`

### Data Augmentation Techniques

- Rotation
- Horizontal and vertical flipping
- Zooming
- Contrast adjustment

## 📊 Model Evaluation

The models were evaluated using the following performance metrics:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Classification Report

The performance comparison results are available in:

`RiceLeaf_Model_Comparison.csv`

## 🔄 Project Workflow

1. Dataset extraction and organization
2. Exploratory Data Analysis (EDA)
3. Image visualization and preprocessing
4. Training, validation, and testing split
5. MobileNetV2 model development
6. Data augmentation
7. Model training and evaluation
8. Model performance comparison
9. Saving trained models and results

## 📁 Repository Structure

```text
Rice-Leaf-Disease-Detection/
│
├── RiceLeaf disease detection.ipynb
│
├── RiceLeaf_Disease_Detection_Model.keras
│
├── RiceLeaf_Augmented_Model.keras
│
├── RiceLeaf_Model_Comparison.csv
│
├── requirements.txt
│
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/NaveenGnanavel/Rice-Leaf-Disease-Detection.git
```

### 2. Navigate to the Project Directory

```bash
cd Rice-Leaf-Disease-Detection
```

### 3. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open `RiceLeaf disease detection.ipynb` to explore the complete project implementation.

## 💾 Trained Models

The repository includes two saved Keras models:

- `RiceLeaf_Disease_Detection_Model.keras` – Original MobileNetV2 classification model.
- `RiceLeaf_Augmented_Model.keras` – MobileNetV2 model trained using data augmentation.

These models can be loaded using TensorFlow Keras for further evaluation and prediction.

## 📈 Project Outcomes

- Explored and analyzed three rice leaf disease categories.
- Developed deep learning models using MobileNetV2 transfer learning.
- Applied multiple data augmentation techniques.
- Evaluated and compared model performance.
- Saved trained models for future use.

## 📝 Conclusion

This project demonstrates the application of deep learning and transfer learning for automated rice leaf disease classification. MobileNetV2 was used to identify Leaf smut, Brown spot, and Bacterial leaf blight. Data augmentation was applied to increase image diversity and support better model generalization.

The project provides a foundation for developing automated agricultural disease detection solutions. Further improvements can be achieved by using larger and more diverse datasets and optimizing the models for real-world applications.

## 👨‍💻 Author

**Naveen Gnanavel**

- GitHub: [NaveenGnanavel](https://github.com/NaveenGnanavel)
- LinkedIn: [Naveen Gnanavel](https://www.linkedin.com/in/naveen-gnanavel-a570a1301/)

---

⭐ If you find this project useful, consider giving the repository a star!
