# Brain Tumor Detection Using CNN

## Project Title
Brain Tumor Detection Using Convolutional Neural Network (CNN)

## Project Description
This project is a Deep Learning-based web application that detects the type of brain tumor from MRI images using a Convolutional Neural Network (CNN). The trained model is integrated with a Flask web application, allowing users to upload an MRI image and receive the predicted tumor class.

## Features
- Upload MRI brain scan images
- Automatic image preprocessing
- CNN-based brain tumor classification
- Displays predicted tumor type
- Displays prediction confidence
- Simple Flask web interface

## Technologies Used
- Python
- TensorFlow / Keras
- Flask
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- HTML

## Dataset
The dataset contains four classes of brain MRI images:
- Glioma
- Meningioma
- Pituitary
- No Tumor

Dataset Source:
https://www.kaggle.com/

(Replace this with the exact Kaggle dataset link you used.)

## Project Structure

```
Final_ML_Braintumor/
│
├── app.py
├── FinalResult_Braintumor.h5
├── requirements.txt
├── README.md
├── Templates/
│   └── index.html
├── static/
│   └── uploads/
└── Final_ML.ipynb
```
## Trained Model

The trained CNN model (`FinalResult_Braintumor.h5`) is not included in this repository because it exceeds GitHub's file size limit.

Download the model from Google Drive:
https://colab.research.google.com/drive/1VArGYhJJB73460jmgoTJee6iMMqtyAxE?usp=drive_link

After downloading, place the file in the project root folder:

BrainTumor/
│── app.py
│── FinalResult_Braintumor.h5
│── requirements.txt
│── README.md
│── Templates/
│── static/
## Installation

1. Clone or download the project.

2. Install the required packages:

```
pip install -r requirements.txt
```

3. Run the Flask application:

```
python app.py
```

4. Open the browser and visit:

```
http://127.0.0.1:5000
```

## How to Use

1. Open the Flask application.
2. Click **Choose File**.
3. Upload an MRI brain image.
4. Click **Predict**.
5. View the predicted tumor class and confidence score.

## Model Information

Model Type: Convolutional Neural Network (CNN)

Input Image Size:
224 × 224 × 3

Output Classes:
- Glioma
- Meningioma
- No Tumor
- Pituitary

## Results

The model predicts one of the four brain tumor classes based on the uploaded MRI image and displays the confidence score.

## Future Enhancements

- Improve model accuracy using Transfer Learning.
- Deploy the application on Render or Heroku.
- Add patient history management.
- Support additional MRI datasets.
- Improve the user interface.

#@Created by :::
      Navya Gambirapuram

