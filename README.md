
# 🌱 **Plant Disease Detection | CNN + Deep Learning + Flask**

A smart deep-learning system for identifying plant leaf diseases using Convolutional Neural Networks (CNN).
This project helps farmers and researchers detect crop diseases early using image classification.

---

## 📌 **Features**

* 🌿 Multi-crop disease detection (Potato, Tomato, Apple, Grape, Strawberry, Corn)
* 🧠 CNN-based deep learning model using TensorFlow/Keras
* 🖼️ Real-time leaf image prediction
* 🔧 Preprocessing: resizing, normalization, and augmentation
* 🚀 Flask-based web interface for easy prediction
* 📊 Performance evaluation using Accuracy, Precision, Recall & F1-Score
* 📁 Dataset sourced from Kaggle

---

## 🏗️ **Project Architecture**

```
Dataset → Preprocessing → CNN Model → Training → Evaluation → Flask Deployment → Prediction UI
```

---

## 📂 **Folder Structure**

```
Plant-Disease-Detection/
│── static/
│   ├── css/
│   ├── images/
│── templates/
│   ├── index.html
│── model/
│   ├── plant_disease_model.h5
│── app.py
│── train.py
│── README.md
│── requirements.txt
```

---

## 🧪 **Technologies Used**

* Python
* TensorFlow / Keras
* NumPy, Pandas
* Matplotlib
* Flask
* OpenCV
* Scikit-learn

---

## 📥 **Installation**

### Clone the repository

```bash
git clone https://github.com/yourusername/Plant-Disease-Detection.git
cd Plant-Disease-Detection
```

### Create and activate virtual environment

```bash
python -m venv venv
source venv/bin/activate       # for Mac/Linux
venv\Scripts\activate          # for Windows
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ **Run the Project**

```bash
python app.py
```

The app will start at:
👉 **[http://127.0.0.1:5000/](http://127.0.0.1:5000/)**

---

## 📝 **How It Works**

1. User uploads an image of a plant leaf
2. Image → preprocessing pipeline
3. CNN model classifies disease category
4. Output displayed with confidence score

---

## 🎯 **Model Performance**

* Accuracy: **(add your accuracy)**
* Loss: **(add your loss)**
* Epochs trained: **(ex: 25, 50)**

---

## 📸 **Screenshots**

*Add before/after UI screenshots here*

---

## 📚 **Dataset**

Dataset used:
🔗 Kaggle Plant Village Dataset (multi-crop)

---

## 🚀 **Future Improvements**

* Add more crop categories
* Mobile app using Flutter
* Real-time camera input
* Integration with fertilizer/pesticide suggestions

---

## 🤝 **Contributing**

Pull requests are welcome!
For major changes, please open an issue first.

---

## ⭐ **Show Your Support**

If you like this project, don’t forget to star ⭐ the repository!

