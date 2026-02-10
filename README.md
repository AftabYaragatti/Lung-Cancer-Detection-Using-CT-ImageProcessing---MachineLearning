<p align="center">
  <img src="screenshots/dashboard-preview.png" width="900" alt="Lung Cancer Detection Dashboard">
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
├── lung-backend/
│   ├── app.py
│   ├── cnn_model.py
│   ├── resnet_model.py
│   ├── nb_model.py
│   ├── preprocessing.py
│   ├── predict.py
│   └── requirements.txt
│
├── lung-frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── dashboard/
│   ├── dashboard.py
│   ├── charts.py
│   ├── metrics.py
│   ├── style.css
│   └── assets/
│
├── dataset/
│   ├── train/
│   ├── test/
│   └── validation/
│
├── screenshots/
│   ├── dashboard-preview.png
│   ├── input-ct-images.png
│   ├── processed-images.png
│   ├── cnn-results.png
│   ├── resnet-results.png
│   └── nb-results.png
│
├── IEEE-Paper-Lung_Cancer_Detection_Using_CT_Scan_Image.pdf
├── Lung_Cancer_Detection_Report.docx
├── Lung_Cancer_Detection_PPT.pptx
├── Lung_Cancer_Detection_Source_Code.pdf
├── Lung_Cancer_Detection_Output_Screenshots.pdf
│
└── README.md
