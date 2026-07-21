# 🩺 Pneumonia Detection System using Deep Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/TensorFlow-2.x-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white">
  <img src="https://img.shields.io/badge/Keras-Deep%20Learning-D00000?style=for-the-badge&logo=keras&logoColor=white">
  <img src="https://img.shields.io/badge/Flask-Web%20Framework-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/OpenCV-Image%20Processing-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
</p>

---

## 📖 Overview

The **Pneumonia Detection System** is a deep learning-based web application that detects pneumonia from **Chest X-ray images** using a **Convolutional Neural Network (CNN)**.

The application provides a simple web interface where users can upload an X-ray image and receive an instant prediction indicating whether the patient is **Normal** or **Affected by Pneumonia**.

This project demonstrates the practical application of **Computer Vision**, **Medical Image Classification**, and **Deep Learning** using TensorFlow/Keras.

---

## ✨ Key Features

- 🩻 Detects Pneumonia from Chest X-ray images
- 🧠 CNN-based image classification model
- 🌐 User-friendly Flask web application
- 📤 Upload X-ray images directly through the browser
- ⚡ Instant prediction results
- 💾 Pre-trained model (`model.h5`) included
- 🔄 Easily retrainable using the provided training scripts
- 📂 Organized project structure for development and deployment

---

## 🛠️ Tech Stack

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Deep Learning | TensorFlow, Keras |
| Model | Convolutional Neural Network (CNN) |
| Web Framework | Flask |
| Image Processing | OpenCV, Pillow |
| Numerical Computing | NumPy |
| Frontend | HTML, CSS |

---

# 🏗️ Project Architecture

```text
              Chest X-ray Image
                      │
                      ▼
           Image Preprocessing
                      │
                      ▼
      Convolutional Neural Network
               (model.h5)
                      │
                      ▼
            Flask Web Application
                      │
                      ▼
          Prediction (Normal/Pneumonia)
```

---

# 📂 Project Structure

```text
Pneumonia Detection System
│
├── app.py
├── model.h5
├── README.md
├── requirements.txt
│
├── model/
│   ├── pneumonia_cnn.py
│   └── Pneumonia_cnn.ipynb
│
├── templates/
│
├── static/
│
├── uploads/
│
└── chest_xray_data_set/
    ├── train/
    │   ├── NORMAL/
    │   └── PNEUMONIA/
    │
    └── test/
        ├── NORMAL/
        └── PNEUMONIA/
```

---

# 🚀 Getting Started

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/karandesam/pneumonia-detection-system.git

cd pneumonia-detection-system
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv

source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

If the requirements file is unavailable:

```bash
pip install flask tensorflow numpy pillow opencv-python
```

---

## 4️⃣ Run the Application

```bash
python app.py
```

Open your browser and visit:

```
http://127.0.0.1:5000/
```

Upload a Chest X-ray image to receive the prediction.

---

# 🧠 Model Information

The application uses a **Convolutional Neural Network (CNN)** trained on Chest X-ray images to classify them into two categories:

- ✅ Normal
- 🦠 Pneumonia

The trained model is stored as:

```text
model.h5
```

Training scripts are available in:

```text
model/
```

---

# 📊 Dataset

The dataset used for training and testing follows the structure below:

```text
train/
    NORMAL/
    PNEUMONIA/

test/
    NORMAL/
    PNEUMONIA/
```

Dataset directory:

```text
chest_xray_data_set/
```

---

# 📸 Application Screenshots

> Add screenshots after uploading them.

| Home Page | Prediction Result |
|-----------|-------------------|
| ![](screenshots/home.png) | ![](screenshots/result.png) |

---

# 🔮 Future Enhancements

- Improve model accuracy using Transfer Learning
- Deploy the application on cloud platforms
- Add Grad-CAM visualization for prediction explainability
- Support multi-class lung disease detection
- Develop a REST API for external integration
- Build a responsive mobile-friendly interface

---

# 🤝 Contributing

Contributions are welcome!

1. Fork this repository
2. Create your feature branch

```bash
git checkout -b feature-name
```

3. Commit your changes

```bash
git commit -m "Add feature"
```

4. Push to the branch

```bash
git push origin feature-name
```

5. Open a Pull Request

---

# 👨‍💻 Author

**Samadhan Karande**

B.Tech Information Technology Student  
Vishwakarma Institute of Technology, Pune

**GitHub:**  
https://github.com/karandesam

---

# ⭐ Show Your Support

If you found this project helpful:

⭐ Star this repository

🍴 Fork it

🤝 Contribute to improve it further.

---

# 📄 License

This project is developed for **educational and research purposes**.

Please verify the licensing of the dataset and trained model before using it in commercial applications.
