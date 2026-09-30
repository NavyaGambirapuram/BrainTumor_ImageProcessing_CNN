# Brain Tumor Detection Using CNN

## 📌 Project Overview

Brain Tumor Detection is a deep learning project that uses a **Convolutional Neural Network (CNN)** to classify brain MRI images into four categories:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

The trained model is integrated with a **Flask web application**, allowing users to upload an MRI image and receive a predicted tumor category.

---

## 🎯 Objective

The main objective of this project is to develop an image classification system that can automatically analyze brain MRI images and classify them into the appropriate category using deep learning.

---

## 🗂️ Dataset

The dataset contains brain MRI images belonging to four classes:

1. Glioma
2. Meningioma
3. Pituitary
4. No Tumor

The images are organized into separate folders based on their respective classes.

---

## 🛠️ Technologies Used

* **Python**
* **TensorFlow**
* **Keras**
* **OpenCV**
* **NumPy**
* **Flask**
* **HTML/CSS**
* **Jupyter Notebook / Google Colab**

---

## 🔄 Work Procedure / Methodology

### Step 1: Data Collection

Collected brain MRI images and organized them into four different classes:

* Glioma
* Meningioma
* Pituitary
* No Tumor

### Step 2: Image Preprocessing

The MRI images were preprocessed before training.

The images were:

* Resized to **224 × 224 pixels**
* Converted into a suitable format for model input
* Prepared for CNN training

### Step 3: Dataset Preparation

The dataset was divided into training and validation data so that the model could learn from the training images and be evaluated on unseen validation images.

### Step 4: CNN Model Development

A **Convolutional Neural Network (CNN)** was developed using TensorFlow/Keras.

The CNN learns important visual features from the MRI images, such as shapes, patterns, and structures, and uses these features for classification.

### Step 5: Model Training

The CNN model was trained using the prepared MRI dataset.

During training, the model learned to identify patterns associated with the four different classes.

### Step 6: Model Evaluation

The trained model was evaluated using validation data to check its classification performance.

The model performance was monitored using metrics such as:

* Training Accuracy
* Validation Accuracy
* Loss

### Step 7: Model Saving

After training, the trained model was saved as:

```text
FinalResult_Braintumor.h5
```

### Step 8: Flask Application Development

A Flask web application was created to provide a simple interface for users.

The user can:

1. Open the web application.
2. Upload a brain MRI image.
3. Submit the image.
4. The application preprocesses the image.
5. The trained CNN model analyzes the image.
6. The predicted class is displayed on the webpage.

---

## 🧠 Model Architecture

The CNN consists of layers designed to extract image features and perform classification.

The general workflow is:

```text
Input MRI Image
       ↓
Image Resizing
       ↓
Image Preprocessing
       ↓
Convolutional Layers
       ↓
Pooling Layers
       ↓
Feature Extraction
       ↓
Flatten / Dense Layers
       ↓
Output Layer
       ↓
Tumor Classification
```

The output consists of four possible classes:

```text
Glioma
Meningioma
Pituitary
No Tumor
```

---

## 🌐 Application Workflow

```text
User
 ↓
Upload MRI Image
 ↓
Flask Web Application
 ↓
Image Preprocessing
 ↓
Trained CNN Model
 ↓
Prediction
 ↓
Display Result
```

---

## 📊 Results

The CNN model was trained to classify brain MRI images into four categories.

The model achieved approximately **72–74% accuracy** during the training experiments with the available dataset.

> Note: Model performance can vary depending on the dataset size, image quality, preprocessing techniques, and training configuration.

---

## 📁 Project Structure

```text
Final_ML_Braintumor/
│
├── app.py
├── FinalResult_Braintumor.h5
├── requirements.txt
│
├── Templates/
│   └── index.html
│
├── static/
│   └── ...
│
└── README.md
```

---

## ▶️ How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
```

### 2. Navigate to the Project Folder

```bash
cd Final_ML_Braintumor
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

### 5. Install Required Libraries

```bash
pip install -r requirements.txt
```

### 6. Run the Flask Application

```bash
python app.py
```

### 7. Open the Application

Open the local Flask URL shown in the terminal, for example:

```text
http://127.0.0.1:5000/
```

Upload a brain MRI image and view the model's prediction.

---

## 📦 Requirements

The main Python libraries used in this project include:

```text
tensorflow
keras
opencv-python
numpy
flask
```

The complete dependencies are available in:

```text
requirements.txt
```

---

## 🚀 Future Improvements

Possible improvements include:

* Increasing the size and diversity of the dataset
* Applying data augmentation
* Improving CNN architecture
* Using transfer learning models such as ResNet or EfficientNet
* Improving validation and test performance
* Adding confidence scores to predictions
* Deploying the application to a cloud platform

---

## ⚠️ Disclaimer

This project is developed for **educational and demonstration purposes only**. It is not intended to replace professional medical diagnosis or clinical decision-making.

---

## 👩‍💻 Author

**Navya Gambirapuram**

Data Science / Data Analytics Enthusiast

GitHub: Add your GitHub profile link here
