# 🌿 AI-Based Plant Disease Detection

An AI-powered web application that detects plant diseases from leaf images using Deep Learning. The system predicts the disease affecting the plant and provides useful information and possible treatment recommendations.

---

## 📌 Features

- 🌱 Upload plant leaf images
- 🤖 Deep Learning-based disease prediction
- 📊 High-accuracy classification
- 💊 Disease information and treatment suggestions
- 🖥️ User-friendly web interface
- ⚡ Fast predictions

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Deep Learning
- TensorFlow
- Keras
- CNN (Convolutional Neural Network)

### Web Framework
- Flask

### Frontend
- HTML
- CSS
- Bootstrap
- JavaScript

### Image Processing
- OpenCV
- Pillow
- NumPy

---

## 📂 Project Structure

```
AI-Based-Plant-Disease-Detection/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── index.html
│   ├── predict.html
│   └── result.html
│
├── model/
│   └── plant_disease_model.h5
│
├── app.py
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Installation

### Clone the Repository

```bash
git clone https://github.com/PRASAD1630/AI-Based-Plant-Disease-Detection.git
```

### Navigate to the Project

```bash
cd AI-Based-Plant-Disease-Detection
```

### Create a Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate it

Windows

```bash
venv\Scripts\activate
```

Linux/Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

Open your browser and visit

```
http://127.0.0.1:5000
```

---

## 📸 How It Works

1. Upload a plant leaf image.
2. The image is preprocessed.
3. The trained CNN model predicts the disease.
4. The application displays:
   - Disease Name
   - Confidence Score
   - Disease Information
   - Recommended Treatment

---

## 🧠 Deep Learning Model

- Model Type: Convolutional Neural Network (CNN)
- Framework: TensorFlow/Keras
- Input: Plant Leaf Image
- Output: Disease Classification

---

## 📊 Dataset

This project uses a plant disease image dataset for training and testing the CNN model.

Example disease classes include:

- Apple Scab
- Apple Black Rot
- Corn Rust
- Tomato Early Blight
- Tomato Late Blight
- Potato Early Blight
- Potato Late Blight
- Healthy Leaves

---

## 🎯 Future Improvements

- Mobile Application
- Real-time Camera Detection
- Multi-language Support
- Fertilizer Recommendation
- Disease Severity Analysis
- Weather-based Disease Prediction

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Added new feature"
```

4. Push

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Bhukya Prasad**

GitHub:
https://github.com/PRASAD1630

---

## ⭐ Show Your Support

If you found this project useful, please give it a ⭐ on GitHub.

---

## 📄 License

This project is licensed under the MIT License.
