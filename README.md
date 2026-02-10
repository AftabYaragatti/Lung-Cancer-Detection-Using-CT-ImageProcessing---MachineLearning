<p align="center">
  <img src="Dashboards/CT-Lung-Cancer-Photo.jpg" 
       alt="CT Scan illustration" 
       width="800"
       style="border-radius:10px;">
</p>

# 🫁 Lung Cancer Detection Using CT Image Processing & Machine Learning

Welcome to my **Lung Cancer Detection System** 🚑  
This project uses **CT scan image processing** combined with **Machine Learning & Deep Learning models** to detect lung cancer at an early stage.

The system is built with:
- 🧠 **3 ML/DL Models**: CNN, ResNet, Naive Bayes  
- 📊 **Interactive Dashboard** for visualization  
- 🖼️ Advanced CT image preprocessing  
- 🌐 Frontend + Backend integration  

This is a **major/final-year project**, designed with real-world medical AI workflow in mind.

---

## 🎯 Project Objective

The primary objective of this project is to:
- Automatically analyze lung CT scan images  
- Classify them as **Normal / Cancerous**  
- Compare multiple ML & DL models for accuracy  
- Provide results through an **interactive dashboard**

🩺 Early lung cancer detection can significantly improve survival rates, and this project demonstrates how **AI + image processing** can support medical diagnosis.

---

## 🧠 Models Used (Very Important ⭐)

This project uses **three different models** to compare performance:

| Model | Type | Purpose |
|-----|------|--------|
| 🧠 CNN | Deep Learning | Feature extraction directly from CT images |
| 🔥 ResNet | Deep Learning | High-accuracy deep residual learning |
| 📊 Naive Bayes (NB) | Machine Learning | Statistical baseline model |

➡️ Final predictions are analyzed and compared using accuracy, loss, and output confidence.

---

## 🛠️ Technologies & Tools

| Technology | Usage |
|-----------|------|
| 🐍 Python | Core programming |
| 🖼️ OpenCV | CT image preprocessing |
| 🤖 TensorFlow / Keras | CNN & ResNet models |
| 📊 Scikit-learn | Naive Bayes model |
| 🔢 NumPy & Pandas | Data handling |
| 🌐 HTML, CSS, JS | Frontend UI |
| 📊 Dashboard | Visualization & results |
| 📁 Dataset | Lung CT scan images |

---

## ⭐ Key Features

✔ CT image preprocessing (noise removal, resizing, normalization)  
✔ Multi-model comparison (CNN vs ResNet vs NB)  
✔ Accuracy & prediction visualization  
✔ Interactive dashboard  
✔ Frontend image upload support  
✔ Research-grade documentation & reports  

---

## 📁 Complete Project Structure

```text
Lung-Cancer-Detection-Using-CT-ImageProcessing---MachineLearning/
│
├── Dashboards/
│   ├── Admin_Dashboard.html
│   ├── Model_Dashboard.html
│   ├── User_Dashboard.html
│   ├── CT-Lung-Cancer-Photo.jpg
│   ├── CT-Scan-Image.jpg
│   ├── CT-Scan-Image2.jpg
│   └── Cancer1.jpg
│
├── lung-backend/
│   ├── app.py
│   ├── model_cnn.py
│   ├── model_resnet.py
│   ├── model_naive_bayes.py
│   ├── requirements.txt
│   └── utils/
│
├── lung-frontend/
│   ├── index.html
│   ├── style.css
│   ├── script.js
│   └── assets/
│
├── dataset/
│   ├── Normal/
│   └── Cancer/
│
├── notebooks/
│   ├── CNN_Model.ipynb
│   ├── ResNet_Model.ipynb
│   └── NaiveBayes_Model.ipynb
│
├── README.md
└── .gitignore


