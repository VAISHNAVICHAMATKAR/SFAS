
# 🎓 Student Attendance System using Face Recognition

This project is a Python-based facial recognition system designed to automate the process of student attendance. It uses a webcam to recognize and mark attendance for registered students in real time.

## 📁 Project Structure

```
Student Attendance/
├── attendance.py          # Mark attendance using facial recognition
├── student.py             # Register new students and capture their images
├── face_recognition.py    # Facial recognition utility
├── training.py            # Train the face recognition model
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone <your-repo-url>
   cd "Student Attendance"
   ```

2. **Install Requirements**
   ```bash
   pip install -r requirements.txt
   ```

3. **Register Students**
   ```bash
   python student.py
   ```

4. **Train the Model**
   ```bash
   python training.py
   ```

5. **Start Attendance System**
   ```bash
   python attendance.py
   ```

## 🔍 Features

- Real-time face detection and recognition
- Register new students via webcam
- Stores attendance logs
- Uses `face_recognition` and `OpenCV` libraries

## ✅ Requirements

- Python 3.6+
- OpenCV
- face_recognition
- dlib
- numpy

(Install via `requirements.txt`)

## 📌 Notes

- Make sure your webcam is connected and accessible.
- Register students in good lighting conditions for better accuracy.
- All attendance records are stored locally.

## ✨ Credits

Developed as a simple solution for automated classroom attendance using facial recognition.
