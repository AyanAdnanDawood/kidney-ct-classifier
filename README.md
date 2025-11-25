# Kidney CT Classification – Deep Learning Project

A deep learning-based system for automated multi-class classification of kidney CT scan images. The model classifies CT images into four categories:

* **Normal**
* **Cyst**
* **Tumor**
* **Stone**

This project uses two architectures:

* A **Custom CNN model**
* **VGG16 (Transfer Learning)**

The system is deployed using **Streamlit** for easy accessibility and real-time inference.

---

## 📌 Project Overview

Kidney diseases affect millions worldwide, and early diagnosis is crucial. Radiological interpretation of CT scans is highly specialized and time-consuming. This project aims to automate classification using deep learning, reducing diagnostic workload and improving early detection.

---

## 🧠 Features

* End-to-end CT scan classification pipeline
* Image preprocessing and augmentation
* Comparative analysis between CNN and VGG16
* Training with accuracy, precision, recall, and F1-score evaluation
* Streamlit-based deployment for live predictions

---

## 📂 Project Structure

```
/
├── app.py                  # Streamlit web app
├── model_cnn.py            # Custom CNN model training
├── model_vgg16.py          # VGG16 training script
├── utils/                  # Helper functions
├── requirements.txt        # Dependencies
└── README.md
```

Note: Due to large file size, trained models are hosted externally (e.g., Google Drive) and downloaded at runtime.

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/<your-username>/kidney-ct-classifier.git
cd kidney-ct-classifier
```

### 2️⃣ Create a virtual environment

```
python -m venv venv
```

### 3️⃣ Activate environment

**Windows**

```
venv\Scripts\activate
```

**Linux/Mac**

```
source venv/bin/activate
```

### 4️⃣ Install dependencies

```
pip install -r requirements.txt
```

---

## ▶️ Running the App

```
streamlit run app.py
```

This will launch the browser UI where users can upload CT scan images and get predictions.

---

## 📊 Results

| Model | Accuracy |
| ----- | -------- |
| CNN   | ~98%     |
| VGG16 | ~99%*    |

* VGG16 performance was constrained by limited training hardware and dataset size, but results indicate strong potential for real-world scalability.

---

## 📦 Model Files

Trained model files are stored externally due to size limits and need to be downloaded link is https://drive.google.com/drive/folders/1geF2-3KZAfcgIkyy7zWG3xEtRVT649Ga?usp=sharing

---

## 🚀 Future Improvements

* Larger dataset for generalization
* 3D CT volume analysis
* Grad-CAM explainability
* Mobile deployment
* Improved segmentation

---

## 🧑‍💻 Contributors

* **Muhammad Aman Qazi**
* **Ayan Adnan**
* **Muhammad Tahir**
* **Syed Awais Waseem**

---

## 📝 License
This project is for educational and research use only.
