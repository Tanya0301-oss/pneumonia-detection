# 🩺 Pneumonia Detection using Deep Learning

This project uses a **Convolutional Neural Network (CNN)** built with **TensorFlow/Keras** to detect **Pneumonia from Chest X-ray images**.
The model classifies X-ray images into two categories:

* **Normal**
* **Pneumonia**

The goal of this project is to demonstrate how deep learning can assist in **medical image analysis** and automated disease detection.

---

## 📌 Project Overview

Pneumonia is a serious lung infection that can be detected through chest X-ray images.
In this project, a deep learning model is trained to automatically classify X-ray images as **Normal** or **Pneumonia**.

The workflow includes:

1. Dataset preprocessing
2. Model training using CNN
3. Model evaluation
4. Prediction on new X-ray images

---

## 🛠 Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 📂 Project Structure

```
pneumonia-detection
│
├── pneumonia_detection.ipynb   # Training notebook
├── pneumonia_model.keras       # Trained model
├── requirements.txt            # Required libraries
└── README.md                   # Project documentation
```

---

## ⚙️ Installation

Clone the repository and install dependencies:

```
git clone https://github.com/your-username/pneumonia-detection.git
cd pneumonia-detection
pip install -r requirements.txt
```

---

## 🚀 How to Run

1. Open the notebook `pneumonia_detection.ipynb`
2. Run the cells to load the trained model
3. Provide a chest X-ray image
4. The model will predict whether the image shows **Normal** lungs or **Pneumonia**

---

## 📊 Model Output

The model predicts the probability of pneumonia in the given X-ray image.

Example output:

```
Pneumonia detected
```

or

```
Normal
```

---

## 🎯 Future Improvements

* Improve model accuracy with more training data
* Add a web interface for easy usage
* Deploy the model as a web application

---

## 👩‍💻 Author

Tanya Maheshwari

---

⭐ If you find this project useful, consider giving it a star on GitHub!
