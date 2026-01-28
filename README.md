![Demo](demo.png)
# Face Emotion Recognition App 🎭

A real-time face emotion recognition web application built using **Python, Streamlit, OpenCV, and DeepFace**.  
This app detects faces from images or webcam input and predicts the dominant emotion for each detected face.

---

## 🎮 Application Features

- Upload image or use webcam
- Real-time face detection using OpenCV Haar Cascade
- Emotion prediction using DeepFace
- Bounding box with emotion label
- Emotion score table for each face
- Emotion bar chart visualization
- Automatic saving of results to `results.csv`

---

## 🕹 How It Works

- The user uploads an image or captures one from the webcam  
- The app detects all faces in the image  
- Each detected face is cropped and analyzed using DeepFace  
- The dominant emotion is shown on the image  
- A table and bar chart show emotion confidence scores  
- All results are saved automatically

---

## 🧠 Technologies Used

- Python  
- Streamlit  
- OpenCV  
- DeepFace  
- NumPy  
- Pandas  

---

## 📂 Project Files

app.py  
requirements.txt  
report.pdf  
results.csv  

---

## ▶️ How to Run the Project

1. Install required libraries  

pip install -r requirements.txt

2. Run the application

streamlit run app.py

📊 Output

Detected faces with emotion labels

Emotion probability table

Emotion bar chart

CSV file with all predictions

👨‍💻 Developer

Harish Kumar
Computer Science Student
Python • Machine Learning • Computer Vision

LinkedIn: https://www.linkedin.com/in/harish-yadav-3b18b9253/
